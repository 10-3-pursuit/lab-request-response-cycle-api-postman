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

> https://www.haloapi.com/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to provide metadata about Halo 5 Campaign missions. Someone might use this as an example when testing their code to display information about a mission in a game they are developing.

- What is the URL of the documentation?

> https://developer.haloapi.com/docs/services/58ace18c21091812784ce8c5/operations/Halo-5-Campaign-Missions

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://www.haloapi.com/metadata/h5/metadata/campaign-missions

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
[
    {
        "missionNumber": 1,
        "name": "Osiris",
        "description": "Fireteam Osiris are dispatched to recover the UNSC’s most wanted criminal: Doctor Catherine Elizabeth Halsey",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array01-9c1ff3f00e364bfaa0e059a90fa37d92.jpg",
        "type": "OsirisTeam",
        "id": "73ed1fd0-45e5-4bb9-ab6a-d2852c04ea7d",
        "contentId": "94ad113a-31ce-4fce-ac4a-87e6cfbb88d9"
    },
    {
        "missionNumber": 2,
        "name": "Blue Team",
        "description": "The Master Chief is reunited with his Spartan II Blue Team for a routine investigation of the lost ONI research station Argent Moon",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array02-b6e6f433fbbf4011856722afba3cba67.jpg",
        "type": "BlueTeam",
        "id": "96c3e3dd-7703-4086-9e64-e3a23932bdc4",
        "contentId": "cc8f8885-956f-4969-9ff0-c05be56d688c"
    },
    {
        "missionNumber": 3,
        "name": "Glassed",
        "description": "Osiris must pursue Blue Team to a glassed world beyond UNSC jurisdiction",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array03-56e025da746b4a7cb0662d3412fbcb1f.jpg",
        "type": "OsirisTeam",
        "id": "1c4f8e19-b046-4f78-9e2d-959cba84663d",
        "contentId": "562eb443-a89a-4944-9425-36a74e450fe2"
    },
    {
        "missionNumber": 4,
        "name": "Meridian Station",
        "description": "Osiris learns that Meridian Station harbors many secrets",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array04-95bc925644684fd482ef9fe39e97a9c5.jpg",
        "type": "OsirisTeam",
        "id": "db9f76c4-6f9a-4c1a-9b48-7aaf59472ccd",
        "contentId": "299c2fe0-f5e8-4434-8435-03b622cf1d10"
    },
    {
        "missionNumber": 5,
        "name": "Unconfirmed",
        "description": "Osiris track Blue Team deep below the surface of Meridian",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array05-4fda17114e954fc293dbc788a3771917.jpg",
        "type": "OsirisTeam",
        "id": "825065cf-df57-42e3-b845-830e7340ea43",
        "contentId": "1dab3ff1-8960-43db-aa44-5c8962e5fbdc"
    },
    {
        "missionNumber": 6,
        "name": "Evacuation",
        "description": "Osiris are separated from Blue Team and must race to catch up",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array06-12c6b7520666460c84a08d0194dd372f.jpg",
        "type": "OsirisTeam",
        "id": "b486c8f6-0b00-4a46-b91a-0514969d7c94",
        "contentId": "57437f30-49a2-4d04-b9b6-5acdc1f4305b"
    },
    {
        "missionNumber": 7,
        "name": "Reunion",
        "description": "Blue Team arrive at the Forerunner world Genesis, where they discover the true reason for the Guardian’s activation",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array07-6bfe2c86d66c440a84e9a18f03e4af2d.jpg",
        "type": "BlueTeam",
        "id": "37c717b8-7ae8-4be4-aaa2-945e083bcf3e",
        "contentId": "dece84ee-3ab0-4f85-9bbd-f0b2e5755eff"
    },
    {
        "missionNumber": 8,
        "name": "Swords of Sanghelios",
        "description": "When evidence reveals the Master Chief is in danger, Fireteam Osiris’ mission changes from retrieval to rescue",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array08-43a85271d864411888053d83bade924a.jpg",
        "type": "OsirisTeam",
        "id": "72c98d4a-4ee4-40db-baf3-1b1cc3672654",
        "contentId": "e3a2b01a-6b09-4b4b-8673-5defbd61d374"
    },
    {
        "missionNumber": 9,
        "name": "Alliance",
        "description": "Osiris joins forces with the Swords of Sanghelios",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array09-a9daf8297db04798b071c7061b12b4b8.jpg",
        "type": "OsirisTeam",
        "id": "9a188f67-1664-4d7b-83ca-1d74f714f764",
        "contentId": "76986953-d3e6-4cbd-ae33-eb976ffaee14"
    },
    {
        "missionNumber": 10,
        "name": "Enemy Lines",
        "description": "In order to activate the Guardian, Osiris must track down a Forerunner Constructor",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array10-99aa976dbea943c3b8256cc698443be7.jpg",
        "type": "OsirisTeam",
        "id": "f352eafd-d307-4341-a192-16f7f3f5b43c",
        "contentId": "f4d96489-474e-42c8-81ef-319fe2e68927"
    },
    {
        "missionNumber": 11,
        "name": "Before the Storm",
        "description": "Osiris and the Swords of Sanghelios prepare for a final battle with the Covenant",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array11-f715334a2a68435fba6dc7467f561c50.jpg",
        "type": "OsirisTeam",
        "id": "2702ea83-2c3e-4fd5-8370-60d9a6e0422f",
        "contentId": "1beccbb9-6f82-472b-af88-5b0f08cadc59"
    },
    {
        "missionNumber": 12,
        "name": "Battle of Sunaion",
        "description": "Osiris race to reach the Guardian before it leaves Sanghelios",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array12-901b0025b17b4667ae8038239e692584.jpg",
        "type": "OsirisTeam",
        "id": "8d72dd82-3afb-409e-bee0-512dc97893d2",
        "contentId": "d1af8745-f9ae-4a01-8e21-6a13033ed5c1"
    },
    {
        "missionNumber": 13,
        "name": "Genesis",
        "description": "Osiris arrive on Genesis, where they meet a new ally in their battle",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array13-c60a8c104a4e4f409c8d275a570730a4.jpg",
        "type": "OsirisTeam",
        "id": "82f8471c-a2ef-4089-ac04-7e829fdec912",
        "contentId": "8426a18e-df4d-40b3-a9fa-a26ee06c7724"
    },
    {
        "missionNumber": 14,
        "name": "The Breaking",
        "description": "The Master Chief and his team face their greatest threat, and his hardest choice as the true power of Genesis is revealed",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array14-722fa773f6b24e8e87e8a9b1fba3576a.jpg",
        "type": "BlueTeam",
        "id": "fcd7caa4-37c9-4365-bdda-9041dc6699ed",
        "contentId": "bdf8c339-e69c-4e40-8f74-459e44591de7"
    },
    {
        "missionNumber": 15,
        "name": "Guardians",
        "description": "As Blue Team’s lives hang in the balance, Osiris must save them and stop the Guardians",
        "imageUrl": "https://content.halocdn.com/media/Default/games/halo-5-guardians/map-images/campaign/campaign_missions_array15-6454e53d0a3942ecad2ed3360b1aad2a.jpg",
        "type": "OsirisTeam",
        "id": "7dc80b62-dd39-41d5-9b7a-d71fd8832c07",
        "contentId": "f6480c21-7399-4bc5-acf4-5166e5cf77b6"
    }
]

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK. I received this because the request was properly accepted.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`:2833

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes a list of campaign missions, where each mission is given a number, a name, a description, an id for the mission, a type displaying the team for the mission, and content ID for internal use purposes.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that provides information on video game missions, such as a wiki page. You could also use information to create an online guide for video game missions.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was descriptive of the received information. It provided an example response and even let you try out a request without having to use an application like postman to use the api key.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation challenging because there doesn't seem to be any request parameter instructions, and figuring out how to use the api-key in postman was challenging.

- Did the quality of the documentation impact your decision to use it?

> Ultimately it did not as I was determined to find a way to use this api as it was information I would be familiar with.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No, I stuck with the one I initially selected and worked through it.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is the order in which data is sent and received on a web page. It is the order in which this process of sending a request for data, and receiving a response happens.

- In your own words, describe what an API is.

> An API is a resource that allows you to integrate data or other functionalities into a program without having to work from scratch. 

- In your own words, describe the purpose of Postman.

> Postman is an application that allows you to send an HTTP request to an api and view the different metadata about the request and response of this process, as well as view the actual response.
