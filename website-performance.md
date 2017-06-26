# Website Performance

[@mitchelsellers](https://twitter.com/mitchelsellers)

* Goal: <250ms for PageSpeed, 2-3secs for user responsiveness
* Specify the metrics to measure. Collect metrics. Minimum 30day retention.

## Easiest Gains

* number of files
* compression/scaling of images
* GTMetrix.com aggregates Google & Yahoo tools

## Additional Gains

* app caching -- DB queries
* image sprites

## CDNs

* pull type CDN (e.g. CloudFlare, CloudFront)
* point your DNS to them -- first-line server
* acts as a middleman, so might end up with unexpected handling
* traditional CDN (e.g. Amazon S3)
* requires some manual work

## Load Testing

* Mimic a real user. Don't just test the page HTML request.
* loadstorm.com
* Possible metrics: reqs/sec, concurrent users, avg server response, % failed, queue length

## Culture

* proactive rather than reactive
* analyze the metrics
* change 1 thing at a time
