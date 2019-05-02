# Graasp App Starter: PhET Labs

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This starter kit provides a thin wrapper around [HTML5 PhET labs](https://phet.colorado.edu/en/simulations/category/html/index) in order for them to run seamlessly on the Graasp ecosystem.

## Usage

1. Use the Graasp CLI and select this repository as a starter kit.
2. Visit the [HTML5 PhET labs listing](https://phet.colorado.edu/en/simulations/category/html/index)
and click on the lab that you want to use.
3. Once on the lab's page, you should see a `Download` button. Click on it download the file for this lab.
4. Open the file, copy the contents and paste them into `dist/index.html`.

## Deployment

If you have the appropriate credentials, you will be able to deploy to the Graasp ecosystem
by following the steps below.

1. Run `./scripts/deploy.sh -e .env.prod`
