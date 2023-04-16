

## Monolith 
- All components are part of a single unit.
- Everything is  developed , deployed and scaled as 1 unit.
- App must be written with 1 tech stack and 1 language .
- Teams needs to be carefull to not effect each other's work.
- 1 single artifact , so you must redeploy  the entire application on each update

### Challenges of monolith architecture
- coordination become difficult when application is too large and complex.
- parts are more tangled into each other
- you can only scale the entire app , instead of specific service.
- higher infrasture costs and less
flexibity in scalling the app.
- Difficulty if services need different dependency versions.
- release process takes longer
- on every change , the entire application needs to be tested.
- Entire application need to be built and deployed 
- bug in any module can potentially bring down the entire application .


## Microservices Architecture.

- Split app into smaller, independent serices.
-   split based on business funcationalities.
- Developed, deployed and scaled separately.
- services can be built and deployed separately.
- each microservices has its own version.

