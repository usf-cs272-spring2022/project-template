---
name: Request Project Review Grade
about: Used to request a "Project Review" grade.
title: Request Review Grade v0.0.0
labels: grade-review
assignees: ''

---

**INSTRUCTIONS**: In the issue title, replace `v0.0.0` in the issue title with the release you want graded. In the issue body, replace `FULL_NAME` with your first and last name, and replace `USF_USERNAME` with your USF username (*not* your Github username). Make sure to keep the `"` double quotes as-is (do not delete them). Open the issue and wait for Github Actions to respond with further instructions.

```json
{
  "name": "FULL_NAME",
  "username": "USF_USERNAME"
}
```
