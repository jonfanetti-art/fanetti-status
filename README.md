# Fanetti AI status

Uptime monitoring for [www.fanettiai.com](https://www.fanettiai.com/), run by [Upptime](https://github.com/upptime/upptime) (MIT) on free GitHub Actions in this public repository.

- Status page: <https://jonfanetti-art.github.io/fanetti-status/>
- Checks: every 5 minutes (`.github/workflows/uptime.yml`). An outage opens a GitHub issue here and closes it when the site is back.
- Config: `.upptimerc.yml`.

This repo holds uptime data only. It has no site code and no secrets; the workflows use the built-in `GITHUB_TOKEN`.

Upptime's `setup`, `update-template` and `updates` workflows are left out on purpose: they rewrite workflow files (which needs a personal access token) and the last one runs an unpinned `@master` action. Upgrade by hand: bump the pinned `upptime/uptime-monitor` SHA in all workflows.

<!--start: status pages-->
<!--end: status pages-->
