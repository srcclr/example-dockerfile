# [:] Example Dockerfile Project

An example project with configuration issues found in Dockerfile 

## Pre-requisites
Ensure the usage of srcclr agent version 3.7.15 or above. Dockerfile configuration scanning was introduced in the srcclr agent version 3.7.15.

## Usage
`srcclr scan . --scan-dockerfile`

## Supported Configurations
- Checks for the usage of the USER instruction
- Checks for the usage of the HEALTHCHECK instruction
- Checks for the usage of the ADD instruction
