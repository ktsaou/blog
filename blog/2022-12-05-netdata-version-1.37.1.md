---
slug: netdata-version-1.37.1
title: "Release 1.37.1: Patch release for security issues"
description: "Release 1.37.1: Patch release for security issues"
image: https://user-images.githubusercontent.com/88642300/205665462-39758bd7-65e7-429e-9b57-c72c95c52be1.png
tags: [product,release notes]
keywords: [netdata,product]
authors: team
---

Netdata v1.37.1 is a patch release to address issues discovered since v1.37.0. Refer to the [v.1.37.0 release notes](https://github.com/netdata/netdata/releases/tag/v1.37.0) for the full scope of that release.

<!--truncate-->

# Release v1.37.1

Netdata v1.37.1 is a patch release to address issues discovered since v1.37.0. Refer to the [v.1.37.0 release notes](https://github.com/netdata/netdata/releases/tag/v1.37.0) for the full scope of that release.

The v1.37.1 patch release fixes the following issues:

- Parent agent crash when many children instances (re)connect at the same time, causing simultaneous SSL re-initialization ([PR #14076](https://github.com/netdata/netdata/pull/14076)).
- Agent crash during dbengine database file rotation while a page is being read while being deleted ([PR #14081](https://github.com/netdata/netdata/pull/14081)).
- Agent crash on metrics  page alignment when metrics were stopped being collected for a long time and then started again ([PR #14086](https://github.com/netdata/netdata/pull/14086)).
- Broken Fedora native packages ([PR #14082](https://github.com/netdata/netdata/pull/14082)).
- Fix dbengine backfilling statistics ([PR #14074](https://github.com/netdata/netdata/pull/14074)).

In addition, the release contains the following optimizations and improvements:

- Improve workers statistics performance ([PR #14077](https://github.com/netdata/netdata/pull/14077)).
- Improve replication performance ([PR #14079](https://github.com/netdata/netdata/pull/14079)).
- Optimize dictionaries ([PR #14085](https://github.com/netdata/netdata/pull/14085)).

## Support options

As we grow, we stay committed to providing the best support ever seen from an open-source solution. Should you encounter
an issue with any of the changes made in this release or any feature in the Netdata Agent, feel free to contact us
through one of the following channels:

- [Netdata Learn](https://learn.netdata.cloud/): Find documentation, guides, and reference material for monitoring and troubleshooting your systems with Netdata.
- [GitHub Issues](https://github.com/netdata/netdata/issues): Make use of the Netdata repository to report bugs or open a new feature request.
- [GitHub Discussions](https://github.com/netdata/netdata/discussions): Join the conversation around the Netdata development process and be a part of it.
- [Community Forums](https://community.netdata.cloud/): Visit the Community Forums and contribute to the collaborative knowledge base.
- [Discord](https://discord.gg/2eduZdSeC7): Jump into the Netdata Discord and hang out with like-minded sysadmins, DevOps, SREs, and other troubleshooters. More than 1300 engineers are already using it!
