# angular-amazons3-pipelines
Deploy AngularJs application to Amazon S3 using Bitbucket pipelines

**NOTES:**
Added optional flags for npm and bower to run with attensee/s3_website Docker image

# USAGE:
- Add S3_ID and S3_SECRET to environment variables (settings -> pipelines -> Environment variables)
- Edit "site" option with your build folder
- Edit branch name to fit yours under bitbucket-pipelines.yml

