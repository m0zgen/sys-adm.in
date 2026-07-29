# sys-adm.in

Minimal static landing page for the SYS-ADMIN ecosystem.

## Projects

- OpenBLD — https://openbld.net/
- System Checks — https://system-checks.org/
- SysConf — https://sysconf.io/
- Lab — https://lab.sys-adm.in/

## Deployment

The repository is deployed to GitHub Pages from the `master` branch using `.github/workflows/pages.yml`.

In repository settings:

1. Open **Settings → Pages**.
2. Select **GitHub Actions** as the source.
3. Set the custom domain to `sys-adm.in`.

For an apex domain, configure the GitHub Pages A/AAAA records according to GitHub documentation, or keep the existing DNS setup if the domain already points to GitHub Pages.
