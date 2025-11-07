# SHOPIFY-SALES-CUSTOMER-FUNNEL-REPORTS
SHOPIFY | CUSTOMER & SALES ANALYSIS
TERMINOLOGY DOCUMENT
1.	Admin GraphQL API ID
A globally unique identifier used by systems that support GraphQL APIs. This ID allows precise querying of specific records (like an order or product) within a backend system. It's generally not human-readable and is used programmatically.
2.	Order Number
A unique and typically sequential number or code assigned to each order placed by a customer. This number helps in tracking, referencing, and customer service queries. It's often shown in emails or invoices (e.g., #12345).
3.	Billing Address City
The city listed in the billing address provided by the customer at checkout or registration. This is used for tax calculation, fraud detection, and record-keeping.
4.	Billing Address Country
The country associated with the billing address. It can be useful for tax rules, payment gateway processing, and regional business reporting.
5.	Billing Address First Name
The first name of the person associated with the billing address. Often required for processing payments and generating invoices.
6.	Billing Address Last Name
The last name (surname) of the person on the billing address. Combined with the first name, it provides full identification.
7.	Billing Address Province
The province, state, or region as per the billing address. For example, "California" or "Maharashtra." This is often required for tax calculations and regional reporting.
8.	Billing Address Zip
The postal code (ZIP code) of the billing address. Used in shipping and tax estimation, and sometimes in fraud prevention by validating card transactions.
9.	CITY
Likely a redundant or duplicate field of "Billing Address City," but it could also be intended for a shipping city or a manually entered override field. Needs clarification or cleanup in the dataset.
10.	Currency
The type of currency used in the transaction, represented in ISO format (e.g., USD for US Dollars, EUR for Euros). It indicates the financial context in which the prices are recorded.
11.	Customer ID
A system-generated unique identifier for a customer. Used to link orders, communications, preferences, and order history to a specific customer.
12.	Invoice Date
The date the invoice was created or finalized for the transaction. This can be important for accounting, tax reporting, and determining payment terms.
13.	Gateway
The payment processing service used to complete the transaction. Examples include Stripe, PayPal, Razorpay, etc. This helps in reconciling payments and understanding transaction channels.
14.	Product ID
A unique identifier for the product being purchased. This is used internally to track inventory, pricing, and product performance across sales.
15.	Product Type
A classification or category of the product. For instance, it could be "Software," "Clothing," "Electronics," etc. Helps in reporting and filtering products.
16.	Variant ID
Products may come in multiple variants (e.g., different sizes or colors). The Variant ID uniquely identifies a specific version of the product.
17.	Quantity
The number of units of the product purchased in the order. Important for inventory management and sales volume analysis.
18.	Subtotal Price
The total cost of all items before applying taxes, shipping charges, or discounts. It reflects the base cost of the order.
19.	Total Price USD
The total price paid, including taxes and possibly shipping, converted to USD (if the transaction was in another currency). Useful for standardizing financial reporting across currencies.
20.	Total Tax
The total amount of tax (like VAT or GST) applied to the order. This is important for compliance and reporting in many regions.

