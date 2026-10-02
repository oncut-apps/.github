# Security policy

oncut apps run close to what people type, so we take security reports
seriously and would rather hear about a problem early than late.

## Reporting a problem

Please report it privately, not in a public issue:

- through GitHub's **Report a vulnerability** button on the repository's
  Security tab, or
- by email to support@oncut.gr, with "Security" in the subject.

Tell us which app and version, what the problem is, and how to reproduce it. We
will confirm that we received it, keep you informed while we work on a fix, and
credit you in the release notes if you wish.

## Which versions

We fix security problems in the latest release of each app. Updates are never
installed automatically: our apps make no network connections of their own, so
a fixed version reaches you only when you download it from
<https://apps.oncut.gr> or the app's GitHub releases.

## Checking a download

Windows installers are signed by oncut (Authenticode). Every release also
carries `SHA256SUMS` and its minisign signature `SHA256SUMS.minisig`; the
public key and the steps are at <https://apps.oncut.gr/keys> (key id
`3AA1B9E2CD1C2AE8`).
