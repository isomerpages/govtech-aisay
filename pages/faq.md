---
title: FAQ
permalink: /faq/
variant: markdown
---
## Technical Capabilities

**1. What file types are supported?**<br>
JPEG/JPG, PNG, TIFF and PDFs are currently supported.

**2. Are there file-size limits?**<br>
A maximum of 20 megabytes.

**3. What is the difference between tailored and non-tailored processing?**<br>
- **Tailored processing** is typically faster, and works better on structured documents. (i.e, Passports, Invoices, Bank Statements etc) While we do have pre-built models for common use-cases, **we are able to cater custom models for unique use-cases**.
- **Non-tailored processing** is slower than tailored yet a great candidate for unstructured documents. (i.e, Contracts, Appeal Letters etc)

**4. What is the difference between Asynchronous and Synchronous APIs?**<br>
- **Asynchronous API** - Analysis request is accepted in a HTTP Request, and polling is necessary to retrieve the result. Recommended for larger/more complex files, or back-end processing use-cases.
- **Synchronous API** - Analysis request is retrieved and result is returned in a Single Request-Response cycle. Recommended for form-filling use-cases with smaller files. _PDFs are not supported._

**5. Does AISAY have a JavaScript (Frontend) SDK or a Mobile App SDK (Android/iOS)?**<br>
Unfortunately, **not yet**. Our current operational model requires your backend system to proxy requests from your frontend.