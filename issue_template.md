name: Issue
description: Report a new issue
title: Issue
assignees:
  - XiMatriarx
body:
  - type: textarea
    id: issue
    attributes:
      label: What is the issue?
      description: Describe your issue in as much detail as possible.  
    validations:
      required: true
  - type: textarea
    id: info
    attributes:
      label: Do you have any additional information?
      description: Provide any code, errors or logs you have.  
    validations:
      required: true
