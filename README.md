# Tema 18 - Postman Collections

This repository contains Postman collections and environment for testing some of Hapifyme APIs

## How to use instructions

1. Download and import the collections and the environment in Postman
2. Select the "Hapify Me Tema 18" env in Postman.
3. Run the APIs in this order:
   1. **Register** - Create a new user.
   2. **Get User Confirmation** - Confirms the email of the user.
   3. **Login** - The token for the user is got.
   4. **Get Profile** - Verify the user profile.
   5. **Delete Profile** - Delete the created user profile.

For testing if the user was successfully deleted through the APIs, you can also send the "Get Profile" request after
"Delete" request.


