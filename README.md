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

> Name: Random-d.uk
> https://random-d.uk/api or https://random-d.uk/api/v2

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to return random image of ducks

- What is the URL of the documentation?

> https://random-d.uk/api

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://random-d.uk/api/random

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "message": "Powered by random-d.uk",
    "url": "https://random-d.uk/api/192.jpg"
}
```

- What status code did you get back from your request? Why did you receive this status code?

> "200 OK"
> I got this status code because the request was successful

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: Does not show in Postman

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received is an object within an array in JSON format, and includes a message in the object with the value "Powered by random-d.uk", and a url "https://random-d.uk/api/192.jpg"

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that shows a picture of a random animal every time a button is clicked (using multiple API's that provide animal photos), or using it in an app that randomly generates a pet duck everytime a button is clicked (with a randomly provided name and age).

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was laid out in a simple format, with brief descriptions of what each endpoint does.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation tricky for only one reason. It has "GET" right in front of the endpoints. It took me a second to realize the URL i'd use in Postman wouldn't have that "GET" in front of /random.

- Did the quality of the documentation impact your decision to use it?

> Yes, because it was simple and straightforward. I wanted to use an API that was not going to be complicated to use.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No, I stuck with the first one I picked and worked through it. It was simple enough that I saw no need to change it.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is the requests and responses (data) that moves between a client and a server. The server responds to the request from a browser with a status code and/or the content that was requested.

- In your own words, describe what an API is.

> An API stands for "Application Programming Interface". It's a tool that allows applications to extract and share data with one another. They communicate with each other using a set of definitions and protocols.

- In your own words, describe the purpose of Postman.

> Postman is an application that tests API's. It can help you build, design and modify an API you might be working on.
