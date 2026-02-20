# MIRQ Client Release Repository

Official MIRQ desktop release artifacts for **secure chat**, **private messaging**, and **privacy-first collaboration software**.

If you are searching for an encrypted team chat app, secure communication platform, or private collaboration client, this repository provides the distributable files used to deploy MIRQ across supported desktop operating systems.

## Start Here

- Website: [https://mirq.chat](https://mirq.chat)
- Product and updates: [https://mirq.chat](https://mirq.chat)

For most users, the website is the fastest way to get started.  
For admins, packagers, and deployment workflows, use the platform release folders below.

## Release Artifacts

| Platform | Location | Contents |
| --- | --- | --- |
| Windows | [`Windows/`](Windows/) | Setup executables, archives, release metadata |
| Linux | [`Linux/`](Linux/) | `.deb`, `.rpm`, checksum files, release metadata |
| Apple | [`Apple/`](Apple/) | Apple platform release artifacts |

Additional metadata is published through `latest.json`, `version.json`, and upload manifests where applicable.

## Current Release Quick Links

### Windows

- Latest metadata: [`Windows/latest.json`](Windows/latest.json)
- First-time installer (recommended): [`Windows/MIRQ.Chat.msi`](Windows/MIRQ.Chat.msi)
- Current folder (v`1.6.2.2`): [`Windows/1.6.2.2/`](Windows/1.6.2.2/)
- Setup extractor: [`Windows/1.6.2.2/MIRQ-Setup-1.6.2.2.exe`](Windows/1.6.2.2/MIRQ-Setup-1.6.2.2.exe)
- Client package: [`Windows/1.6.2.2/MIRQ-Client-1.6.2.2.7z`](Windows/1.6.2.2/MIRQ-Client-1.6.2.2.7z)

### Linux

- Latest metadata: [`Linux/latest.json`](Linux/latest.json)
- Current folder (v`1.6.2.2`): [`Linux/1.6.2.2/`](Linux/1.6.2.2/)
- Debian package: [`Linux/1.6.2.2/mirq-1.6.2.2-Linux-mirq-client.deb`](Linux/1.6.2.2/mirq-1.6.2.2-Linux-mirq-client.deb)
- RPM package: [`Linux/1.6.2.2/mirq-1.6.2.2-Linux-mirq-client.rpm`](Linux/1.6.2.2/mirq-1.6.2.2-Linux-mirq-client.rpm)
- Checksums: [`Linux/1.6.2.2/SHA256SUMS`](Linux/1.6.2.2/SHA256SUMS)

### Apple

- Platform folder: [`Apple/macOS/`](Apple/macOS/)
- Note: Apple release files are not yet published in this repository snapshot.

## Why MIRQ

MIRQ is designed for teams, communities, and organizations that want collaboration tools without surrendering privacy:

- secure chat and private collaboration workflows
- deployment-friendly desktop packaging
- transparent release artifacts and version metadata
- privacy as a core product direction

This is a project built by a small group of patriot developers, and we are actively working to disrupt the market by making true privacy available to all.

## Integrity and Deployment Notes

- Verify package integrity before production deployment.
- Linux releases may include checksum files such as `SHA256SUMS`.
- Use platform `latest.json` files to track current release pointers.

### Windows Installation Behavior

- End users should use [`Windows/MIRQ.Chat.msi`](Windows/MIRQ.Chat.msi) for first-time installation.
- [`MIRQ-Setup-*.exe`](Windows/1.6.2.2/MIRQ-Setup-1.6.2.2.exe) extracts files into the directory where it is executed.
- Before running `MIRQ-Setup`, place it in `%USERPROFILE%\\AppData\\Local\\MIRQ\\` (or your desired install directory), then run it from there.

## Support

Primary project site: [https://mirq.chat](https://mirq.chat)

---

**MIRQ**  
Private chat and secure collaboration software built for people, not data brokers.
