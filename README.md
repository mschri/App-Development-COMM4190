## App Design Project

### App Name: PacePal AI

----

## Overview:
This project simulated the development of an LLM-based application, using the LangChain framework and calls to the gpt-3.5-turbo model using the openai library within Python. Among the steps simulated within the app development process included: researching and compiling training data, mapping user scenarios and pathways, and training the model on specified information/data.

### Description
Our aim is to develop an application that utilizes LLM output trained specifically on data related to higher level sports and athletic development. The intention is for the application to be used by an athlete of any caliber (amateur to professional/elite), and will provide the user with a more targeted, unique level of detail in its output related to elevating athletic performance to the desire of the user. In other words, the application is designed to take the role of, say, an elite level coach whose expertise and advice is now offered in a more widely accessible format. Because this is being designed by two D1 athletes of different sports-XC/Track & Field and basketball-we have both access to explicit training regiments and a greater sense of what kind of training optimizes different athletic goals. Therefore, this kind of information (pace charts, basic knowledge from practice, etc.) is either directly accessible and can be fed into the application training data, or it is information we have a direction for researching further and can continue finding more specific detail on, so as to maximize the accuracy and scope of output. This application is intended to be a step above the average health fitness tracker, because it offers tailored, extensive and expert advice that adapts to the level of the user, in terms of knowledge and athletic ability. Further, the application allows for more engagement with user queries, instead of a device or application that simply tracks certain biometric measures. The idea behind our application is that it is a chatbot to be integrated within existing fitness tracker applications (i.e. Garmin Connect, iPhone's built in Health App, Strava, etc.), so that our application has direct access to an individual's training data, and can answer specific questions of the user. In sum, the application will be a chatbot that specializes in giving running advice.


### Project details


* [01_App Description](01_App_Description.ipynb) - Notebook containing an outline & description of the app idea.
* [02_User Scenarios](02_User_Scenarios.ipynb) - Link to a notebook containing the description of user scenarios for our app.
* [03_Prompt Development](03_Prompting_Experiments.ipynb) - Notebook containing calls to the LLM and prompt interaction. This notebook contains preliminary interactions with the model with user scenario prompts, before training the model.
* [04_Sample Training Data](04_App_training_data) - This directs you to the file containing some sample sets of training data that would be used on the model. Each of the files contained within the folder would be inputted into the model, to train outputs to respond a certain way, or provide context with which the model could tailor responses to the individual user. Note: because this project was primarily a simulation (and not a fully fledged app development), the training data is limited, and only provies a sample of what all of the training data might include.
* [05_User Pathways](05_User_pathways.ipynb) - This links to the notebook the maps user scenarios. The scenarios were mapped using Mermaid diagramming.
* [06_Trained Responses](06_Trained_responses.ipynb) - This notebook contains model interactions and prompts after the model was "trained," using the sample training in file 04. Note: there are cells containing "pre-trained" responses, to demonstrate within the same location the comparisons in responses between trained and pre-trained outputs. There are also cells containing some observations of these differences.
