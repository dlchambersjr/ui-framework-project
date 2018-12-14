![CF](http://i.imgur.com/7v5ASc8.png) JS Framework Comparative Analysis
=======================================================================

## Angular (version 7)

### Research Conducted By: Trevor Stam and David Chambers

### Overall Score and Comments
#### Score (Out of 10): 7.5
#### General Comments
Angular allows the user to create a front-end only interface.  It comes with the ability to create HTTP connects to a RESTful back-end. It has a fast setup process and good tutorial to get a new user started quickly.

#### Pros
* Command Line Interface (CLI) allows for rapid deployment of new modules into the Angular framework.
* Clear Documentation to get started and a fairly intuitive tutorial.  A basic application can be up and running in under 15 minutes, and a more complex application in less than two-hours.
* The CLI also allows for the quick creation and integration of component folders, files, and code along with a testing file. Allows for good separation of concerns.
* Built in Angular components start with a '@' - this creates consistency and clarity as to what is naturally part of the framework.
* Code splitting allows us to essentially break our codebase down into smaller chunks and serve those chunks on demand, which we call “lazy loading”. - (https://toddmotto.com/lazy-loading-angular-code-splitting-webpack)
* Using pipes to modify formatting (i.e., case, currency, etc...)

#### Cons
* Every component creates at least four files before any actual work is doing.  There was a lot of back and forth between files - felt like more than our current understandings
* The launch time is much longer to get the application loaded locally. 
* 

### Ratings and Reviews
#### Documentation
1. (A) Getting Started - Clear and accurate.  
2. (A-) Tutorial Tour of Heroes - navigation is not immediately clear as to where to go next.  Must use the sidebar. Excellent use of summarizing changed files at the end of each section.
3. (A) Easy and quick to find needed information.

#### Testing Options
* (A) Built in testing components with Karma and Jasmine
* e2e = end to end testing - a methodology to test the application flow from start to end. (https://www.softwaretestinghelp.com/what-is-end-to-end-testing/)

#### Systems Requirements
* Must load the Angular CLI to maximize getting up and running.
* Uses npm files as selected by the developer.
* Works on all modern browsers and mobile platforms.


#### Ramp-Up Projections
A simple application could be built within 1-2 hours.  If experienced developers spent 8-16 hours with Angular, they could quickly level up their skills and develop more in-depth applications.

#### Community Support and Adoption levels
[History](https://news.ycombinator.com/item?id=6631576)
[Google Trends](https://trends.google.com/trends/explore?geo=US&q=%2Fg%2F11c6w0ddw9,%2Fm%2F012l1vxv)

### Links and Resources
* [framework](https://angular.io/)
* [Getting Started](https://angular.io/guide/quickstart)
* [examples/tutorials](https://angular.io/guide/quickstart)
* [docs](https://angular.io/docs)

### Code Demos
* [live/running application](http://dc-ts-angular.s3-website-us-west-2.amazonaws.com/)
* [code repository](https://github.com/dlchambersjr/angular-counter)

### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
* `ng serve --open`

