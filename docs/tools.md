# Useful Tools

To optimize your development efforts while working with Saxo's OpenAPI, our team recommends the below tools which range from 'get to know the platform'-apps to fully-fledged debugging environments. You are invited to use these tools as you progress through the articles on this website, as they provide an excellent way to try the features of the OpenAPI yourself.

## Tools Provided by Saxo

### [The Developer Portal](https://developer.saxo)

This is the go-to resource if you are starting out on the OpenAPI. [Create a developer account](https://www.developer.saxo/accounts/sim/signup) on the portal to fully leverage the features it provides (see below). This account lives in Saxo's Simulation (or 'Demo') environment and is pre-configured to be used as OpenAPI user. You can log into [SaxoTraderGO](https://www.saxotrader.com/sim/login/) or [SaxoTraderPRO](https://www.home.saxo/platforms/saxotraderpro) with this account and we generally recommend checking these platforms out if you haven't seen them already - they are both entirely build on top of the OpenAPI infrastructure!

![The Developer Portal](img/devportal1.png){: style="height:350px;width:auto"}

!!! info
    The below tools require a developer account on the Developer Portal.

### [The Tutorial](https://www.developer.saxo/openapi/tutorial)

The Tutorial is a simple 3-minute click-through guide on the Developer Portal that showcases a couple of basic API request/response examples. It provides an excellent introduction into the many aspects of the OpenAPI and is generally recommended as a good 'get to know us'-tool.

![The Tutorial](img/devportal2.png){: style="height:350px;width:auto"}

### [The OpenAPI Explorer](https://www.developer.saxo/openapi/explorer)

Now that you have acquired a basic understanding of the OpenAPI, let's build some requests ourselves! The Explorer is very similar to tools such as Postman (see below) and lets you create your own requests directly on the portal. It is convenient for on-the-fly debugging and trying out certain endpoints to 'get a feel' for how they behave before implementing them into your own application.

![The OpenAPI Explorer](img/devportal3.png){: style="height:350px;width:auto"}

### [24-Hour Tokens](https://www.developer.saxo/openapi/token)

At this point, you probably want to start calling the OpenAPI from within your own application/environment. To make this easy, Saxo provides 24-hour tokens which you can hard-code into the sample you are building (practically skipping the authentication step altogether). Accept the disclaimer on the portal and get started with requests right away!

### [Application Management](https://www.developer.saxo/openapi/appmanagement)

You can register an application in Saxo's SIM environment on the above link and obtain your own `AppKey` and `AppSecret`, which can be used to request access and refresh tokens through [Saxo's standard OAuth implementation].

![Application Management](img/devportal4.png){: style="height:350px;width:auto"}

## Third-Party Tools

The below apps can be used for free and are generally considered exceptional Web/API debugging tools. Saxo is not affiliated with any of these platforms.

### [Postman](https://www.getpostman.com/)

### [Fiddler](https://www.telerik.com/fiddler)