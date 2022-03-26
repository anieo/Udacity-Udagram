# Udacity-Udagram

Deploy a high-availability web app using cloudformation

## Description

In this project, you’ll deploy web servers for a highly available web app using CloudFormation. You will write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software. The procedure you follow here will become part of your portfolio of cloud projects. You’ll do it exactly as it’s done on the job - following best practices and scripting as much as possible.

## Usage

### Deploy

```bash
create network network.yml network-parameters.json
create server server.yml server-parameters.json
```

### Update

```bash
update network network.yml network-parameters.json
update server server.yml server-parameters.json
```

### Delete

```bash
delete network network.yml network-parameters.json
delete server server.yml server-parameters.json
```

