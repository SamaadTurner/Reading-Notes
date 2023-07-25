# Local Storage And How To Use It On Websites  
-Storing information locally on a user’s computer is a powerful strategy for a developer who is creating something for the Web.  
-Local storage has a state unlike HTTP.  
-During development, you might sometimes get stuck and wonder what is going on. Of course, you can always access the data using the right methods, but sometimes you just want to clear the plate. In Opera, you can do this by going to Preferences → Advanced → Storage, where you will see which domains have local data and how much.  
- Local storage is good but it does come with some dangers.
## Questions:  
1.Why would a developer use local storage for a web application?  
-A developer would use local storage for a web application to store data locally on the user's device, allowing the application to persist data across sessions and provide a smoother user experience. It can also reduce server load by offloading some data handling tasks to the client-side.  
2.What information should not be stored in local storage?  
-Sensitive information such as passwords, authentication tokens, and personally identifiable information (PII) should not be stored in local storage.  
3.Local storage can store what type of data? How would you convert it to that type before storing?  
-
Local storage can store data in the form of strings. To store other data types such as objects or arrays, they need to be converted to strings using methods like JSON.stringify() before storing in local storage. Upon retrieval, the data can be converted back to its original data type using JSON.parse().  
## Things I want to know more about:  
How will we incorporate local storage in our work?


