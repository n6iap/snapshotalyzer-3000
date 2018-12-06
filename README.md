# snapshotalyzer-3000
Demo project to manage my AWS EC2 instance and their snapshots.

## About

This project is a demo, and uses boto3 to manage AWS EC2 instances and their snapshots.

## Configuring

shotty uses the configuration file created by the cli e.g.

'aws configure --profile shotty'

#Running

'pipenv run python "shotty/shotty.py <command> <subcommand>
<--project=PROJECT>"'

*command* is instances, volumes or snapshots
*subcommand* - depends on command
*project* is optional
