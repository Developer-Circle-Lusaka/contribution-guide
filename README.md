## DevC Lusaka Contribution Guide 

All repositories under this organization will have to follow the standards mentioned in this guide, this can be updated anytime, actually if you have any addition, kindly send us a PR we will be glad to look it over and merge it as soon we can.  

### Programming Languages  

Realizing the growth and the easy implementation of Javascript, most of the repos will be written in Javascript apart from configuration files and scripts, these too will be mentioned below.  

 - Javascript
 - Python
 - Bash
 - Yaml
 
 ### Version Control 
 
 - Git  
 - Github
 
each feature should have its own branch in all repositories, new features will be communicated via issue threads. 


### Code Quality

> code is all about communicating ideas to other humans. prefer readability over clever writability. @getify

we strongly believe that code isn't just about computers but also a way to communicate with others.  

We will use the following tools to make sure that the code we write is the same across all the repositories.  

 - Eslint
 - Prettier 

 
 ### Front-End 

We are considering libraries that are widely used by most people.  

 - Reactjs
 - Vuejs
 - Angularjs
 
 The libraries above will be used in that order, unless there is a special need we will use `reactjs` as our main user interface library, If you need to learn, you can reach out to us.  

### Back-End  

 - Nodejs
 
 We will use Nodejs for the backend, if need arise to include other services or libraries, this section will be updated.  

### Contributing 

The purpose of most repos in here is to encourage opensource contribution to both beginners and those who have an experience in opensource.  

Check for issues if you want to work on one of them, if you are a beginner, it would be good for you to check the label marked as **first-good-issue** , if you have an issue you need to report make use of the issue template.  

Always create a new branch for the issue you want to work on, this makes it easy for the maintainers to know the exact feature you worked on and this can help with keeping track of the repo.  

Avoid putting unrelated commits in one branch, when you are don e working on the branch submit a PR with a description on what you have done and a brief of what you changed and why that was important. 

#### Quick guide to submitting a pull request

Fork the repo and Clone the forked repo

`git clone https://github.com/your-github-username/name-of-repo` 

Set up the remote version

`git remote add upstream https://github.com/Developer-Circle-Lusaka/name-of-repo` 

verify that you have added the remote and you have 2 remotes

`git remote -v` 

- **origin** should point to your fork
- **upstream** should point to this repo

To Keep your fork up to date, do the following and make sure you run this everytime you want to push your new changes.      

`git pull upstream master` 

After making changes on a specific branch, push your changes, remember to submit a PR on the origin remote.  
Before you do this, make sure the tests are passing and the lint isn't reporting any errors.  

`git push origin your_branch_name` 

After pushing your changes, then create a pull request with enough details to help maintainers know what you were trying to do.  






  
