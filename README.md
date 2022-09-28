# dokku-env-gen

Generates an `.env` file from environment variables for use in the docker build stage.

## Installation

```sh
# dokku 0.4+
$ dokku plugin:install https://github.com/christiandrey/dokku-env-gen.git
```

## Left to-do

- [ ] Allow environment variables whitelist and blacklist
- [ ] Allow specifying a custom file name for the generated .env file
- [ ] Add tests for commands
- [ ] Allow adding to existing .env files instead of skipping all together
