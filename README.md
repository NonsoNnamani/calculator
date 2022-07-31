Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.
Used in Azure DevOps lab to demonstrate Integrating External Source Control with Azure Pipelines.

[![Build Status](https://dev.azure.com/EngrNonsoDevOps/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_apis/build/status/NonsoNnamani.calculator?branchName=master)](https://dev.azure.com/EngrNonsoDevOps/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_build/latest?definitionId=10&branchName=master)
[![Node.js CI](https://github.com/NonsoNnamani/calculator/actions/workflows/github-pipelines.yml/badge.svg)](https://github.com/NonsoNnamani/calculator/actions/workflows/github-pipelines.yml)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

[![Build Status](https://dev.azure.com/EngrNonsoDevOps/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_apis/build/status/NonsoNnamani.calculator?branchName=master)](https://dev.azure.com/EngrNonsoDevOps/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_build/latest?definitionId=10&branchName=master)
[![Node.js CI](https://github.com/NonsoNnamani/calculator/actions/workflows/github-pipelines.yml/badge.svg)](https://github.com/NonsoNnamani/calculator/actions/workflows/github-pipelines.yml)
