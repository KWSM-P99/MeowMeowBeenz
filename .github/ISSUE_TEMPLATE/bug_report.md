---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
    
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com, discord id, etc
    validations:
      required: false
    
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
    
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
