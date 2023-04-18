# CSCProj

CSC PROJECT
NAME: PRIYANKA ANNAPUREDDY
REG ID: 2000032121
SEC: 13
QUESTION:
Build a serverless chatbot (voice and text) with Amazon Lex and integrate with Facebook
STEPS AND SCREENSHOTS:
1.	In management console open amazon lex and click on create a bot: custom bot ![1](https://user-images.githubusercontent.com/96176674/232716983-16467c07-a6d7-4e2f-a063-810d042c0c44.jpg)

2.	Click on create intent and give a unique name to the intent. Add sample greeting inputs given by the user. ![2](https://user-images.githubusercontent.com/96176674/232717544-a0167eaf-7947-4b7c-bc84-2bec8715319a.jpg)

3.	We can give the reply to the user using lambda or directly using amazon lex. In response, click on add message and type the response given by the bot.  ![3](https://user-images.githubusercontent.com/96176674/232717572-3c08db82-de85-499b-948d-82140df99d35.jpg)
4.	Click on save intent and then click on Build. You can test the responses of the bot using Test ChatBot in the right panel.
![4](https://user-images.githubusercontent.com/96176674/232717728-60dbac08-566b-4550-a1d5-6ad360302913.jpg)
5.	Similarly, we need to create other intents like ReservationIntent, ConfirmationIntent, ConclusionIntent and many more.
6.	In ReserveIntent, we need to add slots called Place to take input of the location and day from the user. ![6](https://user-images.githubusercontent.com/96176674/232718065-af715735-ebf0-4dcc-91f0-63a6e0b1571c.jpg)
![22](https://user-images.githubusercontent.com/96176674/232718461-4b27fbde-9ed9-4bfe-b31b-850b70dcad54.jpg)

7.	Click on save intent and then click on Build. You can test the responses of the bot using Test ChatBot in the right panel. ![eae](https://user-images.githubusercontent.com/96176674/232718555-0e74563c-ae6d-40a9-997f-bb8c0f8dffa4.jpg)

8.	Create another Intent to greet the customers for booking.
![8](https://user-images.githubusercontent.com/96176674/232718665-67180864-dfec-4326-aaeb-a3a529949938.jpg)

9.	After verifying, click on publish on the top right, give a name to the bot & alias name, and then click on go to channels. Click on activate and copy the url given below.
10.	Now, open developers.facebook.com and then login with your Facebook account > My Apps > Create app.
11.	Select Business in type and app name in details
12.	In products, click on set up for messenger application. In Access Token section click on add/remove pages. Above copied link should be pasted in the Webhooks > add callback url. 
![77](https://user-images.githubusercontent.com/96176674/232718818-4678d4cb-cd57-4dfe-996a-29d528d42653.jpg)
![4wfe](https://user-images.githubusercontent.com/96176674/232718919-0daf5147-1806-410a-ba2d-17a44bbc3a30.jpg)
It should look like this![f](https://user-images.githubusercontent.com/96176674/232719043-06ee709f-c971-49cb-9b20-5a4fe7641c67.jpg)

click on add subscription>messages>save
 ![done](https://user-images.githubusercontent.com/96176674/232719158-c1281c3b-8a46-4a5d-b342-062b8476cb67.jpg)

THE CHATBOT IS WORKING SUCCESSFULLY FOR THE FACEBOOK PAGE.
HENCE, A CHATBOT HAVE BEEN BUILT FOR FACEBOOK USING AMAZON LEX.
