# Amazon Wrappers

## amazon.oxp

This wrapper is used to extract title, URL, rating and URL to all ratings of movies listed on Amazon.

**Goal:** extract from all movies listed on amazon:
*   title
*   url (to details page)
*   rating (out of 5)
*   ratingurl (to page of detailed ratings)

**Peculiarities:** 

**Note:** Currently restricted to 10 pages of the result list b/c the actual number of results is quite high

## amazon2.oxp

This wrapper is used to extract data from all customer ratings of a specific product from Amazon.

**Goal:** extract from the customer ratings page of an amazon product:
*   rating (out of 5)
*   title (of the review)
*   text (of the review)

**Peculiarities:**

**Note:** This is meant to be used with the urls extracted with the help of `amazon.oxp`.


