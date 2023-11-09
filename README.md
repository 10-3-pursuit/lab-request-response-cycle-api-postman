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

> http://pokeapi.co

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is...to provide an extensive database everything regarding about the video game/show "Pokemon." It covers from Pokemons to berry flavors. Somebody may want to use this if they want to make a project or application that requires pulling information from a large database regarding Pokemon.

- What is the URL of the documentation?

> http://pokeapi.co/docs/v2

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://pokeapi.co/api/v2/evolution-chain/2

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
  "baby_trigger_item": null,
  "chain": {
    "evolution_details": [],
    "evolves_to": [
      {
        "evolution_details": [
          {
            "gender": null,
            "held_item": null,
            "item": null,
            "known_move": null,
            "known_move_type": null,
            "location": null,
            "min_affection": null,
            "min_beauty": null,
            "min_happiness": null,
            "min_level": 16,
            "needs_overworld_rain": false,
            "party_species": null,
            "party_type": null,
            "relative_physical_stats": null,
            "time_of_day": "",
            "trade_species": null,
            "trigger": {
              "name": "level-up",
              "url": "https://pokeapi.co/api/v2/evolution-trigger/1/"
            },
            "turn_upside_down": false
          }
        ],
        "evolves_to": [
          {
            "evolution_details": [
              {
                "gender": null,
                "held_item": null,
                "item": null,
                "known_move": null,
                "known_move_type": null,
                "location": null,
                "min_affection": null,
                "min_beauty": null,
                "min_happiness": null,
                "min_level": 36,
                "needs_overworld_rain": false,
                "party_species": null,
                "party_type": null,
                "relative_physical_stats": null,
                "time_of_day": "",
                "trade_species": null,
                "trigger": {
                  "name": "level-up",
                  "url": "https://pokeapi.co/api/v2/evolution-trigger/1/"
                },
                "turn_upside_down": false
              }
            ],
            "evolves_to": [],
            "is_baby": false,
            "species": {
              "name": "charizard",
              "url": "https://pokeapi.co/api/v2/pokemon-species/6/"
            }
          }
        ],
        "is_baby": false,
        "species": {
          "name": "charmeleon",
          "url": "https://pokeapi.co/api/v2/pokemon-species/5/"
        }
      }
    ],
    "is_baby": false,
    "species": {
      "name": "charmander",
      "url": "https://pokeapi.co/api/v2/pokemon-species/4/"
    }
  },
  "id": 2
}
```

- What status code did you get back from your request? Why did you receive this status code?

> I received the status code 200 OK because the request went fully through and the server responded correctly.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: Not available

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...the pokemon evolution set we were looking which were "Charmander", "Charmeleon" and "Charizard." Along with each pokemon a url is provided for each that redirects you to their species.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ... explains more regarding the evolution chain of a pokemon and maybe add a photo of each as well.

> I could imagine integrating this API into an app that ... is a game that makes you guess what pokemon is missing within the evolution chain. Since we can grab all the evolutions from a single pokemon. We can .(dot) into the one that we are looking for the user to answer.


### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ... broken up very well depending on the category you were looking for. For instance, some categories were "Pokemon", "Moves", "Berries", "Contests", "Evolution", etc. Not only this but they had subset categories under each. There was a large amount of information here. Talk about Pokemon Heaven.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ... to be difficult to understand when it came to using ID's. You would think each pokemon would have a specific id in order to make it easier for the user. However, it wasn't like that. Their ID's were depending on the category. Usually in the game each pokemon has an id. Would've preferred to be able to see a whole list of ID's so I can find exactly what I'm looking for.

- Did the quality of the documentation impact your decision to use it?

> No because...the information that was provided really went into depth for what I was looking for. And the instructions to use commands were really well written as well. 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No I ended up ...sticking with the one I originally wanted which was pokeapi.co

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... is basically a proccess of how the internet is used. The client which is the local machine sends a GET request to the server (Ex: Searching and clicking enter on Youtube.com). Then the server receives your request and then processes it, it does whatever it has to do and then sends the client a response. The client then receives the response and if everything goes well the landing page of Youtube.com is displayed to them. It is basically how the client and the server communicate with each other.

- In your own words, describe what an API is.

> An API is ... basically a tool that allows software applications to communicate and interact with each other. By implementing API's you can make your app function better by exchanging information and improving it's functionality.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... allows you to better understand the API that you are using by giving you extra information that you may not see in the IDE or even terminal. It's basically a tool that allows you to check out the status of the API call you are making.
