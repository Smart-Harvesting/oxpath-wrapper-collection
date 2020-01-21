# Oxford Academic Wrappers

## oxford-academic-loi-as.oxp

This wrapper does not extract any data, but demonstrates how the advanced search can be used to find articles from a specific volume of a journal.
The wrapper clicks on the "Advanced Search" Link, then fills in the "Volume" form field followed by a click on the button to update the search.
Then, the first title on the result list is clicked to get to its detail page.

In a real world example, you would add a loop to click on all the titles in the result list. Then you would add extraction markers to extract data from the detail page of each.
