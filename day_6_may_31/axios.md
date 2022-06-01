# Axios

(reference: https://blog.logrocket.com/axios-vs-fetch-best-http-requests/)

#### What is Axios?
- Promise-based HTTP API based on XMLHttpRequest interface for node.js and browser
- (alternative: fetch())

#### What is it good for?
- sending requests to api
- automatic JSON data transformation
- wider browser support (comparing to fetch())
- intercepting HTTP requests (set a global strategy on sending requests)

#### How can we use it?
- basic syntax for sending a post reqest
  ![image](https://user-images.githubusercontent.com/35707884/171287060-ac0b7937-010c-4869-9c88-6a48589a6d6e.png)

#### Do I want to use axios?
- Yes, it has some built-in APIs that will make sending requests more convenient. However, fetch() can also used to realize most of Axios' features so either method should work in our project.

#### Downsides / Shortcomings
- Still have trouble sending the request to API
![image](https://user-images.githubusercontent.com/35707884/171289675-f9c1e19a-010c-4633-8ccd-2e93f06daca4.png)

- According to some StackOverflow posts, the problem might be because the "Access-Control-Request-Headers" in preflight requests is not listed in "Access-Control-Allow-Headers" from server side. 
![image](https://user-images.githubusercontent.com/35707884/171291360-551f63d0-0fdf-41af-a753-692e610b8097.png)
![image](https://user-images.githubusercontent.com/35707884/171291380-c9722226-f7be-4137-8035-33a7e4984e93.png)

-(Indicating this might need some changes to server-side codes)

### Update
- Codes at server side has been changed and the client side can send requests to backend APIs successfully. 

