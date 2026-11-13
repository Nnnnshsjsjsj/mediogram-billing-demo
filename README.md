# Mediogram Billing: demo

**Live demo: https://nnnnshsjsjsj.github.io/mediogram-billing-demo/**

A working demo of Mediogram's billing service for clinical trials. Every sponsor, study, person, price and bank detail here is fictional.

## How it works

1. **The site doctor** marks what was done at each patient visit. Doctors never see any amounts.
2. **Mediogram (admin)** collects the completed work and sends the sponsor a **proforma invoice**, signed with the admin's password.
3. **The sponsor's clinical reviewer** checks the clinical lines only (visits and procedures, no amounts and no CRO services) and confirms or disputes each line.
4. **The sponsor's accountant** checks the numbers against what the clinical reviewer confirmed, confirms the CRO services, and sends the proforma back, signed.
5. **Mediogram** sees each disputed line with its reason. Everything confirmed becomes the **final invoice** with one button, in the existing Excel template. Disputed lines wait for the next round.

The admin and doctor screens can be switched between **Russian and English** (top right, or in Settings). The sponsor side and the invoices are in English.

## Also in this version

- **Three sponsor roles**: the sponsor's admin (Admin S.) sees everything on the sponsor side (read-only), the clinical reviewer confirms clinical work, and the accountant confirms amounts and CRO services.
- **Electronic signatures**: sending, reviewing and finalising a proforma asks for your password again, and the audit log marks those entries as signed.
- **Queries**: any comment can be raised as a query that stays open until someone resolves it.
- **My tasks**: each account sees what is waiting for it.
- **Subject status** per patient: screening, enrolled, screen failure, withdrawn or completed.
- Several sponsors with their own prices, line-by-line confirmation, comments on any line, evidence files on hourly services, and the invoice builder (split by amount, patient or month).

## Try it

Open the live demo. The sign-in screen lists every demo account: **click one to sign in**. You can also type a login and password:

| Role | Login | Password |
| --- | --- | --- |
| Mediogram admin | anna | Demo-Admin-1 |
| Mediogram admin | mark | Demo-Admin-2 |
| Mediogram admin (billing desk) | billing | Demo-Admin-3 |
| Site doctor: study coordinator | doctor1 | Demo-Site-1 |
| Site doctor: principal investigator | doctor2 | Demo-Site-2 |
| Sponsor: Admin S. 1 (Northwind) | admin.s1 | Demo-AdminS-1 |
| Sponsor: clinical reviewer (Northwind) | northwind.clinical | Demo-Clinical-1 |
| Sponsor: accountant (Northwind) | northwind.accountant | Demo-Finance-1 |
| Sponsor: clinical reviewer (Helix Valve) | helix.clinical | Demo-Clinical-2 |

A good walk-through: sign in as **Anna** and send a proforma from **Invoices**. Then sign in as the **Northwind clinical reviewer** and confirm the clinical lines, then as the **Northwind accountant** to confirm the amounts and dispute one line. Finally, go back to **Anna** and issue the final invoice.

Everything you do is saved only in your own browser. To start over, use **Settings → Reset demo data**.
