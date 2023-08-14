Lab 1: Build CI/CD Solution

Overview

In this lab, you will learn how to implement Continuous Integration (CI) and Continuous Deployment (CD) processes using a Makefile and the Click test runner. You will perform linting, formatting, refactoring, and testing on a Python script to ensure its quality and functionality.

Goals

By the end of this lab, you will:

Understand the importance of CI/CD processes in MLOps.

Learn how to use a Makefile for automating linting, formatting, refactoring, and testing.

Gain experience with the Click test runner for testing command-line tools.

Getting Started

Lab 1: Build CI/CD Solution

Overview

In this lab, you will learn how to implement Continuous Integration (CI) and Continuous Deployment (CD) processes using a Makefile and the Click test runner. You will perform linting, formatting, refactoring, and testing on a Python script to ensure its quality and functionality.

Goals

By the end of this lab, you will:

Understand the importance of CI/CD processes in MLOps.

Learn how to use a Makefile for automating linting, formatting, refactoring, and testing.

Gain experience with the Click test runner for testing command-line tools.

Getting Started

To get started, follow these steps:

Source the virtual environment:

source /home/coder/venv/bin/activate

Run the following steps of the Makefile

make lint

make format

make refactor

make test

Reflection Question: Why does refactor combine lint and format?

Run the following command-line tool and then write a test for it using the Click test runner:

./main.py --help

Write a test for the add_cli functionality of the main.py function in the test_main.py test file. Use the test for ./main.py --help as a guide.

Reflection Question: How could you use this style of testing to build MLOps tools quickly?

References

You can view this lab on GitHub here: 

https://github.com/nogibjj/Coursera-MLOPs-Foundations-Lab-1-CICD
