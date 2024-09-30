# Myntra Product & Brand Analysis

This project performs a comprehensive analysis of product and brand data from a dataset of nearly 150,000 products listed on Myntra. It focuses on understanding brand popularity, pricing, and product performance based on factors like ratings, discount strategies, and tags.

## Table of Contents

- [Introduction](#introduction)
- [Dataset Information](#dataset-information)
- [Project Overview](#project-overview)
  - [1. Product Performance Analysis](#1-product-performance-analysis)
  - [2. Pricing Analysis](#2-pricing-analysis)
  - [3. Brand Popularity Analysis](#3-brand-popularity-analysis)
  - [4. Tag and Category Analysis](#4-tag-and-category-analysis)
  - [5. Discount Impact Analysis](#5-discount-impact-analysis)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This project explores various aspects of product and brand performance using the Myntra dataset. It helps identify patterns in product ratings, pricing, brand popularity, and discounting strategies.

## Dataset Information

The dataset used for this analysis contains the following columns:

- `product_name`: The name of the product.
- `brand_name`: The brand of the product.
- `rating`: The product's rating (on a scale of 1-5).
- `rating_count`: The number of ratings the product has received.
- `marked_price`: The original price of the product.
- `discounted_price`: The price after discount.
- `sizes`: Available sizes for the product.
- `product_link`: URL of the product.
- `img_link`: URL of the product image.
- `product_tag`: Tags associated with the product.

## Project Overview

This project is divided into several parts that provide insights into product performance, pricing strategies, brand popularity, and discounting trends.

### 1. Product Performance Analysis

- **Top-rated products overall**: Find the highest-rated products.
- **Products with the highest number of ratings**: Identify which products have received the most ratings.
- **Correlation between ratings and the number of ratings**: Analyze how product ratings correlate with the number of ratings received.

### 2. Pricing Analysis

- **Average marked and discounted price for different categories**: Compare original and discounted prices.
- **Average discount percentage**: Determine the average discount across all products.
- **Brand-wise discounting trends**: Analyze how discounting strategies vary across different brands.

### 3. Brand Popularity Analysis

- **Brands with the highest number of products listed**: Identify the most popular brands in terms of product count.
- **Average brand ratings**: Determine which brands have the highest average product ratings.

### 4. Tag and Category Analysis

- **Tags associated with the highest-rated products**: Analyze product tags that are correlated with better ratings.
- **Performance of specific tags in ratings and discounts**: Compare how specific tags impact both ratings and discount rates.

### 5. Discount Impact Analysis

- **Discounts vs. ratings**: Explore whether higher-rated products tend to have lower discounts.
- **Rating count vs. discount**: Investigate the relationship between the number of ratings and the level of discount offered.

## Technologies Used

- **Python**: For data processing and analysis.
- **Pandas**: For data manipulation.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive code and visualizations.

