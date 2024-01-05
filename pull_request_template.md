## Linked Issue:
- **[jira-ticket-id](<link-to-jira-ticket>)**

## Linked PRs: (if any)
- **[Description of relation to other PR (or remove section)](<link to PR>)**

## Pre-review Checklist
Make sure all these are true before requesting review
- All code changes covered by unit tests? Yes [ ] | No [ ]
- All unit tests passing? Yes [ ] | No [ ]
- No new rubocop warnings? Yes [ ] | No [ ]
- All relevant documentation updated? Yes [ ] | No [ ]
- All changes QA'd locally? Yes [ ] | No [ ]
- PR Description filled in fully and all items considered? Yes [ ] | No [ ]

## Documentation:
If the answer to any of these is yes please provide links to documentation below details below.
- Includes new endpoint / changes to request params, required permissions, or serialized responses? Yes [ ] | No [ ]
- Includes changes to user frontend? Yes [ ] | No [ ]
- Includes changes/new core business logic that would be useful for the user to understand? Yes [ ] | No [ ]

- **(insert link to documentation or remove bullet point if none)**
- **(insert link to documentation or remove bullet point if none)**

## User Story / Stories
Describe who will be affected by changes in this PR and what value it brings to them. See examples [here](https://www.atlassian.com/agile/project-management/user-stories).
- **As a <persona>, I [want to], [so that]**
- **As a <persona>, I [want to], [so that]**

## Reason for Changes / Problem Description
Short description(s) of the reason(s) behind the work and/or the problem(s) we're trying to solve. Ensure that all changes the PR introduces are covered and not just those described in the ticket. This is to help our future selves understand the intent of the code.
- **(insert short description here)**
- **(insert short description here)**

## Description of Changes
Short description(s) of the technical changes in the PR. This is to help the reviewer (and our future selves) understand at a high-level what was changed in this PR. This should cover all code changes.
- **(insert short description here)**
- **(insert short description here)**

## Deployment Impacts
If the answer to any of these is yes please provide more details below.
- Are database migrations required? Yes [ ] | No [ ]
- Are data migrations required? Yes [ ] | No [ ]
- Are permissions affected? Yes [ ] | No [ ]
- Are serializer affected in a breaking way? Yes [ ] | No [ ]
- Might changes affect lots of different places? Yes [ ] | No [ ]
- Might changes break existing contracts with other Edgescan services? Yes [ ] | No [ ]

- **(Insert deployment impact detail or remove bullet point if none)**
- **(Insert deployment impact detail or remove bullet point if none)**

## Security Impacts
If the answer to any of these is yes please provide more details below.
- Might users gain access to unauthorized data (admin-only, other orgs, etc.)? Yes [ ] | No [ ]
- Might changes cause issues with heirarchical organizations and permissions? Yes [ ] | No [ ]
- Do these changes affect critical functionality? Yes [ ] | No [ ]
- Is RAW SQL being used? Yes [ ] | No [ ]
- Are we invoking any shell or OS commands in code? Yes [ ] | No [ ]
- Does it add additional functionality where users can input data that may be susceptable to SQL injection (i.e. filters, text inputs, etc.)? Yes [ ] | No [ ]
- Might changes permit a Denial of Service attack from users/Edgescan services?
- Are any new dependencies being added with active NPM/bundle audit or security issues? Yes [ ] | No [ ]

- **(Insert security impact detail or remove bullet point if none)**
- **(Insert security impact detail or remove bullet point if none)**
