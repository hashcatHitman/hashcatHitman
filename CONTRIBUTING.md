<!--
SPDX-FileCopyrightText: Copyright © 2025 hashcatHitman

SPDX-License-Identifier: Apache-2.0 OR MIT
-->

# Contribution Guidelines

Thanks for your interest in contributing to the project! These guidelines are
meant to help you contribute effectively, and you are encouraged to read and
follow them!

## AI Policy

This project is made by humans for humans. All use of artificial intelligence
(AI), large-language models (LLMs), or similar techniques is forbidden. This
includes but is not limited to the use of "ChatGPT", "Copilot", "Claude", and
other models.

This applies to **all** contributions. This includes but is not limited to issue
reports, security reports, feature requests, pull requests, translations, commit
messages, comments, audio, videos, images, and ideas. A poorly-made logo made by
an amateur/non artist is preferable to an AI-generated image 100% of the time.

If you are physically impaired and use these tools to assist with the reading
and/or writing of contributions, you should take steps to ensure that no part of
your contributions are changed from your original thoughts. Traditional screen
readers, Text-To-Speech (TTS) tools, and Speech-To-Text (STT) tools will likely
provide better assurance of this.

If you don't understand something, please ask others to explain it to you and/or
research it by hand. A good place to start would be the "Discussions" tab.

I can't really forbid the use of the contents of this repository in the training
of AI/LLMs, as that currently isn't compatible with being "open source". That
said:

**Pretty please don't train AI on this project or the surrounding discussions
(issues, pull requests, comments, etc.).**

## Reporting Issues and Requesting Features

To report issues or request features, use the "Issues" tab. Do NOT report
security issues there - please see [our Security Policy] for that instead.

## Commits

### Atomicity

It is preferred that individual commits are atomic; they should be small and
each individual commit should be capable of passing CI (and ideally, actually
work - at least as well as it did beforehand). This is not a strict requirement
for commits that are part of a pull request, but the pull request as a whole
must pass CI and should, ideally, break nothing.

### Linear History and Rebasing

This repository enforces linear commit history. Please ensure your development
branch is up to date before attempting to make any changes, and rebase onto main
before pushing commits.

### Commit Signing

This repository enforces commit signing. You should have a signing key
configured for your account - SSH is preferred. You can learn more about how to
do that in the [GitHub docs].

### Commit Messages

It is good practice to follow the 50/72 rule for commit messages. The first line
should be 50 characters, and the following description 72 characters per line.

If you need to use more than 50 characters on the first line, don't lose your
mind trying to make 50 characters work. Just try to keep it reasonable.

If you're familiar with [Conventional Commits], the suggestions made there are
typically welcome as well.

An example commit message might look like:

```text
fix: Remove needless panic

For some reason there was a `panic!()` hidden in one of the builders
that was causing crashes. That's gone now.
```

Above all else, your commit message should be descriptive and explain what has
changed.

## Licensing

<!-- Adapted from Arti's README -->

This code is licensed under either of

- Apache License, Version 2.0
- MIT license

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

Additionally, this project attempts to be compliant with [version 3.3 of the
REUSE Specification]. Please make sure it stays that way!

[our Security Policy]: ./SECURITY.md
[GitHub docs]: https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification#ssh-commit-signature-verification
[Conventional Commits]: https://www.conventionalcommits.org
[version 3.3 of the REUSE Specification]: https://reuse.software/spec-3.3/
