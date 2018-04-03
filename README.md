# Feed Reader Testing

To get started, open `index.html` in your preferred browser and check the result of the tests in the footer.

## Tests description

The `RSS Feeds` test suite check if the variable all feeds is defined and all names and urls exists.

`The menu` test suite checks if its visibility works well. 

The tests `Initial Entries` and `New Feed Selection` checks if feeds are loaded correctly. Because this method is asynchronous, I created an object called `Feed` and moved the method `loadFeed` to this object, than I could use the method `done` to make  test wait the execution to check expectations.