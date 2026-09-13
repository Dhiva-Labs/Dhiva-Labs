# Support — DhivaLabs Shell

DhivaLabs Shell is a Bash-based developer terminal for Windows with separate Git and SSH profiles.

## Contact

- General and privacy support: [reachout@dhivalabs.com](mailto:reachout@dhivalabs.com)
- Public bug reports and feature requests: <https://github.com/Dhiva-Labs/Dhiva-Labs/issues/new>
- Publisher: [Dhiva-Labs](https://github.com/Dhiva-Labs)

Do not attach private SSH keys, passwords, access tokens, recovery codes, repository secrets, or confidential terminal output. Security issues should be emailed privately rather than posted publicly.

## Information to include

For faster troubleshooting, include:

- the DhivaLabs Shell version shown in the app;
- the Windows edition, version, and system architecture;
- whether the app came from Microsoft Store or a direct package;
- the exact error message with secrets removed;
- steps that reproduce the problem; and
- a screenshot if it contains no confidential information.

## Basic troubleshooting

### Terminal does not open

Restart the app and try **Local terminal** first. Local terminal does not require a GitHub account, Git identity, or SSH key. If the bundled runtime is reported missing, reinstall the complete package from its official distribution source.

### GitHub authentication fails

Confirm that the profile points to the intended private key, copy its public key from the app, and add that public key to the matching GitHub account. Never paste the private key into GitHub or a support request.

### A repository is blocked by the identity guard

Open the repository with the intended profile and use the repository inspection/configuration action. Review the proposed Git author, email, SSH alias, and remote before applying it.

### Commands behave differently from Linux

DhivaLabs Shell supplies Bash and common Unix utilities on Windows. It is not a Linux kernel or WSL distribution. Native Linux ELF binaries, `systemd`, and Linux-only kernel features require WSL or another Linux environment.

## Removing local data

Removing a profile from inside the app does not delete its SSH keys, history, or repositories. This is intentional protection against accidental data loss.

For a complete cleanup:

1. remove any public SSH key created for the app from the associated GitHub account;
2. uninstall DhivaLabs Shell from **Windows Settings > Apps > Installed apps**;
3. delete retained DhivaLabs Shell application data if it remains;
4. delete generated private/public key files that are no longer needed; and
5. remove repository folders separately only if their contents are no longer required.

Back up important repositories and keys before deleting anything.

## Privacy

Read the [DhivaLabs Shell privacy policy](privacy-policy.md).
