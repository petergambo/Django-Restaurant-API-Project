# Django-Restaurant-API-Project
This is an API project for the LittleLemon restaurant made with Django Rest Framework.

## Project Description
Little Lemon's management wants to develop an online-based order management system and mobile application. They need a back-end API that allows customers to 
- browse food items, 
- view the item of the day and 
- place orders. 
- Managers need to be able to update the item of the day and monitor orders and assign deliveries. - And the delivery crew should be able to check the orders assigned to them and update an order once it’s delivered.

## API endpoints
### User registration and token generation endpoints

| **Endpoint**         | **Method** | **Purpose**                                                                     |
|----------------------|------------|---------------------------------------------------------------------------------|
| /api/users           | POST       | Creates a new user with name, email and password.                               |
| /api/users/users/me/ | GET        | Display only the current user.                                                  |
| /token/login/        | POST       | Generates access tokens that can be used with other API calls for authorization |