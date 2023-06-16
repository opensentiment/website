---
title: "About Open Sentiment"
description: ""
lead: ""
date: 2023-06-16T21:49:35+02:00
lastmod: 2023-06-16T21:49:35+02:00
draft: false
images: []
menu:
  docs:
    parent: "project"
weight: 999
toc: true
---

OpenSentiment is an initiative that leverages the power of artificial intelligence to analyze political bias in news media. By employing advanced Sentiment Analysis techniques, OpenSentiment aims to illuminate the media landscape, making political biases visible and quantifiable. 

## Our Mission

Our mission at OpenSentiment is threefold: 

1. **Promote media literacy**: We aim to provide the public with a tool that helps them critically evaluate the news they consume, fostering a more informed and discerning global citizenry.

2. **Enhance public discourse**: By shedding light on the underlying biases that shape the news, we hope to stimulate a more nuanced public conversation about world events.

3. **Encourage balanced reporting**: Through our bias analysis, we aim to hold media organizations accountable and promote balance and objectivity in news reporting.

## Our Technology

We build upon the foundation of cutting-edge, open-source machine learning models such as Falcon and GPT NeoX. These models are fine-tuned for the task of Sentiment Analysis, enabling them to discern and quantify political bias within a news article. 

### Dataset Creation

Dataset creation and annotation is one of the most challenging aspects of this project. We need to gather a large corpus of news articles, covering diverse media outlets and political leanings, which also includes metadata such as the publisher's name, publication date, and known political alignment. 

For objective annotation, we are exploring various methods that mitigate human subjectivity. One promising approach involves using the model output embeddings to create categories. Instead of labeling articles as "left-wing" or "right-wing", we compare the output embeddings of different articles to see which ones have similar opinions. This approach allows us to create a map of media bias without having to make subjective judgments.

### Continuous Model Updating

News and politics are inherently dynamic, and so our model must be as well. We are committed to continuously updating our models and datasets to reflect the evolving media landscape.

## The Road Ahead

OpenSentiment is still in its early stages. There is a lot of exciting work to be done and we are actively seeking contributors who are passionate about media literacy, AI, and the intersection of the two. Whether your expertise is in machine learning, data collection, project management, or community engagement, there is a place for you in the OpenSentiment project.

### Search Functionality

As we move forward, we plan to develop functionality that will allow users to perform searches based on various criteria. This could involve searching for specific news outlets, topics, or even time periods to understand the evolving biases around specific issues.

## Get Involved

Creating a tool like OpenSentiment is an ambitious project. It is technically challenging but achievable with today's technology and data resources. We believe in the transformative potential of this project and invite you to join us in making it a reality. Together, we can make a meaningful contribution to media literacy and public discourse in the digital age.
