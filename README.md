# Decodelabs  Cleaning Project

## Overview

This project focuses on cleaning and preprocessing an  dataset using Python and Pandas.

The dataset contains customer orders, products, prices, payment methods, coupon codes, and shipping information.

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

## Data Cleaning Steps

The following preprocessing steps were applied:

* Converted `Date` column to datetime format
* Removed unnecessary time values from dates
* Checked and handled missing values
* Filled missing `CouponCode` values with `"No Coupon"`
* Converted suitable columns into `category` datatype
* Rounded float columns to 2 decimal places
* Checked for duplicates
* Verified data types using `.info()`

---

## Dataset Features

The dataset includes:

* Order ID
* Customer ID
* Product
* Quantity
* Unit Price
* Total Price
* Payment Method
* Shipping Address
* Order Status
* Coupon Code
* Referral Source
* Tracking Number
* Items In Cart
* Date

---

## Output

A cleaned dataset was generated and exported as:

* `cleaned_data.xlsx`

---

## Author

Shahd Mahmoud
