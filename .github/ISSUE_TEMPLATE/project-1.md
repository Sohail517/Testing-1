---
name: Project 1
about: To add work flow
title: ''
labels: enhancement, good first issue
assignees: Sohail517

---

name: File Upload Request
description: Upload file based on country and region
title: "[Upload]"
labels: ["upload-request"]
body:
  - type: dropdown
    id: country
    attributes:
      label: Select Country
      options:
        - India
        - USA
        - UK
    validations:
      required: true

  - type: dropdown
    id: region
    attributes:
      label: Select Region
      options:
        - North
        - South
        - East
        - West
    validations:
      required: true

  - type: input
    id: username
    attributes:
      label: Your GitHub Username
      placeholder: octocat
    validations:
      required: true

  - type: textarea
    id: file
    attributes:
      label: File URL
      description: Provide a downloadable link to the file
    validations:
      required: true
