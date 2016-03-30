# Udacity Front-End Nanodegree P7 - Feed Reader Testing

This project is an RSS Feed Reader. It demonstrates the usage of testing software.

## Running this project

In order to run this project, open the "index.html" file in a web browser. The test suites are displayed at the bottom of the page.

## Test process

This project uses [Jasmine](http://jasmine.github.io/) to do testing. The included test suites are:
- RSS feed
	- checks if there is an RSS feed object
	- checks if all URLs are valid
	- checks if all feed names are valid
- Menu
	- checks if the menu is hidden when page is loaded
	- checks if clicking the menu button toggles the menu
- Initial feed loading
	- checks if any entries are actually loaded onto the page
	- checks if href are loaded into links correctly
- Feed reloading
	- checks if new feed entries are loaded when a different feed is selected.

## Future Todo:

Further tests have been created for future features:
- User input feed
	- checks if new feed can be added to feed array
	- checks if new feed can be loaded
- Error checking
	- checks if application shows error to user when feed can't be loaded