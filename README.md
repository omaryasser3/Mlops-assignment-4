# ML Operations Pipeline

This project implements an automated ML model CI/CD pipeline using GitHub Actions.

## Overview

The pipeline validates and tests ML models automatically on every push to the repository.

## Features

- **Python Setup**: Configures Python 3.10 environment
- **Dependency Management**: Installs required packages from requirements.txt
- **Code Quality**: Runs flake8 linter checks
- **Model Testing**: Performs dry runs to ensure model environment is ready
- **Artifact Upload**: Archives project documentation

The GitHub Actions workflow runs on:
- Every push (except to main branch)
- Every pull request

See `.github/workflows/ml-pipeline.yml` for workflow configuration.
