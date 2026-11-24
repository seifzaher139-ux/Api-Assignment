# TMDB API Testing (Postman)

Postman collection and environment from my API testing assignment on The Movie Database (TMDB) API v3. Done as part of my Software Testing Diploma at Route Academy.

## Files

- `Api Assignment/TMDB API Testing Assignment.postman_collection.json`
- `Api Assignment/TMDB Environment.postman_environment.json`

## What is in the collection

- An authentication check request.
- 11 numbered scenarios (S01 to S11): search movies and TV shows, movie and TV details, movie credits, popular movies, genres list, discover by genre, now playing, person details, and adding a movie to the watchlist (POST).
- A setup request that gets the account details.
- Test scripts in Postman (`pm.test`) checking status codes and response fields.

## How to use

1. Import both files into Postman.
2. Select the TMDB environment.
3. Fill in your own values for `api_key`, `bearer_token` and `account_id`. They are intentionally left empty in this repo. You can get them from a free TMDB account.
4. Run the collection with the Collection Runner.

## Limits

- Assignment scope: mostly GET requests and one POST.
- Run manually in Postman. No Newman or CI setup.
