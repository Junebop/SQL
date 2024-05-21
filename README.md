SELECT * 
FROM superstore
ORDER BY price
LIMIT 10;

SELECT SUM(price)
FROM superstore
WHERE category "Kitchen Supplies";

SELECT item_name
FROM superstore
WHERE category = "Electronics";
