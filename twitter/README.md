# Twitter Wrappers

## twittersearch.oxp

This wrapper demonstrates how to perform a search on Twitter and extract the text of the resulting tweets.
Since twitter only loads more results on demand (see below), only the initially visible result tweets are extracted.

## twitter-load-more.oxp

This wraper demonstrates how to get more results if the web page lazily loads more results while the user scrolls through the result list.
The wrapper makes use of a mouse over command to simulate the scrolling by hovering over the bottom of the page.
In this example, the scrolling is limited to 4 iterations.
