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

> https://api.chucknorris.io/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> Chuck Norris facts are satirical factoids about martial artist and actor Chuck Norris that have become an Internet phenomenon and as a result have become widespread in popular culture. The 'facts' are normally absurd hyperbolic claims about Norris' toughness, attitude, virility, sophistication, and masculinity.

- What is the URL of the documentation?

> There is no separate page for documentation:
> https://api.chucknorris.io/

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://api.chucknorris.io/jokes/random

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "categories": [],
    "created_at": "2020-01-05 13:42:18.823766",
    "icon_url": "https://assets.chucknorris.host/img/avatar/chuck-norris.png",
    "id": "NFxaKElARJOKRgUoYAHVBg",
    "updated_at": "2020-01-05 13:42:18.823766",
    "url": "https://api.chucknorris.io/jokes/NFxaKElARJOKRgUoYAHVBg",
    "value": "You can't spell Love without L O, you can't spell is without I S, you can't spell SILO without LOIS. Chuck Norris"
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json;charset=UTF-8

> `Content-Length`: Does not show in Postman

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The most important data we received includes a url for the random joke and a value (which is the actual joke).

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that has random jokes or specifically talks about Chuck Norris.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation gives you examples of what data you can get back with this API:
{
"icon_url" : "https://assets.chucknorris.host/img/avatar/chuck-norris.png",
"id" : "RChm8djZRx6Ovr0sH3aBeQ",
"url" : "",
"value" : "Chuck Norris believes that for every action there is an equal and opposite roundhouse kick to your head."
}

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation lacks examples of joke categories.

- Did the quality of the documentation impact your decision to use it?

> No because Chuck Norris jokes are nostalgic for me. I wanted to see what they had.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No I ended up sticking with the one I initially chose and figured out how to use it based on documentation.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle allows for communication between your browser and a server through a router. Your browser sends a request, and the server responds.

- In your own words, describe what an API is.

> An API stands for Application Programming Interface. It is software that uses the request-response cycle to give you specific data based on the API.

- In your own words, describe the purpose of Postman.

> Postman is an application that interacts with an API using the request-response cycle. You can use it to test endpoints.
