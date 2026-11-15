# ChitTill

**Billing software for clothing stores, by CraftedSoft.** Scan, bill, print and close the day in seconds. ChitTill handles sizes and colours, GST, offers, loyalty points, barcode labels and stock, and it runs on your own counter PC with no internet needed.

## ⬇️ Download

**[Download ChitTill for Windows](https://github.com/delogreleases/chittill-releases/releases/latest)** (latest version)

Open the latest release and download `ChitTill-Setup-<version>.exe` from **Assets** (about 124 MB). Every new install runs as a **7-day free trial**.

---

## What you need

- A **Windows 10 or Windows 11 PC, 64-bit**. To check, go to Start → Settings → System → About; "System type" should say "64-bit operating system". ChitTill does not run on Windows 7 or 8.
- A **bill printer** (80 mm or 58 mm thermal). A4 printers and barcode label printers also work: any printer Windows can print to.
- A **pen drive** or a Google Drive folder on the PC, for backups.
- Recommended: a **UPS** for the PC, so a power cut can't interrupt a save.

The internet is not needed, not even to activate your licence.

## Install

1. **Install your printers first.** Install the driver from the printer maker and print a test page from Windows. ChitTill only lists printers that Windows already knows.
2. Double-click `ChitTill-Setup-<version>.exe`.
3. Windows may show **"Windows protected your PC"**. Click **More info → Run anyway**. The installer is safe; Windows shows this because it isn't signed yet.
4. A short progress bar runs, then ChitTill opens its setup:
   - **Shop details:** name, address, phone, GSTIN (optional) and state.
   - **Bill and branding:** bill number prefix and starting number, UPI ID, footer and terms, and your logo.
   - **Printers and owner PIN:** choose your printers and bill paper size, then press **Print a test bill**. Set your name and a PIN. **Remember the PIN**: it opens ChitTill every day.
5. A **ChitTill** icon is added to your desktop and Start menu.

## What ChitTill does

**Billing counter**
- Scan a barcode or type a code or name, then pick the size and colour.
- Take **Cash, UPI (with a QR on the bill), Card or Split** payments, with change worked out for you.
- Offers, loyalty points and GST are calculated live on every bill.
- Keyboard-first: **F2** new bill · **F4** hold · **F5** recall · **F6** return · **F9** use loyalty points · **F10** save & print.

**Stock by size and colour**
- Stock is counted per size and colour, with live stock shown right at billing.
- Low-stock and out-of-stock lists, stock value at cost and every stock movement.
- Purchases and supplier bills with GST go straight into stock.

**Offers and loyalty**
- Buy X get Y, item discounts and bill discounts (for example "₹200 off above ₹5,000"), with start and end dates. ChitTill applies the right offer by itself.
- Customers earn loyalty points on every bill, with their visits and spend saved.

**GST and reports**
- Bills show CGST + SGST or IGST with HSN codes; apparel slab rates are applied by price; B2B bills carry the buyer's GSTIN.
- **Day close** (F12) with a cash check and an automatic backup.
- Sales, profit after expenses, and GST reports (rate-wise and HSN-wise, net of returns), with Excel export for your accountant.

**Everything else**
- Held bills, returns and exchanges with credit notes, and search and reprint for every bill.
- Barcode labels: design price tags and print 50×25, 38×25 or A4 sheets.
- Staff roles and PINs: Cashier, Stock keeper, Manager and Accountant, each seeing only their own screens.
- 80 mm and 58 mm thermal bills, A4 invoices and PDFs.
- Light and dark themes, plus larger text sizes for the counter.

## Set up backups (do this on day one)

ChitTill keeps everything on this PC. If the PC breaks or is stolen, a backup is the only copy.

1. Go to **Settings → Backup** and choose your pen drive or Google Drive folder.
2. Under **Automatic backup**, choose how often (the default is every day at 9 pm). ChitTill also backs up every time you close the day, and you can press **Back up now** at any time.
3. Keep the pen drive away from the PC. A backup next to the PC is lost with the PC.

If backups aren't set up, or the last one is more than 3 days old, a yellow line at the top of the screen tells you, with a **Back up now** button.

## Activate your licence

ChitTill works free for **7 days** on the Standard plan. To keep billing after that:

1. Go to **Settings → Licence**, press **Copy** next to the **Machine ID**, and send it to us on WhatsApp or by email (see below).
2. Paste the key we send back (it starts with `CTL-`) and press **Activate**.

A key works only on the PC it was made for. If your trial or licence ends, **your data is never deleted or locked**: reports, reprints, GST export and backups keep working. Only new bills, purchases and stock changes wait until a key is entered.

Keep the PC's date and time correct. Turning the clock back does not extend a trial or licence.

## Update to a new version

1. Close the day if you can (this makes a fresh backup), then close ChitTill.
2. Download the new `ChitTill-Setup-<version>.exe` from [Releases](https://github.com/delogreleases/chittill-releases/releases/latest) and run it the same way as the first install.
3. ChitTill opens with all your data. If the new version needs to change the database, it saves a copy first.

## Moving to a new PC

Install ChitTill on the new PC, then contact us. We help you restore your latest backup and send a licence key for the new PC (a new PC has a new Machine ID). Enter the key **after** restoring the backup.

## Where your data is

Your bills, products and settings are in **`%APPDATA%\ChitTill`** (paste that into the File Explorer address bar to open it). **Never delete, move or edit this folder.** Uninstalling or reinstalling ChitTill does not touch it.

## Licences and pricing

- Licences are **yearly**, one per PC. The price depends on the plan (Standard or Pro) and any customisation you need.
- The **first year of updates is free**. After that, choose Annual Maintenance (renewal and updates) or Licence only.
- **All payments are final; we do not offer refunds.** Please use the free trial and a free demo to make sure ChitTill fits your shop before you buy.

## Help and support

From the CraftedSoft team, the engineers who build ChitTill:

- **WhatsApp / phone:** [+91 90809 74663](https://wa.me/919080974663)
- **Email:** [craftedsoftofficial@gmail.com](mailto:craftedsoftofficial@gmail.com)
- **Hours:** Mon–Sat, 9:30 am – 7:00 pm

We can also install ChitTill at your shop, move your data from your old software and train your staff.

---

© 2026 CraftedSoft · Designed and built in India
