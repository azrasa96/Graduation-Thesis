Implementing IBM Watson customer service chatbot

E-commerce site works 24/7/365, and they need customer service that can follow that pace. 
For my graduation thesis I made fully functional E-commerce site that sells designer shoes (I am just a woman who loves shoes). I made this with WordPress, mainly because WordPress has plugin for Watson Asistent. 
How I made Watson: 
Intent: you can see intent as one big category. For example Shipping, or My Account. Because your user can just type what ever he/she wants you need to declare every posible answer. Because I am making customer service, and that is pretty big field, i devide it into categories and subcategories. And every time you want something, Watson will recognize category, and then you type in specific subcategory that are offered and he will give you answer. 
Entity: is a subcategory. And you define it, give example and it is trigerd when categry recognize that user is trying to know information from that subcategory. 
Dialog: is where you define what will Watson say. 

Example: 
User typed in „How much shipping cost?“
What is happening in backround: 
Because i structures it to only search intents, he will search for that example there. He finished searching when he found match in Customer_service_Shipping intent. He replayed with provided answer promting user to type in one of subcategorys provided. 
User types in „shipping rates“, as the name of one subcategory
Watson in backgroud is now searching for enteties that have value „shipping rates“ in chiled nodes of category Customer_service_Shipping intent. He finished the search when he found that entite, and displayed the answer. 

Categories and subcategories of customer service: 
Hours of Operation
Directions 
Rules and policies 
Transfer to an agent 
•	Yes
•	No 
Shipping 
•	Track my item 
•	Shipping rates
•	Delivery date
•	Combined shipping 
•	Changing adress after ordering 
Paying options 
•	Paying with PayPal 
•	Paying when delivered 
My account 
•	Create account 
•	LogIn & LogOut 
•	Change my settings 
•	My account is hacked 
•	How to protect my account 
•	Delete account 
Help with buying 
•	How buying works
•	See my order 
•	How to use search 
•	Cancle my order 
Wishlist 
Returns and refunds 

And for most of answers Watson will provide you a link to a post on FAQ  page that is titeld as subcategorie and will give you more info about that praticular subject. 

Check it out at: https://highheelssociety.000webhostapp.com/  (please be patient, you can wait for answer few minutes even – I have free hosting. If Watson does not know, he will say “I don’t understand”).


