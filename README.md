# Balanced Tree Clothing Company
![image](https://github.com/user-attachments/assets/2883c6bd-e5e8-4e57-b3df-f7e6ff254d41)

## Intro

## Goal

## Case Study Questions
### What is the total amount each customer spent at the restaurant?

```sql
SELECT
  customer_id,
  SUM(price) as total_amount
FROM sales s
JOIN menu m
  ON s.product_id = m.product_id
GROUP BY customer_id
```
### How many days has each customer visited the restaurant?
```sql
SELECT
	customer_id,
	COUNT(DISTINCT order_date) as number_of_day
FROM sales
GROUP BY customer_id
```
customer_id	number_of_day
A	4
B	6
C	2
### What was the first item from the menu purchased by each customer?
```sql
```
### What is the most purchased item on the menu and how many times was it purchased by all customers?
```sql
```
### Which item was the most popular for each customer?
```sql
```
### Which item was purchased first by the customer after they became a member?
```sql
```
### Which item was purchased just before the customer became a member?
```sql
```
### What is the total items and amount spent for each member before they became a member?
```sql
```
### If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
```sql
```
### In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?
```sql
```
