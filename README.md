# Advancement Battle downloads

Public downloads for Advancement Battle, a competitive Minecraft client. The source code is maintained separately in a private repository.

## Install with Prism Launcher

1. Install [Prism Launcher](https://prismlauncher.org/download/) and add your Minecraft account.
2. Open [Releases](https://github.com/AdvancementAuction/client-releases/releases) and download `advancement-battle.mrpack` from the desired release.
3. In Prism, choose **Add Instance → Import**, select the downloaded file, and launch it. Use Java 25 for the current pack.

The optional `advancement-battle-prism.zip` is a native Prism import of the same client and mods.

The client includes a small refresh icon near its version number. When the server's update service is enabled, it can close Minecraft, synchronize the approved client/mods, and reopen the same Prism instance. No separate updater installation or GitHub account is needed. Other launchers can import the pack for manual updates.

**Current status:** releases marked as prereleases are installation/update test builds. The production version-policy endpoint has not been enabled yet; public availability of downloads does not imply that online play or automatic updates are ready for general use.

## Release files

- `advancement-battle.mrpack`: normal player installation.
- `advancement-battle-prism.zip`: optional native Prism import.
- `advancement-battles.jar`: client downloaded by the updater.
- `release.json`: exact client/mod versions, download URLs, sizes, and hashes.
- `policy.json`: candidate server update policy; publication does not activate it.
- `SHA256SUMS`: SHA-256 checksums of the attached files.

Use the attached pack files to install. GitHub's automatically generated source archives contain only this distribution repository, not the game client.
