# &#x20;                        CI AND CD DEVELOPS



## CI/CD (Continuous Integration and Continuous Deployment/Delivery) is the backbone of modern DevOps engineering.





### 🛠️ Continuous Integration (CI)



#### CI focuses on the automated preparation and testing of code changes as soon as developers commit them to a shared repository.

#### • The Process: Developers push code multiple times a day ➡️ An automated server detects the change ➡️ The server builds the application and runs automated unit/integration tests.

#### • The Goal: Detect bugs and integration conflicts as early as possible.



### 🚚 Continuous Delivery (CD)



#### Continuous Delivery takes over where CI leaves off. It ensures that the tested code is automatically packaged and deployed to a staging environment (like testing or pre-production).

#### • The Process: Code passes CI ➡️ Automated tools deploy it to a staging environment ➡️ Further automated testing (like UI or performance tests) occurs.

#### • The Goal: Ensure the codebase is always in a deployable state. Production deployment still requires a manual human approval/click.



### 🚀 Continuous Deployment (CD)



#### Continuous Deployment is an extension of Continuous Delivery that removes the manual human intervention.

#### • The Process: Every change that passes all stages of your automated pipeline is automatically released directly to production and end-users.

#### • The Goal: Minimize the time between writing a line of code and that code providing value to customers.



### 📊 Comparing the Stages





##### Feature	Continuous Integration (CI)	Continuous Delivery (CD)	Continuous Deployment (CD)

##### Primary Focus	Automating build and test phases.	Keeping code deployable at any time.	Automating the final release to users.

##### Deployment Trigger	Code commit by developer.	Automated after CI passes.	Fully automated through to production.

##### Human Intervention	None (Automated).	Manual click needed for production.	None (Fully Automated).

###### Risk Level	Low (Internal feedback).	Medium (Controlled release).	Higher (Relies heavily on robust tests).





## 🎯 Key Benefits of CI/CD



### • Faster Time-to-Market: Features reach users in minutes or hours instead of months.

### • Smaller Code Changes: Developing in small chunks reduces the complexity of fixing bugs.

### • Higher Quality: Automated test suites catch regressions before they ever impact a user.

### • Happier Teams: Eliminates the stress of manual "release days" or messy code merges.



