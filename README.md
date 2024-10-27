# Chatbot Concierge #

## About ##

Frontend starter repository for HW 1 of the ECE 528 (Cloud Computing) class at University of Michigan-Dearborn.

## Usage ##

1. Clone the repository.
2. Replace `/assets/js/sdk/apigClient.js` with your own SDK file from API
   Gateway.
3. Open `chat.html` in any browser.
4. Start sending messages to test the chatbot interaction.

Extended description:

🍽️ Dining Concierge Chatbot

Welcome to the Dining Concierge Chatbot repository! This project showcases an intelligent chatbot designed to assist users in discovering the best restaurants based on their location and cuisine preferences. Built using a combination of JavaScript, AWS services, and various APIs, this chatbot delivers a seamless dining experience to users looking for personalized recommendations.

This project was developed as part of the Cloud Computing (AWS) curriculum in the MS Computer Engineering program at the University of Michigan-Dearborn. 🎓
🌟 Features

    Personalized Restaurant Suggestions: Users can input their preferred cuisine and location to receive tailored recommendations.
    Yelp API Integration: Fetches real-time restaurant data, ensuring users get the latest information.
    AWS Deployment: Utilizes AWS services like Lambda, API Gateway, and S3 for a robust and scalable backend.
    Microservices Architecture: Designed for modularity and efficiency, allowing for easy updates and maintenance.

🏗️ Architecture

The Dining Concierge Chatbot is built using a microservices architecture, enabling it to be flexible and easily maintainable. The key components include:

    Frontend: Developed using HTML, CSS, and JavaScript, hosted on Amazon S3 for a fast, responsive user interface.
    Backend: AWS Lambda functions process user requests and interact with the Yelp API to fetch restaurant data.
    API Gateway: Serves as a bridge between the chatbot and Lambda functions, handling user requests and responses efficiently.
    Data Storage: Utilizes Amazon S3 for static file storage and optional DynamoDB for managing user sessions and preferences.

🛠️ Technologies Used

    Frontend: HTML, CSS, JavaScript
    Backend: AWS Lambda, API Gateway
    Database: Amazon S3, optional DynamoDB
    APIs: Yelp API
    Chatbot Service: Amazon Lex

🚀 Getting Started

To set up the Dining Concierge Chatbot locally, follow these steps:

    Clone the repository:

    bash

git clone https://github.com/yourusername/dining-concierge-chatbot.git

Navigate to the project directory:

bash

    cd dining-concierge-chatbot

    Open the index.html file in your web browser.

    Interact with the chatbot and enjoy discovering new dining options! 🍴

🤝 Contributing

We welcome contributions to enhance the Dining Concierge Chatbot! Please feel free to open issues or submit pull requests to improve the functionality or user experience.
