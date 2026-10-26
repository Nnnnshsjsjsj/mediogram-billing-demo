# Mediogram Billing: demo

**Live demo: https://nnnnshsjsjsj.github.io/mediogram-billing-demo/**

A working demo of Mediogram's billing service for clinical trials. Every sponsor, study, person, price and bank detail here is fictional.

## How it works

1. **The site doctor** marks what was done at each patient visit. Doctors never see any amounts.
2. **The sponsor** sees the visits with prices and approves them, or returns them with a comment. The admin and the doctor see that comment, translated automatically.
3. **Mediogram** gets the approved visits gathered into a weekly invoice draft and issues it with one button, in the existing Excel invoice template.

Admins and doctors work in Russian. The sponsor and the invoices are in English.

## Try it

Open the live demo and pick an account on the sign-in screen:

| Account | Role |
| --- | --- |
| Anna Petrova | Mediogram admin: budgets, patients, invoices, payments, audit log |
| Study coordinator · CHC | Site doctor: patients and visit checklists, without prices |
| Clinical Finance · Northwind | Sponsor: approve or return visits, budget, invoices |

Everything you do is saved only in your own browser. To start over, use **Settings → Reset demo data**.

In this demo, nothing is emailed. New comments are not translated, because the translation service is connected only in the full version.
