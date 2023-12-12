
## Assignment Task

This system provides user registration, login, logout, and a user profile,  public ,private post creation,Image analysis ,content Genration .

## Features 
 - User Registration
 - User Login / Logout
 - Creation Of Posts (Public / Private)
 - Image Analyzer
 - Content Generation
 - RESTApi Support

## Usage 

- ```pip install -r requirements.txt```
- ```python manage.py runserver```

## Urls

- **/signup:** Register a new user
- **/login:** Login with an existing user
- **/logout**: Logout the current user
- **/home/:** View a list of all public posts
- **/create-post/**: Create a new post (requires authentication)
- **/update-post/<post-id>**: Update the post
- **/ImageAnalyzer/**: Take an image as input and return the extracted keywords as output
- **/Content-Generation/**:Take the product title in the request and send the detailed description
- **/admin:** Access the Django admin site (requires superuser privileges)
- 


## Preview
## Signup 
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/106817606/218756154-4b922ae0-a270-4d98-95d0-063d736ed97c.png">

## Login
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/106817606/218756213-c66f86ca-1976-41c0-b237-0a06667caa0f.png">

## Posts 
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/106817606/218755936-533406dc-735e-4ea4-970c-ab9017656a3a.png">
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/106817606/218756064-79930393-c6f9-4a4c-82d5-1d2087ed2731.png">

## API Authentications
<img width="1280" alt="image" src="https://github.com/rahul-nakum14/django-User-system/assets/106817606/91449ae7-97e0-4f14-aebb-9539b17c9bcb">
<img width="1268" alt="image" src="https://github.com/rahul-nakum14/django-User-system/assets/106817606/d53ae805-5d75-454e-bdea-7ebd7d0dbf52">

## Content Generation

1. **Automated Content Generation (API-3):**
    - Generates detailed product descriptions based on the provided product title.
    - Extracts keywords from the generated description to improve SEO.

https://github.com/Vivek17020/BackendAssignment/assets/116427464/b1acc49a-7267-46a1-89b1-c0702bcc0808

## Image Analyzer

2. **Image Recognition (API-4):**
    - Takes an image as input (e.g., test2.jpg) and returns extracted keywords.
    - Utilizes technologies such as Google Cloud Vision API .
      
      

https://github.com/Vivek17020/BackendAssignment/assets/116427464/0df75a59-7870-44b9-9df6-727733ce18b2




