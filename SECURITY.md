# Security Policy

This policy covers every repository in the BlockStormHU organization and the services the BlockStorm team runs.

## Reporting a vulnerability

**Please do not report security problems in public issues, pull requests or discussions.** Report them privately:

- **Public repository:** open the repository's **Security** tab and click **Report a vulnerability**.
- **Anything else** (a private repository, a service we run, or if you are not sure where it belongs): use
  **https://github.com/BlockStormHU/.github/security/advisories/new**

Only you and the organization's maintainers can see the report. It helps a lot if you include:

- the affected repository, version or commit, or the affected address;
- steps to reproduce (a request, a command, a code snippet or a proof of concept);
- what an attacker could do with it;
- a suggested fix, if you have one.

We will confirm that we received your report, keep you informed while we work on it, and credit you in the advisory
once the fix is released, if you want to be credited.

## Supported versions

Security fixes go into the default branch of the repository and are shipped in a new release. Only the latest
release gets fixes; older releases are not patched.

## Forks of other projects

Repositories whose names end in `-fork` are BlockStorm's forks of other open-source projects. If the problem is also
in the original project, please report it to that project as well, following its own security policy. If you
report it only to us, we will pass it on to the original project.

## Please

- Only access, change or delete your own data; use your own accounts for testing.
- Do not run denial-of-service or load tests, and do not attempt social engineering or phishing.
- Give us reasonable time to fix the problem before you share any details publicly.
