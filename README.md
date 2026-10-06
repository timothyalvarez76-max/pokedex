# Global Pokédex Database API

This is the backend service for the Global Pokédex Database.

## API Documentation

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| POST | /api/auth/login | Authenticates user and initiates session. |
| GET | /api/pokemon | Retrieves all Pokémon entries. |
| POST | /api/pokemon/add | Adds a new Pokémon. |

## Error Handling
This API uses a `@RestControllerAdvice` to handle validation errors.