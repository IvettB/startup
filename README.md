# Today's To-Do's

## Design

Have you ever been overwhelmed by the amount of tasks and chores you needed to complete? Have you ever postponed getting things done because you didn't know where to begin? Have you ever missed meetings and assignments because you had too much on your mind? If your answer is yes to any of the questions above, Today's To-Do's is designed for YOU. Customize your own to-do lists, set reminders, and feel the accomplishment of checking things off your list one by one. Don't miss out on important things. Don't miss out on life.

## Key features

- Create and delete to-do lists
- Check off or edit tasks individually
- Customize interface
- Set reminders
- Calendar

## Application Sketch

![IMG_8399](https://user-images.githubusercontent.com/77896065/215166367-a3ea46b3-d454-4ec9-ad80-cac76c54df96.jpg)

# What I learned during the Simon-html assignment

The Simon-html assignment was the most tricky and diffciult assignment that I completed in this class so far. I had issues with cloning a repository into another repository. For some reason, they didn't sinc up, so whatever changes I made in my decelopment environment, I couldn't push to GitHub. Eventually with the help of some TAs I was able to figure out the issue. DO NOT clone a repository into another one. Just download the zip and paste the files into one repository. This solves all the issues and everything syncs perfectly. 

Something else I learned was that web development is very tedious. For some reason, I expected that if I make a change in one of the html files, it would show up on the other pages too, as long as what I changed is a shared attribute across all pages. This was not at all the case. You need to go into every file and change everything one by one.

# What I learned during the Simon-CSS assignment

The Simon-CSS assignment was quite tricky and it took me longer than expdcted to complete. Web Programming it not easy, and one small mistake can break the whole website. I also had issues with committing and pushing the changes to my git repository, even though I thought I figured out these issues last time. Eventually, I was able to just create my own files and copy and paste any code into them wirhout cloning the repository from the CS 260 repository.

Bootstrap is very useful, but I am learning that it does have its limitations. Even though I worked many hours on my Simon CSS, I do feel like it doesn't look much different from the original example. This makes it a little boring and not so fun. 

Notes:
- Use "justify-content" to fix dynamic issues: like when the page looks funny in a smaller window
- Don't forget that if you change something on one of the pages, it doesn't change in the other pages

# Reflecting on Startup HTML and CSS

The Startup HTML and CSS assignment was a big milestone and a great learning experience. My main goal was to have fun and push myself to do the best I can and deliver the best possible looking website. Something I have realized during the development process is that at times it is difficult to imagine what the end result will look like. 

Notes:
- Always take it one task at the time
- Remember that your files aren't automatically linked
- When you create deployFiles.sh, you need to modify accessibility in the terminal (Otherwise you can't deploy to your server)
- Git push often! It is a way to double save your work
- If you have difficulties with your development environment, copy everything to CodePen and keep working until help arrives
- Don't worry too much about what isn't required now. JavaScript will make everything better.

# Simon JavaScript

This assignment was much harder than I expected. Initially, I attempted to write JavaScript from scratch, but nothing worked for hours. I didn't realize that it wasn't enough to just make new functions in JavaScript. Everything needs to be referenced in the HTML files as well. This made the assignment from scratch extremely difficult. I ended up cloning the example repo and worked on understanding the code rather than creating everything from scratch. It was overall a great learning experience, but this assignment definitely made me nervous about my startup JavaScript.

# Startup JavaScript

This has been a tremendous task, and it feels great to be done with it. It's interesting to realize that even a simple website takes a long time and quite a lot of practice to make. I had to derail from my original startup application, because as I was creating my website, I realized my plan was way beyong the scope of this class. Instead, I'm creating a simpler, but still fun website. I added some extras and quirks that I found really fun to work on.

Notes:
- It always takes longer than expected
- Save yourself some time and when you start working on an additional project, jut clone your repo and start on a fresh page
- Padding, padding, padding! It makes everything look better and more clean
- When the expected item doesn't change on the interface after you saved and deployed, STOP! You are likely editing the wrong class!
- Don't be sad because your website doesn't look like a million bucks. Keep learning
- Don't use the same class twice in CSS, it messes things up

# Simon Service

The service assignments prove to be rather difficult for me. It is a tideous and long process, and I'm still just wrapping my head around why it is so useful, and why we should use it if we aren't working with a large database. 

Necessary steps:
- Move all files to public 
- Configure directory to work with node.js
- Install express package
- Create entry point file for node.js
- Add Express JS
- Save and deploy to production environment

Notes:
- VS Code acts up sometimes! Fix: Close all projects, and completely reopen and reset settings
- Server issues: Go to AWS website, stop running, and then restart after a minute. Before deploying to production environment, always check if server is up and running
- ALWAYS make sure you're in the right directory before doing anything
- Pulling requests from third party sometimes takes a minute. Be patient before panicking and thinking there are errors

# Simon DB

This assignment has taught me a lot, but also took way longer than expected. The more third party applications we're using, the more complex the code and execution gets, and it takes time learning how everything works together. 

Necessary steps:
- Clone repo 
- (Get familiar with the code, experiment and learn)
- Enter MongoDB credentials into database.js -> tip: just delete all the brackets and copy and paste the url
- Ssh deploy to production environment
- TEST to make sure everything works

Useful git commands:
- pm2 delete simon
- pm2 start index.js -n simon -- 3000
- cd services/simon
- exit
- :wq
- vi
- ctrl + C
- ssh -i ~/Desktop/kakaoscsiga.pem ubuntu@dotoday.click

Notes:
- If the whole simon production is down: need to fix credentials in database.js
- If the scores aren't getting stored correctly or at all: MONDODB DATABASE ISSUE
- Make sure IP address is 0.00.0... -> EVERYONE CAN CONNECT!!!
- Why are my scores stored on local host, but not when deployed? -> YOUR SERVER HAS A DIFFERENT IP ADDRESS THAN LOCAL!

# Simon login

As usual, this assignment also had some hidden features that were somewhat difficult to figure out. Yet it was a great learning expereince and I feel like I'm starting to understand how data is stored and called, and how web applicatons manage unsers and sensitive information. Learning about databases and uniquie keys also makes me more hesitant about wanting to give out so much personal information when registering to certain applications.

Notes:
- "Go Live" will not work anymore from VS code. Do instead: terminal->node index.js then open browser and host there
- If deploy ssh doesn't work, do the following commands in terminal:
- ssh -i  ~/Desktop/kakaoscsiga.pem ubuntu@dotoday.click
- pm2 delete whatever is running and shouldn't
- pm2 start the correct file

# Simon WebSocket

I am finally starting to get a hang of working with third party databases. The WebSocket assignment was very fun, and I had a great time exploring what every function did and how things come together. I never really understood before how private messaging and information happens on the web, and this assignment enlighetend me about the process. I found it interesting that a websocket is technically a "channel," and only pre-specified members can have access to anything going through that channel. It's also fascinating that sending messages through this websocket works in a way that the message is pushed into this "channel," and everyone receives it, except for the sender.

# Startup service

This is where my notes will go after finishing the startup service.

# Simon React

As the semester comes to an end, it's great to reflect on all the things I've learned. I think a lot of things up to this point led up to React. If I had to learn React before getting a proper introduction to JavaScript, it would've been a lot more diffcult to take in. The Simon React assignment was very interesting, and I learned how to implement the same thing in a different, more efficient way. The Simon website looks the same, it functions the same, but the code is brand new, and that's something I really appreciate about web development. There are many ways to find solutions to problems.

Notes:
- Make sure that all packages are properly installed before deploying to your development environment!
- React takes longer than regular JavaScript. Computer is thinking for a lot longer before executing a command
- If errors occur: check your EC2 server, check packages, and take it from there

# Startup React


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
