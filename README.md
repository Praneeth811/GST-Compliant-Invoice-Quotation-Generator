# GST-Compliant Invoice/Quotation Generator (Python + Colab UI)

##  Description

A fully interactive, GST-ready PDF document generator built in Python and optimized for **Google Colab**. This project lets you quickly create professional **Invoices**, **Quotations**, or **Bills** with your logo, company details, customer information, and itemized billing table — **all without any manual formatting**.

It supports:
- Dynamic table entry
- Auto-invoice numbering
- Place of Supply lookup with **State Code auto-fill**
- Branding with your **own logo and business name**
- GSTIN handling for both sender and recipient

Ideal for **freelancers**, **exporters**, **service providers**, or **SMEs** who need compliant documentation fast.

---

##  Features

 Upload your company logo (PNG)  
 Choose between: **INVOICE**, **QUOTATION**, or **BILL**  
 Auto-generate **Invoice Number**, **Issue Date**, and **Due Date**  
 Input fields for:
- Supplier & Recipient **GSTIN**
- Recipient address
- **Place of Supply** with automatic state code insertion

 Custom item table with user-defined columns (e.g., `S.No, Description, HSN, Qty, Rate, Amount`)  
 Dynamic table generation with any number of rows  
 Optional fields:
- **Bank Details**
- **Declaration / Notes** (auto-placed in PDF)

 Professionally styled PDF with:
- ROIxport branding (modifiable)
- Horizontal tables
- Signature section
- Clean layout and formatting

 PDF automatically generated and downloaded in Colab!

---

##  Built With

- `fpdf`: Lightweight PDF generator  
- `pandas`: Table and data handling  
- `ipywidgets`: Interactive dropdowns and buttons  
- `google.colab`: File upload/download integration

---
