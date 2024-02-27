# Pipeline

## GitHub

Store and commit then push to github

## Prepare circleCI environment variables

Setup all the environment variable needed to configure

### Steps of CircleCI (Build)

- Spin up enviorment
- Prepareing environment variables
- Install node js 14.15
- Install AWS CLI
- Configure AWS
- Setup EB
- Install Front-End dependencies
- Install API Dependencies
- Front-End lint
- Front-END build
- API Build
- Hold to approve

### ### Steps of CircleCI (Deploy)

- Spin up enviorment
- Prepareing environment variables
- Install node js 14.15
- Install AWS CLI
- Configure AWS
- Setup EB
- Deploy the app where we push backend to EB and front end to S3 Bucket
