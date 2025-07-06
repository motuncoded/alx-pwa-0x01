# ALX Project 0x14

This project demonstrates how to correctly understand and interact with an API—in this case, the MoviesDatabase API—by reading the documentation, understanding the request and response structures, and implementing proper authentication and error handling.

## API Overview

The MoviesDatabase API provides access to a wide range of movie-related data. With it, you can:

- Search for movies and TV shows by title
- Retrieve detailed information about specific movies or TV shows
- Get cast and crew details
- Access trending, popular, and upcoming movie lists
- Filter results by release year, genre, and more

This API is designed for developers who need fast and flexible access to movie metadata.

## Version

- **Current Version:** 1.0.0 (as documented on RapidAPI)

## Available Endpoints

Here are some commonly used endpoints in the MoviesDatabase API:

| Endpoint | Description |
|----------|-------------|
| `/titles/search/title` | Search for movies or shows by title |
| `/titles/x/titles-by-ids` | Retrieve multiple movie/show records using their IDs |
| `/titles/{id}` | Get detailed information about a movie/show by ID |
| `/actors/{id}` | Get actor or crew member details by their ID |
| `/titles/random` | Get a random movie or show |
| `/titles/utils/genres` | Get a list of all available genres |

## Request and Response Format

### Request Format

All requests should be made using HTTPS and must include specific headers for authentication (see [Authentication](#authentication)).

Example: Search for a movie by title

