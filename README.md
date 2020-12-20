# HousepartyAPI

Base URL: https://api2.thehousepartyapp.com

Authentication: Send an authentication header with your token. Example:

`authorization: Bearer YOUR_TOKEN_HERE`

### greet

Greets a user (POST)

/users/ID/greet


### start_call

Call a user (POST)

/users/ID/start_call


### abort_call

Stop calling a user (POST)

/users/ID/abort_call



### me

Details about the authenticated user (based on the auth header) (GET)

/me

# me/relationships

Friends of the authenicated user. (GET)

/me/relationships

# me/suggestions

Who HP wants you to be friends with (GET)
