# cool-react-app

## Team Members

Vinh, Devon, Paolo, Peter

## Troubleshooting

### AWS-1.YML

- Problem: 
  - Resource name "cool-react-bucket" is not alpha-numeric
- Solution: 
  - replace all "cool-react-bucket" with coolreactbucket

### AWS-5.YML

- Problem: 
  - Error: Didn't copy build folder recursively, 
  - Error: DistributionConfig:Origins did not match array type
  - Error: Pipeline should start with a stage that only contains source actions 
- Solution: 
  - add recursive to aws s3 command, 
  - add "-" before Origins for array.
  - change source action to source