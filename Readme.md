Model:
id -> primary key and int, 
name -> String, 
desc -> String, 
brand -> String, 
price -> int, 
Category -> String, 
releaseDate -> Date, 
available -> boolean, 
quantity -> Int, 
Image, 

SQL:
INSERT INTO product (name, desc, brand, price, category, release_date, available, quantity)
VALUES
('Tata Nexon', 'A compact SUV with 5 star safety and better performance than competition', 'Tata Motors', '750000', 'cars', '2024-01-15', true, 50),
('iPhone 15', 'Latest smartphone with A16 chip and dynamic island display', 'Apple', '120000', 'electronics', '2023-09-25', true, 100),
('Sony Bravia 55"', '55 inch 4K OLED Smart TV with advanced picture and sound quality', 'Sony', '140000', 'electronics', '2023-11-05', true, 30),
('Adidas Ultraboost', 'Premium running shoes with Boost technology for superior cushioning', 'Adidas', '15000', 'footwear', '2024-02-01', true, 200),
('Samsung Galaxy Tab S9', 'Latest Android tablet with AMOLED display and S-Pen support', 'Samsung', '80000', 'electronics', '2024-03-10', true, 60),
('Hero Splendor Plus', 'Best-selling commuter motorcycle with great fuel efficiency', 'Hero', '70000', 'bikes', '2023-12-20', true, 150);


