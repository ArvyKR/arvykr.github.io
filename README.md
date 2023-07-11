# Implementation AI Chabot for Kampus Merdeka using Watson Assistant
Capstone Project Arvy Kurnia Ramadhan in Infinite Learning 

# Pattern

https://developer.ibm.com/patterns/assemble-a-pizza-ordering-chatbot-dialog/?mhsrc=ibmsearch_a&mhq=

# Description

Chatbot ini dirancang sebagai asisten virtual yang dapat digunakan oleh mahasiswa/i untuk mendapatkan informasi mengenai berbagai aspek program Kampus Merdeka. Chatbot ini didukung oleh kecerdasan buatan (artificial intelligence) dan dapat memberikan jawaban atas pertanyaan yang diajukan oleh pengguna berdasarkan pengetahuan yang telah diprogram sebelumnya. Dengan adanya chatbot Kampus Merdeka, diharapkan mahasiswa/i dapat dengan mudah mengakses informasi yang dibutuhkan dan mendapatkan bantuan yang diperlukan dalam mencari informasi mengenai program Kampus Merdeka.

## Included components
 [![watson][watson]][watson]
* [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/): Build, test and deploy a bot or virtual agent across mobile devices, messaging platforms, or even on a physical robot.

# Flow 

![flow](https://github.com/ArvyKR/arvykr.github.io/assets/95832640/9e35b30b-5be3-4ddb-884f-76dcd6bc1fae)

- User sends messages to the application (running locally or on IBM Cloud).
- The application sends the user message to IBM Watson Assistant service, and displays the ongoing chat in a web page.

## Steps

Follow these steps to setup and run this code pattern. The steps are described in detail below.

1. [Create IBM Cloud services](#1-create-ibm-cloud-services)
5. [Configure Watson Assistant and Test the Chatbot](#2-configure-watson-assistant-and-test-the-chatbot)

## 1. Create IBM Cloud services

Create the following services:

* [**Watson Assistant**](https://cloud.ibm.com/catalog/services/assistant) 

> **NOTE**: use the `Plus` offering of Watson Assistant. You have access to a 30 day trial.

## 2. Configure Watson Assistant and test the Chatbot

### Create assistant

* Find the Assistant service in your IBM Cloud Dashboard.

* Click on the service and then click on `Launch Watson Assistant`.

* Go to your Assistant tab and click `create assistant`. 


### Create Assistant dialog skill and test the chatbot

You will see that you now have the ability to add a:
* Dialog skill


* Click on `Add dialog skill`

> **Note:** You will import the `Dialog skill` that is saved within this repo: `Kampus-Merdeka-BOT.json`.

* Click on `Import Skill`

* Click on `Choose JSON File`. Go to your cloned repo dir, and `Open` the JSON file in `Kampus-Merdeka-BOT.json`

* Click on `Import`

You will see that the dialog has been imported. Click on the words `Kampus-Merdeka-BOT` and explore the dialog to see the intents, entities, dialog.  You can also add to the dialog to extend the conversation.

> **Note:** you can also create your dialog from scratch by selecting `Create skill` and adding in your own intents, entities and dialog.


![image](https://github.com/ArvyKR/arvykr.github.io/assets/95832640/f589811e-1557-49d8-9d06-58ea33d88e15)
![image](https://github.com/ArvyKR/arvykr.github.io/assets/95832640/2889fd65-f6c4-48a8-b7cb-288756b0e16a)
![image](https://github.com/ArvyKR/arvykr.github.io/assets/95832640/87fb6b03-6b2b-4af4-a14f-0f6f155e3aef)




  
### Link
[Kamdek BOT](https://arvykr.github.io/)


  [watson]: https://img.shields.io/badge/watson-assistant-blue
