name: "Suggest an edit"
description: "Suggest an edit for the AI-generated description and tags"
title: "[Edit project's metadata]: "
labels: ["enhancement"]
assignees: []
body:
- type: input
  id: url
  attributes:
  label: "Project URL"
  description: "Link to the project's page from klibs.io:"
  validations:
  required: true

- type: input
  id: description
  attributes:
  label: "Description"
  description: "Suggested description for the project"

- type: input
  id: tags
  attributes:
  label: "Tags"
  description: "Suggested tags for the project."