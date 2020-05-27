# PR20MA

Data Mining Project - Black Friday Sales

## Introduction - Describing the problem

One of the most popular sales nowadays is the Black Friday Sale that actually happens in a certain period of time, every year. People are following the trend and tending to buy a variety of things, such as: clothes, shoes, electronics, furniture, etc. However, people are used to the fact that they should buy only because of the low price, neglecting the purpose for some of the things. Moreover, there are people who tend to bargain and buy things only for the purpose of resaling them for a higher price. However, women are most likely to shop more clothes than men, but what is the purpose of this project is to give answers to these types of questions.

#### These are following questions that I am trying to give the most objective answer:

##### 1. In which city people tend to buy the most amount of products?

##### 2. Who is most likely to spend money on Black Friday, men or women?

##### 3. Should the age be considered as one of the factors for shopping the most?

##### 4. Should we consider marriage as one of the factors, why people are tending to buy things for their sagnificant other or not?

## Data - Describing the data

### The dataset that I am using for my project is called Black Friday.csv and it consists of 12 columns, combined together in a total size of 24 MB.

The unique columns are User_ID which refers to a single user and Product_ID refering to a single product. User_ID is an integer and it contains 7 digits, from 0-9. Classification of products is made in such way that they are divided in 3 different categories, such as: Product_Category_1, Product_Category_2 and Product_Category_3. Each product start with PXXXXXXXX, where Xs stand for digits 0-9. There are 3623 different products, placed in 3 categories, each category contains the amount of the product. Each category can contain maximum number of quantity = 18.

Other categories are: Gender which contains 2 values: M stands for Male and F for Female, Age which divides the ages in 7 groups such as: 0-17, 18-25, 26-35, 36-45, 46-50, 51-55 and 55+. Occupation containing 20 different types of vocations, City_Category refering to 3 different categories: A, B and C, Stay_In_Current_City that expresses the number of stays per person in one city, starting from 1,2,3,4 and 4+ for people who are tending to stay more in one city, Marital_Status contains 0 for single and 1 for married person and Purchase for the total amount of products that a single person bought and starts from 185 till 24K.

### The main findings

Amongst the common stereotypes that the women are keen on buying products and necessities more than men, from the findings, we can see that the male population is at the top of the charts when it comes to buying things.

![](https://i.imgur.com/cIsNEkR.png)

Difference is also seen in the marital status of people:

![](https://i.imgur.com/WMVMj5U.png)

Singles are more likely to buy on Black Friday, than married couples.

And the results in these 2 chars show that of singles, men tend to buy for 0.2% more than women do:

![](https://i.imgur.com/Az06y9O.png)

What we can also see is that the citizens in one city have more consumption of the items in citizens in other city.

![](https://i.imgur.com/uas8KFT.jpg)

Which from the chart, we can see that the most leading category for cities is the second - B.

When the day comes, during black Friday, we can see a rise of the shopping spree at the age of 26-35.

![](https://i.imgur.com/74BETLE.jpg)

People who belong in this category are spending the most money than people from other categories.

## Most interesting results

The most shocking part for me was that men are spending more money than woman and also the singles are more likely to spend money than the married couples, and between these 2 facts, men from the single category are spending the most money with the percentige of 58 against women with 56.

In conclusion:

1. Men go to Black Friday more than women and spend more than women.

2. Two age groups can be identified with higher purchase : 26-35 and 18-25 In the City_Category_A dominant buyers are Males In the City_Category_B they are at the same level In the City_Category_C dominant buyers are Female People living in the City_Category = C are tending to make more purchase than people living in the 2 other city categories. For City_categories B and C, Males tend to dominate the purchasing, whereas Females tend to puchase more in the city_category = A.

3. The stark difference in the purchase acoss City_Categories for the Age Group of 55 and above. It is highest in City_Category_B, as compared to the other age groups which tend to show high purchase in City_Category_C.

4. People who are married tend to buy more than the single people.

5. Most of the purchase is done between 5000-10000 products.

6. Singles tend to spend more money than married people.