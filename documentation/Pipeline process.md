# Pipeline process
after pushing new commits to the main branch the pipleline will be triggered.
## workflow
### build
- Install Front-End Dependencies
- Install API Dependencies
- Front-End Lint
- build frontend app
- Build the backend API     

### Hold 
- if the branch is the main branch and the build jon is finished successfly we will be waiting for manually approve to start the Deploy job

### Deploy
- eb/setup
- aws-cli/setup
- checkout
- Deploy frontend
- Deploy Backend
