Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of the Inventory Tracking App is to provide users with a simple and reliable way to manage inventory items on a mobile device. The app allows users to create accounts, add, update, and delete inventory items, and track quantities over time using persistent local storage. It was designed to address the need for an easy to use, lightweight inventory solution that does not rely on cloud connectivity and respects user trust by limiting permissions to only what is necessary. 


What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

Key screens included a login/registration screen, an inventory grid view, and add/edit item screens. The UI was designed with clarity and efficiency in mind, using a grid layout and clear text hierarchy so users could quickly understand item information. Each screen focuses only on the actions required at that moment, reducing cognitive load and making navigation intuitive. This simplicity helped ensure the UI remained accessible and easy to learn. 


How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached development in a modular, structured way, separating concerns among UI, data handling, and business logic. Database operations were encapsulated in a helper class to keep persistence logic out of the UI layer. I built core functionality first and expanded features incrementally. These same techniques can be applied in future projects to improve maintainability, scalability, and debugging efficiency. 


How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Testing was conducted continuously throughout development by validating individual features, including login, CRUD operations, and database persistence. I also tested edge cases such as invalid input and permission denials. This process is important because it revealed logical issues early and ensured the app behaved consistently across sessions and emulator configurations. 


Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One major challenge was balancing functionality with user trust, particularly around permissions. I addressed this by designing optional SMS alerts that only request permission when the feature is enabled, ensuring the app remains fully usable even if permission is denied. This approach required careful planning but resulted in a more user friendly experience. 


In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The database and persistence layer were a strong demonstration of my skills. Implementing a local SQLite database to support user accounts and inventory management showed my understanding of data modeling, CRUD operations, and long term data storage. This component ties together usability, reliability, and professional development standards. 
