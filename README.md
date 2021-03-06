# Verification Service
[![CircleCI](https://circleci.com/gh/steelbutsmart/steelbutsmart-mvp/tree/master.svg?style=svg&circle-token=7257289c6f3dad71f2d42e30c8883ec04fc571fd)](https://circleci.com/gh/steelbutsmart/steelbutsmart-mvp/tree/master)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fs1seven%2Fverification-service.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fs1seven%2Fverification-service?ref=badge_shield)

## Intro
The Verification Service provides an API and a web interface to verify the authenticity of certificates generated by the Notarization Service. Please refer to  [en10204.io](https://en10204.io).

## Starting app
* Install dependencies `yarn`
* Build all by running `yarn build`
* Start app `yarn workspace verification-service-backend start`
* Go to `localhost:3000`, the app should be running

## Configuration
The URL defining the chain is read from the environment variable `BIGCHAINDB_URL`. In case no value is provided the default `https://test.ipdb.io/api/v1/` is set.

## Testing
* Install dependencies `yarn`
* Build all by running `yarn build`
* Start containers `yarn workspace verification-service-backend docker:test:infra`
* Run unit tests `yarn test`

## Public demo
Can be found at [demo.en10204.io](https://demo.en10204.io).

## Further documentation
Please refer to [documentation.en10204.io](https://documentation.en10204.io).




## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fs1seven%2Fverification-service.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fs1seven%2Fverification-service?ref=badge_large)