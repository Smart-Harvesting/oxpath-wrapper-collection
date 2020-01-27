# StarTrekIndex Wrappers

The wrappers for the German website https://www.startrek-index.de are used to extract data on episodes of the television series "Star Trek".
The site makes heavy use of tables and the wrapper uses this structure to find the links to individual episodes in the respective column of the table.
The detail pages of episodes contain the episode title (both German and English), a detailed description of the plot, and also a detailed rating of the episode, which are all extracted.

## startrekindex.oxp

This wrapper extracts data for a specific series, namely "Star Trek (The Original Series)".
Starting from the table with the episodes, it looks up all the links to the detail pages and clicks them in succession (going back to the table after visiting a detail page each time).

## dsi.oxt

Template wrapper to extract data from several different Star Trek Series. Use a variable file to specify the url like so:

```
url=http://www.startrek-index.de/tv/ent/
```

In contrast to `startrekindex.oxp`, this wrapper makes use of the 'next' links on the episodes' detail pages, i.e. starting from the table, it only clicks on the first eposide and from there, it follows the "next" link to the next episode until there is none. 
Thus, there is no need to navigate back and forth in the browser.
