# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

Semantic HTML is using HTML Tags that provide meaning to each element within the website.  Using Semantic HTML you can improve SEO as it "enhances accessibility, searchability, internationalization, and interoperability."  Meaning you will have higher ranking in search engines, and the website will be available to a wider audience.  It provides better structure and improved readability for other developers as well.

(I did actually quote Bruce Lawson here, it explains it very well and I honestly believe that quote would assist many in understanding how Semantic HTML can benefit both the end-user and the developer.  I personally would have used <div> tags for everything, had I not actually read about the importance of Semantic HTML and how beneficial it is to use.)

2. Name two big differences between ```display: block;``` and ```display: inline;```.

(Can I name more than 2?)
Using display: block will display the element.. literally as it says, as a block.  You have whitespace above and below it, and it will not allow you to have any elements next to it unless you order it as such.

When using display: inline you will have your elements displayed as it says.. inline, usually inside of a block element.


3. What are the 4 areas of the box model?

The four areas of the box model are the Margin, Border, Padding, and Content.  In that order specifically.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

The cross axis.  By default, this will be vertical.


5. Explain why git is valuable to a team of developers.

Git is valuable to a team of developers because you not only can keep track of each individual's work, you can go back and revert to old code, you can have multiple people on the same project with their own branch to work on different features and fixes without worrying about interrupting their partner(s)' work or breaking something they are doing because of any issue within your own code, it becomes invaluable when you have two or more developers all working on the same project and let's say one person's code conflicts with another causing something to break. Normally, you might not know what's breaking it because you may not be aware of what they are working on or what they have done and you could end up sitting here going through your code wasting time looking for something that isn't even because of code you wrote.  Each developer will have their own local repository with a history of commits that belong to them.  A new branch can be added, an old one can be closed, the team can still work on their own local repository.  You have the ability to track all the changes within a project and use Pull Requests to merge their branch into another.  And the team scaling capabilities using Git are immense.

(I can honestly go on about this for quite a while, but I'm running short on time to submit my project)

## Just some things I want to add

I did use google for assitance on my answers to some of these questions.  Particularly on the explanation of Semantic HTML and the advantages of Git.  I personally learned more about these things in doing so, and I believe it helped me better understand them as a student and a developer alike.  If for any reason this is not acceptable, I can and will revise my answers.


## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Add your project manager as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 


## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [ ] Build the HTML and CSS to create the missing navigation and header.
* [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [ ] Copy and paste your home page navigation and header into the about page
* [ ] Update the header image with the about page image
* [ ] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing
* [ ] Add responsive breakpoints to your code by using media queries
