# Privacy Policy — DhivaLabs Shell

**Effective date:** 14 September 2026  
**Applies to:** DhivaLabs Shell for Windows, published by Dhiva-Labs.

## Summary

DhivaLabs Shell does not include advertising, analytics, telemetry, crash reporting, user accounts, or a Dhiva-Labs cloud service. Profile settings, terminal history, Git configuration, and SSH material are stored locally on the user's Windows device.

DhivaLabs Shell is a terminal. Commands started by the user can read local files, launch programs, and communicate with services such as GitHub. Data handled by those commands is sent to the destination selected by the user, not to Dhiva-Labs.

## Who is responsible

Dhiva-Labs is an independent software laboratory based in Chennai, India and operated by Dhivakar Rajaram.

- Email: [reachout@dhivalabs.com](mailto:reachout@dhivalabs.com)
- GitHub: <https://github.com/Dhiva-Labs>

## Information DhivaLabs Shell stores locally

Depending on the features used, the app can store:

- profile names and colours;
- Git author names and email addresses;
- optional GitHub usernames;
- workspace folder paths;
- SSH host aliases and private-key file paths;
- generated Ed25519 private and public SSH keys;
- SSH configuration and trusted GitHub host keys;
- isolated Git configuration and Bash terminal history;
- a backup of the preceding profile configuration when profiles are changed; and
- per-repository Git configuration written when the user asks the app to bind a repository to a profile.

This information is used to provide separate terminal, Git, and SSH environments for work and personal profiles. The app does not transmit it to Dhiva-Labs.

## SSH keys and credentials

When the user selects **Generate an Ed25519 key**, DhivaLabs Shell runs its bundled `ssh-keygen` locally. The current version generates that key without a passphrase. The private key is therefore not encrypted with a passphrase and should be protected using the user's Windows account, device encryption, and normal file permissions.

The private key remains on the device. The app shows the corresponding public key so the user can choose to add it to GitHub. DhivaLabs Shell does not add the key to GitHub automatically and does not receive it.

Users may instead select an existing private-key file. DhivaLabs Shell stores the path to that file; it does not copy the key into a Dhiva-Labs service.

## Network activity

DhivaLabs Shell has no application telemetry or Dhiva-Labs backend. Network activity can occur when the user runs a command or uses a Git/SSH feature, including:

- cloning, fetching, pulling, or pushing a Git repository;
- connecting to GitHub or another user-selected host with SSH;
- running tools such as `curl`, package managers, scripts, or other programs that access the network; and
- opening or running a third-party program from the terminal.

Those connections are governed by the privacy terms of the selected destination or program. Dhiva-Labs cannot see or control data sent by user-run commands.

Microsoft may process Store installation, licensing, update, reliability, or diagnostic information under Microsoft's own terms. DhivaLabs Shell does not receive that information directly from the app.

## Access to the device

Commands launched from DhivaLabs Shell run with the permissions of the Windows user. They may access files, processes, network resources, and installed programs that the user's Windows account is permitted to access. Users should review commands and scripts before running them.

The Microsoft Store edition is intended to run without administrator elevation. DhivaLabs Shell does not disable or bypass Windows security controls.

## Data retention and deletion

Local data remains on the device until the user removes it or Windows removes the app's data.

Removing a profile from inside the app removes it from the profile list, but deliberately retains its terminal history, SSH keys, and repositories to avoid destructive data loss. Repository files and Git configuration also remain in their existing workspace folders.

To remove all related data, users should:

1. remove profiles in the app if desired;
2. uninstall DhivaLabs Shell from Windows Settings;
3. delete any retained DhivaLabs Shell application-data folder, if present;
4. delete generated SSH keys that are no longer needed;
5. remove the corresponding public keys from GitHub or other services; and
6. delete repositories or repository-specific Git configuration separately if desired.

Specific removal help is available on the [support page](support.md).

## Information provided when contacting Dhiva-Labs

When a user emails Dhiva-Labs or opens a GitHub issue, Dhiva-Labs receives the information the user chooses to include, together with information supplied by the email or GitHub service. It is used to respond, investigate the request, and maintain necessary correspondence. Users should not include private SSH keys, access tokens, passwords, repository secrets, or confidential terminal output in a support request.

## Sharing and sale of information

DhivaLabs Shell does not sell personal information. Because the app has no Dhiva-Labs data-collection service, it does not share app usage or profile information with advertisers or data brokers.

User-directed commands can share information with their selected destinations. Dhiva-Labs does not control those transfers.

## Children

DhivaLabs Shell is a developer tool and is not directed to children under 13. The app does not knowingly collect personal information from children.

## Security

DhivaLabs Shell separates managed profiles and uses strict SSH host-key checking for its managed GitHub configuration. These safeguards help prevent accidental identity mixing; they are not an operating-system security boundary. No software can guarantee absolute security.

Security concerns may be reported privately to [reachout@dhivalabs.com](mailto:reachout@dhivalabs.com). Do not publish credentials or exploitable security details in a public issue.

## Changes to this policy

Updates will be published at this address and the effective date will be changed. Material changes affecting data handling will be described with the relevant application update.

## Contact

Questions and privacy requests: [reachout@dhivalabs.com](mailto:reachout@dhivalabs.com)
