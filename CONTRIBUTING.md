# Contributing

Thank you for taking the time. i18next is installed tens of millions of times a week, so every change is code we keep,
test and secure for a long time, and every release reaches all of those projects. That is why we are picky.

## Issue first

Please open an issue before a pull request. When a maintainer confirms in the issue that we take it (the issue gets the
`confirmed` label), a pull request is welcome. A pull request without a confirmed issue is closed with thanks, without
a review. Except:

- security reports: privately, see [SECURITY.md](SECURITY.md), never in a public issue or pull request
- a regression: a pull request that names the version that broke it may come right away
- typo and documentation fixes

## What we merge

- a fix for a problem a real app hit: an issue with a reproduction that names the app or setup
- a regression: something that worked in an earlier version
- a security fix (report it privately first, see [SECURITY.md](SECURITY.md))
- a change that makes the code simpler: it removes more than it adds

A fix for a case nobody hit, a new option or a new module is usually closed with thanks. A backend, language detector,
post-processor or formatter of your own takes your coding agent a few minutes against the
[plugin interfaces](https://www.i18next.com/principles/plugins), and it can live in your own repository.

## Releases

Fixes are released together, usually once a week. Security fixes and regressions are released at once.

## Documentation

The documentation of i18next, react-i18next, next-i18next and i18next-cli lives in
[i18next/www](https://github.com/i18next/www).

## AI-assisted contributions

Welcome, with the same bar as any other: say so in the issue and the pull request, read the diff yourself and run the
tests. An agent can open a pull request in minutes; that is why the issue comes first.

## Developer's Certificate of Origin

By making a contribution to this project, I certify that:

- (a) The contribution was created in whole or in part by me and I have the
  right to submit it under the open source license indicated in the file; or

- (b) The contribution is based upon previous work that, to the best of my
  knowledge, is covered under an appropriate open source license and I have the
  right under that license to submit that work with modifications, whether
  created in whole or in part by me, under the same open source license (unless
  I am permitted to submit under a different license), as indicated in the file;
  or

- (c) The contribution was provided directly to me by some other person who
  certified (a), (b) or (c) and I have not modified it.

- (d) I understand and agree that this project and the contribution are public
  and that a record of the contribution (including all personal information I
  submit with it, including my sign-off) is maintained indefinitely and may be
  redistributed consistent with this project or the open source license(s)
  involved.
