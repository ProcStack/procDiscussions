# procDiscussions

GitHub Discussions repository for [procstack.github.io](https://procstack.github.io) blog comments, powered by [Giscus](https://giscus.app).

## Setup

### 1. Enable GitHub Discussions

In the repository **Settings → General → Features**, check the **Discussions** checkbox to enable GitHub Discussions on this repo.

### 2. Install the Giscus App

Install the [Giscus GitHub App](https://github.com/apps/giscus) and grant it access to this repository (`ProcStack/procDiscussions`).

### 3. Configure Giscus on procstack.github.io

Use [giscus.app](https://giscus.app) to generate your embed snippet with the following settings:

| Setting | Value |
|---|---|
| Repository | `ProcStack/procDiscussions` |
| Page ↔ Discussion Mapping | `pathname` (or your preferred mapping) |
| Discussion Category | `Announcements` (or whichever category you create) |
| Theme | Match your site theme |

Add the generated `<script>` tag to your blog pages where comments should appear.

### Origin Restriction

The `giscus.json` file in this repo restricts Giscus embeds to `https://procstack.github.io` (and `localhost` for local development). Requests from any other origin will be rejected.
