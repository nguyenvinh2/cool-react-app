# cool-react-app

## Troubleshooting

### AWS-1.YML

- Problem: Resource name "cool-react-bucket" is not alpha-numeric
- Solution: replace all "cool-react-bucket" with coolreactbucket


### AWS-2.YML

- Problem: Resources within S3 bucket were not publicly accessible
- Solution: Added a changed in the post-build commands section: private to  public-read

### AWS-4.YML

- Problem: Missing CodeBuild and CodePipelineRole code
- Solution: Adding missing blocks of code.

![yaml-4](assets/yaml-4-deployed.png)