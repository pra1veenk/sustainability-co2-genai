# Introduction

In this exercise users will create a robust business application that seamlessly integrates with an Microsoft Azure OpenAI Large Language Model (LLM) through SAP's Generative AI hub. This project comprises two essential components. Firstly, an SAP Cloud Application Programming backend is established to manage data, user authentication, and facilitate interaction with the LLM. Secondly, a user-friendly React Native app, designed as a Smart CO2 Converter, is developed. The application's primary function is to track carbon dioxide (CO2) emissions data and recommend actionable insights and recommendations. This comprehensive solution aims to promote environmental awareness and sustainability through innovative technology.

Broadly, this consists of:

**SAP BTP services and components such as the SAP Cloud Application Programming (CAP) model, SAP AI Core, SAP HANA Cloud, and SAP destination service**

<details>
The SAP BTP, Cloud Foundry Runtime allows you to create polyglot cloud applications in Cloud Foundry. It contains the Cloud Foundry Runtime service, which is based on the open-source application platform managed by the Cloud Foundry Foundation.
You can deploy your Cloud Foundry applications in different regions, each of which represents the location of a data center.
You can leverage a multitude of buildpacks, including community innovations and self-developed buildpacks. This runtime platform enables you to develop and deploy web applications, supporting multiple runtimes, programming languages, libraries, and services. In this exercise, the backend as well as the frontend will be deployed and run on SAP BTP, Cloud Foundry Runtime.

SAP HANA Cloud provides a single place to access, store, and process all enterprise data in real-time. It is a cloud-native platform that reduces the complexity of multi-cloud or hybrid system landscapes. SAP HANA Cloud provides all of the advanced SAP HANA technologies for multi-model data processing in-memory or on disk. You can benefit from cloud qualities such as automatic software updates, elasticity, and low total cost of ownership by using SAP HANA Cloud either as a stand-alone solution or as an extension to your existing on-premise environment.

SAP AI Core is part of the services portfolio that SAP BTP provides. It is used to train a machine learning model and to deploy the model in the form of a service running in the cloud on SAP BTP. Clients can then send data to the service endpoint and will receive the model's prediction based on that data as a response. Both model training and serving happen in a scalable and for the most part hyperscaler-agnostic way.

SAP AI Launchpad is an application in SAP BTP. With it, one can overview one's own AI use case having the convenience of a user interface in the browser. It showcases artifacts that are relevant to your use case like the dataset used for training and the trained model. Further one can observe the training and serving process and the underlying configurations that are used for them.
</details>


<!--
**Chat-GPT, Large Language Models and Microsoft Azure Open AI Services**
<details>
ChatGPT is a large language model developed by OpenAI, based on the GPT (3.5 or GPT-4) architecture. It is a machine-learning algorithm that is capable of understanding and generating human-like text in response to user input. ChatGPT has been trained on a massive dataset of text from the internet, allowing it to generate text in a wide range of styles and formats.

Large Language Models (LLMs) like ChatGPT are revolutionizing the field of natural language processing (NLP) by enabling computers to process, generate and understand human language like never before. They are capable of performing a wide range of language-related tasks, such as translation, summarization, question-answering, and even creative writing. With their advanced abilities to understand and generate human language, LLMs like ChatGPT are poised to have a profound impact on a wide range of industries, from customer service and education to healthcare and finance.

Microsoft Azure OpenAI Service provides REST API access to OpenAI's powerful language models. These models can be easily adapted to your specific task including but not limited to content generation, summarization, semantic search, and natural language to code translation. Users can access the service through REST APIs, Python SDK, or the web-based interface in the Microsoft Azure OpenAI Studio.
</details>

**React Native**
<details>
React Native is a framework for building mobile applications using JavaScript and React. It allows developers to create native mobile apps for both iOS and Android platforms, using a single codebase, which results in faster development times and lower costs. In addition to supporting JavaScript, React Native also provides support for TypeScript, a typed superset of JavaScript that enables developers to write more scalable and maintainable code by catching errors early in the development process.

In addition to React Native, there are various tools and services available that can enhance and simplify the process of building mobile applications using this framework. One such tool is Expo, a comprehensive set of tools and services built around React Native. Expo aims to streamline the development process by providing an integrated development environment and access to pre-built components and libraries. Expo supports both JavaScript and TypeScript and includes features like live reloading, push notifications, and over-the-air updates, which can make the app development process faster and more efficient. By using Expo, developers can have a more seamless experience building React Native apps and gain access to many useful features and libraries.
</details>

-->
## Reference Architecture of an SAP BTP CAP Application using GPT Models of OpenAI

You want to make use of one of the Large Language Models (LLMs) like the GPT family of LLMs offered by Microsoft Azure OpenAI in combination with an application running on SAP Business Technology Platform (BTP), here is our recommendation how to achieve this and also benefit from the BTP capabilities.
Refer to this documentation for more details - https://github.com/SAP/sap-btp-reference-architectures/blob/main/hyperscalers/openai/README.md

## Technical Architecture 

<p align="center">
<img src="assets/architecture.png" alt="architecture" width="1000" />
</p>

## Exercise Outcome

After completing these steps you will have an app built using the reusable architecture principles of SAP Cloud Application Programming (CAP) model and React Native on SAP BTP. An application extension using GPT via the  Microsoft Azure Open AI service that combines business context with the capabilities of large language models on SAP BTP.

<p>
  <img src="assets/home.gif" alt="home" width="24%" />
  <img src="assets/challenges.png" alt="challenges" width="24%" />
  <img src="assets/suggestions.png" alt="suggestions" width="24%" />
  <img src="assets/habits.png" alt="habits" width="24%" />
</p>


## Get Started

Exercise 1 - [Prepatory Steps](../MicrosoftAzure/ex1.1/README.md) \
Exercise 2 - [Deploy CAP API to Cloud Foundry](../MicrosoftAzure/ex1.2/README.md) \
Exercise 3 - [Run App Locally on Web Browser](../MicrosoftAzure/ex1.3/README.md) \
Exercise 4 - [Enable LLM Access](../MicrosoftAzure/ex1.4/README.md)
