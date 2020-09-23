# 100 Days Of Code - Log

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

I worked on setting up EC2 instances and SSH'ing into them to setup a simple apache webserver OR setting up EC2 instances to load with run scripts and have the apache webserver setup automatically. Once that was up and operational, we worked through setting up an application load balancer and making a target pool of the two servers. once that was done, we practice turning off one server to see the ALB respond

**Thoughts**: As ive stated before, I work with this stuff daily but it escapes me at times how easy it is to setup a fault tolerant system that is fully cloud-native.  

**Link(s) to work**:
    - [Testing World](https://github.com/jragland/TestingWorld)
    - [100 Days of Code](https://github.com/jragland/100doc)