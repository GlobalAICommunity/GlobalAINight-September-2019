# Artwork

- [Logo](https://globalaibootcamp.blob.core.windows.net/artwork/logo.png)
- [Rollup Banner](https://globalaibootcamp.blob.core.windows.net/artwork/ainight_rollup-banner.psd)
- [Meetup Banner](https://globalaibootcamp.blob.core.windows.net/artwork/ainight_banner.psd)
- [Font](https://globalaibootcamp.blob.core.windows.net/artwork/font_quicksand.zip)


# Workshops

## Beginner Track

### **Part 1 -** Creating applications that can see, hear, speak or understand - using Microsoft Cognitive Services (1 hour)

**[Train the Trainer recording](https://youtu.be/S4YTTjfkWrA)** 

In this workshop you will be introduced to the Microsoft Azure Cognitive Services, a range of offerings you can use to infuse intelligence and machine learning into your applications without needing to build the code from scratch. We will cover pre-trained AI APIs, such as computer vision and text analytics, that are accessed by REST protocol. nEXT we will dive into Custom AI that uses transfer learning - Microsoft Azure Custom Vision. This enables you to provide a small amount of your own data to train an image classification model. Wrapping the workshop up by building our custom trained AI into an application - using Logic Apps, this technology is ideal for building data pipeline processes that work with your machine learning models.

#### Materials
* [Github Content - For Session Owners](https://github.com/amynic/ainights-sessionowners)
* [Github Content - For Attendees](https://github.com/amynic/AINights)

#### Pre-requisites for your machine
* Clone these repositories to your local machine to gain images and code samples you need for the demos: git clone [https://github.com/amynic/ainights-sessionowners.git](https://github.com/amynic/ainights-sessionowners.git)
* Microsoft Azure Subscription - get a free trial [here](https://azure.microsoft.com/en-gb/free/?WT.mc_id=globalainights-content-amynic)
* Laptop with a modern web browser (Google Chrome, Microsoft Edge)
* Postman, API Development Environment - [available on Windows, Linux and macOS](https://www.getpostman.com/)
* _[BONUS SECTION] Download docker for your local machine - [available on Windows, Linux and macOS](https://docs.docker.com/v17.09/engine/installation/)_


> All demos and content have been tested on a Windows PC, however all options should run from macOS and Linux machines as well. Please provide information via an issue or pull request if you have feedback on other operating systems
 
 
###  **Part 2 -** Is that wine good or bad? A beginner tutorial on how to build a binary classification machine learning model with no code using Azure Machine Learning Visual Interface (1 hour)

**[Train the Trainer recording](https://youtu.be/VnzUHS0iu9o)** 

In this workshop you will be introduced to the data science process for building custom machine learning models using Azure Machine Learning Visual Interface. We will cover how to find, import, and prepare data, selecting a machine learning algorithm, training and testing the model, and how to deploy a complete model to an API. Lastly we will discuss some common data science beginner gotchas and provide additional resources to continue your machine learning journey!

#### Materials
* [Github Content - Train-the-Trainer](https://github.com/cassieview/wine-quality-azure-ml-visual-interface/)
 
## Intermediate Track

### **Part 1 -** Learn how to train high accuracy machine learning models using automated machine learning (1 hour)

Intelligent experiences powered by AI can seem like magic to users. Developing them, however, is cumbersome involving a series of sequential and interconnected decisions along the way that are pretty time consuming. What if there was an automated service that identifies the best machine learning pipelines for a given problem/data? Automated machine learning does exactly that! Learn how to quickly and efficiently build high accuracy ml models for classification, regression and forecasting scenarios using code and code-free pathways.

#### Materials
* All information needed is available in the [presentation folder here](automated-ml-presentation-material.zip)



### **Part 2 -** Crash course on building and accelerating deep learning solutions (1 hour)

Learn the end to end process of building deep learning solutions from experimentation to deployment. We will start by experimenting locally with different model architectures and hyperparameters using PyTorch. Then, we’ll show you how to use Azure Machine Learning service to train models at massive scale in the cloud and seamlessly deploy them into production.

#### Materials
[Content](https://github.com/sethjuarez/pytorchintro)
* **Part 1:** Getting familiar with Deep Learning and PyTorch
* **Part 2:** Using Azure Machine Learning service to cloud accelerate deep learning

## ML.NET Content

* Below we have listed **4 ML.NET talks** that might be of interest to your communities. 
* Each one has **a link to a video** of the session and how it has been delivered. 
* **Pick from the 4 listed below** which feel relevant for the maturity of your audience in this technology space. 
* **Each talk is 1 hour long**

### **Talk One of Four (1/4):** Introduction to ML.NET 1.0

**Description:** ML.NET 1.0 release is the first major milestone of a great journey that started in May 2018 when we released ML.NET 0.1 as open source. ML.NET is an open-source and cross-platform machine learning framework for .NET developers. Using ML.NET, developers can leverage their existing tools and skillsets to develop and infuse custom AI into their applications by creating custom machine learning models for common scenarios like Sentiment Analysis, Recommendation, Image Classification and more.
This presentation provides an overview of the technology with demos run in a Deep Learning Virtual Machine running Windows Server 2016. Code examples are in C# and F# and run in Visual Studio Community 2019. This technology is ready for production implementation and runs on .NET Core

* Video: [https://youtu.be/NlFTSBc0LzM](https://youtu.be/NlFTSBc0LzM)

### **Talk Two of Four(2/4):** Introduction to AutoML with ML.NET 1.0

**Description:** ML.NET 1.0 release is the first major milestone of a great journey that started in May 2018 when we released ML.NET 0.1 as open source. ML.NET is an open-source and cross-platform machine learning framework for .NET developers. Using ML.NET, developers can leverage their existing tools and skillsets to develop and infuse custom AI into their applications by creating custom machine learning models for common scenarios like Sentiment Analysis, Recommendation, Image Classification and more.
“Automated ML” is a collection of new technologies from Microsoft to enhance the data science development process. Still in preview, Auto ML for ML.NET 1.0 will be demonstrated in a Deep Learning Virtual Machine running Windows Server 2016. Code examples are in C# and run in Visual Studio Community 2019.

* Video: [https://youtu.be/UG5j3CIF-j0](https://youtu.be/UG5j3CIF-j0)

### **Talk Three of Four(3/4):** Introduction to NimbusML

**Description:** NimbusML enables data scientists to use ML.NET to train models in Azure Machine Learning or anywhere else they use Python. NimbusML provides state-of-the-art ML algorithms, transforms and components, aiming to make them useful for all developers, data scientists, and information workers and helpful in all products, services and devices. The components are authored by the team members, as well as numerous contributors from MSR, CISL, Bing and other teams at Microsoft. NimbusML is interoperable with scikit-learn estimators and transforms, while adding a suite of highly optimized algorithms written in C++ and C# for speed and performance.
The trained machine learning model can be used in a .NET application with ML.NET. This presentation will outline the features of NimbusML and provide a notebook-based demonstration using Azure Notebooks

* Video: [https://youtu.be/E36V8W3IFGE](https://youtu.be/E36V8W3IFGE)

### **Talk Four of Four(4/4):** Overview of Automated ML June 2019

**Description:** Automated machine learning (automated ML) automates feature engineering, algorithm and hyperparameter selection to find the best model for your data. The mission: Enable automated building of machine learning with the goal of accelerating, democratizing and scaling AI. 
This presentation covers some recent announcements of technologies related to Automated ML, and especially for Azure. The demonstrations focus on Python with Azure ML Service and Azure Databricks

* Video: [https://youtu.be/zSA8q_lZ1QA](https://youtu.be/zSA8q_lZ1QA)

