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

> I Chose to use Icon Horse its url is https://icon.horse/ .

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to get the best looking icons on a website that the user chooses. If there is no icon available, it will never fail because Icon Horse has a default image. While not the best, they display a letter and a background color, so even when a failed website is inputted, there will be no error. This defualt image can even be changed with seting a new defualt.

- What is the URL of the documentation?

> https://icon.horse/usage

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://icon.horse/icon/youtube.com

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.


> [image](assets/youtube%20image.png)
```json

data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAMAAABlApw1AAAAY1BMVEUAAAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/AAD/ICD/EBD/gID/39//UFD/////r6//7+//z8//QED/n5//YGD/v7//MDD/cHD/j48apPPOAAAAEXRSTlMAQICPvyAwYK/P/99w759QENiU5hIAAALlSURBVHgB7NSFkcVADANQ23FICz/9N3vMzLea0WvAbBMRERERERERERERIeHX4taUnxR3/Npsv2lxXyNiy8wdv6nkhSkiVnf/ibwjMgv+T+YW8aVSlrrtGEfLqS72YfNUMKDWT/YRnhhWqYe9Y04MrbwzhcDwtsNedSQItMVesTRQaCtx/tdW8vyBhTx/tMOeOHZQSXui4xbnGTiu0S5RAZ2wB1bwafbADkKr3ZnBaLM7FZTsToKS260GSmE3FnBK3if65JFOIDU/vWHWK24A9xWDVbcrDnC/oRPA/YYCtM4FL0WHdjEEYNcubBwIgiCKHjMN+C9D/lGec/BUSyWNM3i2d5vqyR9g+/nSlwF9IWhaBlIOLgStAaVe4gvBfUsADMkcwFgCBQoATHMo4Ks5AJYcCHgQABjXuEomAcC2mwOg5BjAmwpAvYSsF59kgICi8CAGMBZzAEyzMUBfFB6vgHc1gHGVNkMfcgBsyRwAJZsDqLM5AIZkDmA82uefxAB9UQgGwJnNAYyrOQC2ZA6Aks0B1NkcAEMyBzAe5gCYZnMAnLkD/u6e+18o/CHur9FeyEruzVxvpx0Hmj5SCob6D/e1yndfbN2+WuzLXfv1+pMacOYPHcD9xPSoBoyH+Mhnf2bVHrpnfebMPWrwqgNsKSTsYR+3cQ883btHzuxDf+6xyw/74Kt79PjJPfz94x6//6fuLA4YiGEA5vjCvP+y5b7KXGmB4Fey8v0BvoLCloA8XMPKdBGu0FVES5dBF7qOW+lCtIEr6ZkeBUj0LEOnhzECPU3i4HGYJPC4SqUHkia8kKTwSFg5PAC2rzLgobwOTxUmeCwyTXbuMk05iy+U/bOTtX3KZerff6M25CouAq6fG87ujpwuL+oeisf/1SFSr04exgxdrP3trduo1Xh5jWnMUNVurU3509gNcT9CwX94gsXQI9E+QdQjwexw8knW7cEhAQAAAICg/689YQQAAAAAAOATNL7hl6/fA9cAAAAASUVORK5CYII=
```


- What status code did you get back from your request? Why did you receive this status code?

> I got status 200 ok

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: image/png

> `Content-Length`: 938

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data received include an image file that links to an icon that matches the searched website to the best of it's ability

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...

> If users were adding their favorite websites to a list for a survey, the system could add the icon next to the websites they enter or act as a preview before they enter them.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...

> The documentation has a GUI that allows users to test the most basic function on their site by entering the basic Icon Horse function with the specified website. Later on, it provides more in-depth information for advanced users, detailing many more uses that the Horse Icon has. In this section, it covers possible parameters, the ability to change defaults and their defualts , and provides a brief description of their potential usage in Icon Horse's API.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...
> I have a small complaint about the documentation. I believe that the documentation should include details about the 1000 usages per month, which is part of the free version, as well as information about the larger usage limits in the paid version. Additionally, any other benefits such as no logs or data collected should be highlighted instead of only being on the bottom of the homepage.

- Did the quality of the documentation impact your decision to use it?

> Yes, it was easy to use as a beginner in working with APIs, and it allowed me to gradually explore and implement more advanced features as I delved deeper into my and its capabilities.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes, at the start i used a different API that focused on currency, but its documentation frequently malfunctioned, causing me frustration. The second API I tried was from the Art Institute of Chicago. It had amazing documentation and fantastic features, enabling searches for art related to a subject or direct searches by ID. While it was an amazing API, I found the topic less appealing, and despite its excellent documentation, I wasn't as motivated to use it. I may consider it for a future project. Eventually, I chose a middle ground with Icon Horse, and I'm glad I did. It has a simple yet a well documented API, and I'm satisfied with the learning experience i got from useing it.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...
> The request-response cycle is like an online conversation. When you click a link or open a webpage, your computer sends a request to a server. The server processes your request and sends back the webpage you asked for. It's a simple exchange, you ask, and the server responds, making websites interactive.

- In your own words, describe what an API is.

> An API is ...
> An API is like a helpful waiter in a restaurant. It serves as both a shared language and a set of rules. You (the client) don't need to know how the chef (server) prepares the dish (handles the request). Instead, think of the API as the menu, providing clear guidelines on how to place orders (requests) and what you can expect to get in return. It's a seamless way for different programs to communicate without needing to understand all the behind the scenes details.

- In your own words, describe the purpose of Postman.

> Postman is an application that ...
> Postman is like a recipe book for programmers. It's a tool that helps them experiment with APIs. It lets us easily create requests, see the responses, and organize everything. It's a handy testing area where they can test and refine their API requests before putting them into their app.