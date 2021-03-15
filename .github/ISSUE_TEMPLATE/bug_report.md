---
name: Bug report
about: Report a bug in this project
title: ''
labels: kind/bug, triage/pending
---

<!--
Please note:
============

We use github issues to track and triage already identified bugs in the code.
This provides a way for developers of the community to notify us of unexpected behavior of the code. We expect community members which report bugs through Github to be able to compile the source code and test the produced binary.

If you are not a developer, and you are having trouble identifying, isolating, or reproducing an issue, please reach out to our support team, which is better equipped to help you in that regard:
Visit https://support.newrelic.com/
-->

**Reporter checklist**
- [ ] I am able to reproduce the bug with the latest version of the integration
- [ ] I am able to reproduce the bug with the latest version of the [infrastructure agent](https://github.com/newrelic/infrastructure-agent)
- [ ] I am able to trace the root cause of the problem to the code hosted in this repository
  + Need help troubleshooting/isolating the problem? [Our support team is here to help!](https://support.newrelic.com/)

### Bug description
A clear and concise description of what the bug is.

#### Expected behavior
A clear and concise description of what you expected to happen, and why.

### To Reproduce
Describe the simplest environment where this behavior can be observed.

#### Configuration

```yaml
  replace this: with the configuration being used for the integration
  as well as:
    - Agent configuration files, if relevant
    - Configuration files for monitored services, if relevant
```

#### Versions used
- OS: [e.g. Ubuntu 20.04]
- Integration: (e.g. 1.3.4)
- Service version: (e.g. `MySQL 10.1.29-MariaDB`)

### Additional context
Add any other context about the problem here.
