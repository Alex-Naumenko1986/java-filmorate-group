# Java-Filmorate (API Filmorate)
### Stack
- Java 11
- Spring Boot
- JDBC
- Maven
- Lambok
- JUnit
- PostgreSQL

# Group project 
The Filmorate application should become a platform for communication and interaction between users. 
Added the ability to make friends, leave reviews and recommend movies to each other.
To help users navigate what is happening on the platform, we added an event feed. 
Plus, we added a search — by keyword from the title or description of the movie.

# Team
## Many thanks to the team with whom I had the opportunity to work on this project!
### GitHub:
* [Alex-Naumenko1986](https://github.com/Alex-Naumenko1986)
* [OrionSleeve](https://github.com/OrionSleeve)
* [Nucleus1337](https://github.com/Nucleus1337)
* [AndreiSmazin](https://github.com/AndreiSmazin)

#### [Everyone's contribution to the project](https://github.com/users/Buhanzaz/projects/1)

## Features

### Films

- Create a film
- Update a film
- Get a film by ID
- Like a film
- Unlike a film
- Get popular films
- Delete a film

### Users

- Add a user
- Update a user
- Get all users
- Get a user by ID
- Add a user as a friend
- Remove a user from friends
- Get user's friends
- Get common friends with a user
- Delete a user

### Genres

- Get all genres
- Get a genre by ID

### Rating

- Get an age rating by ID
- Get all age ratings

## Testing

The functionality has been tested using JUnit 5 in the `tests` package.

## Installation

To use this API, follow these steps:

1. Clone the repository: `git clone https://github.com/Buhanzaz/java-filmorate.git`
2. Navigate to the project directory: `cd java-filmorate`
3. Install any required dependencies: `npm install`

## Diagram 
![Database diagram](/DBDiogram.png)

### Request Examples:
1. Getting a user with ID = 1:
```sql
   SELECT*  
   FROM users  
   WHERE user_id = 1;
```
3. Getting a film with ID = 10:
```sql
   SELECT*  
   FROM films  
   WHERE film_id = 10.
```
## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-branch`
5. Submit a pull request.
