name: Custom issue template
about: Roadmap Item
title: ''
labels: []
projects: ["opencloud-eu/projects/2"]
assignees:
  - tbsbdr
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Add a user story and some details
      placeholder: "## As a ..., I want to ... so that ..."
      value: "## As a ..., I want to ... so that ..."
    validations:
      required: false
  - type: checkboxes
    id: platform
    attributes:
      label: Platform
      multiple: true
      options:
        - label: Server
        - label: Web
        - label: Desktop App
        - label: Android App
        - label: iOS App
    validations:
      required: false
