# RoyalHackElites
Solution for Zero Hunger (Theme for IBM Call for Code Hackathon 2021)

## Contents

1. [Overview](#overview)
2. [Video](#video)
3. [The idea](#the-idea)
4. [How it works](#how-it-works)
5. [Diagrams](#diagrams)
6. [Documents](#documents)
7. [Datasets](#datasets)
8. [Technology](#technology)
9. [Getting started](#getting-started)
10. [Resources](#resources)
11. [License](#license)

## Overview

### What's the problem?
Approximately 9 percent of the global population is suffering from hunger. And, much of the world’s food is grown by small-scale, independent farms and distributed through local community cooperatives who sell the surplus produce. The co-ops are a central point for quality control, deliveries, and enabling food commodity markets. However, these co-ops face a myriad of logistical challenges to get the right food to the right places with minimal time and cost.

### Idea/Innovation Opportunity Scenario 

In this real-world of global hunger challenge, Design of an Mobile and Web app will act as one stop for creating awareness of food security, improving nutrition, and promoting sustainable agriculture as well as help accomplishing our goal of Zero Hunger. It will ensure that food provider reduces food wastage and provides the food to needy on time by any delivery platform. It will help improve access to nutritious food in local communities and those suffering from acute hunger.
Idea is to design a Mobile Application (App Name: ZHunger) which will ensure people in hunger receives food as well as it will ensure that food provider doesn't waste food and provide the needy on time . Also to improve access to nutritious food in local communities, especially those suffering from acute hunger, co-operative systems can be digitized and enhanced. By aggregating and analyzing market, transportation, demand, horticultural, and environmental data, co-ops can optimize productivity, reduce overhead, and decrease volatility in the supply chain of the farming communities. Farmers would be able to upload the crop production photos for quality analysis and testing using AI and ML services after which they will receive the results via Messaging services.
Learning from the User : Mobile will assess the behavior pattern of user by observing the various tasks completed and helping the needy. It will notify the user to accomplish the goal, predict the necessary science behind the scene on the collected data and will provide farmers and other users the information about food security, improving nutrition, and promoting sustainable agriculture.
Badge gamification for the User : Mobile App will assess the behavior pattern of the user and provide badges and points over each completion of task or help provided by the user and will get some goodies time to time for encouragement and make this process continue for long.
Data classification : Business insights can be retrieved from the data collected from the Mobile app interaction with the user which in turn helps in creating more awareness in the targeted areas (targeted areas can be predicted through applying classification algorithm on data retrieved through mobile app interaction with user) .Insights achieved through data can help government in maintaining sustainable food production systems accordingly.

IBM Watson Assistant service helps you build, train, and deploy conversational interactions into any application, device, or channel. Creating a chatbot using Watson Assistant can help us achieve Zero Hunger.

## Video

https://www.youtube.com/watch?v=MCnOLRmb1r8

## Telegram ZHunger Chatbot

https://t.me/ZHungerbot

## Zero Hunger Web integration link

https://node-red-bsapj-2021-07-21.eu-gb.mybluemix.net/home

## Business benefits 

Implementation of Mobile app with all the features will reduce the maintenance of several application say wfp.org/zero-hunger , un.org/sustainabledevelopment/poverty/ and so on ..  It will act as one stop application which will provide entire source information about food security, improving nutrition, and promoting sustainable agriculture and with nearby information of food availability.
1.	Prevents or reduces food wastage and ensures food availability.
2.	Aid in food security, improving nutrition, and promoting sustainable agriculture.
3.	Helps farmers improve their nutritious quality of crop production.
4.	More business insights can be generated from the data retrieved through the data collected from user interaction with the mobile app. Data insights from the environment would help for better crop resilience and overall yield for sustainable food production systems. More crops mean better access to food for the community.

## How it works


## Diagrams

### Website integration with Zero Hunger communication chatbot

![ZHunger IBM Architecture](/Images/ZHunger IBM Architecture.png)

1.	User visits a website or App with the ZHunger chatbot and tells he/she is hungry.
2.	Node.js web server calls the Watson Assistant service hosted in IBM Cloud.
3.	Watson Assistant uses natural language understanding and machine learning to extract entities and intents of the user question.
4.	Watson Assistant replies to the user inquiry.
5.	Watson Assistant invokes an OpenWhisk open source powered IBM Cloud Function.
6.	User provides his/her Name, Address and Location Pin code for tracking and food delivery by Drone.
7.	User will be getting Weather information so that they can decide which crop would be suitable for growth according to the weather condition
8.	Watson Weather Dashboard will be helping the users to clearly visualize the weather of the Area.
9.	Watson assistant conversation with user will be stored in the cloundant DB.
10.	Cloudant DB data will be feed to machine learning algorithm for predictions like how far we were able to solve Zero Hunger goal.
11.	Predicted data will be stored in CSV format and same will be feed to IBM COGNOS dashboard for display insights


## Datasets

- We used the conversational chat history of the bot with user 

## Technology

### IBM technology

- [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/)
- [IBM Cloud Functions](https://cloud.ibm.com/functions/)
- [IBM Cloudant DB](https://www.ibm.com/cloud/cloudant/)
- [IBM Watson Studio](https://cloud.ibm.com/functions/)
- [IBM Cognos Dashboard](https://www.ibm.com/cloud/watson-studio/)


### Open source technology
- [Node-RED](https://nodered.org/)
