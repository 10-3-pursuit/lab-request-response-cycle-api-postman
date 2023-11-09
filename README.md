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

I chose 'Art Institute Of Chicago API'.
> http://api.artic.edu

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to give museum data and it allows developers to explore and integrate the museum’s public data into their projects. 

- What is the URL of the documentation?

> http://api.artic.edu/docs

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://api.artic.edu/api/v1/artworks/129884

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "data": {
        "id": 129884,
        "api_model": "artworks",
        "api_link": "https://api.artic.edu/api/v1/artworks/129884",
        "is_boosted": true,
        "title": "Starry Night and the Astronauts",
        "alt_titles": null,
        "thumbnail": {
            "lqip": "data:image/gif;base64,R0lGODlhBAAFAPQAABw/Zhg/aBRBaBZBahRCaxxBahxEahNIchZJcR9LdB9OdiZIZSBEbShLbjxRZyBPeipRcSpReUpWaitXgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAAAAAAALAAAAAAEAAUAAAURoMJIDhJAywAcAlEkxhNNTQgAOw==",
            "width": 5376,
            "height": 6112,
            "alt_text": "Abstract painting composed of small vertical dabs of multiple shades of blue with a small area of similar strokes of red, orange, and yellow in the upper right."
        },
        "main_reference_number": "1994.36",
        "has_not_been_viewed_much": false,
        "boost_rank": 1,
        "date_start": 1972,
        "date_end": 1972,
        "date_display": "1972",
        "date_qualifier_title": "",
        "date_qualifier_id": null,
        "artist_display": "Alma Thomas\nAmerican, 1891–1978",
        "place_of_origin": "United States",
        "description": "<p>After decades as a representational painter, in her seventies Alma Thomas turned to abstraction, creating shimmering, mosaic-like fields of color with rhythmic dabs of paint that were often inspired by forms from nature. The artist had been fascinated with space exploration since the late 1960s, and her later paintings often referenced America’s manned Apollo missions to the moon. Although she had never flown, Thomas began to paint as if she were in an airplane, capturing what she described as shifting patterns of light and streaks of color. “You look down on things,” she explained. “You streak through the clouds so fast. . . . You see only streaks of color.”</p>\n<p><em>Starry Night and the Astronauts</em> evokes the open expanse and celestial patterns of a night sky, but despite its narrative title, the work could also be read as an aerial view of a watery surface, playing with our sense of immersion within an otherwise flat picture plane. The viewer is immersed not only in the sense of organic expanse that this painting achieves, however, but also in an encounter with Thomas’s process: the surface here is clearly constructed stroke by stroke. Meanwhile, the glimpses of raw canvas between each primary-colored mark seem as vivid as the applied paint itself—almost as if the composition were backlit. Thomas relied on the enlivening properties of color throughout her late-blooming career. “Color is life,” she once proclaimed, “and light is the mother of color.” This painting was created in 1972, when the artist was eighty. In the same year, she became the first African American woman to receive a solo exhibition at a major art museum, the Whitney Museum of American Art in New York City.</p>\n",
        "dimensions": "152.4 × 134.6 cm (60 × 53 in.)",
        "dimensions_detail": [
            {
                "depth_cm": 0,
                "depth_in": 0,
                "width_cm": 134.6,
                "width_in": 53,
                "height_cm": 152.4,
                "height_in": 60,
                "diameter_cm": 0,
                "diameter_in": 0,
                "clarification": null
            }
        ],
        "medium_display": "Acrylic on canvas",
        "inscriptions": null,
        "credit_line": "Purchased with funds provided by Mary P. Hines in memory of her mother, Frances W. Pick",
        "catalogue_display": null,
        "publication_history": null,
        "exhibition_history": null,
        "provenance_text": null,
        "edition": null,
        "publishing_verification_level": "Web Basic",
        "internal_department_id": 246,
        "fiscal_year": 1994,
        "fiscal_year_deaccession": null,
        "is_public_domain": false,
        "is_zoomable": true,
        "max_zoom_window_size": -1,
        "copyright_notice": null,
        "has_multimedia_resources": false,
        "has_educational_resources": true,
        "has_advanced_imaging": false,
        "colorfulness": 53.6375,
        "color": {
            "h": 45,
            "l": 49,
            "s": 94,
            "percentage": 0.0035946655163737015,
            "population": 29
        },
        "latitude": 41.8805769576144,
        "longitude": -87.6218733015747,
        "latlon": "41.880576957614,41.880576957614",
        "is_on_view": true,
        "on_loan_display": null,
        "gallery_title": "Gallery 291",
        "gallery_id": 25468,
        "nomisma_id": null,
        "artwork_type_title": "Painting",
        "artwork_type_id": 1,
        "department_title": "Contemporary Art",
        "department_id": "PC-8",
        "artist_id": 44708,
        "artist_title": "Alma Thomas",
        "alt_artist_ids": [],
        "artist_ids": [
            44708
        ],
        "artist_titles": [
            "Alma Thomas"
        ],
        "category_ids": [
            "PC-8",
            "PC-142",
            "PC-825",
            "PC-830"
        ],
        "category_titles": [
            "Contemporary Art",
            "African American artists",
            "Women artists",
            "African Diaspora"
        ],
        "term_titles": [
            "painting",
            "painting (image making)",
            "acrylic paint",
            "patterns",
            "contemporary",
            "canvas",
            "blue (color)",
            "red (color)",
            "orange (color)",
            "yellow (color)",
            "modern and contemporary art"
        ],
        "style_id": "TM-12062",
        "style_title": "contemporary",
        "alt_style_ids": [],
        "style_ids": [
            "TM-12062"
        ],
        "style_titles": [
            "contemporary"
        ],
        "classification_id": "TM-9",
        "classification_title": "painting",
        "alt_classification_ids": [
            "TM-155"
        ],
        "classification_ids": [
            "TM-9",
            "TM-155"
        ],
        "classification_titles": [
            "painting",
            "modern and contemporary art"
        ],
        "subject_id": "TM-12793",
        "alt_subject_ids": [
            "TM-11843",
            "TM-11851",
            "TM-11905",
            "TM-11842"
        ],
        "subject_ids": [
            "TM-12793",
            "TM-11843",
            "TM-11851",
            "TM-11905",
            "TM-11842"
        ],
        "subject_titles": [
            "patterns",
            "blue (color)",
            "red (color)",
            "orange (color)",
            "yellow (color)"
        ],
        "material_id": "TM-2407",
        "alt_material_ids": [
            "TM-3124"
        ],
        "material_ids": [
            "TM-2407",
            "TM-3124"
        ],
        "material_titles": [
            "acrylic paint",
            "canvas"
        ],
        "technique_id": "TM-3891",
        "alt_technique_ids": [],
        "technique_ids": [
            "TM-3891"
        ],
        "technique_titles": [
            "painting (image making)"
        ],
        "theme_titles": [
            "African American artists",
            "Women artists",
            "African Diaspora"
        ],
        "image_id": "e966799b-97ee-1cc6-bd2f-a94b4b8bb8f9",
        "alt_image_ids": [],
        "document_ids": [
            "0779b4bd-296f-671f-215e-129f2101ad07"
        ],
        "sound_ids": [],
        "video_ids": [],
        "text_ids": [
            "0779b4bd-296f-671f-215e-129f2101ad07"
        ],
        "section_ids": [],
        "section_titles": [],
        "site_ids": [],
        "suggest_autocomplete_boosted": "Starry Night and the Astronauts",
        "suggest_autocomplete_all": [
            {
                "input": [
                    "1994.36"
                ],
                "contexts": {
                    "groupings": [
                        "accession"
                    ]
                }
            },
            {
                "input": [
                    "Starry Night and the Astronauts"
                ],
                "weight": 35074,
                "contexts": {
                    "groupings": [
                        "title"
                    ]
                }
            }
        ],
        "source_updated_at": "2023-04-05T18:07:55-05:00",
        "updated_at": "2023-11-08T23:26:20-06:00",
        "timestamp": "2023-11-09T13:32:28-06:00"
    },
    "info": {
        "license_text": "The `description` field in this response is licensed under a Creative Commons Attribution 4.0 Generic License (CC-By) and the Terms and Conditions of artic.edu. All other data in this response is licensed under a Creative Commons Zero (CC0) 1.0 designation and the Terms and Conditions of artic.edu.",
        "license_links": [
            "https://creativecommons.org/publicdomain/zero/1.0/",
            "https://www.artic.edu/terms"
        ],
        "version": "1.9"
    },
    "config": {
        "iiif_url": "https://www.artic.edu/iiif/2",
        "website_url": "http://www.artic.edu"
    }
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK. I recieved this because a status of 200 lets you know that it was a successful request

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: 3077

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes the name of the artwork, the artist, an id, the dimensions, a link to the image, and a description to let you know exactly what it is you are seeing.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that is a text add-on that can send pictures of the artwork. I could also see it in a game that needs pictures on a wall, or maybe a virtual gallery. 

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was really helpful. It explained what the API does, what APIs are in general, and even shared some best practices. There was a lot of information available, making it easy for anyone to understand, even if they're not a technical expert.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation relatively easy to maneuver, however there is a lot of information it might be a tad bit overwhelming.

- Did the quality of the documentation impact your decision to use it?

> Yes because it was clean, it had a lot of information, and it literally shows an endpoint at the top of the page.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up switching a couple of times because some docs didnt really work, or some were vague and bare.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is basically a way to test that a url endpoint works and you can see what happens as you request. You can request different HTTP methods to interact with the server. The server then processes the request and sends back a response. 

- In your own words, describe what an API is.

> An API is essentially a bridge between servers and applications enabling them to communicate and interact. You access them by using specific functions and as a result you have access to data provided by the API 

- In your own words, describe the purpose of Postman.

> Postman is an application that allows you to test your APIs making it a valuable tool for developers working on API-related projects.
