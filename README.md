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

> http:// https://valorant-api.com/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is...
The purpose of the Valorant API is to provide information about the popular game Valorant. It offers data related to agents, weapons, maps, and more. Developers might want to use this API to create applications, websites, or tools that enhance the gaming experience, provide insights into in-game statistics, or offer additional features for Valorant players.

- What is the URL of the documentation?

>https://valorant-api.com/

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://https://valorant-api.com/v1/agents

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
  "status": "success",
  "data": [
    {
      "id": "1",
      "name": "Brimstone",
      "role": "Controller",
      "description": "Brimstone's orbital arsenal ensures his squad always has the advantage.",
      "abilities": {
        "ability1": "Incendiary",
        "ability2": "Sky Smoke",
        "ability3": "Stim Beacon",
        "ultimate": "Orbital Strike"
      }
    },
    {
      "id": "2",
      "name": "Viper",
      "role": "Controller",
      "description": "Viper deploys an array of poisonous chemical devices to control the battlefield and cripple the enemy's vision.",
      "abilities": {
        "ability1": "Snake Bite",
        "ability2": "Poison Cloud",
        "ability3": "Toxic Screen",
        "ultimate": "Viper's Pit"
      }
    },
    // More agent data...
  ]
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`:application/json; charset=utf-8

> `Content-Length`: Postman didn't show it.

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...
ID: A unique identifier for the agent.
Name: The name of the agent (e.g., Brimstone, Viper).
Role: The role of the agent in the game (e.g., Controller).
Description: A brief description of the agent and their abilities.
Abilities: Specific details about the agent's abilities, including the first, second, and third abilities, as well as their ultimate ability.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...
Agent Guide App, Stats Tracker, Loadout Planner, News and Updates Hub

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...
Clear Endpoints and Usage Examples, Detailed Data Models, Authentication Guidelines, API Explorer.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...
Yes, the quality of the documentation did impact my decision to use it. Clear and well-structured documentation is essential for a smooth integration process.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...
The cycle begins with the client sending a request to the server. This request typically includes information about the action the client wants the server to perform.

- In your own words, describe what an API is.

> An API is ...
An API, or Application Programming Interface, is like a bridge that allows different software applications to communicate and interact with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that ...
Postman is a helpful resource for developers, providing a user-friendly environment to look up the process of testing, documenting, and interacting with APIs. 
