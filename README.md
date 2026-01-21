## RSVP Movies — IMDb SQL Case Study (Data-Driven Content Strategy)

## Overview
This project analyzes an IMDb-style relational database for RSVP Movies to support strategic decisions around content selection, genre trends, rating performance, and talent-driven insights using SQL-based analytics.

## Business Objective
- Identify high-performing movie genres, languages, and production patterns
- Evaluate ratings, votes, and audience preferences
- Support decision-making for future movie acquisition and production planning

## Database Schema (Entity-Relationship Diagram - ERD)
The database includes:
- `movie` (title, year, country, languages, production_company, worldwide_gross_income)
- `genre` (movie_id, genre)
- `ratings` (avg_rating, median_rating, total_votes)
- `names` (people metadata)
- `director_mapping` (movie_id ↔ director)
- `role_mapping` (movie_id ↔ cast/crew roles)

ERD available in: `docs/ERD_RSPV_Movies.jpeg`

## Key Work Done (Action → Impact)
- Translated business questions into optimized SQL queries using joins across `movie`, `ratings`, `genre`, and talent-mapping tables.
- Identified top genres, high-rated titles, and vote-backed audience preferences to improve content selection accuracy.
- Built director/actor performance insights using role + director mappings to shortlist high-impact talent combinations.
- Evaluated production house and language trends to recommend market-aligned movie investments.
- Summarized findings into executive-ready recommendations to support stakeholder decision-making.

## Tech / Tools
- SQL (MySQL/PostgreSQL compatible)
- Joins, CTEs, Aggregations, Window Functions
- Data Modeling (Relational Schema / ERD)
- Analytical Storytelling

## Deliverables
- SQL Solution: `sql/RSVP_Movies_CaseStudy_Solution.sql`
- Executive Summary: `docs/Executive_Summary_and_Recommendations.pdf`
- Dataset (raw): `datasets/raw/imdb_movies_data.xlsx`
- ERD: `docs/ERD_RSPV_Movies.jpeg`
