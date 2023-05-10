# AWS Client Development Kit CDK TypeScript sample project

This is a blank project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template

## Required Resources

[AWS Client](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
[AWS CDK](https://aws.amazon.com/pt/getting-started/guides/setup-cdk/module-two/)
[Node.js](https://nodejs.org/en)
[Typescript](https://www.typescriptlang.org/download)

AWS Cli installation

```sh
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```

Configure AWS Client

```sh
aws configure
```

AWS CDK installation

```sh
npm i -g aws-cdk
```

Typescript installation

```sh
npm i -g typescript
```

Check versions

```sh
aws --version
node --version
cdk --version
npm --version
```

## CDK Toolkit commands

| Command  | Function |
| -------------- | ------------------------------------------------------------------- |
| cdk list (ls)  | Lists the stacks in the app  |
| cdk synthesize (synth) | Synthesizes and prints the CloudFormation template for one or more specified stacks |
| cdk bootstrap | Deploys the CDK Toolkit staging stack; see Bootstrapping |
| cdk deploy | Deploys one or more specified stacks |
| cdk destroy | Destroys one or more specified stacks |
| cdk diff | Compares the specified stack and its dependencies with the deployed stacks or a local CloudFormation template |
| cdk metadata | Displays metadata about the specified stack |
| cdk init | Creates a new CDK project in the current directory from a specified template |
| cdk context | Manages cached context values |
| cdk docs (doc) | Opens the CDK API Reference in your browser |
| cdk doctor | Checks your CDK project for potential problems |
