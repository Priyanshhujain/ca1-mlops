# E-Commerce Price Prediction

## Problem Statement

The goal of this project is to predict the future price of an e-commerce product based on its features such as product category, price, discount, and sales quantity. This model will assist users in estimating the likely future price of a product, helping them make informed purchasing decisions.

## Dataset

The dataset used for this project contains information about various e-commerce products, including:
- **Product Name**: The name of the product.
- **Category**: The category under which the product falls (e.g., Electronics, Gadgets, Accessories).
- **Price**: The initial price of the product.
- **Discount**: Discount percentage on the product.
- **Sales Quantity**: The number of units sold.
- **Future Price**: The price after applying the discount, which is our target variable.

You can generate the dataset with the provided code in the `ecommerce_data.csv` file.

## Project Structure

```bash
├── e_commerce_price_prediction.py   # Python script for training the model
├── ecommerce_data.csv               # Dataset for training and testing
├── test_e_commerce_price_prediction.py # Unit tests
├── README.md                        # Project documentation
