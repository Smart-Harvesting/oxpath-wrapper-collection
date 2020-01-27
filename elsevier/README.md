# Elsevier Wrappers

Collection of wrappers used to extract data from Elsevier publications.

## elsevier-book-toc.oxt

TODO:
- what it's used for
- example for url parameter

## elsevier-book-search-by-year-results.oxt

Used to search books from a specific publisher by year.
Use with a variable file to specify the year:

```
year=2017
```

Extracts title, ISBN and URL to details page, which can be used with another wrapper (see below).

## elsevier-book-search-by-year-details.oxt

Using the urls extracted from the `elsevier-book-search-by-year-results.oxt` wrapper (field `<details>`), this wrapper can be used to extract more details on the individual books.
Use a variable file containing the url, e.g.:

```
url=https://www.elsevier.com/books/environment-modeling-based-requirements-engineering-for-software-intensive-systems/jin/978-0-12-801954-2
```
