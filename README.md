# Charly Team Web

This repo contains a earlier version of CharlyTeam Web to be publish in the web

## Deploy

Just run the next script with the need data to deploy to aws-amplify-react

```bash
aws s3 sync \
--profile <aws_profile> . s3://<s3_bucket_name> \
--exclude ".git/*" --exclude "Readme.txt" --exclude "README.md"
```

Just like:

```bash
aws s3 sync \
--profile charly_team_api_dev . s3://temp-charly-team-web-demo \
--exclude ".git/*" --exclude "Readme.txt" --exclude "README.md"
```
