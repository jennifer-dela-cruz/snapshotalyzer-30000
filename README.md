# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

# Configuring

shotty uses the configuration file created by the AWS CLI e.g.

'aws configure --profile shotty'

# Running

'pipenv run python shotty/shotty.py <command> <--project=PROJECT_NAME>'

*command* is instances, volumes or snapshots
*subcommand* - depends on the command, can be list, create, start or stop
*project* is optional
