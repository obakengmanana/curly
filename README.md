# curly-invention
Matogen Digital Full Stack Dev Assessment

# Hello!
Thank you for agreeing to complete our full stack dev assessment. We want to get a sense of your experience and capabilities, and see how they match up with some of the work we do.  the assessment includes the following: 
* Set up a copy of WordPress on your local machine
* Create a custom post type, add custom fields, and display these in a loop on a home page.
* Call a 3rd party API.
* Style your pages using Bootstrap 5.
* Deploy your site as a static site.
* Commit and push your code to this repo

# What you'll find in this repo
The repo includes all the files you need to set up a WordPress site, excluding wp-config.php. We use Understrap as the starting point for many of our projects. It gives us enough flexibility to build awesome stuff from scratch, but comes with some useful tools to make developing a bit easier. Full documentation for Understrap is available [here](https://docs.understrap.com/#/)

# Design
Use the design on [this XD file](https://xd.adobe.com/view/7c0dd0d6-9441-4609-6d0f-2ec8efae8057-0a3c/) as a reference for your site. 
* Pages 1 and 2 show the home page of the blog, with hover interaction on one of the posts.
* Page 3 displays one of the blog posts
* Page 4 is the contact page (please ignore for the purposes of this assessment)

# The brief
## Set up a copy of WordPress
* Start up a new instance of WordPress on your computer using your preferred tool. We use [Local by Flywheel](https://localwp.com/).
* Download this repo onto your computer, and copy the files over to your WordPress instance. Make sure to copy your hidden git files too so that you can push back into this repo at a later stage.
* Install Understrap and Understrap Child.
* Follow the instructions to install required NPM packages in Understrap Child, and check the commands that are required to watch for CSS and JS changes.
* Update .gitignore to exclude all image uploads and other unneeded files from the repo.
* Activate the Advanced Custom Fields plugin, and use this licence key to enable all features: b3JkZXJfaWQ9MTU2NDcxfHR5cGU9cGVyc29uYWx8ZGF0ZT0yMDE5LTAzLTI3IDA5OjAxOjA1

## Create a custom post type and add custom fields
* In WordPress we'd normally use Posts to display blog posts. For the purposes of this assessment, please create a new custom post type titled Blog Posts
* Using Advanced Custom Fields, add fields to the Blog Posts custom post type for the following:
  * Intro copy
  * [Flexible content field](https://www.advancedcustomfields.com/resources/flexible-content/) that includes Heading, Body and Image fields. The content editor should be able to add any number of these fields to their post to display their content.
* Use categories to label blog posts according to country.
* Add a custom field to the blog post category to display a unique image per country.
* Use the [Local JSON functionality](https://www.advancedcustomfields.com/resources/local-json/) in Advanced Custom Fields to add your custom fields directly to the repo.

## Display blog posts in a loop on the home page
* Use WP_Query to display blog posts in a loop on the home page.

## Call a 3rd party API
* This is not on the design. Please call a 3rd party API to display today's weather in the footer.

## Style your pages using Bootstrap 5
* The Understrap theme includes Bootstrap, and Bootstrap 5 is selected by default.
* Use Bootstrap styles throughout to limit the amount of custom CSS required.
* Set Bootstrap variables for fonts and colours.

## Deploy your site as a static site
* There are a couple of ways to deploy a WordPress site as a static site, including through CloudFlare, or using a static site generator such as Gatsby.

## Commit your code
* Once you're done, please commit and push your code to a branch named 'dev' in this repo.
* Schedule a code review session with me using [this link](https://calendar.app.google/Y4FePNYVv9A43WyHA).
* I'll pull your changes and have a chance to review what you've done before we chat.

# Final notes
* If you have any questions or you get stuck, it happens! Please don't waste hours of your life trying to figure out why npm install fails :) Please reach out to Ian: ian@digital.matogen.com or 0741967229.
* Please use ChatGPT or Github CoPilot to speed up your work. Just be sure you can explain to me how everything works.
