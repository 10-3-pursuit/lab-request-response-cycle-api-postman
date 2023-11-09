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

> Xeno-canto; https://xeno-canto.org/api/2/recordings

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to get a recording of a wildlife sound. Someone may use the recordings to study wildlife sounds

- What is the URL of the documentation?

> https://xeno-canto.org/explore/api

### Responsex

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://xeno-canto.org/explore/api

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
   {
    "numRecordings": "20683",
    "numSpecies": "846",
    "page": 1,
    "numPages": 42,
    "recordings": [
        {
            "id": "494231",
            "gen": "Saltator",
            "sp": "grandis",
            "ssp": "",
            "group": "birds",
            "en": "Cinnamon-bellied Saltator",
            "rec": "Victor Reyes",
            "cnt": "Mexico",
            "loc": "Atoyac de Álvarez, Guerrero",
            "lat": "17.4199",
            "lng": "-100.1707",
            "alt": "1800",
            "type": "call",
            "sex": "",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/494231",
            "file": "https://xeno-canto.org/494231/download",
            "file-name": "XC494231-Saltator coerulescens et. al.,_01.mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/ffts/XC494231-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/ffts/XC494231-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/ffts/XC494231-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/ffts/XC494231-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/wave/XC494231-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/wave/XC494231-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/HLKLGSWWAE/wave/XC494231-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "1:36",
            "time": "09:30",
            "date": "2019-05-28",
            "uploaded": "2019-08-26",
            "also": [
                "Turdus assimilis"
            ],
            "rmk": "",
            "bird-seen": "no",
            "animal-seen": "no",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "48000"
        },
        {
            "id": "393488",
            "gen": "Euphonia",
            "sp": "godmani",
            "ssp": "",
            "group": "birds",
            "en": "West Mexican Euphonia",
            "rec": "Lauren Harter",
            "cnt": "Mexico",
            "loc": "Cañón Cieneguilla, Alamos, Sonora",
            "lat": "26.9847",
            "lng": "-108.9437",
            "alt": "550",
            "type": "call",
            "sex": "female",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/393488",
            "file": "https://xeno-canto.org/393488/download",
            "file-name": "XC393488-SCEU_Alamos_14Dec2013_Harter_01.mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/ffts/XC393488-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/ffts/XC393488-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/ffts/XC393488-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/ffts/XC393488-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/wave/XC393488-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/wave/XC393488-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/YQNGFTBRRT/wave/XC393488-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "0:17",
            "time": "07:30",
            "date": "2013-12-14",
            "uploaded": "2017-11-18",
            "also": [],
            "rmk": "Came in to whistled imitation of Ferruginous Pygmy-Owl. Not natural intervals. The first two calls, at least, were given by a female, but more than one bird was present.",
            "bird-seen": "yes",
            "animal-seen": "yes",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "48000"
        },
        {
            "id": "302619",
            "gen": "Euphonia",
            "sp": "godmani",
            "ssp": "",
            "group": "birds",
            "en": "West Mexican Euphonia",
            "rec": "David Vander Pluym",
            "cnt": "Mexico",
            "loc": "Cañón Cieneguilla, Alamos, Sonora",
            "lat": "26.9847",
            "lng": "-108.9437",
            "alt": "550",
            "type": "call",
            "sex": "",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/302619",
            "file": "https://xeno-canto.org/302619/download",
            "file-name": "XC302619-SCEU_CCSON_DVP_151220_10.mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302619-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302619-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302619-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302619-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302619-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302619-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302619-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "0:24",
            "time": "08:10",
            "date": "2015-12-20",
            "uploaded": "2016-02-07",
            "also": [
                "Corthylio calendula",
                "Melanerpes uropygialis"
            ],
            "rmk": "90% certain main call is this species. Same flock (~20 individuals in area) but different individuals as XC302615, XC302613, and XC302616 Nice area of Tropical deciduous forest. High pass filter ran and amplified.",
            "bird-seen": "no",
            "animal-seen": "no",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "48000"
        },
        {
            "id": "302616",
            "gen": "Euphonia",
            "sp": "godmani",
            "ssp": "",
            "group": "birds",
            "en": "West Mexican Euphonia",
            "rec": "David Vander Pluym",
            "cnt": "Mexico",
            "loc": "Cañón Cieneguilla, Alamos, Sonora",
            "lat": "26.9847",
            "lng": "-108.9437",
            "alt": "550",
            "type": "call, song",
            "sex": "",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/302616",
            "file": "https://xeno-canto.org/302616/download",
            "file-name": "XC302616-SCEU_CCSON_DVP_151220_09.mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302616-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302616-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302616-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302616-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302616-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302616-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302616-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "0:30",
            "time": "08:10",
            "date": "2015-12-20",
            "uploaded": "2016-02-07",
            "also": [
                "Myiarchus nuttingi",
                "Myiarchus tuberculifer"
            ],
            "rmk": "Same flock (~20 individuals in area) but different individuals as XC302615, XC302613, and XC302619 Nice area of Tropical deciduous forest. High pass filter ran and amplified.",
            "bird-seen": "yes",
            "animal-seen": "yes",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "48000"
        },
        {
            "id": "302615",
            "gen": "Euphonia",
            "sp": "godmani",
            "ssp": "",
            "group": "birds",
            "en": "West Mexican Euphonia",
            "rec": "David Vander Pluym",
            "cnt": "Mexico",
            "loc": "Cañón Cieneguilla, Alamos, Sonora",
            "lat": "26.9847",
            "lng": "-108.9437",
            "alt": "550",
            "type": "call",
            "sex": "",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/302615",
            "file": "https://xeno-canto.org/302615/download",
            "file-name": "XC302615-SCEU_CCSON_DVP_151220_08.mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302615-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302615-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302615-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302615-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302615-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302615-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302615-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "0:01",
            "time": "08:10",
            "date": "2015-12-20",
            "uploaded": "2016-02-07",
            "also": [],
            "rmk": "Cut from a longer track. Same flock (~20 individuals in area) as  XC302616, XC302619, and possibly same individual as XC302613 Nice area of Tropical deciduous forest. High pass filter ran and amplified.",
            "bird-seen": "yes",
            "animal-seen": "yes",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "48000"
        },
        {
            "id": "302613",
            "gen": "Euphonia",
            "sp": "godmani",
            "ssp": "",
            "group": "birds",
            "en": "West Mexican Euphonia",
            "rec": "David Vander Pluym",
            "cnt": "Mexico",
            "loc": "Cañón Cieneguilla, Alamos, Sonora",
            "lat": "26.9847",
            "lng": "-108.9437",
            "alt": "550",
            "type": "call",
            "sex": "",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/302613",
            "file": "https://xeno-canto.org/302613/download",
            "file-name": "XC302613-SCEU_CCSON_DVP_151220_06.mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302613-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302613-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302613-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/ffts/XC302613-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302613-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302613-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/IBYEFBUOWZ/wave/XC302613-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "0:17",
            "time": "08:10",
            "date": "2015-12-20",
            "uploaded": "2016-02-07",
            "also": [
                "Glaucidium brasilianum",
                "Setophaga nigrescens"
            ],
            "rmk": "Same flock (~20 individuals in area) as XC302616, XC302619, and possibly same individual as XC302615. Nice area of Tropical deciduous forest. High pass filter ran and amplified.",
            "bird-seen": "yes",
            "animal-seen": "yes",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "48000"
        },
        {
            "id": "298946",
            "gen": "Euphonia",
            "sp": "godmani",
            "ssp": "",
            "group": "birds",
            "en": "West Mexican Euphonia",
            "rec": "Michael Lester",
            "cnt": "Mexico",
            "loc": "Cañón Cieneguilla, Alamos, Sonora, MX",
            "lat": "26.9847",
            "lng": "-108.9437",
            "alt": "550",
            "type": "call",
            "sex": "",
            "stage": "",
            "method": "field recording",
            "url": "//xeno-canto.org/298946",
            "file": "https://xeno-canto.org/298946/download",
            "file-name": "XC298946-SCEU2.(w NUFL).mp3",
            "sono": {
                "small": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/ffts/XC298946-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/ffts/XC298946-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/ffts/XC298946-large.png",
                "full": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/ffts/XC298946-full.png"
            },
            "osci": {
                "small": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/wave/XC298946-small.png",
                "med": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/wave/XC298946-med.png",
                "large": "//xeno-canto.org/sounds/uploaded/WGNMHUVNUB/wave/XC298946-large.png"
            },
            "lic": "//creativecommons.org/licenses/by-nc-sa/4.0/",
            "q": "no score",
            "length": "0:37",
            "time": "09:00",
            "date": "2015-12-20",
            "uploaded": "2016-01-11",
            "also": [
                "Myiarchus nuttingi"
            ],
            "rmk": "High pass filter (3000Hz, 48dB rolloff). Amplified (35.6dB).",
            "bird-seen": "yes",
            "animal-seen": "yes",
            "playback-used": "no",
            "temp": "",
            "regnr": "",
            "auto": "no",
            "dvc": "",
            "mic": "",
            "smp": "44100"
        },


```

- What status code did you get back from your request? Why did you receive this status code?

> 200. I received this status code because the response successfully sent

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: N/A

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes a description of the animals, the scientific names of the animals, the English names of the animals, the country where the animals are from, the location of the animals, and the recordings of the animal sounds.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that plays animal sounds and shows the region where the animal is from as a string.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was specific in how to use the API, so there was no uncertainty in how to use it. For example, the documentation described that 'There are two possible query parameters for this API' and proceeded to explain how to use those two parameters. The documentation also provided a summary of how a successfull query would look like.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation a bit dense when describing the query parameters and the payload fields of a successfull query. For example, when describing the page parameter, the documentation states "The page parameter is optional and is only needed if the results from a given search don't fit in a single page. If specified, page must be an integer between 1 and results.numPages (see results format below for details)." After reading this am seocnd time, I was able to understand what the documentation was talking about.

- Did the quality of the documentation impact your decision to use it?

> Yes because the documentation was easy to understand even though it was a bit dense. After reading and understanding what input was needed and what output I would expect, I decided to test and use the API

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No, I switched the API I chose initially because the payload was simply an image and there was no JSON file to parse. I stuck with this API after reading some of the documentation and making sense out of it

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is what occurs when a client requests a piece of information from a server. The server responds to the request by sending a response. 

- In your own words, describe what an API is.

> An API is a way to communicate with and gather information from a specific piece of software or hardware, such as a database or a cloud server

- In your own words, describe the purpose of Postman.

> Postman is an application that allows a user to test an API to ensure that the responses are being sent accurately and that information is flowing smoothly from an endpoint.
