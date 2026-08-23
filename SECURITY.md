# Security Policy

## Supported versions

Security fixes should target the latest release and the default branch.

## Reporting a vulnerability

Do not disclose suspected vulnerabilities in a public issue. Use GitHub's
**Security** tab and **Report a vulnerability** when private vulnerability
reporting is available, or contact the upstream maintainer privately through a
verified channel.

Include the affected version, coding agent and platform, reproduction steps,
impact, and a minimal proof of concept in a disposable repository.

Never include real credentials, private source code, personal data, or
unredacted agent transcripts. Revoke any credential that may have been exposed.

## Sensitive areas

Treat skill and instruction files as executable supply-chain inputs. Changes
that can cause an agent to execute commands, modify files, access networks,
read credentials, weaken approval boundaries, or load third-party content
require additional review.

Test in an isolated repository, use least-privilege credentials, review diffs
before committing, and never allow untrusted repository content to override
higher-priority safety or authorization instructions.
