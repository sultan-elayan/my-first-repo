# Application State with Redux

## What are the advantages of storing tokens in “Cookies” vs “Local Storage”

 #### Local Storage
##### Pros: It's convenient.

> - It's pure JavaScript and it's convenient. If you don't have a back-end and you're relying on a third-party API, you can't always ask them to set a specific cookie for your site.
> - Works with APIs that require you to put your access token in the header like this: Authorization Bearer ${access_token}.

#### Cookies
##### Pros: The cookie is not accessible via JavaScript; hence, it is not as vulnerable to XSS attacks as localStorage.

> - If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
> - It's automatically sent in every HTTP request to your server.



## Explain 3rd party cookies.

>  Third-party cookies are set by a third-party server (ad-tech) via a code placed on the web domain by the owner of that domain. ... Third-party cookies allow advertisers to track users across the internet (cross-site) and target advertising wherever that user goes.


## How do pixel tags work?

> A tracking pixel, also known as a marketing pixel, is a 1×1 pixel graphic used to track user behavior, site conversions, web traffic, and other metrics similar to a cookie. The tiny pixel-sided image is usually hidden and embedded in everything from banner ads to emails


<hr>

- cookies : Cookies are files created by websites you visit. They make your online experience easier by saving browsing information. With cookies, sites can keep you signed in, remember your site preferences, and give you locally relevant content. ... First-party cookies are created by the site you visit

- authorization : Authorization - Where someone is given privileges within the application to access particular functions like admin, work, accounting, etc. Authentication mechanisms can be generic because they do not need to know anything about what happens inside the application. They just allow or disallow access to the application

- access control : Access control is a fundamental component of data security that dictates who's allowed to access and use company information and resources. Through authentication and authorization, access control policies make sure users are who they say they are and that they have appropriate access to company data.

- conditional rendering : Conditional rendering is a term to describe the ability to render different user interface (UI) markup if a condition is true or false. In React, it allows us to render different elements or components based on a condition. This concept is applied often in the following scenarios: Rendering external data from an API.

<hr>


## what is redux 

> A Predictable State Container for JS Apps

![](https://miro.medium.com/max/1400/0*95tBOgxEPQAVq9YO.png)

> Redux is a predictable state container designed to help you write JavaScript apps that behave consistently across client, server, and native environments and are easy to test. While it's mostly used as a state management tool with React, you can use it with any other JavaScript framework or library.

![](https://programmer.group/images/article/8c99fd4602732259516531854e185323.jpg)

> Redux can be used as a data store for any UI layer. The most common usage is with React and React Native, but there are bindings available for Angular, Angular 2, Vue, Mithril, and more. Redux simply provides a subscription mechanism which can be used by any other code.
