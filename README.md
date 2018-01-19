# Task for back end developers for NOVASOL

As a user I want to see list of properties in a page that are available so I can know what properties could be booked.

Acceptance criteria:
1. Available properties must be fetched from API using GET request.
(Response example is attached because API is not publicly accessible)
2. Page should list 10 properties 
3. Listing should have pagination to see other properties.
(Parameters: ‘count’ - the number of rentals which are to be returned; ‘offset’ - the offset at which rentals in the results are to be returned from.)
4. Page and property list should be themeable.
5. List should be filtered by ‘from’ - ‘to’ dates.
(Date format accepted by API - Ymd. Both ‘from’ and ‘to’ parameter values are required)
