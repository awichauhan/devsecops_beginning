## writing simple yaml pipelines:


### Write a YAML file that defines an Azure DevOps CI/CD pipeline with two steps: "build" and "test". The pipeline should be triggered whenever there is a code change in "master" branch. The code should be run on "ubuntu-latest" machine.

trigger:
branches:
include:
- master

stages:
- stage: Build
  displayName: Building Azure DevOps App
  pool:
  vmImage: "ubuntu-latest"
  steps:
    - script: |
      mvn clean package

- stage: Test
  displayName: Testing Azure DevOps App
  pool:
  vmImage: "ubuntu-latest"
  steps:
    - script: |
      mvn clean test

# Key Takeaways
- Trigger Syntax: Use the correct format to monitor branches.
- Stages Block: YAML doesn't allow duplicate stages blocks.
- Indentation: Maintain proper indentation for all nested blocks (steps, script, etc.).
- Combine Stages: Ensure all stages are listed under a single stages block.
