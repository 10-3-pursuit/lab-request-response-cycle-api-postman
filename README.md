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

> https://ygoprodeck.com/api-guide/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to find yu-gi-oh cards that fit certain parameters. If someone was making a specific deck of Yu-Gi-Oh cards, this API can give you cards that suit the conditions like max attack, card type, etc. 

- What is the URL of the documentation?

// the documentation is not separated from the main page
> https://ygoprodeck.com/api-guide/ 

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://db.ygoprodeck.com/api/v7/cardinfo.php?name=Kurikara Divincarnate

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "data": [
        {
            "id": 35405755,
            "name": "Kurikara Divincarnate",
            "type": "Effect Monster",
            "frameType": "effect",
            "desc": "Cannot be Normal Summoned/Set. Must be Special Summoned (from your hand) by Tributing all face-up monsters on the field that activated their effects this turn in your opponent's Monster Zone. Gains 1500 ATK for each monster Tributed to Special Summon this card. During your End Phase: You can target 1 monster in your opponent's GY; Special Summon it to your field. You can only use this effect of \"Kurikara Divincarnate\" once per turn.",
            "atk": 1500,
            "def": 1500,
            "level": 1,
            "race": "Fairy",
            "attribute": "FIRE",
            "card_sets": [
                {
                    "set_name": "OTS Tournament Pack 23",
                    "set_code": "OP23-EN001",
                    "set_rarity": "Ultimate Rare",
                    "set_rarity_code": "(UtR)",
                    "set_price": "0"
                },
                {
                    "set_name": "Power of the Elements",
                    "set_code": "POTE-EN031",
                    "set_rarity": "Secret Rare",
                    "set_rarity_code": "(ScR)",
                    "set_price": "14.38"
                },
                {
                    "set_name": "Power of the Elements",
                    "set_code": "POTE-EN031",
                    "set_rarity": "Starlight Rare",
                    "set_rarity_code": "(StR)",
                    "set_price": "0"
                }
            ],
            "card_images": [
                {
                    "id": 35405755,
                    "image_url": "https://images.ygoprodeck.com/images/cards/35405755.jpg",
                    "image_url_small": "https://images.ygoprodeck.com/images/cards_small/35405755.jpg",
                    "image_url_cropped": "https://images.ygoprodeck.com/images/cards_cropped/35405755.jpg"
                }
            ],
            "card_prices": [
                {
                    "cardmarket_price": "48.37",
                    "tcgplayer_price": "31.69",
                    "ebay_price": "16.99",
                    "amazon_price": "17.25",
                    "coolstuffinc_price": "31.99"
                }
            ]
        }
    ]
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK, it's the regular response to a successful request.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: was not shown on Postman

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes the cards: Name, type, race, level, atk/def, and attribute.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that lets you simulate the cost of a deck that a user would want to make. Another purpose I see it serving is finding specific cards that fit your necessary parameters (cards below a certain attack, or cards of a specific attribute).

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was straight forward on what you will be getting back as the example usages are clear and to the point. (I was not a big fan and struggled to find what I liked)

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation to be disorganized on all other parts besides the examples as everything was under one webpage, rather than separating each part into different links. Since there are so many different parameters, it can get confusing on how you would apply a couple of them at once as the http: can get quite intricate.

- Did the quality of the documentation impact your decision to use it?

> No because I liked the topic of Yu-Gi-Oh and I figured why not choose a topic I like and deal with the consequences later.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes because a lot of the API's in the list were no longer running so I was looking at different ones that interested me. I tried the "Tonald Drump" (quotes a lot of dumb things trump has said) API but it was lacking in information so I changed and for the Yu-Gi-Oh API.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is a communication process between a client and a server on the web. It begins with the client sending a request to the server, specifying the desired action. The server processes the request and sends back a response, completing the cycle.

- In your own words, describe what an API is.

> An API is a tool that allows different software applications to talk to each other and it defines the methods and rules for how the applications should communicate. It allows developers to use the functionality of one software in another, making it easier to build applications.

- In your own words, describe the purpose of Postman.

> Postman is an application that helps developers test API's that we are working with by sending requests to APIs, test their functionality, and organize their work. Postman simplifies the process of developing and testing APIs by helping us visualize our endpoints through its user-friendly interface.
