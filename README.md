# CSCProj

CSC PROJECT
NAME: PRIYANKA ANNAPUREDDY
REG ID: 2000032121
SEC: 13
QUESTION:
Build a serverless chatbot (voice and text) with Amazon Lex and integrate with Facebook
STEPS AND SCREENSHOTS:
1.	In management console open amazon lex and click on create a botcustom bot
2.	Click on create intent and give a unique name to the intent. Add sample greeting inputs given by the user. 
3.	We can give the reply to the user using lambda or directly using amazon lex. In response, click on add message and type the response given by the bot.
4.	Click on save intent and then click on Build. You can test the responses of the bot using Test ChatBot in the right panel.
5.	Similarly, we need to create other intents like ReservationIntent, ConfirmationIntent, ConclusionIntent and many more.
6.	In ReserveIntent, we need to add slots called Place to take input of the location and day from the user.
7.	Click on save intent and then click on Build. You can test the responses of the bot using Test ChatBot in the right panel.
8.	Create another Intent to greet the customers for booking.
9.	After verifying, click on publish on the top right, give a name to the bot & alias name, and then click on go to channels. Click on activate and copy the url given below.
10.	Now, open developers.facebook.com and then login with your Facebook account > My Apps > Create app.
11.	Select Business in type and app name in details
12.	In products, click on set up for messenger application. In Access Token section click on add/remove pages. Above copied link should be pasted in the Webhooks > add callback url. 
click on add subscription>messages>save
 
THE CHATBOT IS WORKING SUCCESSFULLY FOR THE FACEBOOK PAGE.
HENCE, A CHATBOT HAVE BEEN BUILT FOR FACEBOOK USING AMAZON LEX.
