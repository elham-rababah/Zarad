[![Stories in Ready](https://badge.waffle.io/Sportitsu/Zarad.png?label=ready&title=Ready)](https://waffle.io/Sportitsu/Zarad)
# Zarad

> project description
Zarad is app help  the sport clubs to manage  their  activities and facilitate ***trace** the players and their history,also it helps player to see the videos related to his club.    

## Team

  - __Product Owner__: Mohammad al-bakri
  - __Scrum Master__: Mihyar Al-masalma
  - __Development Team Members__: Fatima hammami, Elham rababah

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> app is now running online through :
[here](zara.herokuapp.com)

>to run the app locally:
```sh
ionic serve 
```
>to run the app on phone platforms
```sh
ionic serve --lab
```

## Running Test
-run front end test
```sh
npm run karma
```

-run back end test with coverage
```sh
npm test
```

-run front end cover test
```sh
npm run cover
```
## styling guide
```sh
gulp
```
## Requirements

- Node 6.3.x
- mongoDB 4.1.0
- ionic 1.3.1

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install -g ionic
npm install
```



# RESTful Routes
| Method        | Endpoint      | Description  |
| ------------- |:-------------:| ------------:|
|Post           |/api/admin/create|create new admin |
|Post|/api/admin/signin|check if the admin authenticat to use the app|
|get|/api/admin/x/:username|get the data of admin depend on username.Username must be passed in as the last part of the URL path|
|post|/api/admin/delete|delete +++Spacefic++ admin  |
|Post|/api/admin/admins|get information of all admin|
|get|/api/tournament/x/:name|get information of tournament depend on name.name must be passed in as the last part of the URL path|
|get|/api/tournament/tournaments|get information of all tournaments | 
|post|/api/tournament/create|create new tournaments|
|post|/api/tournament/delete|delete +++Spacefic++ tournaments|
|post|/api/tournament/edit'|update tournament information|
|post|/api/tournament/addLike'| add like on tournament|
|post|/api/club/register|create new club|
|get|/api/club/x/:username|get information of club depend on username.username must be passed in as the last part of the URL path|
|get|/api/clubs| get information of all club|
|post|/api/club/delete|Remove +++Spacefic++ club |
|post|/api/club/editProfile|update information of club|
|post|/api/club/signin|check if the club authenticat to use the app|
|post|/api/club/getclub|get information of club|
|post|/api/user/delete|delete +++Spacefic++ user|
|post|/api/user/editProfile| update information Profile of user|
|get|/api/user/x/:username| get information of user depend on username.username must be passed in as the last part of the URL path|
|get|/api/users| get information of all user|
|post|/api/user/signin| check if the user authenticat to use the app|
|post|/api/user/signup| create new user|
|post|/api/user/resub| check  the user ***subsecrbtion** to use the app|
|post|/api/user/goals| add goals for +++Spacefic++ user|
|get|/api/quotes/get|get information of quote |
|post|/api/quotes/newquote| add new quote to +++Spacefic++ user|



#The Database 
| Table        |
| admin|
| tournament|
| club|
| user|
| quote|

### Roadmap

View the project roadmap [here](https://waffle.io/Sportitsu/Zarad)


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## Production

See our website [here](http://zarad.herokuapp.com/#/).

## Builds

See our latest build [here](https://travis-ci.org/Sportitsu/Zarad).
