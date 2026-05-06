Assignment for Back-End Developer Capstone course

API paths


| URL                   | METHOD                                      | USER LEVEL     | DESCRIPTION                                                                     |
| -------------------------- | ----------------------------------------- | ---------- | --------------------------------------------------------------------------- |
| /auth/token/login/         | POST                                     | anyone        | login with a correct username and password and will generate token that can be used to request other urls                                                           |
| /auth/token/logout/        | POST | anyone       | Logout the user (remove user token)                          |
| /auth/users/                | POST                          | anyone       | Creates a new user with name, email and password                            |
| /auth/users/me/            | GET          | anyone        | Displays the current user                                                   |
| /auth/users/me/            |PUT, PATCH     | anyone| Update the current user                                                     |
| /auth/users/me/            | DELETE | anyone     | Delete the current user                                                     |
| /restaurant/users          | GET                                     | Admin        | Returns all users                                                           |
| /restaurant/users          | POST                                    | Admin       | Creates a new user                                                          |
| /restaurant/menu-items            | GET |  customer| return all menu-items |
| /restaurant/menu-items/{menuItem} | GET | customer                     | Returns the specific menu-item      |
| /restaurant/menu-items/{menuItem} | PUT, PATCH                   |  admin| Updates the menu-item item |
| /restaurant/menu-items/{menuItem} | DELETE     | admin                   | Deletes the menu-item item |
| /restaurant/bookings             | GET | customers        | Returns all bookings user   |
| /restaurant/bookings              | POST   |customers    | Creates a new booking       |
