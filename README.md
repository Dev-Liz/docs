# Welcome to [TMDB](https://www.themoviedb.org/) API Reference Docs👋
This is the V3 of TMDB API Reference Docs, my Capstone project for [TWMP](https://technicalwritingmp.com/) API docs cohort.

This reference doc was built with Mintlify, and has 100+ endpoints for various use cases.

## About The Movie Database (TMDB)
   The Movie Database (TMDB) is a community-built database for movies and TV shows. Its API allows users to get information about movies, TV shows, movie professionals etc.

## Project Goal
   The aim of this project was to revamp and improve the existing [TMDB documentation](https://developer.themoviedb.org/docs/getting-started).

## The process

1. ### Existing Docs Audit
   To improve on the existing TMDB documentation, I did an audit to understand its strengths and weaknesses, I also discussed with possible users (developers) to understand their pain points. From my audit, the documentation needed an improvement on Information architecture and overall user experience.
   ![image](https://github.com/user-attachments/assets/b0912734-3ba0-4b2e-85a1-d781c3b7d0dd)


2. ### Testing the Endpoints with Postman
   I tested the 100+ endpoints on TMDB platform (using [Postman](postman.com)) to ensure that they were not broken or incorrect in any way.

   https://github.com/user-attachments/assets/adcca91d-d356-4b58-a120-baf2d8b3aeca


3. ### Exporting to OpenAPI Spec
   After a successful test of all the available endpoints on Postman, I used the Postman export feature to convert the API references to an OpenAPI spec file. I further converted the exported json file into yaml, using [TWMP](https://technicalwritingmp.com/)'s OpenAPI spec converter. I edited the converted YAML file to add the necessary descriptions and components, using [Swagger editor](https://editor.swagger.io/) and the VS Code IDE.
   ![oas-edit](https://github.com/user-attachments/assets/1eae03c1-3964-4de9-8ced-3b148479ba7c)



4.  Building the docs on Mintlify
   For the final phase of this project, I used the [Mintlify](https://mintlify.com/) documentation tool to bring the OpenAPI reference to life. I imported the API reference from the OpenAPI spec file, customized the look and feel of the documentation, and improved its overall user experience using Mintlify components and custom CSS.
   ![image](https://github.com/user-attachments/assets/0d360eab-3857-40ae-9c67-b4d87ccf0f41)



### Link to final documentation
[Revamped TMDB Docs](https://devliz.mintlify.app/introduction)





