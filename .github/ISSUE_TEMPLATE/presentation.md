---
name: Presentation
about: Issue to represent a presentation
title: "[Presentation Title]"
labels: ''
assignees:
body:
  - type: markdown
    attributes:
      value: |
        Thanks for considering giving a presentation!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you?
      placeholder: ex. email@example.com, discord handle
    validations:
      required: false
  - type: textarea
    id: presentation-details
    attributes:
      label: Idea
      description: Please provide your idea!
    validations:
      required: true
---

**Title**: [Presentation Title]

**Description**:
[Description]
