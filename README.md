# Node Auth Boilerplate

This is a boilerplate for an Express app with local user authentication. This is customized and handy for future projects.

## What It Includes

*Local Auth (email and password)
*Passport and passport-local
*Sessions for saving user info and displaying flash messages
*Settings for PostgresSQL and Sequelize
*Hashed passwords
*EJS templating and EJS layouts
*Seqeulize User model
*Materialize styling - nav and footer

## Included Models

**User Model**
|Column| Type | Notes |
|-----------------|------------|-------------|
| id | Integer | Serial primary Key|
| firstname | String | Required length > 1 |
| lastname | String | - |
| email | String | Unique Login |
| password | String | Hash |
| birthday | Date | - |
| admin | Boolean | Defaulted to False |
| pic | String | - |
| bio | Text | - |
| createdAt | Date | Automatically added by Sequelize |
| updatedAt | Date | Automatically added by Sequelize |



## Included Routes

## Directions For Use