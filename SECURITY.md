# Security policy

## Reporting a vulnerability

**Do not open a public issue for a security problem.**

Report it privately through GitHub: go to the affected repository, open the **Security** tab,
and choose **Report a vulnerability**. That opens a private advisory visible only to the
maintainers.

Please include what an attacker can do, the steps to reproduce it, and the affected version.
A proof of concept helps; a working exploit is not required.

## What to expect

- Acknowledgement of the report.
- An assessment of whether it is exploitable, and in what configuration.
- A fix released before public disclosure, with credit to you unless you prefer otherwise.

## Scope

These repositories are developer tooling: they run inside your build, on code you already
control. The findings we care most about are ones that let repository content escalate into
code execution, credential exposure, or a silently passing check that should have failed.
