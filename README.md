# Just Another Text Editor (J.A.T.E)

## Description

My motivation for creating this app was to be able to create a Manifest, service worker, and bundle code to create an offline app

I built this app in order to practice my ability to config webpack files, service files and to actually download and install an app that works offline.

I learned how to navigate and trouble through the types of errors that could come up when working with service workers and webpackaging.

## 

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [Screen Shot](#screenshot)
5. [YouTube Walkthrough Video](#youtube-walkthrough-video)
6. [Installation](#installation)
7. [License](#license)
8. [Technologies Employed](#technologies-employed)
9. [Future Development](#future-development)
10. [Tests](#tests)
11. [Questions](#questions)

## Usage
### User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria 

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Screenshot:
### PWA JATE Screenshot

![](/images/SS01.png)

## YouTube Walkthrough Video
[Click Here to Watch! 7.5 min.](https://youtu.be/SOGFL9JmhA8) 

## Installation
This application is deployed to [Heroku](https://still-beyond-34360-a9426848df90.herokuapp.com/).

To run J.A.T.E locally:

1. Clone or fork this repository
2. Run ```npm i``` to install all dependencies
3. Invoke application with ```npm run start```

## License
This project is licensed under the MIT license.

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.<p/>For more information visit [MIT Licensing](https://choosealicense.com/licenses/mit/).

## Technologies Employed
* Mini-CSS-Extract Plugin
* Webpack+Workbox
* Concurrently
* JavaScript
* IndexedDB
* Express
* NodeJS
* Babel

## Future Development
- Overhaul CSS

## Tests
No tests were run to complete this CMS.

## Questions
[Nate's GitHub](https://github.com/Nweekley84)<br/>


- - -
© 2023 Just Another Text Editor (J.A.T.E): PWA by Nathan Weekley, Confidential and Proprietary. All Rights Reserved.
