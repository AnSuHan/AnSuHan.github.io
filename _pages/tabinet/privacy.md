---
title: "Tabinet Privacy Policy"
permalink: /tabinet/privacy/
layout: single
author_profile: false
toc: true
product: tabinet
lang: en
alt_lang: /tabinet/privacy/ko/
alt_lang_label: "한국어"
effective_date: "2026-09-01"
updated: "2026-09-01"
---

{% include doc-meta.html %}

Developer: An Suhan (안수한) — glorygem195@gmail.com

## 1. Summary

Tabinet does not collect, transmit, or sell any personal information. Everything the extension saves stays
in your browser. There is no Tabinet server, no analytics, and no advertising.

## 2. What Tabinet stores

- **Saved tab groups** — the title and URL of each tab you choose to save, plus the group name and color you
  give it.
- **Your settings** — options such as whether workspaces stay live in the background and whether tabs are
  pre-loaded.

This data is written through the Chrome extension storage API. By default it is stored locally on your
computer. If you turn on *Sync across devices*, Chrome stores it in your own Google account so it appears on
the Chrome browsers you are signed in to. In that case the data is handled by Google under your account, not
by the developer.

## 3. Why Tabinet asks for permissions

| Permission | Why it is needed |
|---|---|
| `tabs` | Read tab titles and URLs so a workspace can be saved and reopened. |
| `tabGroups` | Create and update native tab groups that represent a workspace. |
| `storage` | Store saved workspaces and settings in the browser. |
| `downloads` | Save the JSON file when you export your groups. |
| `sidePanel` | Display the Tabinet sidebar. |
| Host access (`http`/`https`) | When you open a workspace, Tabinet loads the pages you saved so that clicking a tab shows a ready page instead of a blank one. Requests go directly from your browser to those sites, using your existing browser session. Nothing is sent to the developer. |

## 4. What Tabinet never does

- No data is sent to the developer or to any third party.
- No tracking, analytics, advertising, or profiling.
- Your browsing history is not read; only the tabs you explicitly save are stored.
- Your data is never sold or shared.

## 5. Keeping and deleting your data

Saved workspaces stay until you delete them in Tabinet or uninstall the extension. Uninstalling removes the
locally stored data. If sync was enabled, the copy in your Google account is removed through Chrome's sync
settings.

## 6. Children

Tabinet is a general-purpose tool and is not directed to children under 13.

## 7. Changes

If this policy changes, the new effective date appears at the top of this page, and the previous text remains
available in the site's public repository history.

## 8. Contact

An Suhan — [glorygem195@gmail.com](mailto:glorygem195@gmail.com)
