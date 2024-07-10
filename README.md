# CI-CD
[![CI](https://github.com/LoicSteve/CI-CD/actions/workflows/cicd.yml/badge.svg)](https://github.com/LoicSteve/CI-CD/actions/workflows/cicd.yml)
[![CI](https://github.com/LoicSteve/CI-CD/actions/workflows/cicd.yml/badge.svg)](https://github.com/LoicSteve/CI-CD/actions/workflows/cicd.yml)
## Overview

 
In this lab, we will learn how to implement Continuous Integration (CI) and Continuous Deployment (CD) processes using a Makefile and the Click test runner. We will perform linting, formatting, refactoring, and testing on a Python script to ensure its quality and functionality.

## Goals
1. Understand the importance of CI/CD processes in MLOps.
2. Learn how to use a Makefile for automating linting, formatting, refactoring, and testing.
3. Gain experience in writing tests for command-line tools using the Click test runner.

## Getting started

1. Source the virtual environment:
source /home/coder/venv/bin/activate
2. Run the following steps of the Makefile:
make lint
make format
make refactor
make test
Reflection Question: Why does refactor combine lint and format?

3. Run the following command-line tool and then write a test for it using the Click test runner:
Write a test for the add_cli functionality of the main.py function in the test_main.py test file.
Use the test for ./main.py --help as a guide.
