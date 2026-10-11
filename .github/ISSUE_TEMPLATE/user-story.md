---
name: User Story
about: Template for creating user stories
title: 'Add a navigation bar'
labels: enhancement
assignees: ''

---

## User Story

**As a** user,  
**I need** a navigation bar to access different sections of the application,  
**So that** I can navigate the application easily.

## Details and Assumptions

- The navigation bar should be visible at the top of the dashboard.
- It should contain links to the Home and Dashboard pages.
- The navigation bar should be easy to use.

## Acceptance Criteria

```gherkin
Given I am on the application dashboard
When I click the Home link in the navigation bar
Then I should be redirected to the Home page

Given I am on any page of the application
When I view the navigation bar
Then I should see links to the Home and Dashboard pages
```
