<img src="https://github.com/yhirano55/ama/blob/master/app/assets/images/logo.png?raw=true" width="255" height="80" alt="">

[![CircleCI](https://circleci.com/gh/yhirano55/ama.svg?style=svg)](https://circleci.com/gh/yhirano55/ama)

"Ask Me Anything" with Rails 5.2 Application.

This app is aim to take questions and feedbacks from audience.

## Dependencies

- Ruby 2.5.0
- Ruby on Rails 5.2.0.rc2 (with Active Storage)
- Yarn 1.3.2
- Webpacker
- Bootstrap 4
- Stimulus 1.0.1
- Postgresql 9.6.3
- cmake

## Getting started

### on local

```
$ bin/setup
$ vim .env # for set GitHub auth key/secret. See: https://github.com/settings/developers
$ bin/rails s
```

### on docker

```
$ docker-compose build
$ docker-compose run --rm app bin/setup
$ vim .env # for set GitHub auth key/secret. See: https://github.com/settings/developers
$ docker-compose up -d
```

## License

[MIT License](https://opensource.org/licenses/MIT)
