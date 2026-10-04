# hello-world

A minimal sample repository used for CI/CD pipeline experiments.

It contains a `Jenkinsfile` built on the fabric8 pipeline library that
runs a Maven CI build on pull requests and, on the main branch, performs a
canary release followed by a staged rollout (Stage → approval → Run) on
OpenShift.
