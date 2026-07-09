# Data Dictionary

## Overview

This document describes the datasets used in the Retail Analytics Platform. Each dataset represents a core business entity and supports reporting and analytics.

---

## Orders

**Description**

Contains one record for each customer order.

**Primary Key**

- order_id

**Example Columns**

- order_id
- order_date
- customer_id
- product_id
- quantity
- sales_amount
- discount
- profit

---

## Customers

**Description**

Stores customer demographic information.

**Primary Key**

- customer_id

**Example Columns**

- customer_id
- first_name
- last_name
- city
- state
- country
- segment

---

## Products

**Description**

Contains product information.

**Primary Key**

- product_id

**Example Columns**

- product_id
- product_name
- category
- sub_category
- brand
- unit_price

---

## Returns

**Description**

Stores returned orders.

**Primary Key**

- return_id

**Example Columns**

- return_id
- order_id
- return_date
- reason

---

## Inventory

**Description**

Tracks inventory levels.

**Primary Key**

- inventory_id

**Example Columns**

- inventory_id
- product_id
- warehouse
- stock_quantity

---

## Marketing

**Description**

Contains marketing campaign performance.

**Primary Key**

- campaign_id

**Example Columns**

- campaign_id
- campaign_name
- spend
- clicks
- impressions
- conversions