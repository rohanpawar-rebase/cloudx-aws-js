# CloudX AWS Practitioner CDK Project

This project is a starter template for AWS CDK development with TypeScript.  
It provisions an S3 bucket for static website hosting and a CloudFront distribution for secure content delivery.

---

## Project Structure

- **lib/**: CDK stack and constructs
- **resources/build/**: Static site files (e.g., `index.html`)
- **cdk.json**: CDK Toolkit configuration

---

## Useful Commands

- `npm run build` &nbsp;&nbsp;&nbsp;&nbsp;Compile TypeScript to JavaScript
- `npm run watch` &nbsp;&nbsp;&nbsp;&nbsp;Watch for changes and compile
- `npm run test` &nbsp;&nbsp;&nbsp;&nbsp;Run Jest unit tests
- `npx cdk deploy` &nbsp;&nbsp;&nbsp;&nbsp;Deploy this stack to your AWS account/region
- `npx cdk diff` &nbsp;&nbsp;&nbsp;&nbsp;Compare deployed stack with current state
- `npx cdk synth` &nbsp;&nbsp;&nbsp;&nbsp;Emit the synthesized CloudFormation template

---

## Stack Outputs

- **S3 Bucket Name:**  
  `deploywebappstack-deploymentfrontendbucket5503305f-tnrygmuhu4sm`
- **CloudFront URL:**  
  [https://d3ssvee57gf4ea.cloudfront.net](https://d3ssvee57gf4ea.cloudfront.net)
- **Stack ARN:**  
  `arn:aws:cloudformation:us-east-1:989005111520:stack/DeployWebAppStack/66134d00-9601-11f0-9988-0affc9afce05`

---

## Useful Links

- [AWS CDK Documentation](https://docs.aws.amazon.com/cdk/latest/guide/home.html)
- [AWS CloudFormation Documentation](https://docs.aws.amazon.com/cloudformation/index.html)
- [Amazon CloudFront Documentation](https://docs.aws.amazon.com/cloudfront/index.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Jest Documentation](https://jestjs.io/docs/getting-started)
