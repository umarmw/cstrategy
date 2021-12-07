# Component version strategy

## Aim

Define a proper way how to version components in different stages
- Dev
- Stable
- Release
- Canary

# Basic commands

Change the last digit in the package number:

`npm version patch`

Change the second digit in the package number:

`npm version minor`

Publish the package with the latest tag:

`npm publish`

Publish the package with a custom tag:

`npm publish --tag beta`
# Pre ID usage

Setting a preid to a package number:

`npm version prerelease --preid=stage`

Example:

` v1.1.2 => v1.1.3-stage.0`

Publish the package with a custom tag for easy search:

`npm publish --tag stage`

# Branching

# Testing

# Notes

