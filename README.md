# Curvestone | Angular homework
Create an application where the user can enter the state of their assets portfolio on a particular day in the past and see how much money would it be worth today.
The only class of assets we’re considering here are stocks and/or mutual funds.

*Example:*
> Start Date: 2013-03-20 
>
> Initial Balance: $32500 
>
> Portfolio Allocation: AAPL: 20% GOOG: 50% VTI: 30% 

#### Required features:

##### back-end:
- create the small Node.js app that will act as a backend for the UI app,
- write a custom endpoint that will return the data for the given request:
    - implement the logic of calling the https://marketstack.com/ API to get the data from the start point for the given assets
        - https://marketstack.com/ has a free plan. Create your own account to get a key
    - perform weekly data aggregation and return this format of data to the front-end application.

##### front-end:
- make a small app where the user can enter this data and can get the results,
- call the Node.js app’s endpoint to get the data for the entered parameters
- based on the response, please create a list of charts (one per asset) using the Highcharts library (https://www.highcharts.com/) and pick the proper chart type to visualize stock changes,
- add spinner while loading the data,
- make sure that application looks good on various screen resolutions.

#### Notes:
- There’s a boilerplate of Node.js backend app that you can use as a starting point, available at: https://github.com/itc-developer/curvestone-home-assignment.
- For the frontend application pick the technology (React.js or Angular) that you’re most comfortable with and generate the appropriate boilerplate.
- Document any assumptions you’ve made in the Readme file, especially any questions you’d like to ask the domain experts if you had a chance.
- Show how you would test this code.
- Focus on showing us the few key programming and design practices you’re following in your daily work and highlight them explicitly in the Readme file.
- **Remember that the purpose of this task is to demonstrate your skills, not create a real app, so the domain knowledge is not crucial.**
- We suggest you spend up to *4 hours* on this task (the sweet spot should be 2 hours – please let us know if this takes more).
- In the Readme file provide instructions allowing the reviewer to run the project easily.

#### Sharing

Use the naming convention: `curvestone_<first-name>-<last-name>`. You can share your work with one of these accounts:

* Github:
    * https://github.com/itc-developer/
* Gitlab:
    * https://gitlab.com/itc-developer
* Bitbucket:
    * https://bitbucket.org/itc-developer/ (jobs@itcraftship.com)
    
Please also confirm that you completed the homework by sending an email to jobs@itcraftship.com.
