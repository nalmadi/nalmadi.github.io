---
layout: post
title: "Student Spotlight - Zehra Gundogdu '25 (Enerjisa Uretim)"
author: "Naser"
categories: Interview
tags: [Interview, student]
image: zehra_internship.jpg
---
Photo by Zehra Gundogdu '25
  

This post is part of a spotlight series highlighting the work of exceptional students and alumni.  The series aims to facilitate knowledge sharing on topics such as internships, jobs, entrepreneurship, and graduate school.  


Today, I have the pleasure of talking to Zehra Gundogdu '25, who will tell us about her recent experience as a Software Engineering intern at Enerjisa Uretim, a leading Turkish sustainability focused energy provider.


**Naser: Can you tell us about your role and responsibilities during your tech internship?**


Zehra: The software developer team that I interned with this summer was managing an application called “Vega”. The company, Enerjisa Uretim, carries out its energy and associated trade operations in domestic and international markets and also performs risk management through this software. My team used agile methodology and scrum process framework to manage the project. 

The first task I took on was creating a shared-kernel within the separate projects under Vega code. Vega consists of different APIs that communicate with each other (vega-backend-api, vega-contract-api, vega-dealcapture-api, etc.). These separate projects had C# files called “microservice integration events'' in them, most of which were shared within projects. This means that the same microservice integration event files were added in more than one project separately. This resulted in a lot of code repetition, which is inefficient for developers. As a solution to this issue, I created a shared-kernel, which gathered all microservice integration events in Vega code together. I used Git submodules so that if there was a change to be made in the shared-kernel code, all other projects using the shared-kernel were updated. 

This internship was also my first time getting familiar with data flow management tools. My team was switching from a tool called NiFi to Airflow because it was more suitable for the project, and I worked on moving workflows from NiFi to Airflow. The purpose of the workflows was to create requests for real data from Bloomberg’s API, such as exchange rates of USD and euro, tax rates, sales revenues, etc. These values were then used and updated daily on Vega to perform real-life operations. Using Python and SQL, I created a DAG on Airflow which posts requests to Bloomberg API and writes the request-ids returned by the API to a database daily. I also created data controller DAGs for data such as daily reference prices, market clearing prices, and spot prices. These controllers check the databases for data periodically and print out error messages for missing data on a New Relic dashboard if missing data is detected. 


**Naser: How did you find this internship? And why did you select it?**


Zehra: I was searching for an internship opportunity back home in Istanbul because I wanted to visit family and friends this summer. I started researching for software developer internships on LinkedIn and talking to friends from back home about opportunities. EnerjiSA Uretim is a well-established company that was on my must-apply list. The company was recommended to me because of its friendly working environment, as well. I also support their focus on sustainable energy production and investments for a future with cleaner energy, so I was very happy to get the position. 


**Naser: Can you tell us about the interview process? And how did you prepare for it?**


Zehra: After I sent my resume to the HR team, a member of the software development department contacted me through email to schedule an interview. I also took an online exam. During the interview, they asked me about what kind of projects I took part in that are relevant to the internship, as well as the coding languages and tools that I have experience with. I was also asked what made their company stand out to me, and why I thought I was a good fit. I did research on the company's mission and achievements to prepare for the interview, along with brainstorming which experiences on my resume I could highlight and tell them more about. 


**Naser: How did the internship align with your academic studies at Colby, and did it provide any unique perspectives or insights?**


Zehra: It was a great opportunity to see in what ways the business environment differs from the class environment and put the material I learned into practice. I took a Software Engineering class last year at Colby and learned about agile methodology and scrum project management framework through group projects. Gaining more experience with these methodologies in a real-life work environment was great! I was grateful that I was already introduced to these subjects at Colby and felt more confident to take on responsibility. 


**Naser: What tips would you give students interested in doing an internship in the future?**


Zehra: If you are interested in doing a tech internship, don’t assume that your choices are limited to big tech companies. Today, renowned companies across many fields have IT or software development departments where you can find relevant positions. If you are confused about where to start, there are many great repositories on GitHub listing internship opportunities. Lastly, don’t let the rejections discourage you, and keep applying! I applied to 24 internships last summer and only got accepted to 2 of them. Computer science is a very popular and competitive field, and rejections often don’t mean that you are not a good fit for the position you applied to.
