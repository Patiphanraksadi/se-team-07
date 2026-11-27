# Intent: Search, rate, and review movies in Rotten Potatoes.
Author: KillerUNai, for the customer proxy. Status: draft.

## Problem
Currently, users can only filter and sort movies, but cannot search for specific titles or leave ratings and reviews.

## Proposed outcome
Movie-goers can search for movies by title, view details, and submit ratings and reviews. Administrators can add, update, and remove movie information with clear messages when actions fail.

## Affected users and systems
* *Movie-goers (Viewers):* Search, filter, sort, view details, and submit ratings and reviews for movies.
* *Administrators (Content Managers):* Add, edit, and delete movie entries.
* *Information involved:* Movies and reviews.

## Constraints
* Regular users must not be able to edit or delete movie details.
* The system must not collect personal information beyond what is explicitly approved.

## Open questions
* Should movie posters and summaries be pulled from an external movie service or entered manually?
* Do users need to log in (e.g., via an external sign-in provider) before writing a review?
* If users must log in, what personal details are allowed to be stored?
* Which features are strictly out of scope?