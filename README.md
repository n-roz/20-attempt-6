# Getting Started with Create React App

## Description

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

[View my unsuccessful deployment here.](https://n-roz.github.io/attempt-6-on-20/)

I actually started to like this project! I learned a lot. My portfolio is unfinished (I cannot get it to deploy on GH Pages and no styling). I am submitting this in the hope of getting some partial credit. I will be styling this later to use as my portfolio for job searching.

This is a new repo I created while trying to deploy. [My old repo is here.](https://github.com/n-roz/20-lizard-blizzard)

See my ```heroku logs --tail``` below for an insight into my deployment errors.

![Alt text](src/assets/herokulogs.png "heroku logs --tail")

## User Story 
```
AS AN employer looking for candidates with experience building single-page applications
I WANT to view a potential employee's deployed React portfolio of work samples
SO THAT I can assess whether they're a good candidate for an open position
```

## Acceptance Criteria
```
GIVEN a single-page application portfolio for a web developer
WHEN I load the portfolio
THEN I am presented with a page containing a header, a section for content, and a footer
WHEN I view the header
THEN I am presented with the developer's name and navigation with titles corresponding to different sections of the portfolio
WHEN I view the navigation titles
THEN I am presented with the titles About Me, Portfolio, Contact, and Resume, and the title corresponding to the current section is highlighted
WHEN I click on a navigation title
THEN I am presented with the corresponding section below the navigation without the page reloading and that title is highlighted
WHEN I load the portfolio the first time
THEN the About Me title and section are selected by default
WHEN I am presented with the About Me section
THEN I see a recent photo or avatar of the developer and a short bio about them
WHEN I am presented with the Portfolio section
THEN I see titled images of six of the developer’s applications with links to both the deployed applications and the corresponding GitHub repository
WHEN I am presented with the Contact section
THEN I see a contact form with fields for a name, an email address, and a message
WHEN I move my cursor out of one of the form fields without entering text
THEN I receive a notification that this field is required
WHEN I enter text into the email address field
THEN I receive a notification if I have entered an invalid email address
WHEN I am presented with the Resume section
THEN I see a link to a downloadable resume and a list of the developer’s proficiencies
WHEN I view the footer
THEN I am presented with text or icon links to the developer’s GitHub
```

## Mock Up

![Alt text](src/assets/homepage.png "Homepage")

![Alt text](src/assets/portfolio.png "Portfolio")

![Alt text](src/assets/contactme.png "Contact Me")

![Alt text](src/assets/resume.png "Resume")

![Alt text](src/assets/ghpages.png "GH Pages")

## Grading Requirements
```
Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following:
Yes - Application must use React to render content.
Yes - Application has a single Header component that appears on multiple pages, with a Navigation component within it that’s used to conditionally render About Me, Portfolio, Contact, and Resume sections.
Yes - Application has a single Project component that’s used multiple times in the Portfolio section.
Yes - Application has a single Footer component that appears on multiple pages.
It's deployed with errors but technically yes - Application must be deployed to GitHub Pages.

Deployment: 32%
Maybe if you are a very generous person - Application deployed at live URL.
No - Application loads with no errors.
Yes? - Application GitHub URL submitted.
Yes - GitHub repository contains application code.

Application Quality: 15%
Yes - User experience is intuitive and easy to navigate.
Probably not - User interface style is clean and polished.
Technically yes - Application uses a color scheme other than the default Bootstrap color palette.

Repository Quality: 13%
Yes - Repository has a unique name.
Yes - Repository follows best practices for file structure and naming conventions.
Yes - Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
Yes - Repository contains multiple descriptive commit messages.
Yes - Repository contains high-quality README file with description, screenshot, and link to deployed application.
```      

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`