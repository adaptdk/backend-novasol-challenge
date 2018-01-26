# Task for back end developers for NOVASOL

As a user I want to see list of properties in a page that are available so I can know what properties could be booked.

Acceptance criteria:
1. Organize code as Drupal 8 module
2. Use Drupal's DIC, Guzzle, PHPUnit
3. Properties should be fetched from API mock (response.json), serialized to entity (pure PHP class, not Drupal entity)
4. Creat Controller to show properties list
5. Listing should have pagination to see other properties.
(Parameters: ‘count’ - the number of rentals which are to be returned; ‘offset’ - the offset at which rentals in the results are to be returned from.)
6. There should be templates for page, list, single property item.
7. List should be filtered by ‘from’ - ‘to’ dates.
(Date format accepted by API - Ymd. Both ‘from’ and ‘to’ parameter values are required)
8. Parts which should be covered with test: page rendering, serialization, pagination and filtering.


***
Send applications to karolis.linkevicius@adapt.dk
