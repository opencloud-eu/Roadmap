---
name: Custom issue template
about: Roadmap Item
title: ''
labels: ''
projects: ["opencloud-eu/projects/2"]
assignees:
  - tbsbdr
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Add a userstory and some 
      placeholder: ## As a ..., I want to ... so that ...
      value: "## As a ..., I want to ... so that ..."
    validations:
      required: false
  - type: checkboxes
    id: platform
    attributes:
      label: Platform
      multiple: true
      options:
        - Server
        - Web
        - Desktop App
        - Android App
        - iOS App
      default: 0
    validations:
      required: false
 

---


