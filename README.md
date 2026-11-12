<p align="center">
  <img src="screenshots/icon.png" alt="Asaan Optics logo" width="96">
</p>

<h1 align="center">Asaan Optics</h1>

<p align="center">
  <strong>Optical shop software for Android and Windows: prescriptions, counter sales, stock and staff shifts on one shared shop account.</strong>
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.techwinesolutions.asaanoptics"><img src="https://img.shields.io/badge/Google_Play-Get_the_app-3DDC84?style=for-the-badge&logo=google-play&logoColor=white" alt="Get it on Google Play"></a>
  <a href="https://asaanoptics.com/download"><img src="https://img.shields.io/badge/Windows_10%2F11-Download-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Download for Windows"></a>
  <a href="https://asaanoptics.com"><img src="https://img.shields.io/badge/Website-asaanoptics.com-C62828?style=for-the-badge" alt="asaanoptics.com"></a>
</p>

<p align="center">
  <img src="screenshots/desktop/dashboard.webp" alt="Asaan Optics Desktop dashboard with quick actions, monthly revenue, customer growth, pending accounts, store expenses, a weekly revenue chart and cash-flow composition" width="100%">
  <br>
  <sub>The Windows dashboard, shown with demo data.</sub>
</p>

---

## About

Asaan Optics is a subscription product for opticians, eyewear stores and eye clinics. It replaces the paper register with one shop account that works from a Windows PC at the counter and an Android phone: patients and eye prescriptions, spectacle orders and repairs, frame, lens and contact-lens stock, counter sales, staff shifts and receipts.

It started with optical shops in Pakistan and now also supports the languages and tax rules of Saudi Arabia, the Gulf and India. Both apps keep working when the internet drops.

Asaan Optics is published by [Techwine Solutions](https://www.techwinesolutions.com). It was designed and built by [Farhad Nazir](https://farhadnazir.com), its founder and sole developer.

> **About this repository.** This is the public showcase for Asaan Optics. It contains this README and product screenshots only. The product's source code (apps, backend and website) is private and is not published here. To use the software, install it from the links below.

## Platforms and downloads

| Platform | Get it | Details |
|---|---|---|
| **Android** | [Google Play](https://play.google.com/store/apps/details?id=com.techwinesolutions.asaanoptics) | Free to install, with paid plans through Google Play |
| **Windows 10 / 11 (64-bit)** | [asaanoptics.com/download](https://asaanoptics.com/download) | Self-updating installer, 30-day free trial |

There is no iPhone or iPad app at this time.

On Google Play the app is rated **4.8 from 116 reviews** (Pakistan storefront, November 2026). Release notes for both apps are on the [What's new](https://asaanoptics.com/whats-new) page.

## Key features

**Patients and prescriptions**
- Customer records with search by name, phone, serial, doctor or remarks, filters for status, balance, fulfilment and birthday, and Excel export.
- Prescription orders with SPH, CYL, AXIS, ADD, IPD and PD for each eye, frame and lenses picked from stock, several pairs on one bill, and advance and balance due.
- Prescription scanning on Android: the camera reads a printed prescription on the phone with on-device text recognition (OCR), and a parser checks the values against optical rules and highlights anything doubtful for staff to confirm.
- Repair jobs with their own serial series, status, balance and receipt.
- Eye screening aids on Android: a tumbling-E acuity chart calibrated to the phone's screen, an Amsler grid, a colour test and a pinhole record, saved to the customer. These are screening aids, not a diagnosis.

**Sales, receipts and tax**
- Counter sales by barcode or search, with discounts and cash, card or other payment methods, plus shop expenses on the same screen.
- PDF receipts for A4 and thermal printers, including Arabic text. The app prepares the receipt message and opens the customer's WhatsApp chat for staff to send.
- Saudi VAT receipts with a ZATCA QR code and GSTIN on Indian receipts. ZATCA Phase 2 e-invoicing is built into the Windows app and is switched on per device after onboarding.
- Sales statements filtered by type and date, exported to Excel or PDF.

**Inventory and barcodes**
- Separate stock for frames, spectacle lenses (single power or power range), contact lenses and accessories.
- Code 128 barcode labels for thermal sticker printers, read with a USB scanner on the PC or the phone camera.
- Stock Control Center: stock value at cost and retail, potential profit, stock by category, and alerts for low stock, out of stock and items not sold in 90 days.
- Supplier accounts with bills, payments and returns, and a spreadsheet import wizard for customers and stock.

**Staff, shifts and branches**
- Owner and staff logins with access set per screen.
- Shifts with X and Z reports, cash movements, manager PIN overrides and a staff audit log.
- My Branches (Windows): an owner with several shops sees each branch's sales, bills and low stock on one screen and can step into any branch.

**Tools, languages and security**
- 19 optical calculators in five categories, including transposition, vertex distance, spherical equivalent, Prentice prism, lens thickness and minimum blank size.
- Nine languages: English, Urdu, Arabic, Hindi, Turkish, German, Spanish, French and Portuguese, with right-to-left layouts for Arabic and Urdu.
- An offline help panel that answers how-to questions from a built-in product guide.
- Home-screen widgets on Android for quick actions, today's work and deliveries.
- Email or Google sign-in, a fingerprint or face lock on Android, in-app account deletion, and automatic background updates on Windows.

## Screenshots

### Windows desktop

All desktop screenshots use demo data.

<table>
  <tr>
    <td width="50%" align="center"><img src="screenshots/desktop/new_sale.webp" alt="Create New Sale dialog with a server-issued serial, customer details, line items, payment method and net payable"><br><sub><b>Counter sale</b> with a serial number issued by the server</sub></td>
    <td width="50%" align="center"><img src="screenshots/desktop/stock_control_center.webp" alt="Stock Control Center with stock value, retail value, potential profit, stock by category and alerts"><br><sub><b>Stock Control Center</b>: value, margins and alerts</sub></td>
  </tr>
  <tr>
    <td width="50%" align="center"><img src="docs/screenshots/desktop-search-customers.webp" alt="Search Customers table with balances, order status, fulfilment, prescription or repair type and WhatsApp actions"><br><sub><b>Customer search</b> with status, balance and fulfilment filters</sub></td>
    <td width="50%" align="center"><img src="screenshots/desktop/vision_calculators.webp" alt="Optical calculators screen with the transposition calculator"><br><sub><b>19 optical calculators</b> in five categories</sub></td>
  </tr>
  <tr>
    <td width="50%" align="center"><img src="screenshots/desktop/my_branches.webp" alt="My Branches screen listing each branch with today's sales, bills and low stock"><br><sub><b>My Branches</b> for owners with several shops</sub></td>
    <td width="50%" align="center"><img src="screenshots/desktop/dashboard_ar.webp" alt="Asaan Optics dashboard in Arabic with a right-to-left layout"><br><sub><b>Arabic</b> with a full right-to-left layout</sub></td>
  </tr>
</table>

### Android

<p align="center">
  <img src="screenshots/phone/2_prescription.webp" width="24%" alt="Receipt details with a full eye prescription for both eyes">
  <img src="screenshots/phone/3_receipt.webp" width="24%" alt="Receipt with ordered glasses, subtotal, advance and balance due">
  <img src="screenshots/phone/4_customers.webp" width="24%" alt="Customer search with pending balances and WhatsApp buttons">
  <img src="screenshots/phone/5_sales.webp" width="24%" alt="New product sale with Scan Barcode and Add from Inventory buttons">
</p>

<table>
  <tr>
    <td width="25%" align="center"><img src="docs/screenshots/android-add-prescription.webp" alt="Prescription order with a Scan Prescription button and frame and lens items from stock"><br><sub>Prescription order with the scanner</sub></td>
    <td width="25%" align="center"><img src="screenshots/mobile/repair_ticket.webp" alt="Repair ticket with patient details, job details and payment"><br><sub>Repair ticket</sub></td>
    <td width="25%" align="center"><img src="screenshots/mobile/eye_acuity.webp" alt="Distance visual acuity test with a tumbling E"><br><sub>Acuity chart</sub></td>
    <td width="25%" align="center"><img src="screenshots/mobile/eye_amsler.webp" alt="Amsler grid test"><br><sub>Amsler grid</sub></td>
  </tr>
</table>

### Website

<p align="center">
  <img src="docs/screenshots/website-transposition-calculator.webp" alt="Free optical transposition calculator on asaanoptics.com" width="80%">
  <br>
  <sub>The product website, <a href="https://asaanoptics.com">asaanoptics.com</a>, also offers free optical calculators such as the <a href="https://asaanoptics.com/transposition-calculator/">transposition calculator</a>.</sub>
</p>

## How it is built

- **Apps:** Flutter and Dart for the Android app and the Windows desktop app.
- **Backend:** a multi-tenant REST API in Node.js and Express, with every signed-in request checked against the shop it belongs to.
- **Data:** TiDB Cloud (MySQL-compatible) in production, SQLite on each Windows till, and Firebase for sign-in and push notifications.
- **Offline-first:** writes carry an idempotency key and wait in a durable queue when the connection drops, so a sale is never recorded twice. Each till keeps its shift and cash ledger locally.
- **On-device OCR:** Google ML Kit text recognition reads prescriptions on the phone, with no cloud call.
- **Billing:** Google Play billing through RevenueCat on Android, and card checkout for desktop plans.
- **Releases:** GitHub Actions and fastlane ship the Android app to Google Play; the Windows app is an Inno Setup installer that checks a version manifest and updates itself.

## Links

- Website: [asaanoptics.com](https://asaanoptics.com)
- Android app: [Google Play](https://play.google.com/store/apps/details?id=com.techwinesolutions.asaanoptics)
- Windows app: [Download](https://asaanoptics.com/download) · [Desktop details](https://asaanoptics.com/desktop-details)
- What's new: [asaanoptics.com/whats-new](https://asaanoptics.com/whats-new)
- Video overview: [Asaan Optics in 2 minutes](https://www.youtube.com/watch?v=QN14SsmsQpw)
- Tutorials: [Asaan Optics Tutorials playlist](https://www.youtube.com/playlist?list=PLI9xnOxtXgaE) (37 videos)
- Case study: [How I built Asaan Optics](https://farhadnazir.com/projects/asaan-optics/)

## Author

**Farhad Nazir**, founder and sole developer of Asaan Optics, [Techwine Solutions](https://www.techwinesolutions.com).

- Website: [farhadnazir.com](https://farhadnazir.com)
- Email: [farhadnazirksa@gmail.com](mailto:farhadnazirksa@gmail.com)
- LinkedIn: [linkedin.com/in/farhadnazir](https://www.linkedin.com/in/farhadnazir)
- WhatsApp: [+966 53 656 6380](https://wa.me/966536566380)
- GitHub: [github.com/farhadnazir](https://github.com/farhadnazir)

---

<p align="center">
  <sub>© 2026 Techwine Solutions. Asaan Optics is proprietary software; this repository does not include its source code.</sub>
</p>
