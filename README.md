# Udacity Project: Feed Reader Testing

### Description 

In this project i have used Jasmine to write tests for a given web-based application that reads RSS feeds.

1. Consturcted tests that loops through each feed in the `allFeeds` object and ensures it has a URL and name are defined, and that the URL's and names are not empty.

2. Constructed a test suite named `"The menu"`

- Ensures the menu element is hidden by default.

- Ensures the menu changes visibility when the menu icon is clicked.

3. Constructed a test suite named `"Initial Entries"`

- Ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

4. Consturcted a test suite named "New Feed Selection"

- Ensures when a new feed is loaded by the loadFeed function that the content actually changes.

### How to run

- Download repository to your computer. 
- Open file `index.html` in browser. 
- The test results will be displayed at the bottom of the page. 
- The spec file is in `./jasmine/spec/feedreader.js`

- Alternatively, you can view the site on github pages by using the link: 


### References

References used in this project: 

- Udacity forums
- Udacity Slack channels for FEND 
- [Trigger function on youtube](https://www.youtube.com/watch?v=0-WJHDXqQxA) (For understanding the trigger)
- [Jquery](http://api.jquery.com)
- [Dev Mozilla](https://developer.mozilla.org/en-US/)
- [Stackoverflow](https://stackoverflow.com/)
- [w3schools](https://www.w3schools.com/)  
