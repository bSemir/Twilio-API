# Example Application - Complimentr

This application is meant to be used with the [ 🎥 Introduction to APIs course](https://github.com/craigsdennis/intro-to-apis-course) as a part of two week online training for paid internship at **Tech387**.
#
You'll need to make your own Twilio account and their phone number if you want to test this out.
#
It's kind of RESTful:
- Client-Server Architecture (Vue.js app is a client and every client could connect and use it, Node.js is a Server)
- Stateless (we aren't requeiring any prior knowledge about a client)
- Layered System (our API calls another API, client doesn't know that)
- Cacheability (not really but we could pay attention to those headers)
- Uniform Design (no bc we failed at the 1st subcategory of it - it has 4)
- Code On Demand (this is optional and it means that our API returns some code to the client that is runable)

#
Live: https://humane-hyper-accordion.glitch.me

## Use this on Glitch

[Remix on Glitch](https://glitch.com/edit/#!/import/git?url=https://github.com/craigsdennis/intro-to-apis-node)

⚠️ Several students have reported that cloning erroneously sets up a default Glitch application. If this happens to you, in the Glitch app that is created choose **Tools** >> **Extras** >> **Git Import and Export** >> **Import from GitHub** when prompted enter  `craigsdennis/intro-to-apis-node`


## Local Installation

Copy `.env.example` to `.env` and update it with your [Twilio](https://twilio.com) credentials.

## Running the application

* `npm install`
* `npm start`

### In Development mode

* Run [ngrok](https://ngrok.com/) on port 3000
* Visit your ngrok url!
