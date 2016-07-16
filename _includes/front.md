# Join [AMIMOTO.io](https://github.com/amimoto-ami)

This is an Open Source Project that aims to build a robust toolkit for all developers who run WordPress on the AWS platform.

The repositories contain Opscode Chef, AWS CloudFormation setting, and all the other scripts for automation, provisioning, and making our life easier. We embrace the concept "Infrastructure as code."

We want to welcome all the developers to look at our projects, use it, give feedback, join, and contribute to it.

# Main projects

Here are some main projects that play main roles when launching instances and building the architecture.

## Launch with one click

[lw1](https://github.com/amimoto-ami/lw1-amimoto), is the cookbook you can use to automate launching EC2 instances with one click. The recipes cover the setting up of the WordPress, and the configuration is a fruit of the expertise in both WordPress and AWS.

[https://github.com/amimoto-ami/lw1-amimoto](https://github.com/amimoto-ami/lw1-amimoto)


## Enterprises Cloud Formation

With [amimoto-enterprise-cfn](https://github.com/amimoto-ami/amimoto-enterprise-cfn), we set up the formation of different services. With EC2 in the central, RDS for database, S3 for assets, and CloudFront for CDN serving and caching. All preconfigured and optimized.

<img src="https://github.com/amimoto-ami/amimoto-enterprise-cfn/blob/master/img/stack001.png?raw=true" alt="" />

[https://github.com/amimoto-ami/amimoto-enterprise-cfn](https://github.com/amimoto-ami/amimoto-enterprise-cfn)


# Tools

We also have tools to make our life in WordPress on AWS easier. Let's have a look at some of them.


## C3 CloudFront Clear Cache

Handling caches is the key when we utilize CloudFront. __C3 CloudFront Clear Cache__ is plugin to delete all the CloudFront caches when posts get published on WordPress sites.

[https://github.com/amimoto-ami/c3-cloudfront-clear-cache](https://github.com/amimoto-ami/c3-cloudfront-clear-cache)

## WP-CLI Anywhere

When we are inside AMIMOTO instance, we can use this __WP-CLI Anywhere__ to run wp-cli commands at any directory. You don't need to move to your WordPress dir just to run the commands. Let's automate everything from anywhere in the instance.

## Create Snapshot

A tool to automatically create snapshot of instances.

Check out more at our <a href="https://github.com/amimoto-ami">github organization</a>!







