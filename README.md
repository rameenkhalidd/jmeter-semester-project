# JMeter Performance Testing Project

## Overview
This project demonstrates performance testing using Apache JMeter with CI/CD automation through GitHub Actions.

## Test Configuration
- **Users:** 50 concurrent threads
- **Ramp-up:** 30 seconds
- **Duration:** 120 seconds (2 minutes)
- **Requests:** 500 total

## Pipeline
Tests run automatically on every push to the main branch.
## GitHub Actions CI/CD

This project uses GitHub Actions to automatically run JMeter performance tests.

### Test Details
- **Concurrent Users:** 50
- **Duration:** 120 seconds
- **Target Endpoint:** jsonplaceholder.typicode.com
- **Automated:** Yes - runs on every push

### Results
View the latest test results in the Actions tab.
