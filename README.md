AWS Shell Utilities
===================
Shell utils to make it easier to work with AWS instances


Dependencies
------------
- JQ: http://stedolan.github.io/jq
- AWS CLI: http://aws.amazon.com/cli/


Contents
--------
 - ec2instancemetadata : retrieve json metadata for instance using aws cli
 - ec2ip : work out the private ip address for an aws instance using jq and aws cli
 - ec2ssh : initiate an ssh session to an instance, assumes that you have SSH keys in your ~/.ssh directory as <keyname>.pem and that you are logging in as ec2-user
