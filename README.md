# Mediogram Billing: demo

**Live demo: https://nnnnshsjsjsj.github.io/mediogram-billing-demo/**

A working demo of Mediogram's billing service for clinical trials. Every sponsor, study, person, price and bank detail here is fictional.

## How it works

1. **The site doctor** marks what was done at each patient visit. Doctors never see any amounts.
2. **The sponsor** sees the visits with prices and approves them, or returns them with a comment. The admin and the doctor see that comment, translated automatically.
3. **Mediogram** gets the approved visits gathered into a weekly invoice draft and issues it with one button, in the existing Excel invoice template.

Admins and doctors work in Russian. The sponsor and the invoices are in English.

## What's new

- **Several sponsors**, each with its own billing details, invoice suffix, invoice limit and service catalogue (hourly or fixed-price).
- **Approval line by line**: the sponsor ticks Screening now and Baseline later, or holds back one item. Confirmed lines are invoiced right away; the rest go on a later invoice.
- **Comments under any line**, translated between Russian and English.
- **Evidence files** attached to hourly services.
- **Invoices split under a limit** (e.g. ≤ €15,000), each part with its own number; lines can be moved between parts.
- **Doctor folders** per sponsor and study.
- **Clindex check**: upload the Clindex visit report (CSV) to see visits missing in billing, missing in Clindex, or with different dates.

## Try it

Open the live demo and pick an account on the sign-in screen:

| Account | Role |
| --- | --- |
| Anna Petrova | Mediogram admin: budgets, patients, invoices, payments, audit log |
| Study coordinator · CHC | Site doctor: patients in a folder per sponsor, visit checklists, no prices |
| Clinical Finance · Northwind | Sponsor (Northwind Cardio): tick visits and single lines, return lines with a reason |
| Clinical Operations · Helix Valve | Second sponsor (Helix Valve) with its own services and a €15,000 invoice limit |

Everything you do is saved only in your own browser. To start over, use **Settings → Reset demo data**.

In this demo, nothing is emailed. New comments are not translated, because the translation service is connected only in the full version.
