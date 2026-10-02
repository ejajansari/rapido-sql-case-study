# Rapido-Inspired Ride Booking SQL Case Study

## 1. Project Overview

This SQL case study analyzes a synthetic / academic Rapido-inspired ride-hailing database in MySQL. The project focuses on ride activity, customers, captains, cities, vehicle types, revenue, payments, cancellations, and ratings.

## 2. Project Goal

The main goal is to use SQL to analyze ride-booking data and generate meaningful business insights related to rides, customers, captains, revenue, payments, and service performance.

## 3. Key Objectives

- Analyze ride performance across cities.
- Compare Bike, Auto, and Cab usage.
- Analyze revenue, fares, distance, duration, and surge pricing.
- Identify high-value customers based on ride activity.
- Evaluate captain performance using completed rides and ratings.
- Analyze cancellation patterns and reasons.
- Analyze customer payment preferences.
- Evaluate customer satisfaction using ratings, reviews, and sentiment.
- Identify top-performing captains and customers.
- Practice JOINs, subqueries, GROUP BY, HAVING, aggregate functions, CASE expressions, and window functions.

## 4. Dataset Structure

The source SQL dump contains:

- 12 cities
- 3 vehicle types
- 193 localities
- 19 cancellation reasons
- 16,980 customers
- 3,001 captains
- 50,000 rides
- 7,844 ride cancellations
- 43,760 payments
- 31,579 ratings/reviews

## 5. Main Tables

### Reference tables
- `payment_methods`
- `cities`
- `vehicle_types`
- `localities`
- `cancellation_reasons`

### Master tables
- `customers`
- `captains`

### Transaction tables
- `rides`
- `ride_cancellations`
- `payments`
- `ratings_reviews`

### View
- `vw_ride_details`

## 6. Business Questions

The query file contains questions covering:

1. Completed rides by city
2. Ride volume by vehicle type
3. Highest cancellation city
4. Highest-rated captain
5. High-performing captains
6. Captains above average rating
7. Revenue by vehicle type
8. Revenue by city
9. Top 3 captains in each city by completed-ride revenue
10. Most-used payment method
11. Cancellation reasons
12. Average fare by vehicle type
13. Top customers by completed rides
14. Average customer rating by city
15. Overall cancellation percentage

## 7. SQL Skills Demonstrated

- Filtering with `WHERE`
- Aggregation with `COUNT`, `SUM`, and `AVG`
- `GROUP BY`
- `ORDER BY`
- `LIMIT`
- `CASE`
- `JOIN`
- Scalar and correlated subqueries
- Window functions
- `DENSE_RANK()`
- Views

## 8. Interpretation Note

All business findings should be described as findings from this synthetic dataset. They should not be presented as official operational statistics of Rapido.

## 9. Portfolio Presentation

For a portfolio or interview, explain the project in this order:

1. Business problem
2. Dataset and database structure
3. SQL concepts used
4. Important business questions
5. Key query results
6. Business interpretation of those results
7. What you learned from the project
