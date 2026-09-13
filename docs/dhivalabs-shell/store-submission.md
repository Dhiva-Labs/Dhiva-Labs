# Microsoft Store information — DhivaLabs Shell

Use these values for the first Microsoft Store submission.

## Identity

| Field | Value |
| --- | --- |
| Product name | DhivaLabs Shell |
| Publisher display name | Dhiva-Labs |
| Package identity name | `Dhiva-Labs.1.DhivaLabsShell` |
| Store ID | `9P4PP04P6GDX` |
| Category | Developer tools |
| Price | Free |

The Package SID is intentionally not published because customers and support pages do not need it.

## URLs

- Privacy policy: <https://github.com/Dhiva-Labs/Dhiva-Labs/blob/main/docs/dhivalabs-shell/privacy-policy.md>
- Support: <https://github.com/Dhiva-Labs/Dhiva-Labs/blob/main/docs/dhivalabs-shell/support.md>
- Website: <https://www.dhivalabs.com/>
- Publisher: <https://github.com/Dhiva-Labs>
- Support email: [reachout@dhivalabs.com](mailto:reachout@dhivalabs.com)

## Short description

> A Bash terminal for Windows with separate work and personal Git and SSH identities.

## Search terms

`bash`, `terminal`, `git`, `github`, `ssh`, `developer`, `command line`, `unix`, `shell`, `git profiles`, `multiple github accounts`

## Certification notes

> DhivaLabs Shell is a user-operated Windows desktop terminal built using Windows ConPTY. It bundles Bash, Git, OpenSSH, and common command-line utilities. Commands and network connections occur only following direct user action.
>
> The application does not install a Windows service, register itself for automatic startup, modify Windows security settings, or collect telemetry. GitHub configuration is optional.
>
> To test without an account, open Local terminal and run `echo hello`, `git --version`, and `ssh -V`. Open a second terminal tab and verify that both sessions accept input.
>
> The Microsoft Store edition does not require administrator elevation. Profile settings, SSH material, terminal history, and Git configuration are stored locally on the device.

## Release gate

Do not submit a package until its manifest contains the reserved identity and publisher values, the Store build has no elevation requirement, third-party licensing is complete, and the package passes the Windows App Certification Kit.
