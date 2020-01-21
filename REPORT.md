# OAuth Comparative Analysis

## OAuth LinkedIn

### Research Conducted By: Trevor, Conor, David

### Overall Score and Comments
#### Score (Out of 10): 10
#### General Comments

The LinkedIn API uses OAuth 2.0 for user authorization and API authentication. Applications must be authorized and authenticated before they can fetch data from LinkedIn or get access to member data. LinkedIn offers two different ways to authorize an application, one allows the API to grab LinkedIn member information and the other allows basic login access through LinkedIn. The usability is very vast as many third party applications allow the use of LinkedIn. The documentation defines clear guidance when it comes to getting the application up and running with the LinkedIn OAuth.

#### Pros
* Straight forward documentation.
* Has a clear cut path towards registering their application.
* Clearly walks through the steps that the API server and application go through.

#### Cons
* There's two different authorization routes that may cause confusion.
* Having to register your application before being granted access.

### Ratings and Reviews
#### Documentation
Thoughts go here

#### Systems Requirements
The requirements for the access to the LinkedIn OAuth is that you register your application through `https://www.linkedin.com/developers/apps/new`. Upon registering your application, the client must have a unique identifier (`state`) that is granted by LinkedIn. You must pass the authorization route `scope`, `redirect_uri`, `response_type` and `code`. LinkedIn OAuth is able to be used in both AWS and Heroku. It does not require a certain database.

#### Ramp-Up Projections
It shouldn't take mid-junior developers long to become productive using LinkedIn's OAuth. The documentation is very similar to other popular OAuth applications such as Github. The documentation also outlines the five step very precisely to allow a client to follow the steps to allow their application to access the OAuth.

#### Community Support and Adoption levels
OAuth is very popular within the JS community. It is widely used in mobile, web and cloud applications to allow users to log in using third-party applications instead of creating an account. Within the JS community, it is seen as a very popular based on user experience so the user isn't limited to just creating an account for the specific application. Major companies such as Google, Facebook and Microsoft use their own internal databases to log in throughout their web of applications. Smaller companies will use OAuth to allow users to log in through these larger services.

### Links and Resources
* [docs](https://docs.microsoft.com/en-us/linkedin/shared/authentication/authorization-code-flow?context=linkedin/context)
* [examples/tutorials](https://requests-oauthlib.readthedocs.io/en/latest/examples/linkedin.html)

### Code Demos
* [live/running application](http://xyz.com)
* [code repository](http://xyz.com)

### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
* `npm start`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.