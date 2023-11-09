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

> Bandsintown API: not sure if this is what you want (https://rest.bandsintown.com/) which was provided on this direct API link: (https://app.swaggerhub.com/apis/Bandsintown/PublicAPI/3.0.0)

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is designed for artists and enterprises representing artists (like agencies, management companies, manager/entities, etc). Even though it offers read-only access to artist info and artist events, the former returns a link to the Bandsintown artist page, current number of trackers, artist photo, and more; while the latter returns a link to the list of events, date and time, venue info: name and location, ticket info, description, line-up, as well as a link to the Bandsintown event page.  
> One can also specify a range of dates, past dates or upcoming dates for events attached to particular artists.

- What is the URL of the documentation?

> (https://publicapis.io/bandsintown-api)

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> (https://rest.bandsintown.com/artists/Kaytranada?app_id=YOUR_APP_ID)

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```{
    "id": "5035831",
    "name": "Kaytranada",
    "url": "https://www.bandsintown.com/a/5035831?came_from=267&app_id=YOUR_APP_ID",
    "mbid": "",
    "options": {
        "display_listen_unit": false
    },
    "tracking": [],
    "image_url": "https://photos.bandsintown.com/large/10057975.jpeg",
    "thumb_url": "https://photos.bandsintown.com/thumb/10057975.jpeg",
    "facebook_page_url": "http://www.facebook.com/536774999682431",
    "tracker_count": 396487,
    "upcoming_event_count": 2,
    "support_url": "",
    "links": [
        {
            "type": "facebook",
            "url": "https://www.facebook.com/Kaytranada/"
        },
        {
            "type": "amazon",
            "url": "https://music.amazon.com/artists/B00BF73Z3G"
        },
        {
            "type": "website",
            "url": "https://www.kaytranada.com/"
        },
        {
            "type": "twitter",
            "url": "https://twitter.com/KAYTRANADA"
        },
        {
            "type": "instagram",
            "url": "https://www.instagram.com/kaytranada/"
        }
    ],
    "artist_optin_show_phone_number": false,
    "show_multi_ticket": true
}
```

- What status code did you get back from your request? Why did you receive this status code?

> 00

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`:

> `Content-Length`:

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...

- In your own words, describe what an API is.

> An API is ...

- In your own words, describe the purpose of Postman.

> Postman is an application that ...
