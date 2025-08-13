# Coffee_Machine_App-PowerApps-PowerAutomate-PowerBI-
☕ Coffee Machine App

A Power Apps application paired with a Power BI dashboard to manage coffee machine inventory, process customer orders, and analyze sales performance.
Developed for Infrastructure Development Authority of the Punjab.

📌 Overview

This project combines Power Apps for interactive inventory/order management and Power BI for business intelligence insights.
It enables full CRUD operations, real-time stock updates, and visual sales analysis.

🚀 Features
Power Apps

Filter Panel

Filter machines by Type, Price Range, and Primary Color.

Real-time stock availability check.

Machine Gallery

Display machine details: Name, Color, Price, Type, Summary, Average Espresso.

Add to cart or view machine details.

Machine Management (CRUD)

Create – Add new machines.

Read – View machine details.

Update – Edit machine data.

Delete – Remove machines from inventory.

Order Checkout

Select multiple machines to order.

Collects Customer Name and Email.

Generates Unique Order ID.

Stores order data in the Orders table.

Data Sources

Excel (OneDrive/SharePoint)

Machine Table – Machine details (ID, name, price, stock, etc.)

Orders Table – Order details (Customer, Machine ID, Quantity, Date).

Power BI Dashboard

Page 1 – Sales Overview

KPIs: Total Orders, Revenue, Stock Status.

Sales by customer, machine type, and color.

Interactive slicers for filtering.

Page 2 – Regional Insights

Interactive map of machine distribution in Pakistan.

Machine revenue performance by region.

City-based filtering with detailed tooltips.

🛠 Key Functionalities

Dynamic filtering with dropdowns & sliders.

Order validation based on stock.

Unique order ID generation (timestamp-based).

Global variables for state management.

Interactive BI visuals for decision-making.

📊 Data Model

Tables:

Machine – Inventory details.

Orders – Customer purchases.
Relationship: Linked via MachineID.
