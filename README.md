# HR Management & Payroll System

A professional desktop **HR & Payroll** application for Windows and Linux.
Staff directory, attendance calendar, payroll calculation with Indian
statutory deductions (PF / ESI / Income Tax), payslips, A4 PDF reports,
charts dashboard, email payslips, and role-based access — with
**licence-key protection** (machine-locked, signed licences).

**Copyright © Byt Bump - (2026)**

---

## What's included

| Platform | File | Notes |
|----------|------|-------|
| Windows 10/11 (64-bit) | `windows/HR_PAYROLE_V2.02.1.EXE` | Single-file executable, no installation of Python needed |
| Linux (x86-64) | `linux/HR_Payroll.tar.gz` | Portable app — extract and run, no Python needed |

> This repository ships **ready-to-run builds only** — no source code.

---

## Specifications

- **OS:** Windows 10 / 11 (64-bit) **or** Linux x86-64 (Ubuntu 20.04+ and
  most glibc-based distributions)
- **Disk:** ~250 MB free
- **Internet:** required **once** — for the first licence activation
  (works offline afterwards, 30-day offline grace)
- **Display:** 1366×768 or larger
- **Privileges:** no admin/root required

---

## How to use

### Windows
1. Download `HR_PAYROLE_V2.02.1.EXE`
2. Double-click it — the **Activation Required** dialog opens on first run
3. Copy the **Hardware ID** shown and send it to us (see *Get a Licence*)
4. Save the `Licence.json` you receive **next to the .EXE file**
5. Click **Re-check Licence** — the app opens the login screen
6. Log in with the demo accounts below and start using it

### Linux
```bash
tar -xzf HR_Payroll.tar.gz
cd HR_Payroll
./HR_Payroll
```
Follow the same activation steps as above.

### Demo login accounts
| Role | Username | Password |
|------|----------|----------|
| Administrator | `admin` | `admin123` |
| HR | `hr` | `hr123` |
| Viewer (dashboard only) | `viewer` | `view123` |

Change these after first login (File menu).

### The four modules
1. **Setup & Staff Directory** — add employees, salaries, tax groups,
   performance/potential scores, departments; company settings
2. **Attendance Calendar** — per-day Present / Vacation / Sick / Unpaid
   marking, month navigation, bulk actions, month PDF export
3. **Payroll Calculator** — auto-fetch by Employee ID, overtime, PF/ESI/
   tax breakdown, compute one or all, save runs, export / email payslips
4. **Dashboard** — live KPIs and charts (9-box matrix, headcount by
   department, attendance distribution, payroll cost trend) + A4 PDF export

Every report is A4 with the copyright footer: *Copyright © Byt Bump - (2026)*.

---

## Pricing (all prices in INR)

| Plan | Price | Notes |
|------|-------|-------|
| **Monthly** | **₹500 / month** | Billed every month |
| **Half-Yearly** | **₹450 / month → ₹2,700 for 6 months** | Save ₹300 vs monthly |
| **Annual (OFFER)** | **₹4,999 / year** | ~~₹8,999~~ — limited offer price |

One licence = one computer (locked to that machine's Hardware ID).
Renewals extend the same licence.

---

## How to get a Licence

1. **Contact us:** **+91 70630 08160** (Phone / WhatsApp)
2. **Choose your plan** (monthly / half-yearly / annual) and make the
   payment as instructed
3. **Send us:**
   - your **payment proof** (screenshot / receipt), and
   - your computer's **Hardware ID** (shown automatically in the
     Activation dialog on first launch — click *Copy*)
4. We issue and send you your **`Licence.json`**
5. Place `Licence.json` in the application folder (next to the EXE /
   executable) and click **Re-check Licence** — done

Need the Hardware ID later? Windows: run `show_hwid.bat` next to the app
build tools, or read it from **Help → License Status** inside the app.

---

## Support

- Phone / WhatsApp: **+91 70630 08160**
- Licence status is always visible under **Help → License Status**
- Expiry is shown there as well; renew before expiry to stay active

---

**© 2026 Byt Bump. All rights reserved.**
*Copyright © Byt Bump - (2026)*
