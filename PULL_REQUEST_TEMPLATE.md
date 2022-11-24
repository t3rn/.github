# Summary of changes

**Summarize** the description of your changes. 

If it fixes a bug or creates a feature, link the issue.

## Acceptance Checklist

What types of changes does your code introduce?
_Put an `x` in the boxes that apply_

- [ ] Bugfix (non-breaking change which fixes an issue):
    - [ ] Have you **written tests **to protect against future occurrences of the bug?
- [ ] New feature (non-breaking change which adds functionality)
    - [ ] Have you **seen it working** in a development environment?
    - [ ] Have you **written tests** for **happy** and **unhappy** paths?
    - [ ] Have you implemented this feature as per the **issue acceptance criteria**?
- [ ] Breaking change (a feature that would cause existing functionality not to work as expected
    - [ ] Is the breaking change **documented**?
    - [ ] Has any previous changes been **deprecated**?
- [ ] CI/CD
    - [ ] If introducing new actions, have you **looked at the action code** for anything spurious?
    - [ ] Have you written **custom scripts** for things that could be actions already on the marketplace?
    - [ ] If introducing new actions, have you **pegged a static version**?
- [ ] Documentation Update
    - [ ] Have you checked other documentation, such as the docs repository?
    - [ ] If updating script documentation, have you **tested it on both environments**?
- [ ] Substrate
    - [ ] RPC methods?
    - [ ] Chainspec, both JSON specs & the module?
    - [ ] Runtime versioning?
    - [ ] Benchmarks?
- [ ] Any dependent changes have been merged and published in downstream modules

## Further comments

Feel free to explain in further detail your choices if this is a significant change.

## Screenshots (if applicable)
