# Internet-of-Things-Project---IOT-Project--Smart-Price-Tag-for-Future-Convenient-Store

This is arduino code implementation for the Internet of Things Smart Price Tag for the Internet of Things Project. Here is the project 
description and pseudocode.

Project Description : 
A smart price tag that can be changed in real time based on demand or supply trends and customer's purchase history and loyalty. This smart price tag system is connected with a cloud system which keeps track of the real time data of the supply and demand of various products and change the price of the product when required. Also it keeps track of the purchase record of a customer and makes decision whether he is loyal or not based on his past purchasing history. For example, if a customer purchases some particular items many times (15-20) times then there will be a specific discount given to the customers. So more and more customers will be interested to buy products more and thus a store can make more profit. Also since the price is based on real time (Real times means totally up-to-date time- Not 2 days ago or 3 days ago price), So a store can maximize its profit using this smart price tag. This types of tag have a great chance to lead the convenient store industry in future because of its various highly useful and important features. More important features can be added in future. Based on supply and demand theory pricing can be set using this model: 
1.In the supply and demand model of price determination, there is never a surplus or shortage of goods at the equilibrium level. The market always settles at the point where supply equals demand.
2.If demand increases (decreases) and supply is unchanged, then it leads to a higher (lower) equilibrium price and quantity.
3.If supply increases (decreases) and demand is unchanged, then it leads to a lower (higher) equilibrium price and higher (lower) quantity.
4.If a price for a particular product goes up and the customer is aware of all relevant information, demand will be reduced for that product.

Customer/ User Study- Discount calculation


Var customer
Var counter;
Var purchase;
Var discount;
Var product_price;
Counter = 0; 
counter = counter + 1;
if (purchase > 10 && purchase < 15) {
            Discount = total price * 0.10 // 10 percent discount //Provide 10 % discount for more than 10 to 15 times
            Product price = product_price- Discount
}
Elseif (purchase > 15 && purchase < 20)
      {
            Discount = total price * 0.15 // 15 percent discount //Provide 15 % discount for more than 15 to 20 times
            Product price = product_price- Discount
       }
Else {
            Discount = “No Discount”
       }

Pseudocode- Price Update

var  Price
var Demand 
var Supply
var  Shortage
var  Surplus 
var optimum
 \\ 1st condition test 
if (demand > optimum) {
    Price will increase;
}
else 
    Price will decrease;
\\ 2nd condition test
   if (supply> optimum) {
    Price will decrease;
}
else 
    Price will increase;
