# Econstor Wrappers

## econstor.oxp

Used to extract metadata from a specific journal on EconStor.
Journal: "Theoretical Economics - An open-access journal in economic theory, The Econometric Society"
Clicks on each publication from the result table and extracts metadata (title, authors, year, abstract, type, citation) from the details page.
Uses Kleene star expression to loop through paginated result list.

TODO: fix the wrapper - does not terminate, although 'next' link is not there on last page
