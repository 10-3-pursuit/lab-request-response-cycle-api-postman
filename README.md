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
> Zen Quotes

> https://zenquotes.io/


- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is... to fetch quotes from infuential figures throughout history into JSON format. Someone might want to use it if they want to have a different random influencial quote display at the top of the page each time the page is loaded. 

- What is the URL of the documentation?

> https://docs.zenquotes.io/zenquotes-documentation/

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://zenquotes.io/api/random

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
[
    {
        "q": "The people who are crazy enough to think they can change the world are the ones who do.",
        "a": "Steve Jobs",
        "h": "<blockquote>&ldquo;The people who are crazy enough to think they can change the world are the ones who do.&rdquo; &mdash; <footer>Steve Jobs</footer></blockquote>"
    }
]

```

- What status code did you get back from your request? Why did you receive this status code?

> 200

> The 200 OK status code means that the request was successful.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: none

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...

>"q": the quote text

>"a": the author name 

>"h": the preformatted HTML quote

> The resulting API data is formatted as a JSON array. A pre-formatted HTML output is included in the body.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ... 

> I can imagine this being used in an app that helps people plan/organize/track their goals (ie: a quit smoking app, no drinking app, lose weight app). It can be used to display inspirational quotes when they reach certain milestones or when they need a little nudge to help them reach their goal. 

> I can imagine this being used to show a random inspirational quote in a calendar app (ie: Ramdon Quote Of the Day).

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ... very informative and had an easy to navigate Table OF Contents describing all the ways in which the API can be used. 

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ... very easy to read and understand, did not find it challenging.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because... YES - I chose this API because I was able to understand the documention and easily find out how to use this API.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...YES - I switched the API I was going to use initially because I clicked through to the documentation and found it to have no explanations of how to use the API or any other details. 

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... is the communication between me (the client/browser) and the server. The request is what I am asking for and the response is the information I requested if it is found, or a status message.

- In your own words, describe what an API is.

> An API is ... is a way for two or more programs to communicate with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... allows you to create and send API requests. Users can send a request to an endpoint or test an API's functionality.
