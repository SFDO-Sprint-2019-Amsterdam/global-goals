
#### Team Members:

* Jonny Elliot, Solution Engineer, Salesforce.org
* Thijs Bokkers, Partner Solution Engineer, Salesforce.org
* <b>Marcelle Porteous</b>, Customer Success Manager, Salesforce.org


#### Project Overview:

To provide a mechanism through which our customers can provide progress towards the 17 UN Global Goals, whereby Salesforce can aggregate data to show the impact of customers.
    
#### What impact will this have on the Community?
    
It will allow for non-profits to easily report on the progress they are making towards their mission, and tie this to the SDGs. <BR>
It will allow for Salesforce.org to measure how our whole ohana is progressing with the SDGs. <BR>
It will allow for the UN to see what the impact is of the Salesforce Ohana towards their overal SDGs. <BR>
It will allow for corporate organisations to connect their CSR strategy towards the SDGs and measure upon them.
    
#### How could this project be distributed into the Community? 
    
We believe this could be released to the community in 3 phases as described below. 
    
   * Crawl
    
A pilot in which a basic package with custom objects / custom settings / reports & dashboards etc. is created for customers to install in to their individual instances of Salesforce.
    
   * Walk
    
A managed package on the app exchange that has the facility for individual customers to opt-in to sharing their data with Salesforce. 

A heroku back-end to aggregate the data.
    
   * Run
    
An open Einstein Analytics engine on the heroku database that allows .org leadership, our customers, the UN, and other actors to analyse the data for insights.

    
#### Is this a new project, or one carried over from a prior sprint?
    
No, this is a new project, however we feel this could be included in future sprints for further development. 


#### What have you accomplish during this sprint?

We have defined the project, the phases, and user stories (See below).

We made a start on the overall architecture:
* PNG: https://github.com/SFDO-Sprint-2019-Amsterdam/global-goals/blob/master/architecture-spec/SDG%20Architecture%20Diagram%20(1).png
* Original editable file: https://www.lucidchart.com/invitations/accept/8fbeab89-05ef-4bda-99ba-7aa2145cf846

We have defined an object and field spec for the CRM level of the architecture. 

Quip notes: https://salesforce.quip.com/XPO7AA9jNgml <BR>
   
Global Goals Tracking: https://sustainabledevelopment.un.org/?menu=1300


#### What else needs to be done before you can share this project with the Community?

* Tasks that can be worked on by the Community or at a future Sprint
* How can the broader open source Community help to finish this project?
* What (if any) help would you like from Salesforce.org in order to share this project with the Community?

# User Stories

## .org Customer

* As a strategic leader (role TBC) I want visibility of our progress towards achieving our chosen impact goals

* As a program manager, I want to be able to enter our sustainable development goals into Salesforce so I can make our goals visible to our users

* As a nonprofit I want to be able to map the indicators in our Theory of Change to the Global Goals to demonstrate the credibility of our work to key stakeholders e.g. current and potential funders.

* As a nonprofit I want to be able to choose when I elect for our progress against the GG targets to be shared / made public. 

* As a nonprofit I want to be able to benchmark the contribution that my organisation is making to the GGs alongside other organisations operating in my space.

* As a nonprofit I want to be able to find other types of organisations that are focused on the same indicators in order to identify opportunities for collaboration and economies of scale. 

* As a non-profit organization I would like to easily report on my mission by publishing an external webpage which links my mission towards the SDGs, so that we can report to our stakeholders on the progression we make towards our mission. 

* As a nonprofit I would like to store my mission results inside Salesforce so that I can easily report on progress towards our mission. 


## .org Leadership

* As a Salesforce.org (http://salesforce.org/) leader, I want to see which Sustainable Development Goals are being measured by our customers so I can assess the impact Salesforce's customers are having

* ... so that we can communicate the collective impact of our community to our customers and supporters

* ... so that I can use the insights to drive our strategic partnerships e.g. with the UN

* As Marc Benioff I want to be able to see the contribution of .com AND .org customers so that I can understand the net contribution that our entire customer base is making to solving the world's major challenges.

* As a member of customer success, I want to be able to see which SDG our High Touch .org customers are tracking so that i can feed this in to our quarterly strategic reviews

## The UN Director General

* Understand the current progress that civil society is making towards the global goal targets so that I can discern which impact areas need investment or do not need further investment

* Understand which GGs the sector is working towards so that I can better target investment within global goal areas

* See a live dashboard of progress against targets so that I can make timely decisions aligned to key planning moments (e.g. grant cycles, Davos)

* Compare progress against targets by country vs. the needs of those countries so that I can Target country-level investment strategy for over-subscribed / under-subsribed areas

* See YoY change so that I can isolate anomalies for further research


## As a Corporate via Philanthropy Cloud

* As a philanthropy program manager, I want to be able to log which SDG we are tracking in a visible way so that I can track our progress towards our goals

* As an employee of an organisation that is tracking SDGs I want to be able to see how our company is making a difference

* As a CSR program manager I want to be able to choose the nonprofits that our employees will engage with by impact area / thematic area of interest

