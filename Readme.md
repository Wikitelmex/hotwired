# Hotwired oriented to Rails
Technology to build modern web applications, without using a lot of javascript, in Rails 7 is included automatically, you just need to setup certain thing to use it. Hotwired is divided in 3 main technologies, called: Stimulus, Turbo, Strada. In this tutorial, we'll just focus on Stimulus and turbo.

## Stimulus
Is a Javascript little Framework, to handle code with traditional javascript, but not for handle all the entire front-end, just concerned about certain behavior in event of the components.

In the next link, you can go to the Stimulus tutorial.
[Stimulus Tutorial]()

## Turbo

Turbo bundles several techniques for creating fast, modern, progressively enhanced web applications without using much JavaScript. It offers a simpler alternative to the prevailing client-side frameworks which put all the logic in the front-end and confine the server side of your app to being little more than a JSON API.

With Turbo, you let the server deliver HTML directly, which means all the logic for checking permissions, interacting directly with your domain model, and everything else that goes into programming an application can happen more or less exclusively within your favorite programming language. You’re no longer mirroring logic on both sides of a JSON divide. All the logic lives on the server, and the browser deals just with the final HTML.

Turbo is divided in some topics and we'll take car about of:
- Turbo Drive: Is an link router for our SPA.
- Turbo Frames: Fragments of the page(frames) wich are updated instead updating the entire page.
- Turbo Stream: Is a web-socket which stablish comunnication with the back-end, sending HTML code, instead JSON.

In the next link, you can go to the Turbo tutorial.
[Turbo Tutorial]()
