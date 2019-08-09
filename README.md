# shnapshotalyzer-30000

Demo project to manage AWS EC2 instance shnapshots

## About

This project is a demo, uses boto3 to manage AWS instance shnapshots

## Configuring

shotty uses the configuration file created by the AWS calc_dist

'aws configure' --profile shotty'

## Running

'pipenv run "python shotty/shotty.py' <command> <subcommand>
<-project=PROJECT>"''

*command* is instances, volumes, or snapshots
*subcommand* depends on command
*project* is optional 
