# PolicyMate

PolicyMate monitors legislation, regulation, parliamentary and regulatory
events, and hearing transcripts across the jurisdictions your team follows.
This plugin brings that work into Antigravity: ask about your feed, your
briefings, bills and policymakers, and the agent answers from PolicyMate's
sources, with a link to each one.

## Before you start

- **A PolicyMate account with an active subscription.** The plugin signs in as
  you, so there is no API key to copy. [Request a demo](https://policymate.io)
  if your organisation does not use PolicyMate yet.
- **Two-step verification**, if your organisation requires it. Set it up in
  PolicyMate under **Settings → Security** before you connect.

## Connecting

1. Install the plugin, then open **Customizations → Installed**.
2. Under **MCP Servers**, click **Authenticate** next to PolicyMate.
3. Sign in to PolicyMate in your browser and approve the connection.
4. Copy the authorization code back into Antigravity and click **Submit**.

The agent only sees what your PolicyMate account can see. A colleague's
private space stays private.

To disconnect, open PolicyMate's **Settings → Integrations → MCP access** and
click **Disconnect** next to Antigravity. Access ends at once.

## What the agent can do

| Tool | What it does |
|---|---|
| `list-spaces`, `get-space-context` | Lists your spaces, and reads a space's mandate, topics, regions and instructions. |
| `get-my-profile` | Reads your personal preferences. |
| `get-recommendations` | Reads your personalised feed, with the reason each item matters to each space. |
| `get-daily-briefings` | Reads your saved daily briefings. |
| `get-upcoming-events` | Lists upcoming hearings, committee meetings and consultations relevant to you. |
| `search-publications` | Searches bills, regulations, reports and other official publications. |
| `search-policy-entities` | Searches policymakers, institutions, committees and legislative files. |
| `search-events` | Searches parliamentary and regulatory events. |
| `search-transcripts` | Searches hearing and debate transcripts. |
| `read-policy-page` | Reads the full content behind a PolicyMate link. |

By default the connection is **read-only**. If you also allow changes when you
approve it, the agent can, when you ask, update a space's preferences and
regions, create, edit and delete topics, follow and unfollow entities, and give
feedback on recommendations. Changes to a shared space apply to every member.

## Example prompts

- *What are the three most important updates in my PolicyMate feed this week?*
- *Which hearings and committee meetings are coming up in my spaces?*
- *Find recent EU publications on AI liability and summarise where each one stands.*
- *Who sits on the committee handling the packaging waste file?*
- *Turn this morning's briefing into a short client email.*

## Support

Email [help@policymate.io](mailto:help@policymate.io) or read the guides
at [policymate.io](https://policymate.io).
