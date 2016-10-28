# Docker PHP 7.0 & MySQL

This is a Docker container intended to be used to run your tests on PHP 7.0. It assumes you will be attaching your app as a volume to `/app`.

Be default it assumes your app has a `run.sh` file in the root that runs your tests (e.g. `composer install` and `phpunit`). See the [run.sh](run.sh) file for an example.

## Run

```
docker run -v /path/to/your/app:/app gilbitron/php7.0-mysql
```

Looking for [PHP 5.6](https://github.com/gilbitron/php5.6-mysql)?
