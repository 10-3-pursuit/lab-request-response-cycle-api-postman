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

I chose Random-d.uk

> http://random-d.uk/api

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to generate random images of ducks. Someone might want to use this if they are creating an app that features ducks

- What is the URL of the documentation?

> https://random-d.uk/api

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

Random: https://random-d.uk/api/v2/random

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

When I make a request to that endpoint, it generates an object containing a random photo of a duck.

```json
{
  "message": "Powered by random-d.uk",
  "url": "https://random-d.uk/api/271.jpg"
}
```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK
> I received this status code because it successfully generated a random photo of a duck.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: none provided

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes a random photo of a duck.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app with duck pictures for a calendar or a virtual random pet generator.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was easy to read and straight-forward. It did not have loads and loads of information.

- What did you find challenging about the documentation? Cite specific examples.

> Since the documentation was very straightforward, the instructions were very short and it caused me to over think the instructions.

- Did the quality of the documentation impact your decision to use it?

> Yes, because it was very simple to understand and therefore easy for me to learn from.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes, I ended up switching the API that I chose because I wanted to be able to understand the basic concepts of using an API.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is the exchange of information from the client to the server. The server then processes the request and creates a HTTPS response.

- In your own words, describe what an API is.

> An API allows different applications to use spefic data and formats.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows the use of APIs to be easier. It shows more oganization and collaboration features.
