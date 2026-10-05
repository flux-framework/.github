### Security Policy

#### Reporting a vulnerability

Please do not report security issues in GitHub issues, pull requests, or
discussions.  Instead, use GitHub's private vulnerability reporting:
go to the _Security_ tab of the affected repository and click _Report a
Vulnerability_.  If you are unsure which repository is affected, or if
private vulnerability reporting is not enabled on the affected repo,
report it against `flux-core` and we will move it if needed.

If you are not sure whether something is a security issue, report it privately
anyway.  We would rather triage a non-issue than have a real problem
discussed in public.

#### Helpful information to include

- Affected repository and version (or commit)
- Description of the issue and its potential impact
- Steps to reproduce, or a proof of concept if you have one
- Any relevant configuration, for example multi-user vs single-user instance,
  IMP configuration

#### Scope

Issues in components that run with elevated privilege or enforce isolation
between users are of particular interest, including flux-security (the IMP
and signing), flux-pam, and the flux-core broker, connectors, and job
execution paths in a multi-user instance.

Hardening or defense-in-depth issues with no plausible attack path may be
handled publicly at the maintainers' discretion.

#### Supported versions

Security fixes are made against the latest release of each project.
Back-ports to older releases are considered case by case.

#### What to expect

We aim to acknowledge reports within five business days and will keep you
informed as we investigate.  We will coordinate disclosure timing with you
and are happy to credit reporters in the published advisory unless you prefer
to remain anonymous.
