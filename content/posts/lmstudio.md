---
title: "Why should you choose LM Studio for your next project?"
date: 2024-10-31
description: "LM Studio is a platform helps you run LLMs on your own machine."
--- 

## TL;DR
Think of LM Studio as a central hub of all your big AI models which run on your machine, fully private and secure.

## What even is LM Studio?
LM Studio is a desktop app for developing and experimenting with LLMs on your computer. It offers a desktop application for running local LLMs with a familiar chat interface. Additionally, it includes search and download functionality via Hugging Face 🤗, a local server that can listen on OpenAI-like endpoints, and systems for managing local models and configurations.

![Chat Page](https://i.imgur.com/NN0xEN7.png)

So basically you can talk to any open source model like LLaMa, Gemma and others, and get responses in real-time. Think of it like ChatGPT but on your machine. And you don't need to do any support, just hit download, load the model and chat!

![Easy to install models](https://i.imgur.com/Dd88ydA.png)

## So why don't you just use ChatGPT?
ChatGPT is a great tool, but it's not open source and you can't run it on your machine. LM Studio is a desktop app that allows you to run LLMs on your machine, fully private and secure. It's a great tool for developers who want to experiment with LLMs and build their own models. Developers can build AI features into their applications without having to worry about privacy or security issues or the cost of using cloud-based services.

## How does it work?
LM Studio uses a library called as `llama.cpp` internally to run the models. It's a simple library that can be used to run LLMs on your machine. The library is written in C++ and hence is super fast. 

## What are the advantages of using LM Studio?
- **Privacy**: You can run LLMs on your machine, so your data never leaves your computer.
- **Cost**: You don't have to pay for cloud-based services to run LLMs. And you don't need to pay for that OpenAI subcription anymore. :)
- **Speed**: LM Studio is super fast because it runs on your machine.
- **Customization**: You can customize LM Studio to suit your needs. You can make variety of different AI 'agents' which are specialized in different tasks.
- **Offline**: You can run LM Studio offline, so you don't need an internet connection to use it. Imagine that! ChatGPT but offline.
- **Variety of choice**: You can choose from a variety of different models to run on your machine. You can even run your own models if you want.
- **Differents types of UI**: It has different types of UI for different complexities. If you are just for a simple chat experience, use the 'User' mode. If you are a power user and want to see more, use the 'Power User' mode. If you are a developer and want to see everything, use the 'Developer' mode. 

![Developer Page](https://i.imgur.com/TXQdo1I.png)


## How can I get started?
You can download LM Studio from the [official website](https://lmstudio.ai). It's available for Windows, Mac, and Linux. Once you've downloaded it, you can start experimenting with LLMs on your machine, super simple and easy to get running in minutes.

## Can you point an usecase where LM Studio can be used?
Lets say you are making a movie recommendation system. Now your CTO wants you to write a feature where users can describe what kind of a movie they want to watch, it could be based on mood, plot, ratings etc. You can use LM Studio to build a chatbot which can understand the user's query and recommend movies based on that. You can use the Structured Outputs API to get the response from the model and then use that to query your database and get the results. This makes your platform ✨AI-powered✨ and you can do all of this on your machine, without needing OpenAI's API or any cloud service.

So lets give our LLM some initial instructions of how it should work

![Instructions](https://i.imgur.com/LzZPDzJ.png)

Now lets tell the LLM to return the output in a certain format so our backend knows that it will always respond in a certain format and we can parse it easily.

![Structured Outputs](https://i.imgur.com/50CQbsn.png)

Now lets run the model and see the output

![Output](https://i.imgur.com/iEm2ryY.png)

And viola! You have a movie recommendation system powered by LM Studio. 🎉 
This is a very simple example, to improve on this, you would probably need to give your model all the movies your platform has and then it can recommend based on that. But as you can see, just with a few clicks, you can make your AI-powered featured. And now you can use LM Studio in server mode on your server and expose the API to the backend and you have a fully functional AI-powered platform.


## What are the disadvantages of using LM Studio?
- **Limited resources**: You can only run LLMs on your machine, so you're limited by the resources of your computer.
- **No cloud**: You can't run LLMs on the cloud, so you cannot share your models with others easily. But you can run LMStudio on a server and expose the API to the world.
- **Engines Support**: Currently, LM Studio only supports llama.cpp and MLX but they are working on adding more engines.
- **Closed Source**: LM Studio is not open source, so you can't see the code or contribute to it. But some components are open source and you can contribute to them.

## Conclusion
LM Studio is a great tool for developers who want to experiment with LLMs and build their own models. It's a desktop app that allows you to run LLMs on your machine, fully private and secure. It's super fast, customizable, and offline. You can choose from a variety of different models to run on your machine and you can even run your own models if you want. It's a great tool for developers who want to build AI features into their applications without having to worry about privacy or security issues or the cost of using cloud-based services. So why not give it a try and see what you can build with LM Studio?