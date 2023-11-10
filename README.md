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

> Free Dictionary
>https://api.dictionaryapi.dev/api/v2/entries/en/hello



- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> It provides definitions,pronounciations and definitions of words.

- What is the URL of the documentation?


> https://dictionaryapi.dev/

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://api.dictionaryapi.dev/api/v2/entries/en/hello

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
[
    {
        "word": "hello",
        "phonetics": [
            {
                "audio": "https://api.dictionaryapi.dev/media/pronunciations/en/hello-au.mp3",
                "sourceUrl": "https://commons.wikimedia.org/w/index.php?curid=75797336",
                "license": {
                    "name": "BY-SA 4.0",
                    "url": "https://creativecommons.org/licenses/by-sa/4.0"
                }
            },
            {
                "text": "/həˈləʊ/",
                "audio": "https://api.dictionaryapi.dev/media/pronunciations/en/hello-uk.mp3",
                "sourceUrl": "https://commons.wikimedia.org/w/index.php?curid=9021983",
                "license": {
                    "name": "BY 3.0 US",
                    "url": "https://creativecommons.org/licenses/by/3.0/us"
                }
            },
            {
                "text": "/həˈloʊ/",
                "audio": ""
            }
        ],
        "meanings": [
            {
                "partOfSpeech": "noun",
                "definitions": [
                    {
                        "definition": "\"Hello!\" or an equivalent greeting.",
                        "synonyms": [],
                        "antonyms": []
                    }
                ],
                "synonyms": [
                    "greeting"
                ],
                "antonyms": []
            },
            {
                "partOfSpeech": "verb",
                "definitions": [
                    {
                        "definition": "To greet with \"hello\".",
                        "synonyms": [],
                        "antonyms": []
                    }
                ],
                "synonyms": [],
                "antonyms": []
            },
            {
                "partOfSpeech": "interjection",
                "definitions": [
                    {
                        "definition": "A greeting (salutation) said when meeting someone or acknowledging someone’s arrival or presence.",
                        "synonyms": [],
                        "antonyms": [],
                        "example": "Hello, everyone."
                    },
                    {
                        "definition": "A greeting used when answering the telephone.",
                        "synonyms": [],
                        "antonyms": [],
                        "example": "Hello? How may I help you?"
                    },
                    {
                        "definition": "A call for response if it is not clear if anyone is present or listening, or if a telephone conversation may have been disconnected.",
                        "synonyms": [],
                        "antonyms": [],
                        "example": "Hello? Is anyone there?"
                    },
                    {
                        "definition": "Used sarcastically to imply that the person addressed or referred to has done something the speaker or writer considers to be foolish.",
                        "synonyms": [],
                        "antonyms": [],
                        "example": "You just tried to start your car with your cell phone. Hello?"
                    },
                    {
                        "definition": "An expression of puzzlement or discovery.",
                        "synonyms": [],
                        "antonyms": [],
                        "example": "Hello! What’s going on here?"
                    }
                ],
                "synonyms": [],
                "antonyms": [
                    "bye",
                    "goodbye"
                ]
            }
        ],
        "license": {
            "name": "CC BY-SA 3.0",
            "url": "https://creativecommons.org/licenses/by-sa/3.0"
        },
        "sourceUrls": [
            "https://en.wiktionary.org/wiki/hello"
        ]
    }
]

```

- What status code did you get back from your request? Why did you receive this status code?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`:application/json; charset=utf-8

> `Content-Length`:(None)

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received is an array of objects with keys value pairs.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app designed that fuctions as a dictionary. 
> I could probably use this API to develop a word game.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was short and concise. 

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...Not Applicable.

- Did the quality of the documentation impact your decision to use it?

> Yes, because it was very short and not verbose.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes, I switched to the dictionary API after looking at a few others that were very confusing.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is more complex than it seems. Every request gets a single response. When you send a request to a webserver, it may send that data to a database before returning a response. And all this takes only a few seconds.

- In your own words, describe what an API is.

> An API is a way for two computer or more computers to communicate with each other and share data.

- In your own words, describe the purpose of Postman.

> Postman is an application platform for building and using API's.
