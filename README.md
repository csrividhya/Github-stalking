Repo for a web application that uses Github API to pull a user's public repository information. 

Created by Srividhya Chandrasekharan on 07-April-2017.
================

The repo contains an index.html file, it's corresponding CSS file(style.css) and for a quicker loading, the JQuery JS file(jquery.min.js).

The problem of getting user info from Github was solved using Github's APIs dedicated to pull user details and repository details. The JSON properties returned by HTTP requests to these APIs were figured out by doing a curl to appropriate APIs from the command line terminal.
For eg) curl https://api.github.com/users/defunkt (OR)  curl https://api.github.com/users/defunkt/repos

The results got were printed in a structured manner using a division whose content is set based on the details returned by the API's or with an error message in case the username is incorrect. 

I used an inline javascript code using the 'script' tag mainly because it is easier to access the HTML elements. JQuery was used to get JSON response from API. 

Trade-offs I made :- The aesthetic appeal of the web app is not much. I focussed on getting the code working so that the web app does exactly what this challenge was about. If I were to spend additional time, I would definitely experiment with a whole lot of CSS styling to make the web app cool. And also, I'd have several tabs for the user info returned - Repos , Personal , Company etc. 

Here's a link to my up-to-date resume - http://web.cse.ohio-state.edu/~chandrasekharan.12/resume.pdf
