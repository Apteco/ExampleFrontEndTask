# Holiday destination pivot table front-end application

![Destination By Year](./docs/teal-green-holidays.jpg)

This is a front-end development exercise that we expect you to be able to complete in around one week of your own time.

## The task
We estimate that this task will take around **6 hours** if you did it all in one go, but feel free to manage your time how you see fit!  
If you find yourself taking a lot longer then just submit what you have created and document in your project's **README.md** anything else that would have liked to add/do given the time.

### Details
To complete this task, you must:
- Read the scenario, main user story and extension stories below.
- Create a single webpage application to fulfil the requirements of the main story plus **at least one** of the extension stories (they aren't listed in priority order - you can choose which one(s) you want to tackle).
- Create a git repository on a public host (such as GitHub) and **continuously** commit your code as you work towards your solution.
- Create a project **README.md** where you'll put your project description, notes, assumptions etc...
- Include basic instructions on how to build and run your application in the README file.
- Design the front end as you see fit.
- When you're finished, send over a link to the repo and links to other relevent resources (if any).
- Feel free to also include any feedback on the task itself!

#### The Scenario
You are writing an application for a fictious travel agency (called "Teal Green Holidays") that holds information on its customers and the holiday bookings that they have made (amongst other details).
There is an API already available that can return this information, including aggregated results.
The application is for marketing staff within the travel agency to better understand their customer base (including their booking history) so that they can communicate more effectively with their customers.
The application should run on a modern web browser (i.e. Chrome)

#### The User story
```
As a marketing user at Teal Green Holidays,
I would like to see a breakdown of the number of people that have been to each holiday destination per year in a table,
So that I can understand how the numbers of people that have been to each destination has changed over time.
```

A JSON object containing the results of a call to the API for an aggregation of all data is available at [/data/cube-results.json](data/cube-results.json).  You should use this data in the format it is provied as the basis for this story.  A description of the format of the data is available at [/docs/aggregation-result-format.md](docs/aggregation-result-format.md).

#### Extension user stories
Once the main user story has been completed we would like you to also implement at leat one of the following extensions.
These aren't listed in priority order so you can choose which one(s) you would like to implement.

```
As a marketing user,
I would like to be able to sort the data in the table,
So that I can more easily see the largest/smallest values in the table.
```

```
As a marketing user,
I would like to be able to filter the data in the table,
So that I can focus in on the data for particular destinations and/or years.
```

```
As a marketing user,
I would like to be able to pull the data from the Teal Green Holidays API
So that I can have live access to up-to-date information.
```

A description of how to connect to and authenticate with the Teal Green Holidays API is available at [/docs/connecting-to-api.md](docs/connecting-to-api.md).
You will need credentials (which we can supply) to authenticate with the API.

### Assumptions:
- Your project must work in the latest version of Google Chrome, you can ignore all other browsers.
- Please list any other assumptions you may have made.
- Feel free to use/not use any JS libraries/frameworks.
- Feel free to use/not use any HTML/CSS frameworks.
- If you have the time then host the page on a server/service of your choice and put the link in your README file.

### Assessment Criteria
Your project will be assessed on the following criteria (in order of importance):

1. Approach to the problem.
2. Code organisation and structure, including repo structure.
3. Maintainability.
4. Choice of frameworks.
5. UX.
6. Flair.
7. *bonus points* if you can host the page and it's dependencies on a publically available location.

We're trying to see your thought processes with this task. What's more important to us is how you approach the task, rather than the actual final output itself.

Looking forward to seeing your project :)