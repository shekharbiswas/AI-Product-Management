<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/56f32a94-7c1f-41c3-874d-7b5f1096890a" width="450">

https://developers.google.com/machine-learning/problem-framing/problem

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/22331d4b-c1f4-40fa-9b9d-c9f4d10ed86c" width="450">

Heuristics are methods of solving problems using a simplified set of rules which are generally based on past experience or past data.

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/116d6637-bf91-4247-8911-a758a490ffa3" width="450">

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/1fdf5d2e-9e0c-483b-aca6-b8be7bce06c3" width="450">


**Why ML Projects hard to manage**
- https://medium.com/@l2k/why-are-machine-learning-projects-so-hard-to-manage-8e9b9cf49641

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/f9ec9da8-84b8-4b61-85ad-b99809c63508" width="700">

### Outcome metrics

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/13542cec-31e8-42b9-8120-411be2ec6637" width="400">

### Output metrics 

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/c5bead38-6c98-482f-b11c-745dc756e857" width="400">

### comparison 


<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/98389979-5f32-4e38-8f3a-c68a421792f7" width="400">

### Best practices of data collection

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/66d1a522-b357-46ae-98f2-b0ec3e7c4c74" width="400">

### data silos can be a danger

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/386c2a7f-71a4-4108-8959-9f00fca30c8a" width="400">

### how facebook did

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/64dfe944-4091-45b0-863d-4780ac01c29b" width="450">

### spotify

https://engineering.atspotify.com/2020/02/27/how-we-improved-data-discovery-for-data-scientists-at-spotify/



### Data lineage 

It involves the tracking of data from the source all the way to consumption,

<img src="https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/a3f2ba55-b31f-427e-a659-db9b37e3a3eb" width="650">

### ML system design decisions

![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/846c838d-800f-4314-976c-6b0f47ddf7f9)

### system design examples

![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/979c4693-e9e8-49b1-ad55-05e72c20c27c)

### Edge AI 
![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/4ff74db6-bacd-4be6-8e21-a98d453a2463)


### Edge vs Cloud 

![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/a99cebf3-21d4-4ffa-bf61-20281b9ab6ee)


### Examples

Recommedation in Netflix - in this particular case we might choose to run our model periodically. For example run a model and retrain our model every night, generate our predictions, cash, our predictions. So that when a user goes and turns the TV on to get a movie recommendation, our predictions are immediately then available to the user to get. 

An example of an edge machine learning system might be an intelligent security system. So for example, we might have intelligence security cameras that are constantly scanning their environment and they're looking for certain certain signals or triggers. In this case we need the ability to immediately recognize certain objects or actions with very low latency. And likewise we also can't always count on internet connectivity.

There are three primary approaches that we can take to doing this the first that we may choose to use edge AI to generate certain triggers based on actions that recognizes. And these triggers will then initiate a cloud machine learning system. So an example here might be again a security camera which is trained to identify certain events or actions. And when that generates a trigger, it then starts streaming data from the camera back to the cloud for further processing and modeling and initiates a cloud machine learning system.

Second approach might be to run the machine learning model in the cloud, but then also to store common pre computed predictions by our cloud system on the device for quick look up so that we can minimize latency for our user.

And a third approach might be to take advantage of local data centers across the areas where we're serving users. So that when a user sends a query or sends data up to a cloud system for modeling the travel distance is minimized by sending it to a local data center so that we can minimize any latency in our application.

One example of a hybrid machine learning system might be a smart speaker with a built in voice a system. A speaker might include an edge machine learning system that's trained to recognize what's called a wake word. So for example, if we have an amazon Alexa, it might be trained to recognize the word Alexa. And when it's model runs and here's the word Alexa, it then issues a trigger which connects up to the cloud system that we have sends our future data. Or in the case the future voice commands that we then issue after we say the wake word Alexa, those get sent up to the cloud for processing and modeling and then we receive our results back from our cloud system.

So how should you decide between a cloud machine learning system versus an edge machine learning model, they're a couple of key questions to ask to reach your decision. First question is how much does latency matter in your application?

If latency is a big concern and your users need immediate results back from the model, you might want to consider an edge model. If latency is less of a concern, you might be okay going with the cloud system.

Second question to ask is is reliability on internet connectivity acceptable in your use case. If your model needs to be able to work even in situations where you don't have connectivity, you might go with an edge system. But if you can assume internet connectivity during the models use you might be okay with a cloud system.

Thirdly, are your users comfortable sending their data up to the cloud?

If privacy is a big concern such as the use case we looked at using facial recognition to open up your phone, you might prefer to use an edge system where users don't need to send their data up to the cloud.

Or if privacy is less of a concern in your particular use case, you might choose a cloud machine learning system.
camera which is trained to identify certain events or actions.

### decay 

![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/97f3d1b8-337c-4725-8cb4-7c13e4e967f4)

### how medical AI failed

https://www.technologyreview.com/2020/04/27/1000658/google-medical-ai-accurate-lab-real-life-clinic-covid-diabetes-retina-disease/


### Drift in ML

![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/d12d9b3c-b1e9-4dae-9fe1-7f9c49ed2172)


https://www.datacamp.com/tutorial/explainable-ai-understanding-and-trusting-machine-learning-models
( SHAP and LIME )


![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/131c72ea-569a-46d9-ac5d-4dc145192c73)


![image](https://github.com/shekharbiswas/AI-Product-Management/assets/32758439/2488ccec-eda8-436e-a748-603c8186cc8d)
