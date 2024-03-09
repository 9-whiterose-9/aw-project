##  Supermarket Search Microfrontend

### Responsability 

### Why it should be a microfrontend
- This microfrontend focuses solely on providing supermarket search functionality, making it simple and easy to maintain.

-  Its single responsibility is to handle the search for supermarkets and meat products, ensuring clear separation of concerns.

- The supermarket search component can be reused in other applications or pages where similar search functionality is required.

- Can be deployed independently, allowing for updates and changes to the search system without affecting other parts of the application.

- A dedicated team can manage the supermarket search microfrontend, enabling rapid development and improvements.

- Provides a vertical service layer specifically for searching and accessing information about supermarkets and meat products.

### Suggestions of improvement
- Integrate Google location API to allow user to select a supermarket location by putting a pin on a map.
- Add search filters by area, or by a specific type of meat (which may not happen to be available at all supermarkets).
- Add location based recommendations.