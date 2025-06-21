# MoviesDatabase API Integration

This project integrates with the **MoviesDatabase API** to fetch and display movie-related data such as titles, genres, actors, and more.

## API Overview

The MoviesDatabase API provides access to a comprehensive set of data about movies, TV shows, and people in the film industry. It supports endpoints for searching, retrieving detailed information, and browsing popular or trending content. It is ideal for applications focused on entertainment discovery or movie-related content.

## Version

**API Version:** v1

## Available Endpoints

| Endpoint                      | Description                                                              |
|------------------------------|--------------------------------------------------------------------------|
| `/titles`                    | Retrieve a list of movie titles based on filters like genre or year.     |
| `/titles/{id}`               | Get detailed information for a specific movie or show by ID.             |
| `/search/title`              | Search for movies or TV shows by keyword.                                |
| `/genres`                    | Retrieve a list of available genres.                                     |
| `/people/{id}`               | Get information about a person (actor, director, etc.) by ID.            |
| `/titles/random`             | Fetch a random movie or show suggestion.                                 |

## Request and Response Format

### Request Example

**Endpoint:** `GET /titles`

**Headers:**
```http
Authorization: Bearer YOUR_API_KEY
Content-Type: application/json
