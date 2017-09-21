# GitLab: Responsible Disclosure Policy 

* Contact: security@gitlab.com
* Website: https://about.gitlab.com/disclosure/
* Verified: 2017-09-21

Please email security@gitlab.com to report any security vulnerabilities. We will acknowledge receipt of your vulnerability report the next business day and strive to send you regular updates about our progress. If you're curious about the status of your disclosure please feel free to email us again. If you want to encrypt your disclosure email please email us to ask for our <a href="http://pgp.mit.edu/pks/lookup?op=get&amp;search=0xD1749DE8E13BA89D">PGP key</a>.

Alternatively you may also send us your report via <a href="https://hackerone.com/gitlab">HackerOne</a>.

Please refrain from requesting compensation for reporting vulnerabilities. If you want we will <a href="https://about.gitlab.com/vulnerability-acknowledgements/">publicly acknowledge</a> your responsible disclosure. We also try to make the confidential issue public after the vulnerability is announced, for an example see our <a href="https://gitlab.com/gitlab-org/gitlab-ce/issues/15548">impersonation feature issue</a>. HackerOne also makes the bug reports <a href="https://hackerone.com/disclosure-guidelines">public after 30 days</a> if neither party objects, for an example see <a href="https://hackerone.com/reports/129736">the report for a persistent XSS on public project page</a>.

You are not allowed to search for vulnerabilities on GitLab.com itself. GitLab is open source software, you can install a copy yourself and test against that. You can either download <a href="https://about.gitlab.com/downloads/">CE</a>, <a href="https://about.gitlab.com/downloads-ee/">EE</a>, or the <a href="https://gitlab.com/gitlab-org/gitlab-development-kit">GitLab Development Kit</a>. If you want to perform testing without setting GitLab up yourself please contact us to arrange access to a staging server.

You can find more details on how we handle <a href="https://gitlab.com/gitlab-org/release-tools/blob/master/doc/security.md">security releases here</a>.

On our website you can find more about <a href="https://about.gitlab.com/gitlab-com/#availability-and-security">the availability and security of GitLab.com</a>. Security issues that are not vulnerabilities can be seen on <a href="https://gitlab.com/gitlab-org/gitlab-ce/issues?label_name%5B%5D=security">our public issue tracker</a>.</p> <h2 id="confidential-issues">Confidential issues</h2> <p>When a vulnerability is discovered we create a <a href="https://docs.gitlab.com/ce/user/project/issues/confidential_issues.html">confidential issue</a> to track it internally. Security patches are pushed to <a href="https://dev.gitlab.org">dev.gitlab.org</a>, which is not publicly accessible, and merged into the <code>security</code> branch. They should not appear on <a href="https://gitlab.com">GitLab.com</a> until the security release has been announced and updated packages are available.

Details can be found in our <a href="https://about.gitlab.com/handbook/engineering/critical-release-process/">critical release process</a>.
