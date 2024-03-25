## Destaques Microfrontend

### Responsibility 
- Allows a user to see the trending meat products at the moment.

### Why it should be a microfrontend
- This microfrontend focuses only on loading and displaying to the user the currently trending meat products, therefore serving only one purpose.

- Its standalone nature allows for independent scaling, which is critical for performance optimization, especially if these products change frequently and receive a high volume of views.

- Can easily be updated or modified to include new types of products or trends without the need to redeploy the entire application, ensuring a smooth and continuous user experience.

- It encapsulates all the functionality related to showcasing featured products, which includes fetching data, rendering items, and handling user interactions like clicking on a product to see more details.

- A dedicated team can focus on improving the algorithms for determining what products are trending, and how they are displayed, without being bottlenecked by other development cycles in the application.

- Is reusable in different contexts within the application where a list of featured or recommended items is needed, such as in personalized user dashboards or promotional pages.


