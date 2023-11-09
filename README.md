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

> https://www.boredapi.com/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to help you find things to do when you're bored! There are fields like the number of participants, activity type, and more that help you narrow down your results.

- What is the URL of the documentation?

> https://www.boredapi.com/documentation

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://www.boredapi.com/api/activity

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "activity": "Have a bonfire with your close friends",
    "type": "social",
    "participants": 4,
    "price": 0.1,
    "link": "",
    "key": "8442249",
    "accessibility": 0.1
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: 
application/json; charset=utf-8

> `Content-Length`: 149

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes a random activity, which changes upon refresh, a type for activity such as educational or relaxation, number of participants the activity can accomodate, a price point for the given activity on a scale of 0 to 1, a link to website of activity (if applicable), a key and the accessability (ease if implementation) of the activity on a scale of 0.0 to 1.0.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that recommends activities when you want to keep your budget down for multiple people. It could also be used for if you need a new activity to keep yourself/others occupied as it does give multiple activity types to choose from.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was extremely clear to read and implement. As it was visually based, you didn't need to guess anything as it was plainly spelled out with actionable examples, all placed into labeled categories.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation very simple and clear. There wasn't anything I found challenging or dislikable about it. This was the second API I chose and it gave me no issues whatsoever. The first was more of a hassle which is why I went on the hunt for another option.

- Did the quality of the documentation impact your decision to use it?

> Yes because I'd just come from one which was information dense but still didn't give me the information I was looking for. It was like wading through swamp with the first API, you're moving your legs but not really going anywhere. It was a bit frustrating before I made the decision to just move on, even though I liked the idea of the first one better.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up changing the API choice because the documentation was too dense and hard to get through. Also, it was a foreign language API and once once Google translate was employed, the network information changed in a way I could not use.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle works mostly from the client side in an ask then answer cycle. First a user gives a client a URL, the client builds a request for information (or resources) to be generated by a server. When the server receives that request, it uses the information included in the request to build a response that contains the requested information. Once built, that response is sent back to the client in the requested format, to be rendered to the user.

- In your own words, describe what an API is.

> An API is a software intermediary that allows two applications to talk to each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that helps to access, build, test and modify APIs.
