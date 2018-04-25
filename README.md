# AWS Tools

A meta-package to install common AWS-related tools for use
within Stanford UIT.

Only a single tool is installed directly by this package -
`aws-tools` - which checks that the other tools are installed.

The other tools that are installed as dependencies for `aws-tools` are:

  * awscli - the AWS command line tools
  * git - a more recent version of Git
  * git-crypt - for encrypting/decrypting sensitive files in git repos
  * jq - for validating, querying, and parsing JSON
  * terraform - for building out infrastructure in AWS

