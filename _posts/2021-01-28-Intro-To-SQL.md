---
title: "Intro To SQL"
date: 2021-01-28
---
When I started this course, I didn’t really expect much from it. I knew what SQL was, and querying didn’t sound all that interesting to me. I was surprised how much it started to intrigue me when I took the course. Querying turned out to be far more important than I realized and actually sitting down and making small things with it opened my eyes to how much work goes behind each and every password system, user base or database. There was a lot of neat code behind it and I think that it was a good experience to be able to see that firsthand. Learning how to use SQL to do even basic tasks was a big help to broadening the horizon of what’s possible and that all of the back-end aspects of computer science are far more interesting than I ever gave them credit for.  

Here is a Gif of a completed project in this module:  
<img src="https://raw.githubusercontent.com/lydiaroy/portfolio/master/assets/images/intro-to-sql.gif" alt="Image of the Store Database project.">  
This project can be found here at <a href="https://www.khanacademy.org/computer-programming/spin-off-of-project-design-a-store-database/4793683657834496">Khan Academy</a>  

Here is the code for the same project:
``` 
CREATE TABLE storeInfo (id INTEGER PRIMARY KEY, item TEXT, itemDesc TEXT, price INTEGER, stock INTEGER);

INSERT INTO storeInfo VALUES (1, "T-Shirts", "Various T-Shirts; many colours", 5, 956);

INSERT INTO storeInfo VALUES (2, "Shorts", "Regular shorts; many colours", 5, 795);

INSERT INTO storeInfo VALUES (3, "Jogging Pants", "Jogging pants; grey", 10, 587);

INSERT INTO storeInfo VALUES (4, "Jeans", "Jeans; blue", 15, 614);

INSERT INTO storeInfo VALUES (5, "Sweaters", "Hoodie-style sweaters; black", 5, 844);

INSERT INTO storeInfo VALUES (6, "Hats", "Hats; many colours", 2, 913);

INSERT INTO storeInfo VALUES (7, "Sunglasses", "Sunglasses; brown", 2, 541);

INSERT INTO storeInfo VALUES (8, "Socks", "Socks; white", 1, 365);

INSERT INTO storeInfo VALUES (9, "Gloves", "Gloves; black", 2, 592);

INSERT INTO storeInfo VALUES (10, "Boots", "Boots; white", 20, 315);

INSERT INTO storeInfo VALUES (11, "Coat", "Coat; grey", 50, 90);

INSERT INTO storeInfo VALUES (12, "Scarf", "Scarf; red", 4, 484);

INSERT INTO storeInfo VALUES (13, "Shoes", "Shoes; many colours", 60, 29);

INSERT INTO storeInfo VALUES (14, "Jacket", "Jacket; black", 20, 50);

INSERT INTO storeInfo VALUES (15, "Sandals", "Sandals; pink", 3, 435);

SELECT * FROM storeInfo ORDER BY price;
```
