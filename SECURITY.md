# Security policy

[한국어](docs/SECURITY.ko.md)

## Reporting a problem

Please don't open a public issue for security or privacy problems. Report them privately so a fix can ship before the details are public:

- **[Report a vulnerability](https://github.com/Jeon0976/docnest-feedback/security/advisories/new)** here on GitHub. Only you and the maintainer can see it.
- Or email **hello@sanmarustudio.com** with "Security" in the subject.

Tell us your Docnest version (Settings → About), your macOS version and what you saw. Steps or a proof of concept help, but they aren't required. Please don't send real document contents or credentials. A description is enough.

## What counts

Anything that could let data leak or change when it shouldn't. For example:

- Document contents, conversations or session details leaving your Mac
- Docnest reading files outside what it says it collects, such as credential folders
- HTML previews running scripts or reaching the network
- Changes to an AI tool's settings beyond Docnest's own entries
- License or update checks that could be abused

## After you report

We'll reply in the private report or by email. Security fixes only go into the latest release, so if you can, please check that the problem still happens after updating Docnest.
