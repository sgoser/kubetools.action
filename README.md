# Kubetools to testing Manifests

This repo using to automate testing Manifests using container *deck15/kubeval-tools:latest* and GitHub Actions.

Link to source: [>> HERE <<](https://github.com/HighwayofLife/kubernetes-validation-tools).

## Using

Github Action Testing Manifests by location (env in workflows) *TESTING_PATH: ./manifests/*.

Collecting data to artifact.

Sending notifications and artifact log file to Slack.

Running tests:

- kubeconform
- kubeval
- kube-linter

## Requirements

GitHub Secrets: Slack Token.
