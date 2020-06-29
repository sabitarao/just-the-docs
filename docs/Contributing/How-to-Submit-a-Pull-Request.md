---
layout: default
title: Pull request procedure
parent: Contributing
---
# Pull request procedure
## For contributors
1. Ensure that your code meets the [coding style guidelines](https://github.com/moja-global/About-moja-global/blob/master/Governance/Coding-Guidelines.md) 
1. Perform relevant [Tests] for the repository that you are submitting the pull-request for
1. ...go through steps of pull-request
1. Include in the comments section the tests that you have completed and if they were a pass or fail

## For Maintainers

# Standard tests

Testing needs to be performed by both developers and maintainers for new or modified code. Developers are expected to perform standardise tests before submitting the pull-request, and maintainers conduct testing when going through the process of assessing a pull-request.
Tests suites should be included in the repositories of existing code, and test suites should be developed for new repositories where tests do not already exist.
The standardised test suites are expected to be completed for all pull-requests. A standardised test suite should include:
1. Unit tests
1. Integration tests
1. System tests

System tests include performance tests, including guidelines on speed performance to ensure that any new features or bug fixes do not compromise system performance. These tests need to be performed by the contributor and will also be executed by the maintainer and may result in non-acceptance of the pull-request if performance is adversley affected.

Acceptance testing, is the final step in testing and should be conducted for final acceptance of the pull-request. At present, community of contributors to moja repositories is relatively small and a detailed framework for acceptance is not required. As the community grows, this will be reviewed and a more hierarchical sturucture may be necessary to ensure that new features fit within the strategic priorities of moja before they are accepted into the Master Branch. 
