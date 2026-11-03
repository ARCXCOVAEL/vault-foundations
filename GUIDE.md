# Vault Foundations guide

Version 1.1.1. Review the included license and the linked policies before starting a trial or buying full access.

Open this guide in Obsidian from **Settings → Vault Foundations → Open guide**, or run **Vault Foundations: Open guide** in the command palette. The guide is included locally and does not require trial or paid access.

## For developers and AI workspaces

Bring development documentation, project decisions and AI-assisted work into an Obsidian workspace you can navigate. Keep your repository structure, use ordinary Markdown for shared project context, and choose which files belong in the vault’s working view.

### Watch your repository grow while agents work

Use Obsidian as a live window into the documentation in your repository. Keep a contents note and the native graph open while you or your agents add notes, create folders, move documents and update links, so you can see the project take shape.

Obsidian displays changes to included vault files. With **Vault Foundations Full navigation enabled**, configured folder tables of contents, the root index and optional Home navigation refresh automatically as eligible files are added, moved or removed. Their real Markdown links let the native graph and optional Graph Views Structure view grow with your project. You do not need to reopen the vault for each update.

Updates are batched rather than guaranteed to appear instantly. Native file detection and indexing affect visibility; a 60-second catch-up pass covers missed events while Obsidian is open, and reopening catches up later. Only included, eligible content participates: the graph follows notes and links and does not automatically turn every code file or filesystem folder into a node. Free keeps native note viewing and existing generated links available; automatic navigation upkeep requires active Full access.

To try this with one small project:

1. Use a vault containing the repository documentation you want to view. Preserve your repository layout and review exclusions for source-control internals, dependencies, build outputs and caches.
2. Preview Vault Foundations navigation, then enable Full upkeep only for the intended folders and output locations. Keep independent backups and use one folder-index writer.
3. Open the configured contents/index note beside the native graph. For optional Graph Views Structure, choose that note as the root.
4. Have your assistant create one ordinary Markdown note in an included project folder. Watch its link appear in the maintained contents note after the update pass and in the graph after native indexing. You can then edit, move or remove the test note through your normal workflow and observe the corresponding updates.

These updates run while Obsidian is open; the plugin does not monitor a closed vault as a separate background service.

- **Keep the reasoning with the work.** Connect architecture notes, decisions, tasks and runbooks to the projects they explain. Find the reason behind a change alongside the material you are developing.
- **Give your preferred AI useful context.** With approved file or app access, your assistant can work with project notes and repositories, help explain settings, and leave clear handoffs for the next session.
- **Make busy repositories easier to navigate.** Choose exclusions for dependency folders, build outputs and caches. Preview folder links, then use Full navigation upkeep to keep configured indexes current as eligible files move.
- **Explore the connections that matter.** Use native links and backlinks, plus optional Graph Views: Overview for the wider vault, Focused Writing around selected notes, and Structure from your project contents note.

When bulky repos or duplicate-looking nodes appear, check their full paths before cleaning up. Same-named notes, worktrees, clones and cross-links can be legitimate. Start with targeted exclusions and focused views; review changes and backups before moving or deleting anything.

Your AI needs access you deliberately provide through its own file or app tools. These plugins do not bundle an AI assistant or grant one control of Obsidian. Check current platform compatibility and use the supported controls available to your setup.

### Copy this prompt to your preferred AI

Give your assistant the vault/repository locations you want it to work with, and grant the intended access in that assistant’s permission controls. Then paste this prompt:

```text
Help me connect my Obsidian vault, development repositories and AI workspace using base Obsidian, Vault Foundations and optional Graph Views.

Start by identifying the vault and repository locations I approve, my Obsidian/plugin versions, existing project instructions and the tools you can actually use. Ask only for missing paths or permissions. Check current compatibility and Free/Full access before proposing settings.

Build on my current layout. Keep source code authoritative in its repository and preserve my existing notes. Recommend a practical arrangement for project overviews, architecture, decisions, tasks, runbooks and handoffs. Link useful existing material instead of copying whole repositories or producing duplicate notes. Do not relocate repositories or introduce symlinks without agreement.

Help configure deliberate exclusions for observed dependency folders, source-control internals, build outputs, caches and irrelevant clones/worktrees. Keep authored documentation and important project files accessible. Check Git ignore rules and Obsidian/Vault Foundations exclusions separately; one does not configure the other.

Use Vault Foundations' preview before enabling Full folder-navigation upkeep. Let it own its generated sections and preserve handwritten content outside those markers. Do not run a second folder-index writer. Help me use Obsidian search, links and backlinks, then Graph Views' Overview, Focused Writing and Structure views around a useful project contents note.

With my approved tools, help read and update project notes, investigate code, explain plugin settings and leave concise decisions and next steps as work progresses. Use supported app controls when available; otherwise give precise manual steps. Do not invent plugin APIs or claim to control an app you cannot access.

When a repo becomes bulky or duplicate-looking graph nodes appear, investigate full paths and file identities first. Distinguish actual duplicate files from same-named notes, legitimate worktrees, repository clones, symlinks, generated indexes and ordinary cross-links. Prefer targeted exclusions and focused views before proposing moves or removal. Check repository status, uncommitted work, backlinks and recoverable backups before an approved cleanup. Never merge or delete by title alone.

Show a short plan, then make the changes I approve. Keep secrets, licensing records and private material out of shared notes or uploads. Ask before installations, destructive cleanup, repository restructuring, external sharing or broader permissions.

Start with one small, non-sensitive project. Finish with the layout, settings and example workflow, what you changed, what you verified in Obsidian, and any steps that still need my input.
```

## Start safely

Use the verified Windows desktop host version listed in the README. Maintain current, independent backups of your vault, notes and configuration, and verify that you can restore them before enabling automated navigation, changing exclusions, moving generated-output locations or updating the plugin. Local recovery files are an additional safeguard, not a substitute for your own backup. This responsibility does not waive rights that cannot lawfully be excluded. Enable Vault Foundations in your existing vault. Save your work and restart Obsidian once after first enabling it, before checking early filtering. Filtering defaults respect native exclusions; folder-note upkeep starts disabled. Configure exclusions before using a large technical directory as a vault. Do not run a second external folder-index writer alongside this plugin.

Open Settings → Vault Foundations. Prepare the exclusions and optional navigation paths, use the preview control to inspect the proposed links and then **Apply settings**. Typing a setting does not run a graph query on each keystroke. Changing established generated-output locations later needs a planned migration; it is not an ordinary folder rename.

## Notes, folders and the graph

Folder notes contain links to original eligible documents. Exact folder spelling is retained. Same-named folders at different locations have distinct note paths. Native links, backlinks and ordinary editing remain native; there is no second graph renderer or duplicate original document collection.

Write personal descriptions outside generated comment markers. Those annotations are preserved. Text inside managed markers is regenerated. Original folder moves and case-only/nested renames follow local directory identity on the verified Windows hosts. Renaming an application/compiler's fixed runtime path may still require that application's own configuration migration.

Native file events schedule short batched updates. A 60-second catch-up pass covers missed events while the application is open; reopening catches up later. This is not a Windows service, an always-running Python process or a full-drive ping. Native notification/indexing delays also affect visibility.

## Recommended paired setup: Graph Views

We recommend pairing Vault Foundations with [Graph Views](https://community.obsidian.md/plugins/graph-views) for a more useful visual workspace. Vault Foundations maintains the links; Graph Views gives you ways to explore them without creating a second graph or copying your notes.

1. In Vault Foundations, configure exclusions and preview optional folder-note navigation. Enable upkeep when the proposed links and output locations match your intended vault layout.
2. On a verified compatible desktop version, open **Settings → Community plugins → Browse**, search for **Graph Views** by **ARCXCOVAEL LLC**, then install and enable it. Enable the core **Graph view** plugin if necessary. Installation is your choice; Vault Foundations does not install it for you.
3. Open the native global Graph view. Choose **Overview** to explore the admitted vault. For **Focused Writing**, choose the notes you want to work around and their incoming/outgoing connections. For **Structure**, choose your own contents note or the configured folder/root index as the root; it follows the actual links, with shared branches and cross-links retained. Use branch folding and saved node positions to make that view easier to work with.
4. Keep linking and editing your original notes normally. Folder-index upkeep follows eligible creates, moves and renames while full navigation access is active. Your own contents note remains yours to curate. Switch back to Overview whenever you want the wider vault view.

Expected result: one native web of real notes and links, with a broad overview or a more deliberate writing/contents view. Structure reflects the links in its chosen root note; it does not automatically turn every filesystem folder into a node. Folder notes supply those links only where you configure them. Graph Views does not create or maintain folder notes.

The current Graph Views public beta is verified only on Windows desktop 1.14.4 and 1.14.5; check its own compatibility before updating either plugin or the host. It is optional and free under MPL-2.0, with a separate installation and license. Disabling it restores the ordinary native graph and does not remove notes or folder links. A Vault Foundations trial expiry does not disable Graph Views; automatic navigation upkeep follows Vault Foundations' access rules, while existing notes and links remain available. Large graphs can still be expensive; no fixed performance improvement is promised.

## Connect an account

Open Settings → Vault Foundations → Manage connection, or run **Vault Foundations: Manage licensing**. Choose whether to remember the connection on this computer and select **Connect account**. The plugin opens your browser, where Clerk handles sign-in. Compare the browser's code with the plugin's code and confirm only a connection you started.

The temporary callback listens on IPv4 loopback only and closes after completion, cancellation or expiry. It carries a one-use connection code; account-session tokens and the long-lived licensing credential do not travel in the callback URL. Closing the licensing panel cancels an unfinished connection. If it expires, start a new connection; do not repeatedly reload an old callback page.

Signing in alone does not start a trial. Read the linked terms, privacy, sales and support information. When ready, check the deliberate-acceptance control and press **Start 30-day trial**. A local notice and status-bar label identify active trial access. Your original activation belongs to the account and survives reinstall, device/vault changes and reconnects. Accepting revised terms does not restart it. No automatic purchase or subscription is created.

The panel displays the original 30-day trial end and the next required online-check deadline. Trial renewal uses bounded HTTPS requests outside graph drawing, with cancellation and outage backoff. A service outage cannot create unsigned access or extend the signed allowance. Offline trial access lasts up to 24 hours after a successful signed check and never beyond the original trial end. A verified purchased 1.x proof has no periodic renewal expiry. Keep normal device/vault recovery in place; if the proof is lost, account-based recovery requires connectivity.

## Before purchasing

All sales are final. We do not offer discretionary refunds, including change-of-mind refunds. Use the 30-day trial to evaluate compatibility, performance and suitability before purchasing. This policy does not limit any refund or other remedy required by applicable law. Read the linked license and sales policy before payment. A trial creates no automatic charge or subscription.

## Safe fallback

If a trial expires or a fresh signed proof cannot be obtained before its check deadline, automatic root/folder/Home upkeep pauses. An already-admitted transaction can finish; subsequent paid navigation operations stop and retained identities/intents allow later resume. Existing generated pages and handwritten annotations remain ordinary editable Markdown. Early exclusions, performance controls and status/recovery remain available. The plugin never remotely wipes, encrypts or locks your notes.

Use read-only preview or existing links while resolving access. Do not remove protective exclusions or delete a metadata cache just to clear an entitlement error.

## Saved connection and sign-out

Remembering a connection encrypts its credential and signed proof with Windows protected storage outside your vault. Vault synchronization does not carry that connection to another computer. A window-only connection is explicitly labeled and lasts only in that window. Other apps running as the same Windows user are outside this protection boundary.

**Sign out on this computer** clears the local connection and requests server revocation. Browser sign-in is separate. If local clearing or server revocation fails, reconnect is blocked and **Retry sign-out** remains available. Repair protected storage/network access and retry. If protected clearing failed, an older saved sign-in can return after a restart; do not close/reopen until clearing is confirmed.

If startup cannot verify an existing saved record, connecting is blocked. Repair storage and choose **Retry saved connection**. There is no plaintext fallback for an unreadable encrypted record. A verified absent record can use window-only mode if encryption is unavailable.

## Check health and recover

Use **Show filtering and navigation status**. The plugin's local `status.json` reports phase, completed pass, conflicts, resource bounds and secret-free licensing status. `data.json` holds configuration; `state.json` records folder identities and recovery intents. Do not share these files publicly: paths and private policy can be present even though licensing credentials are stored elsewhere.

A brief error may recover on the next successful pass. For a recurring timeout, record when it happens and the exact phase; preserve notes and settings. Do not keep forcing refresh, clear caches or apply broad settings changes. A status snapshot alone does not prove a permanent fault or permanent recovery.

For collisions, damaged generated markers or concurrent edits, the writer preserves the current note and reports the conflict. Inspect that exact path and the plugin's checksum-backed local recovery. Never bulk-restore old Home/index notes over newer writing or remove another writer's active lock.

Before updating, close the application normally and preserve the previous package plus current configuration/state and notes. Replace only authorized distributed package files; retain local settings/recovery. A rollback likewise restores only a specifically inspected prior package after compatibility review. Notes, later edits and other plugins must remain intact. Do not restore a saved licensing credential from an unrelated profile.

Contact **support@arcxcovael.com** for support/privacy requests. Read the [Privacy](https://license.arcxcovael.com/privacy), [Support](https://license.arcxcovael.com/support) and [Sales](https://license.arcxcovael.com/refunds) policies. Send a concise symptom and secret-free status summary first. Do not send passwords, activation codes, signed proofs, encrypted credential files or vault contents as routine support evidence.

## Native graph recall and pause — candidate revision

Vault Foundations can retain one eligible native graph while you open a note in the same tab. Back and Forward can return to that graph with its view, filters, selection, viewport and displayed node positions preserved. Live-mode recall does not require manually pausing first. Graph Views is an optional presentation companion; the acceleration belongs to Vault Foundations.

Retention is bounded. Resource pressure, closing the tab, a visibility-policy change or an incompatible host/visualization version can release a retained graph. Another graph can replace it. Native navigation then creates a fresh graph. Changed contents or visualization settings require a fresh result after return.

Use **Graph live · Pause** to hold automatic graph content and layout updates. **Graph paused · Resume** stays visible while paused. Pan, zoom, select and drag remain available, including after an eligible note round trip. Mode, depth, folding and tracing changes wait for Resume. Resume applies the latest bounded result or requests a fresh one if the pending result was discarded.

Queries, note editing, indexing and folder table-of-contents upkeep continue. Pause does not suspend the whole application or promise zero worker CPU. Visibility-policy changes end pause so newly excluded content is not retained in the held display. These graph protections remain separate from paid automatic folder-note upkeep.

**Private candidate status:** live verification is pending, including ordinary Back/Forward at Structure depth 10 and the other supported views/depths. A successful package build or source test is not proof of navigation speed or display acceptance. This revision is not approved for installation or release yet.
