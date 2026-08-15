# Contributing to ShadyUI

Thank you for helping us build trustworthy software for untrustworthy-looking interfaces.

## Before opening a pull request

1. Search existing issues and discussions.
2. Open an issue for substantial API, behavior, or architecture changes.
3. Keep changes focused and add tests for new behavior.
4. Run the repository's `npm run ci` command locally.
5. Explain both the user-facing effect and the implementation tradeoffs in the pull request.

All changes to `main` go through a pull request, passing CI, and one approving review.

## Safety

ShadyUI parodies deceptive interfaces; it must not facilitate credential harvesting, impersonation, malware delivery, unwanted navigation, or other harmful behavior. Components should look shady and behave responsibly.
