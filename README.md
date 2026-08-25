# Full Stack Open — Part 11: CI/CD

Exercise repository for the Continuous Integration / Continuous Delivery
part of the Full Stack Open course.

## Deployed application

Pokedex: https://full-stack-open-pokedex-allm.onrender.com/

## Exercise 11.21 / 11.22 repository

Bloglist Fullstack: https://github.com/Marcio-Cassio/bloglist-fullstack

## Pipeline

The deployment pipeline runs lint, unit tests, and Playwright end-to-end
tests on every pull request. Merges to `main` additionally deploy to Render,
bump the version tag, and notify Discord. A separate scheduled workflow
performs a periodic health check against the deployed app.