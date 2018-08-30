# *Lihte*

## Engineering Roadmap:
- [ ] Landing
- [ ] Login/Signup
- [ ] Add Samples
- [ ] Claim Samples
- [ ] Message Center
- [ ] Google Analytics
- [ ] In-house metrics
- [ ] Create a CMS - Admin center
- [ ] Split and A/B tests
- [ ] iOS app for messages and notifications.

## DevOps Roadmap:
- [ ] Set up a space for documentation(Something like a google docs folder for now)
- [ ] Set up Linux AMI EC2 - will host MySQL and the repo
- [ ] Code deploy with Github
- [ ] Set up Linux AMI EC2 staging enviroment
- [ ] Code deploy with Github to staging
- [ ] Security - cloudflare, cloudfront ...


## Code Deploy Process

![alt text](http://www.caseycorvino.co/deployprocess.png)


### How to Code Review. Look for:
* Modularity
* Complexity (ex. for loops vs recursive calls)
* Consistent indentation (indent should be two-spaces)
* Minimal global variables. Only use if completly neccessary


## Language Overview:
* Database      -   MySQL
* Server side    -    NodeJS
* Client side     -    PUG, CSS, JavaScript, JQuery, Ajax

![alt text](http://www.caseycorvino.co/langauge%20model.png)


### Languages Explained:
NodeJS:
* Server side code written in JS to create our webpages and connect out MySQL Database
* Modules:
    * MySQL
    * Http
    * Express

PUG
* Simplified HTML. The code is written in a indent based way and converted to HTML.

CSS
* Default style.

JQuery
* Simplified comonly used Javascipt.

Ajax
* Used to retrieve info from server side to client side.
* Ex: interactive JS on the front end calls a method on the server to retrieve data from the MySQL database, without leaaving the page.

