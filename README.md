# TV/Movie release tracker

## Functionalities

- Users can track TV shows'/ movies' release dates by their referenced IMDB/TheMovieDatabase identifiers
- Users can tick TV shows/movies as already watched
- Users can enable alerts/ weekly reports of upcoming movies by email

## Entities

- User
  - Third party authentication identifier
    - Can NEXT Auth be integrated?
  - Tracked shows
    - Watched episodes
  - Tracked movies
    - Watched movies
  - Alerts
  - Permissions?
- TV Show
  - Internal ID
  - External/reference id
    - IMDB?
    - TheMovieDatabase?
  - Overall title
  - Show banner link
  - Episodes
    - Title
    - Air date
    - Episode banner link
- Movie
  - Internal ID
  - External/reference id
    - IMDB?
    - TheMovieDatabase?
  - Title
  - Movie banner link
  - Air date

## Technologies

- Database: PostgreSQL
- ORM: Prisma
- Backend & Frontend: Nuxt.js 3

