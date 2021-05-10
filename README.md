# Authentication & Authorization

- Client Server Communication
  - Authentication & Authorization
- E-Commerce Application
  - Authentication Flow
- Route Parameters
  - history
### Authentication
Authentication is the process of verifying a user's identity.
### Authenticated Credentials:
Username: rahul
password: rahul@2021 
  or 
Username: praneetha
password: praneetha@2021
### Authorization
Authorization is the process of verifying whether the user is authenticated and permitted to perform some actions like accessing resources, etc.

### Example:

After successful authentication, employees are only allowed to access certain resources based on their roles.

Admin can Read, Create, Delete, and Update the Resources
User can only Read and Create the Resources
![image](https://user-images.githubusercontent.com/46521639/117604026-03055000-b172-11eb-96a3-ddc0684ae2e6.png)

### Authentication Flow
![image](https://user-images.githubusercontent.com/46521639/117604076-1a443d80-b172-11eb-88fe-1918d2a5e5f1.png)

### Client-Server Communication
![image](https://user-images.githubusercontent.com/46521639/117604104-27f9c300-b172-11eb-9d73-165dec6777f6.png)

### Route Parameters
When a component is rendered by the Route, some additional props are passed.

They are:

match
history
location

### History
The history object has some methods to control the navigation in the browser, and it also maintains the history of the routes we navigated.
It has the following methods to control the navigation in the browser:
  push()
  replace()
  go()
  goBack()
  goForward(), etc.
The history.push() and history.replace() methods are used to navigate to other routes programmatically.

### history.push()
With the history.push() method, the user can go forward and backwards in the browser, and the URL will change.
  **Syntax: history.push("PATH");
  ![image](https://user-images.githubusercontent.com/46521639/117604294-ad7d7300-b172-11eb-949c-ff2ddab87dad.png)

### history.replace()

The history.replace() method replaces the current URL with new one. The user can't go backwards to the previous URL.
**Syntax:history.replace("PATH");
![image](https://user-images.githubusercontent.com/46521639/117604324-bff7ac80-b172-11eb-91bf-01de79398466.png)



