# Basic Auth with Spring Boot and Angular
Basic auth with Spring Boot, Spring Security 6 and in-mem users

## About
Some testing and practice for future reference. Main goal is to update Spring Security from 5.8 to 6.x.

## Requirements
- Node v.16.14.2
- Angular v.14
- Spring Boot 3.0.2
- Java 17
- Gradle 7.6

## Running
From the front end root, run "ng build --configuration production --aot"
After this, from the root of the project run ".\gradlew bootRun"

## Issues
Currently unable to resolve situation with Cors configuration. But then again one can always use ng build --watch for local development.

## Status
In memory users put to place, and working. Just added an extra bean for userdetails with defaultPasswordEncoder.
Did note that the very first time after initial building the browser authentication popped up. But did started to work after this. Wondering if this would be an issue in production.

The application itself is very simple, I might add some added complexity.

## Authentication
Basic auth - username and password.

## Next steps
Persisting user info in h2-database, custom userdetails.
