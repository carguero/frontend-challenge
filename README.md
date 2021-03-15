# frontend-challenge

## Introduction
Hi! Thank you for your interest in participating in our selection process for dev front-end in Carguero.
The objective of the proposed challenge is to allow a better assessment of your skills as a candidate for the front-end vacancy. This challenge must be done 
only by you. It's implementation and choice of tools may be questioned at another stage.
 
## The challenge
Using the free movie API <a href="https://developers.themoviedb.org/3/getting-started/introduction" target="_blank">themoviedb</a> in version 3, 
you will be responsible for creating a listing of the most popular films of the day, by referring to the 
<a href="https://developers.themoviedb.org/3/discover/movie-discover">GET /discover/movie</a> endpoint to make the listing. 
When clicking on an item in this listing, another page with the details of the chosen movie should be displayed. To access more details about the film, you 
can consult the <a href="https://developers.themoviedb.org/3/movies/get-movie-details">GET /movie/{movie_id}</a>.
We have insights that lead us to believe that users on this list tend to have a better experience if they can create a filter using their favorite genres. 
Therefore, you will also be responsible for creating film filters by genre in that listing. Note that a new endpoint must be consulted to obtain a list of 
possible genres to be filtered, <a href="https://developers.themoviedb.org/3/genres/get-movie-list">GET /genre/movie/list</a>.
To ensure that the user finds the movie they are looking for, this list should be paged whenever there is no active genre filter.
It should be possible to rank <a href="https://developers.themoviedb.org/3/movies/rate-movie">POST /movie/{movie_id}/rating</a> 
rating and favor <a href="https://developers.themoviedb.org/3/account/mark-as-favorite">POST /account/{account_id}/favorite</a> the movies that the user wants, 
there is no need to create an account per user, you can use the guest account using this <a href="https://developers.themoviedb.org/3/authentication/create-guest-session">GET /authentication/guest_session/new</a>
 

## Functional requirements
 
- The user must have access to a list of the most popular films of the day
- User should be able to page through the list to find new movies
- The user must be able to filter the films listed by genre, with the possibility of using more than one genre
- When making filters, the same must be persisted by the pagination
- The user must be able to remove filters and the listing must be updated according to the removed filter
- The user must have access to another page with details about the film, by clicking on an item in the listing
- The user should be able to return to the movie listing page with the filters still active
- User must be able to add movie to favorites
- The user must be able to rank the films
- Create login using guest account
- Any type of pagination is accepted, but keep in mind when choosing any form of pagination.

## Non-functional requirements
- The app must be hosted on a cloud service, such as: Surge, Netlify, ZEIT. Other more robust platforms like AWS will also be accepted
- The app must be created using React
- At the root of the project, you will need to include a README.md file with instructions for building your project locally
- The page with details of a film must have its own route and be prepared to be indexed in search engines
- The app must be responsive
- Write or configure tests of any kind, such as: static tests, unit, integration, etc.

## Extras

- Apply a CSS-in-JS or CSS Modules solution
- Implement other features that you think are useful for the user of this app
- Rating criteria
- Good development practices such as: tests, design patterns, clean code
- Mastery of the tools and languages that make up a modern frontend app
- Performance care applied to the app, such as: data structure, efficiency of the way to distribute and apply CSS
- Knowledge in areas adjacent to the frontend, such as UX applied to the challenge
- Documentation: explanation for building the app locally, history and git workflow


## Rating criteria

- Good development practices such as: tests, design patterns, clean code
- Mastery of the tools and languages that make up a modern frontend app
- Performance care applied to the app, such as: data structure, efficiency of the way to distribute and apply CSS
- Knowledge in areas adjacent to the frontend, such as UX applied to the challenge
- Documentation: explanation for building the app locally, history and git workflow

## Delivery

To deliver the challenge, create a new repository on Github with your entire solution and sent to us by e-mail.

Don't forget to create a README.md file containing instructions for building the app locally, as well as any other links or materials used to build 
the app, such as: prototypes, diagrams, sketches, etc.
