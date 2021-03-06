---
layout: post
title: Getting started with Hasura cloud for GraphQL
description: >
Hasura cloud is a GraphQL engine provider for your data source. For this post, I'll connect my postgres db hosted in heroku with the cloud.
image: 
  path: https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qybvw1pbomav9rbrlqlb.png
#   srcset:
#     1060w: /assets/img/blog/example-content-iii.jpg
#     530w:  /assets/img/blog/example-content-iii@0,5x.jpg
#     265w:  /assets/img/blog/example-content-iii@0,25x.jpg
related_posts:
  - example/_posts/2017-11-23-example-content-ii.md
  - /example/2012-02-07-example-content/
sitemap: false
---

First post in the series [Android app with Hasura cloud backend #1]

### What is Hasura?

Hasura cloud is a GraphQL engine provider for your data source. 

For this example, I'll connect my postgres db hosted in heroku with the cloud. 


---



### Getting started

To start with the cloud, go to https://cloud.hasura.io/ and create an account. It is free for dev usage.



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qybvw1pbomav9rbrlqlb.png)



Once account created by verifying the email, you'll land in dashboard —> Projects.



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/20xsyc1f984hgsrremvr.png) 



Go ahead, and click on New project. It might ask you to select Free / Standard tier. I'm selecting Free. Now you should see a new new project created (even named?!) for you. 



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mtgjqstud2vgiwi2v7gj.png)



I like the part where they took away the painful part of coming up with a name for the project. With few clicks, I already have a working graphQL engine to consume. But the source??



Launch the project console and ***onwards***.



---



### Connecting data source



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j03jr11704il8456hp9p.png)



Once the project console launched, you will land in API explorer. Without a data source, we don't have much to do here. Head over to the **Data** tab, where we create/connect the data source.



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/twpyf23x9rg93wajzl8c.png)



Click - **Connect Database** and switch to Heroku tab



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/t2zoz7b8tn8f0axoawha.png)



Now click on **Create Database**, if you have logged into Heroku - the session would connect. Otherwise signup for a free heroku account and authorise to connect Hasura.



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2mb449t6afftmvm1pion.png)



You should see a nice animation and a database created and connected with your project.



![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/b59gk1tj66esivuwvv7t.png)


In case, you wonder what happended with Heroku, headover to https://dashboard.heroku.com/apps.

![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/eas9xzavq73lrd78dkft.png)

---

In the next post, I'll cover creating a table for an expense manager.