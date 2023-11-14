# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> Bored API https://www.boredapi.com/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is... to generate a random activity as inspiration when the user is bored	

- What is the URL of the documentation?

> https://www.boredapi.com/documentation

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://www.boredapi.com/api/activity?type=relaxation

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "activity": "Go to a nail salon",
    "type": "relaxation",
    "participants": 1,
    "price": 0.4,
    "link": "",
    "key": "7526324",
    "accessibility": 0.5
}
```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK - the request was successful

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 128

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data shows the activity name, what kind fo activity, how many participants, the cost, a possible link, a unique key, and an accessibility rating. 

- Identify at least two ways to use the data within a web application.

> 1. Showing lists activities based on filtered values (such as group number/number of participants)
> 2. suggesting activities that can be done after a stressful problem on a homework website

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was very straightfoward. I liked how it included response examples so that you would be able to understand how to use the data before even requesting it. 

- What did you find challenging about the documentation? Cite specific examples.

> I didn't find it particularly challenging. I wish there was also documentation for how to find an activity with more than one specified value, such as searching for an activity that involves cooking and 4 people.

- Did the quality of the documentation impact your decision to use it?

> Kind of. This was the first API I decided to use, but I didn't switch to another one because I found it easy to comprehend.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No, I stayed with my first API

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> A client requests information from a server, and responds with the data. Whether or not the data requested can be found, a request will return a status code signifying any problems that may have occured. 

- In your own words, describe what an API is.

> An API is an intermediary point of contact between a client and server in the request-response cycle. It returns the data in a specified format to make it more managable. 

- In your own words, describe the purpose of Postman.

> Postman is an application that makes it easy to test out API's.
