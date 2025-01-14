# AWS CLI Resource Fetcher

## Description
This shell script takes two user inputs: `region` and `service_name`, and outputs a list of active resources belonging to the specified AWS service in the specified region. The script uses the AWS CLI to fetch and filter resources, displaying their IDs, names, and types.

## Features
- Accepts dynamic user inputs for region and service name.
- Fetches active AWS resources using AWS CLI.
- Displays resource IDs, names, and types for better resource management.

## Prerequisites
- AWS CLI installed and configured.
- Valid AWS credentials with permissions to access the specified resources.

## Usage
```bash
bash fetch_resources.sh
