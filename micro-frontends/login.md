##  Login/Register Microfrontend

### Responsability 
Responsible for handling user authentication and registration processes.

### Why it should be a microfrontend
- Focuses only on authentication and registration, therefore its simple and easily maintained.
- Its single responsability is managing user authentication and registration, which ensures a clear separation of concerns.
- It is reusable. This login and registration can be easily used across different aplications.

- Can be deployed independently of other microfrontends, allowing for updates and changes without affecting other parts of the application.

- A dedicated team can manage this microfrontend, making it easier to iterate and make improvements without dependencies on other teams.
-  It provides a vertical service layer focused solely on user authentication and registration.

- Can be customized and adapted to different authentication methods or requirements without impacting other parts of the application.

### Suggestions of improvement
Adding support for authentication that uses biometric data such as FaceId or fingerprint.
