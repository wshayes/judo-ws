

### AWS Commands

Update website files - run from root directory of hugo website

    aws s3 sync public s3://auburnjudo.club/ --delete --profile personal

Remove website files
    aws s3 rm s3://auburnjudo.club/ --recursive --profile personal
