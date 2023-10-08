[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# UQPAY API Postman

[English](README.md) | [简体中文](README_Zh.md)

[Postman](https://www.postman.com) is an API collaboration platform.

To allow users to quickly and conveniently use RESTful APIs, Uqpay offers several Postman Collections and Environments files (JSON files). You just need to import and set up your own API key to get started.

You only need to import and set up your own API key to get started.

## How to import and configure?
- Download `uqpay-api-postman` save to local.

- Click the `Import` button. For example, on the Windows version of Postman, the button is located in the top left corner.

  <img src="assets/1.png" alt="A screenshot of the Windows version of Postman, pointing out the `Import` button in the top left corner."/>

- On the Import pop-up page, click the `folders` button and then select the root folder of the downloaded repository. 

  <img src="assets/2.png" alt="A screenshot of the Windows version of Postman showing the import screen."/>

- Choose the collections and environments you want to import, and then click the `Import` button.

  <img src="assets/3.png" alt="A screenshot of the Windows version of Postman, showing the import screen after selecting the folder."/>

- Select the `Environments` tab on the left, select an environment, and set your `x-client-id` and `x-api-key` in the `Current value` column (see screenshot). After setting the values, remember to click the `Save` button in the top right corner.

  <img src="assets/4.png" alt="A screenshot of the Windows version of Postman, showing where users fill in the API key."/>

- From the environment dropdown, select the newly added environment. On Windows, it's located in the top right corner. 

  <img src="assets/5.png" alt="A screenshot of the Windows version of Postman, showing how to select the imported environment from the dropdown."/>


## Postman Security Practices

To ensure account security, it's recommended to follow these best security practices

- Do not use Postman Collections obtained from unknown sources.
- Check the Environment JSON file before using.
- Do not use any code you do not understand.
- After using the API endpoint, delete all API keys.

## Frequently Asked Questions
**Q:** Why am I not getting any response?

Check if you have imported the environment settings and selected the corresponding environment from the list. Please set up your environment according to the steps above.

**Q:** How to debug or how to view the request URL?

- Within Postman's console, you can see the parameters and URL printed for each request.
- You can debug by editing the `Pre-request Script` tab.


## If you have questions
You can post an issue in this repository [`issue`](https://github.com/uqpay/uqpay-api-postman/issues).
