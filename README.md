Simple CLI interface for Amazon AWS services
============================================

This is an ultra-simple exercise, exposing the [boto3 API interface](https://boto3.readthedocs.io/en/latest/index.html) as a command line interface using python-fire.

While it covers the entire API, it is not heavily used at this time.

It uses config stored as per boto3 documentation, in ~/.aws/config and ~/.aws/credentials

## Usage

``` bash
$ python b3.py client glacier - list-vaults
ResponseMetadata: {"RequestId": "…", "HTTPStatusCode": 200, "HTTPHeaders": {"x-amzn-requestid": "…", "content-type": "application/json", "content-length": "30", "date": "Thu, 08 Feb 2018 20:39:34 GMT"}, "RetryAttempts": 0}
```
