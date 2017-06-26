# AWS Lambda

[@crolek](https://twitter.com/crolek) / [ChuckRolek.com](http://www.chuckrolek.com/) / [github.com/crolek](https://github.com/crolek)

* Stateless NodeJS/Python/Java app.
* Doesn't run until it receives data (e.g. S3)
* Similar to EC2 and Elastic Beanstalk
* Good as middleman or orchestrator
* No direct support for env vars. Can use private S3 bucket.
* Can take up to 2secs to spin up.

## Demo

## Snags

* Updating the code inline
* Creating/matching up API Gateway
* IAM permissions

## Resources

* [serverless/serverless](https://github.com/serverless/serverless)
* [claudiajs/claudia](https://github.com/claudiajs/claudia) -- v2, see example projects
* [teebu/node-lambda](https://github.com/teebu/node-lambda)
* [ThoughtWorksStudios/node-aws-lambda](https://github.com/ThoughtWorksStudios/node-aws-lambda)

## Misc

* 403 error means you have the wrong route URL
* Ability to see logs from the ran server

## Summary

* Middleman for services. Maybe not full app.
* Good if you are already in AWS ecosystem.
