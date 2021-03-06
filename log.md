# 100 Days Of Code - Logd

### Day 0: September 14, 2020

**Today's Progress**:  Setup a couple of initial repositories on github and then got my local system configured to use ssh with github. In an effort to have "somethign" to work with, I searched for a 'todo list' app on github and stumbled across the following:

**Link(s) to research**: [Todo List](https://github.com/cassidoo/todometer)

**Thoughts**: I have been wanting to do this for a while, but ive been hesitant to just start. Changing that today. Guess we will se what comes of this. The following are links to the inital repos that I am going to use for this. [100doc] will be used to log my learning and growth, [TestingWorld] will be used to hold various tests or experimentations I want to work with

**Link(s) to work**: 
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)


### Day 1: September 15, 2020

**Today's Progress**:  Started today with changing the default branches in both of my new repos to 'main' instead of using 'master'. Next, I gave some thought to the 'todo' app that I got yesterday. 
 
**Link(s) to research**: [Todo List](https://github.com/cassidoo/todometer)

**Thoughts**: The conversation around the topic of 'master' is something that I am still working through. However, I feel its a good practice to get away from the 'master'/'slave' terminologies in techology as there have always been better ways to describe the functions those terms were used for. I went into github and also set the default for my account to use as 'main'. Off to start my day, will work on this more later today.

I am not sure how I am going to use the todo list jsut yet. I am thinking of just running it via a random, one-off, docker host ec2 instance. I guess ill get that going and see if its a viable solution for a to-do app.

**Link(s) to work**: 
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)


### Day 2: September 16, 2020

**Today's Progress**: Spent some time working on my docker container. I work with containes daily, but having to build them is something new to me. Most of today has been just getting my Dockerfile to do what I want/need. Feeling slightly more comfortable with the docker CLI, just need to memorize the commands better

**Thoughts**: Docker versus Containerd is something I keep thinking about. Not sure if there is really a point to differentiate between the two, but with all the things happening with Docker over the last year, I cant help but wonder if Containerd is the better technology to work with. 

**Link(s) to work**: 
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 3: September 17, 2020

**Today's Progress**:  I didnt get as much done today as I wanted. I did play with Portainer for a while but decided to remove that image and go back to the drawing board in regards to my container. 

**Thoughts**: No thoughts today - hoping to get a bit more done tomorrow 

**Link(s) to work**: 
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 4: September 18, 2020

**Today's Progress**: Spent some time reading about node and some of the intricacies of using node with containers. I am still debating on what I want to do with this project and am not sure. 

**Thoughts**: I am hopeful that I can spend some time tomorrow documenting a more well-rounded plan to this project. This week has been a bit crazy with work and I havent gotten as much operational on this as I would like

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 5: September 19, 2020

**Today's Progress**: Started on a node tutorial with FreeCodeCamp, but ran into issues with getting my repo to validate correctly. So... I started messing around with various things I could find. I copied down a working version of the `package.json` file that is referenced in the tutorial and then tried to get it to pass validation. It wouldnt pass validation, but I got the errors I was seeing to clear in VS Code, so who knows. Im probably just missing something in my configuration wtih FCC. I submitted the `package.json` file to github and then pointed Snyk at it as ive been wanting to use that service for a while. Everything came back clean so I added a badge to my `README.md` for the `TestingWorld` repo and pushed it up. 

**Link(s) to tutorial**: [FreeCodeCamp - NPM](https://www.freecodecamp.org/learn/apis-and-microservices/managing-packages-with-npm/how-to-use-package-json-the-core-of-any-node-js-project-or-npm-package)

**Thoughts**: While I may not have got the FCC challenge to validate correctly, I am proud of myself for just going out and grabbing bits and pieces and shoving it together to make something. I feel this approach works better for me and allows me to freely explore. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 6: September 20, 2020

**Today's Progress**: I didnt get as much done today as I wanted. I basically played with Docker on my local system and was trying to get myself more familiar with the comamnds 

**Thoughts**: No thoughts to add - today was mostly a recovery day

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 7: September 21, 2020

**Today's Progress**: I didnt spend anytime on this today. I was very busy with work-related issues though. Will make up for this tomorrow.  

**Thoughts**: No thoughts to add

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 8: September 22, 2020

**Today's Progress**: I decided to work on some training modules on A Cloud Guru. Specifically, I am working through the training course for the AWS Cloud Practioner that ACG offers. 

I worked on setting up an EC2 instance and SSH'ing into it to setup a simple apache webserver. I then setup an EC2 instance  ~~to load with run~~ that was set to load a bootstrap script that would install an apache webserver setup automatically with a simple html page. Once that was up and operational, we worked through setting up an application load balancer and making a target pool of the two servers. once that was done, we practiced turning off one server to see the ALB respond and load traffic from the remaining operational webserver. 

Next, we started to review databases and how they are represented in AWS. The lab consist of building an RDS mysql instance spread across multiple AZ's. Going to let that finish building and then finish the lab either later tonight or tomorrow. 

**Thoughts**: As ive stated before, I work with this stuff daily but it escapes me at times how easy it is to setup a fault tolerant system that is fully cloud-native. I have long been a fan of A Cloud Guru, but to see how they setup these classes its really cool to see that someone who has NEVER touched this stuff can walk through doing exactly what I just did. I cant imagine how exciting that must be for someone who hasnt dealt with technology their whole life. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 9: September 23, 2020

**Today's Progress**: Spent some time this morning checking on the RDS instance that I built out last night in AWS. That was up and operational so I can now proceed with the ACG course. Beyond that, I did setup an integration between Snyk and my Slack instance so I can dump notifications into one location.  

**Thoughts**: Looking forward to continuing with my course, but dont have the energy in me today. Spending time trying to bike more and my ride tonight was rough. Hoping I can get some stuff done in the AM before I start my work day

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)

### Day 10: September 25, 2020

**Today's Progress**: I didnt log into or do anything.... Sorry. Work was the primary focus today.   

**Thoughts**: Spent all day documenting various systems at work and then having to setup some tracing for some lambdas we use. I did notice while I was setting up this entry that my dates and days seem to be off. I will need to look at that tomorrow and see what happened... probably a copy/pasta error last week.  

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 11: September 26, 2020

**Today's Progress**: Didnt spend anytime writing code, just read through a couple of intro to Node articles today. I need to go through my history and find the links as they are on my phone.    

**Thoughts**: Today was all research and reading  

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 12: September 27, 2020

**Today's Progress**: I read a single article and then skimmed through a bunch of stuff on twitter and reddit.      

**Thoughts**: Another day of no code writing, but I did find myself reading through various personal blogs and tech-related blogs about Node. I am still trying to fully grasp the ecosystem node-based world. I am hesitatnt to even try to describe it. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 13: September 28, 2020

**Today's Progress**: I worked through a bunch of work stuff      

**Thoughts**: I need to  figure out a way to work through these days and acutally work on this project. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 14: September 29, 2020

**Today's Progress**: Not feeling 100% today - took the day off from work and slept the vast majority of today.       

**Thoughts**: I did try to read some articles today - got myself setup on dev.to and the new stack. My hope is to start getting more development-related news and information from these sources. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 15: September 30, 2020

**Today's Progress**: Feeling better today, but didnt have much time to work on stuff.        

**Thoughts**: Debating on making a simple blog to start piping these posts through and highlight my efforts. Was thinking about that tonight on my walk. Seems like something that should be easy enough to do. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 16: October 01, 2020

**Today's Progress**: Didnt do anything today - just didnt have any time after work.         

**Thoughts**: Going to dedicate some time tomorrow night to working on my ACG tutorials. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 17: October 02, 2020

**Today's Progress**: Im cheating today - using my work as my credit for today! I spent the majority of today working with a coworker to get a new system he built opertional. Ideally this should be as easy as "here is the docker info and environment variables you need".... but....          

**Thoughts**: Learned a good bit about docker, artifactory, the elixir language, and getting them to all work together. Elixir is one of those languages that my coworker really enjoys, but he warned me up front that it was kind of fringe. Seems like a powerful enough language, just has its own issues and catches to learn. All in all, it was a good day. We found a dependency issue that were not sure how to fix, but we will get it. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 18: October 03, 2020

**Today's Progress**: No progress today

**Thoughts**:  

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)

### Day 19: November 15, 2020

**Today's Progress**: I ran through a series of updates on my system and the environments ive built for myself. I have played with CircleCi a bit from my last update. Its doing things, but im not 100% on what it's actually doing. 

**Thoughts**: I have been very busy with work both in a learning/growing sense, but also a "Oh, shit... we need to keep the ship floating..." sense. I am hopeful to be back to this all soon, but for the mean time.. the 100doc is kind of on pause.. 

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)
    - [ACG Practice Blog](http://myalb-1003511962.us-east-1.elb.amazonaws.com/)


