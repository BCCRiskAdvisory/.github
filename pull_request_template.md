## Linked Issue:
- **[jira-ticket-id](<link-to-jira-ticket>)**

## Linked PRs: (if any)
- **[Description of relation to other PR (or remove section)](<link to PR>)**

## Pre-review Checklist
> <i>Make sure all these are true before requesting review.</i>
- [ ] All code changes covered by unit tests?
- [ ] All unit tests passing?
- [ ] No new rubocop/eslint warnings?
- [ ] All relevant documentation updated?
- [ ] All changes QA'd locally?
- [ ] Any FE changes QA'd at both min and max resolution?
- [ ] PR Description filled in fully and all items considered?

## Documentation:
> <i>If the answer to any of these is yes please provide links to documentation below details below.</i>
- [ ] Includes new endpoint / changes to request params, required permissions, or serialized responses?
- [ ] Includes changes to user frontend?
- [ ] Includes changes/new core business logic that would be useful for the user to understand?
<!-- (Don't Delete) Location Marker for Citrine Parsing: documentation section start -->
- **(insert link to documentation or remove bullet point if none)**
- **(insert link to documentation or remove bullet point if none)**
<!-- (Don't Delete) Location Marker for Citrine Parsing: documentation section end -->

## User Story / Stories
> <i>Describe who will be affected by changes in this PR and what value it brings to them. See examples [here](https://www.atlassian.com/agile/project-management/user-stories).</i>
- **As a <persona>, I [want to], [so that]**
- **As a <persona>, I [want to], [so that]**

## Reason for Changes / Problem Description
> <i>Short description(s) of the reason(s) behind the work and/or the problem(s) we're trying to solve. Ensure that all changes the PR introduces are covered and not just those described in the ticket. This is to help our future selves understand the intent of the code.</i>
<!-- (Don't Delete) Location Marker for Citrine Parsing: problem description start -->
- **(insert short description here)**

<!-- (Don't Delete) Location Marker for Citrine Parsing: problem description end -->
## Description of Changes
> <i>Short description(s) of the technical changes in the PR. This is to help the reviewer (and our future selves) understand at a high-level what was changed in this PR. This should cover all code changes.</i>
- **(insert short description here)**
- **(insert short description here)**

## Deployment Impacts
> <i>If the answer to any of these is yes please provide more details below.</i>
- [ ] Are database migrations required?
- [ ] Are data migrations required?
- [ ] Are permissions affected?
- [ ] Are serializer affected in a breaking way?
- [ ] Might changes affect lots of different places?
- [ ] Might changes break existing contracts with other Edgescan services?
<!-- (Don't Delete) Location Marker for Citrine Parsing: deployment impact start -->
- **(Insert deployment impact detail or remove bullet point if none)**
- **(Insert deployment impact detail or remove bullet point if none)**

<!-- (Don't Delete) Location Marker for Citrine Parsing: deployment impact end -->
## Security Impacts
> <i>If the answer to any of these is yes please provide more details below.</i>
- [ ] Might users gain access to unauthorized data (admin-only, other orgs, etc.)?
- [ ] Might changes cause issues with hierarchical organizations and permissions?
- [ ] Do these changes affect critical functionality?
- [ ] Is RAW SQL being used?
- [ ] Are we invoking any shell or OS commands in code?
- [ ] Does it add additional functionality where users can input data that may be susceptible to SQL injection (i.e. filters, text inputs, etc.)?
- [ ] Might changes permit a Denial of Service attack from users/Edgescan services?
- [ ] Are any new dependencies being added with active NPM/bundle audit or security issues?
<!-- (Don't Delete) Location Marker for Citrine Parsing: security impact start -->
- **(Insert security impact detail or remove bullet point if none)**
- **(Insert security impact detail or remove bullet point if none)**
<!-- (Don't Delete) Location Marker for Citrine Parsing: security impact end -->
