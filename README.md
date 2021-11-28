# My Application

Considering this is not a real world aplication, I chose to build the home page in plain html+css+js and the cart as a ssmall reactjs app.
I used the environment that was proposed in the test. In the /src folder you can find an html document for the home page and another for the cart and in /scripts is a general script (app.js), and in the /react-app folder are the react files.

# Dependancies
> node ^10.15.3

> grunt-cli ```npm install -g grunt-cli```

# Get Started

- Fork this repo
- Clone your repo

## Install dependancies
```
npm i
``` 

## Build the app
```
grunt
```

## Start application and server
```
node server.js
```

## Creative assets  
Look in ```./design-assets```

### Fonts
All free to download or include from [https://fonts.google.com/specimen/Libre+Franklin](https://fonts.google.com/specimen/Libre+Franklin) (Regular and ExtraLight)

## Which Browsers/Devices or Virtualisation services did you check the application in?
- Mozilla Firefox developer (90.0b6) / Mac computer
- Chrome (96.0.4664.55) / Mac computer


## Anything you want to tell us?
- Assumptions?
I treated this as an exercise, so some desitions are based on showing different approaches and some are made to build in a simpler and quicker way. 
- Decisions?
I put extra focus on the user experience and clean code. 
The cart app is very simple in how it works. If it would be a real project, the ways APIs are called would be from a class in a separate file and folder and probably the whole project would be a Reactjs app. I would have used a state management tool like "Redux" to manage the states of the items in the cart through all pages and to show also how much items are in the cart on the menu, above the cart icon, in all pages.
If I had more time for the project I would have done a toggle and management of "dark/light" modus of the page (the css variables are defined in this way and there is some commented code for the dark mode), I also would have worked on some small animations/transitions in the cart app when for example a whole row is deleted, so that it has a transition or fade out and I would have worked more on the experience when the user selects the "Buy now" button and what happens after that.
- What you used to develop and test?
I used the proposed environment with grunt and express. I have not so much experience doing testing, so I decided to focus more on my strengths.
- Libraries used and why?
I used scrollreveal for the scroll effect and swiperjs for the carousel. I used both libraries because they are simple to implement, open source, lightweight and don´t have any extra features I don´t need for this project. I also used react for the cart page, since it is a good way to manage reactive apps and state based functionalities.
- How long you spent?
I used about 18-20 hours. 


## What did you think of this test/exercise?
### What did you like?
1. The clarity of the tasks and posibilities.
2. The freedom of approach you could take.
