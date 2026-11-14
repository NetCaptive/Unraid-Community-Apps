# Unraid Community Apps Templates

This repository contains Unraid Docker templates (XML) that let you install selected self-hosted
apps in a few clicks from the **Apps** tab (Community Applications) in Unraid.

## Who made what

**Unless otherwise specified, I am not the developer of the applications, containers or plugins
referenced here.** I only author and maintain the XML templates that make them easy to install
through Community Applications. The software itself belongs to its respective developers and
projects, and each one keeps its own license.

Each template links to the upstream project in its `<Project>` field, and the app's own page is
the best place to find its documentation, license and authors.

## Where to get help

- **Problems with the app itself** (bugs, features, how it works): please go to the upstream
  project's repository or community. I can't fix problems in software I didn't write.
- **Problems with a template** (wrong default port, missing path or variable, broken icon, or a
  container that won't start from the template): open an issue in this repository.
- **Unraid support forum threads:** each template's `<Support>` link points to a thread for that app.

## Using these templates

The easiest way is to search for the app by name in the **Apps** tab in Unraid. Once Community
Applications lists this repository, no manual setup is needed.

To test a template manually, copy its XML file from `templates/` into
`/boot/config/plugins/dockerMan/templates-user/` on your Unraid server. It will then appear under
**Docker → Add Container** in the template dropdown.

## Contributing

Fixes and improvements to templates are welcome. Please open an issue or pull request describing
the change. If you are the developer of an app listed here and would like a template updated,
transferred to you, or removed, open an issue and I'll take care of it.

## Disclaimer

I provide these templates as-is, with no warranty. They pull container images published by
third parties, and I don't control or audit those images. Review an app before running it,
especially if you give it access to your data or network.

This project is independent and is not affiliated with, endorsed by, or sponsored by Lime
Technology, Inc. (Unraid). Unraid is a trademark of its owner. Other product names are trademarks
of their respective owners and are used only to identify the software the templates install.

## License

The XML templates, metadata and documentation in this repository are released under the
[MIT License](LICENSE). This license covers only the contents of this repository. The applications
and container images the templates reference are licensed separately by their authors.
