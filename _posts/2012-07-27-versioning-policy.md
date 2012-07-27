---
layout: post
category: information
tags: 
---
{% include JB/setup %}

# Versioning Policy


This document describes how version numbering reflects the type of
changes in a new release.

The version numbering is a usual one: X.Y.Z, where X is major, Y is
minor and Z is bugfix release number.

Each number is (usually) increased by one at a time, and when one of the
numbers is increased, the less significant numbers are reset to zero. To
show an example, a stretch of Jansson’s version history is 1.0.3 → 1.0.4
→ 1.1.0 → 1.1.1.

When a new release is made, the version number is increased according to
the following rules:

-   If there are only bugfixes, the bugfix number Z is increased, e.g.
    1.0.3 → 1.0.4
-   If there are backwards compatible changes, the minor number Y is
    increased, e.g. 1.0.4 → 1.1
-   If there are major feature increase, the major number X is
    increased, e.g. 1.2 → 2.0

This versioning scheme also dictates the development of new features.
There should be a considerable amount of new features, or enough time
should have passed, when the minor version is increased so that it
doesn’t grow very fast. And the major version number should only be
increased when there is a serious reason to make backwards incompatible
changes.