# OAuth Comparative Analysis

## OAuth Provider: Amazon 

### Research Conducted By: Andy Fiedler & Jonathon Schwamman

### Overall Score and Comments
#### Score (Out of 10): 7
#### General Comments
See below.

#### Pros
* Excellent Documentation - explained in normal english with code snippets/examples
* Easy to integrate Amazon login buttons into site

#### Cons
* "Implicit Grant" returns the authorization code (access_token) in after a hash in the redirected URI. This means it is unable to pass on the token to our backend server.


### Ratings and Reviews
#### Documentation
Documentation was easily readable/understandable and clearly laid out in step by step instructions. Code snippets are also provided to easily integrate with your project with thorough explanation of what each piece does.

#### Ramp-Up Projections
How long would/should it take a team of mid-junior developers to become productive?  

Although we ran into some issues in our implementation we expect using oauth through Amazon could be implemented within 1-2 days.

#### Community Support and Adoption levels
How popular is this framework? What big companies are running on it? How is it "seen" in the general JS community?  Is there an active community of developers supporting and growing it?  

Amazon is one of the major oauth providers, primarily for ecommerce site since it incorporates access to the amazon wallet. Some major websites using Login With Amazon include Zappos, Woot, MattressFirm, etc.

### Links and Resources
* [Amazon docs](https://developer.amazon.com/docs/login-with-amazon/web-docs.html)

### Code Demos
* [frontend code repository](https://github.com/AndyFiedler-401d4-Advanced-Javascript/www-server)
* [backend code repository](https://github.com/AndyFiedler-401d4-Advanced-Javascript/auth-server)

### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
* `npm start`
* Endpoint: `/oauth/:provider`
  * Authorizes user after being returned from oauth provider with access token

