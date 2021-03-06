# llSPS-INT-90-AI-Powered-News-Search-App-Level-1-
AI Powered News Search App (Level-1)

>*AUTHOR: OISHEE MAZUMDER*

**OVERVIEW**

In this project, we built our own news mining web application using Node-RED App and the IBM Watson Discovery Service, which was then integrated with Slack. 
To do this, we:
* Build a Server Side Application using Node-RED
* Used the pre-built Watson Discovery News collection
* Accessed the Watson Discovery Service through the Discovery API

Moreover, we:
* Used a Slack interface to query the data
* Finally, deployed the app on IBM Cloud

**PURPOSE**
 
The web is home to massive amounts of data, with more being created every day. Organizations can harness this constant stream of information to gain understanding, plan strategies, and find opportunities. Enriched news data can help applications make dynamic connections across current events faster.

**EXISTING PROBLEM**

Though there are several news apps existing in the market at the moment, most of them categorize the news. There are hardly news apps present which let you search news articles topic wise. Moreover, they hardly convey to the readers the sentiment of the article.
Bots in all fields of applications are one of the upcoming trends, however they haven’t been used extensively in news searches. Integrating a news searches within a bot provides the flexibility to not to have to create a separate app for it.

**PROPOSED SOLUTION**

* The user will be able to interact with the web app UI, built with Node-Red to request relevant news content.
* The app sends user requests to Watson Discovery News.
* The Watson Discovery Service is continually crawling the web to update its Discovery News collection.
* The web app provides the user with the top trending news articles for the specified query, along with each article’s sentiment analysis.
* The Watson Discovery Service responds to Slack search requests.

![flowchart](https://user-images.githubusercontent.com/64250870/81824151-c6008080-9552-11ea-9036-2cab60f34b15.png)

# Also See:
* [Project Development Procedure](pro-dev.md)
* [Project Results](pro-results.md)
* [Node-Red Flow](node-red-flow.json)

