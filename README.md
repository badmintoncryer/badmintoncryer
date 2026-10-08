I'm kazuho cryershinozuka!

I love Badminton　🏸　

- [AWS Community Builders](https://builder.aws.com/community/@cryer)
- [AWS CDK Top Contributor](https://github.com/aws/aws-cdk/blob/main/CONTRIBUTORS.md)
- [AWS CDK Community Reviewer](https://github.com/aws/aws-cdk/wiki/CDK-Community-PR-Reviews)
- [Core contributor of aws-serverless-full-stack-webapp-starter-kit](https://github.com/aws-samples/serverless-full-stack-webapp-starter-kit)
- APJ community leaders awards 2025

<img width="406" height="384" alt="スクリーンショット 2026-05-23 20 44 30" src="https://github.com/user-attachments/assets/10bc1350-d5ed-46dc-b147-3468ea23cb31" />

<p align="left">
  <img alt="AWS CDK Contributor" height="150px" src="https://cdk-stats.vercel.app/api?username=badmintoncryer" />
  <img alt="github stats" height="200px" src="https://github-readme-stats.vercel.app/api?username=badmintoncryer&theme=onedark&show_icons=true" />
</p>

## OSS contribution

- [AWS CDK](https://github.com/aws/aws-cdk/pulls?q=is%3Apr+author%3Abadmintoncryer)
- [Terraform provider AWS](https://github.com/hashicorp/terraform-provider-aws/pulls?q=is%3Apr+author%3Abadmintoncryer)
- [Grafana](https://github.com/grafana/grafana/pulls?q=is%3Apr+author%3Abadmintoncryer)

## Projects

### CDK tools

#### [cdk-preflight](https://github.com/badmintoncryer/cdk-preflight)

[![npm](https://img.shields.io/npm/v/cdk-preflight.svg)](https://www.npmjs.com/package/cdk-preflight) [![downloads](https://img.shields.io/npm/dt/cdk-preflight.svg)](https://www.npmjs.com/package/cdk-preflight)

Catch deploy-time CloudFormation failures at `cdk synth` time. A Rego rule pack (3,000+ rules) for the CloudFormation validation engine built into `aws-cdk-lib`.

#### [cfn-exec-policy](https://github.com/badmintoncryer/cfn-exec-policy)

[![npm](https://img.shields.io/npm/v/cfn-exec-policy.svg)](https://www.npmjs.com/package/cfn-exec-policy) [![downloads](https://img.shields.io/npm/dt/cfn-exec-policy.svg)](https://www.npmjs.com/package/cfn-exec-policy)

Least-privilege CloudFormation execution role for AWS CDK. Generates the IAM policy your templates actually need, so `cdk bootstrap` no longer hands out `AdministratorAccess`.

#### [CDK daily summary](https://d2t5fomzexey4a.cloudfront.net/)

Daily summary of the PRs merged into AWS CDK. ([Repo](https://github.com/badmintoncryer/aws-cdk-summary))

<img width="560" alt="CDK daily summary architecture" src="https://github.com/user-attachments/assets/522939bc-a2e0-475a-9726-222b7a8ee30b" />

#### [CDK unsupported properties App](https://d1upnzw71mlot9.cloudfront.net/)

List of CloudFormation properties not yet supported by CDK L2 constructs. ([Repo](https://github.com/badmintoncryer/cdk-unsupported-property-app))

### CDK constructs

#### [cdk-iot-core-certificates-v3](https://constructs.dev/packages/cdk-iot-core-certificates-v3)

[![npm](https://img.shields.io/npm/v/cdk-iot-core-certificates-v3.svg)](https://www.npmjs.com/package/cdk-iot-core-certificates-v3) [![downloads](https://img.shields.io/npm/dt/cdk-iot-core-certificates-v3.svg)](https://www.npmjs.com/package/cdk-iot-core-certificates-v3)

Creates an AWS IoT Core Thing with a certificate and policy.

<img width="560" alt="cdk-iot-core-certificates-v3 architecture" src="https://github.com/badmintoncryer/cdk-iot-core-certificates-v3/raw/main/images/iot.png" />

#### [cdk-code-server](https://constructs.dev/packages/cdk-code-server)

[![npm](https://img.shields.io/npm/v/cdk-code-server.svg)](https://www.npmjs.com/package/cdk-code-server) [![downloads](https://img.shields.io/npm/dt/cdk-code-server.svg)](https://www.npmjs.com/package/cdk-code-server)

VS Code Server on an EC2 instance that is not reachable from the internet.

<img width="560" alt="cdk-code-server architecture" src="https://github.com/badmintoncryer/cdk-code-server/raw/main/images/code-server.png" />

#### [cdk-private-s3-hosting](https://constructs.dev/packages/cdk-private-s3-hosting)

[![npm](https://img.shields.io/npm/v/cdk-private-s3-hosting.svg)](https://www.npmjs.com/package/cdk-private-s3-hosting) [![downloads](https://img.shields.io/npm/dt/cdk-private-s3-hosting.svg)](https://www.npmjs.com/package/cdk-private-s3-hosting)

Private S3 bucket served through an internal ALB, with a listener rule that forwards requests to the bucket.

<img width="560" alt="cdk-private-s3-hosting architecture" src="https://github.com/badmintoncryer/cdk-private-s3-hosting/raw/main/images/private_s3_hosting.png" />

#### [cdk-rds-scheduler](https://constructs.dev/packages/cdk-rds-scheduler)

[![npm](https://img.shields.io/npm/v/cdk-rds-scheduler.svg)](https://www.npmjs.com/package/cdk-rds-scheduler) [![downloads](https://img.shields.io/npm/dt/cdk-rds-scheduler.svg)](https://www.npmjs.com/package/cdk-rds-scheduler)

Starts and stops RDS (Aurora) clusters or instances on a schedule.

<img width="560" alt="cdk-rds-scheduler architecture" src="https://raw.githubusercontent.com/badmintoncryer/cdk-rds-scheduler/HEAD/image/architecture.png" />

#### [cdk-preinstalled-amazon-linux-ec2](https://constructs.dev/packages/cdk-preinstalled-amazon-linux-ec2)

[![npm](https://img.shields.io/npm/v/cdk-preinstalled-amazon-linux-ec2.svg)](https://www.npmjs.com/package/cdk-preinstalled-amazon-linux-ec2) [![downloads](https://img.shields.io/npm/dt/cdk-preinstalled-amazon-linux-ec2.svg)](https://www.npmjs.com/package/cdk-preinstalled-amazon-linux-ec2)

Amazon Linux 2023 EC2 instance with software preinstalled.

### Hardware

#### Nixie tube barometer

Temperature, humidity and pressure barometer with Nixie tubes. I built everything from the analog circuit and board design to the software. ([Movie](https://user-images.githubusercontent.com/64848616/221582740-e0a4b2ab-accf-4f7c-9ca1-1ef2a64a822d.mp4))

<p align="left">
  <img alt="Nixie tube barometer" height="300px" src="https://user-images.githubusercontent.com/64848616/221585177-107b6846-eeb8-4d6c-87d1-512ed03a3435.jpg" />
  <img alt="Nixie tube barometer" height="300px" src="https://user-images.githubusercontent.com/64848616/221585191-0335c0a3-731f-4cc2-a930-41afc94decdd.jpg" />
</p>

<!---
badmintoncryer/badmintoncryer is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
