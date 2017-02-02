# opsworks-jenkins-cookbooks

This is a wrapped cookbook to install Jenkins.

## Source

Source code of this repository is at https://github.com/chef-cookbooks/jenkins

## Why

http://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-installingcustom-repo.html

Because AWS OpsWorks has it's own SCM structure requirement as above link, we cannot directly use source repository. Since we still haven't Jenkins set up, I manually created this repository by executing command below based on source repository.

berks vendor ../opsworks-jenkins-cookbooks
