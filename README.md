<p align="center"><img src="https://raw.githubusercontent.com/0xC000005/image-hosting/master/20210805212557.png"></p>
<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="unfold" src="https://awesome.re/badge.svg"/></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"/>
</p>


> "Unfold envelopes to smooth the ruffles of heart."

## Inspiration
This project idea was the offspring of one of our team member's 20 months struggle with depression, brought to fruition by the combined efforts of our entire team. When he first moved to Canada, he did not speak English and had never lived away from his parents in his life. This caused him to develop a reclusive personality that eventually resulted in a state of severe bipolar depression that both encouraged and resulted in a lack of the sense of belonging in the school environment, as well as the utter incapability to form long-lasting emotional bonds. As a result of this, he was determined to help the millions of other Canadians in similar situations as him two years ago when he conducted the user survey recently. We as a team genuinely hope, even outside of this competition, to use our abilities and experience in making this digital landscape a more inclusive and therapeutic environment for everyone that might benefit from these services. 


## What it does
Unfold is a mental health app that helps people overcome the lack of communication and control of their lives during and after the pandemic. It uses the top two most popular therapeutic practices: talking therapy and writing therapy to help people overcome this difficulty during the pandemic. Unfold aims to provide a healing community for expressing feelings safely, through means of anonymous letters and a personal AI companion.

### Why different compare to traditional therapy?
Unlike traditional 1-to-1 therapy, emotions in Unfold are shared in the community. An artificial intelligence-based recommendation system is used in our application. It listens to the user patiently and feels what the user feels, and carefully selects three different letters from other users that are sent out each day. These letters can be a short story, emotional quotes, or personal experiences. From reading the letters, our users might smile, laugh, or even have a drop of tears.  will resonance long after the reading, and this provides an emotional catharsis for our users. Not only the app can make a smarter decision, but also enable users to track their emotional stage. Most traditional/existing psychology therapy can only passively measuring the effectiveness of the outcome.

---

### Here's how this app works.
#### 1. Express 🙋
Does your mind fall apart from time to time? Do you have trouble opening up to people? Write a letter about what's bothering you and send it out. There will be a warm soul waiting to cheer you up or warm someone else with your soul.

#### 2. Your personal AI therapist 🩺
Understand your mood by chatting with the AI, which is not just your buddy, but also automatically assesses your mental state and provides appropriate advice through the conversation. As the AI becomes more familiar with you, the greater the likelihood that you will receive the “right” letter.

#### 3. Stay on top of your heart ☝️
There are times when we just have too much to do. Unfold uses advanced algorithms to feel your heart and translate elusive emotions into easy-to-read charts and data. See for yourself how your positive energy increases day by day and work with you to take back control of your life again.

---

## How we built it
Our work is divided into three main parts: user survey, product design and a machine learning based demo to prove the feasibility of our algorithm. For the user survey and interview, we used Google form and jupyter notebook etc. for data analysis and visualization. We also used jupyter notebook to pre-process the training dataset: Twitter sentiment data related to the 2016 presidential election debate. Figma was our main design tool, along with miro. For the machine learning part, we used sklearn, keras and TensorFlow for text sentiment analysis. To better demonstrate our model, we used python+flask as the backend and react as the frontend to develop an online demo.

##Challenges we ran into

We faced three main challenges: design philosophy, lack of training datasets leading to inaccurate trained models, and the inability to turn the models into online demos. we thought long and hard about the design from the user's perspective and interviewed potential users to get our final feature design. Due to the natural sensitivity of sentiment analysis datasets, we spent a lot of time searching for datasets at the beginning of the Hackathon. And even after finding a dataset we were still not satisfied with the accuracy of the model. Also most of our developers studied data science, and we had no experience with flask and react at all, so we also spent some time learning these techniques on an ad hoc basis.

## Accomplishments that we're proud of
First, we are proud to see our machine learning models actually being used in production environments and helping people in need. For a long time before, we measured a machine learning model by its correct prediction rate. But this is different. Although we were not very satisfied with the correctness of our model, we managed to deploy it on a server and make it a publicly available API that anyone can now use for sentiment analysis.
Second,  we didn't expect to finish submitting a product with such a high degree of completion. Everything we learned about flask and react was learned on the spot, and for that we compressed our sleep tremendously, but we finally made it!

## What we learned
1. remote collaboration, which I think is the most important.
2. we learned to look at our machine learning models from a production perspective, rather than an academic perspective. And learned how to turn a model into an API that everyone can use.
3. We studied the psychological difficulties Canadians faced during the pandemic and learned why they were reluctant to talk. This reminded me of a state of depression that I had also experienced before, (those people really need a helping hand) which increased my social responsibility.

## What's next for Unfold
If we had more time, we would try to collect the sentiment analysis dataset ourselves, which is the bottleneck in the correctness of our model. Also I'd like to spend more time developing the flask backend, using more formal queries rather than the brute force-forced construction url we use now to query. One last thing, if time permits, we'd like to develop our web front end more and start receiving some user feedback. This way we can see if people like the features we've designed, and it gives the AI a chance to learn itself.
