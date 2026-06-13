# Screenshot replacement tracker

The UI changed across the board, so **every screenshot is being re-captured**. Work through this list in manual order and tick each off as you replace it. Not published (see `.mintignore`).

All files live in `images/onboarding/screenshots/` as `.webp`.

**Every image tag is now wired into the pages** — for every row below, the only action left is to save the `.webp` file under the listed name and it renders automatically. No more page edits needed.

**Tags**
- **REPLACE** — file already exists; re-capture and overwrite the same filename.
- **CAPTURE** — page points at this filename but the file is missing; save it under that name.
- **NEW** — image tag is wired; the file does not exist yet, so it shows as broken until you save it.
- 🟡 — you've already shared this one; just save it under the filename.
- ♻ — reused on more than one page; replacing the file updates every page at once.

Totals: ~36 existing to replace · 2 to capture · 33 new.

---

## Getting started
- [ ] **REPLACE** `s01-what-is-neuramill-upload-overview.webp` ♻ — upload dialog with CAD + GD&T zones — what-is-neuramill.mdx:17, upload-cad-only.mdx:17
- [ ] **REPLACE** `s03-profile-menu-my-profile-highlight.webp` ♻ — profile menu / where to see your plan — subscriptions.mdx:59

## Your account
- [ ] **REPLACE** `s04-account-registration-form-labeled.webp` — registration form — creating-your-account.mdx:33
- [ ] **REPLACE** `s05-login-form-labeled.webp` — sign-in form — logging-in.mdx:13
- [ ] **NEW** `s71-forgot-password-link.webp` — Forgot Password link on the sign-in page — forgot-password.mdx:12

## Dashboard
- [ ] **REPLACE** `s06-dashboard-overview-tabs-new-session.webp` — dashboard overview with tabs + New Session — overview.mdx:7
- [ ] **CAPTURE** `s06-dashboard-jobs-table.webp` — Jobs table — jobs-tab.mdx:7 *(file missing; consider renaming to s0X to avoid the s06 clash)*
- [ ] **REPLACE** `s07-dashboard-jobs-filters-open.webp` — Jobs filters open — jobs-tab.mdx:31
- [ ] **REPLACE** `s08-dashboard-machines-filters-open.webp` — Machines list + filters — machines-tab.mdx:15
- [ ] **REPLACE** `s09-dashboard-tools-filters-open.webp` — Tools list + filters — tools-tab.mdx:28
- [ ] **NEW** `s68-dashboard-policies-list.webp` — Policies list: type, tier, clamping strategy — policies.mdx:9
- [ ] **NEW** `s69-dashboard-machining-config.webp` — Machining configuration library sections — machining-config.mdx:11
- [ ] **REPLACE** `s10-dashboard-users-table-actions.webp` — Users table + row actions — users-tab.mdx:47
- [ ] **REPLACE** `s11-dashboard-invitations-status-table.webp` — Invitations status table — invitations-tab.mdx:22
- [ ] **NEW** `s70-dashboard-usage-counts.webp` — Usage view: jobs / machines / users counts (no limit bars) — usage.mdx:7

## Profile
- [ ] **REPLACE** `s12-profile-menu-my-profile-highlight-duplicate.webp` — profile menu — my-profile.mdx:14
- [ ] **REPLACE** `s13-my-profile-account-info-edit-mode.webp` — account info edit mode — my-profile.mdx:31
- ~~s14-company-usage-progress-bars~~ — removed (company usage left the Profile)
- ~~s15-machining-policy-tiers-add-policy~~ / ~~s16-policy-toggle-on-off~~ — removed (machining policy preferences merged into Dashboard → Policies)

## Starting a session
- [ ] **REPLACE** `s17-dashboard-overview-new-session-duplicate.webp` — dashboard + New Session — what-is-a-session.mdx:30
- [ ] **REPLACE** `s18-upload-cad-only-step-attached.webp` — STEP file attached — upload-cad-only.mdx:38
- [ ] **REPLACE** `s19-upload-cad-gdt-both-attached.webp` — CAD + GD&T both attached — upload-cad-and-gdt.mdx:26

## GD&T review *(new section)*
- [ ] **NEW** 🟡 `s43-gdt-review-screen-full.webp` — full review screen: viewer + markers + annotation list — overview.mdx:31
- [ ] **NEW** 🟡 `s44-gdt-document-viewer-markers.webp` — document viewer + numbered markers — reviewing-annotations.mdx:17
- [ ] **NEW** `s45-gdt-link-annotation-drag.webp` — dragging an annotation row onto a 3D feature — linking-annotations.mdx:23
- [ ] **NEW** `s46-gdt-approve-button.webp` — Approve GD&T action — approving-gdt.mdx:20

## 3D viewer toolbar
- [ ] **REPLACE** `s20-viewer-toolbar-overview-labeled.webp` — toolbar with all tools labeled — toolbar-overview.mdx:9
- [ ] **NEW** `s49-viewer-measure-distance.webp` — measure tool: two points + distance — measure-tool.mdx:22
- [ ] **NEW** `s47-viewer-solid-vs-wireframe.webp` — solid vs. wireframe — view-controls.mdx:25
- [ ] **NEW** `s48-viewer-stock-overlay.webp` — model inside transparent stock box — view-controls.mdx:43

## Step 1: Machining setup
- [ ] **REPLACE** `s30-machining-setup-overview-full.webp` — full machining setup screen — overview.mdx:14
- [ ] **REPLACE** `s31-machining-material-dropdown-properties.webp` — material dropdown + properties — material.mdx:26
- [ ] **REPLACE** `s32-machining-machine-dropdown-specs.webp` — machine dropdown + specs — machine.mdx:17
- [ ] **REPLACE** `s33-machining-rigidity-dropdown.webp` — rigidity dropdown — rigidity.mdx:24
- [ ] **REPLACE** `s34-machining-stock-size-with-overlay.webp` — stock size + overlay — stock-size.mdx:33
- [ ] **REPLACE** `s35-machining-stock-validated-banner.webp` — stock validated banner — stock-validation.mdx:15
- [ ] **CAPTURE** `s36-machining-setup-approved-before-after.webp` — Approve button before/after — stock-validation.mdx:29 *(file missing; s36 clashes with the clamping file below — consider a fresh number)*
- [ ] **NEW** `s50-machining-quick-setup-confirmation.webp` — quick setup confirmation (below Validate button) — quick-setup.mdx:11

## Step 2: Direction of cut
- [ ] **REPLACE** `s21-direction-of-cut-overview-tabs-approve.webp` ♻ — DOC overview + approve — overview.mdx:16, approving.mdx:21
- [ ] **NEW** `s72-direction-hybrid-view.webp` — Hybrid view: 3D model + grouped feature cards — hybrid-view.mdx:7
- [ ] **NEW** `s73-direction-feature-editor.webp` — Feature editor: Select and group / Configure / Review steps — editing-features.mdx
- ~~s22-direction-cad-view~~ / ~~s23-direction-setup-view~~ — removed (CAD + Setup views merged into Hybrid)
- [ ] **REPLACE** `s24-direction-grid-view-table.webp` — grid view table — grid-view.mdx:7
- [ ] **REPLACE** `s25-direction-feature-card-annotated.webp` ♻ — annotated feature card — feature-cards.mdx:7, flagging-features.mdx:27
- [ ] **REPLACE** `s26-direction-move-to-setup-popup.webp` — move-to-setup popup — changing-setup-direction.mdx:18
- [ ] **REPLACE** `s27-direction-flag-feature-dialog.webp` — flag feature dialog — flagging-features.mdx:34
- [ ] **REPLACE** `s28-direction-feature-flagged-state.webp` — flagged state — flagging-features.mdx:50
- [ ] **REPLACE** `s29-direction-multi-select-advanced-classification.webp` — multi-select — advanced-classification.mdx:22

## Step 3: Clamping strategy
- [ ] **REPLACE** `s39-clamping-collapsed-strategy-card.webp` — collapsed strategy card — what-is-clamping.mdx:17
- [ ] **REPLACE** `s36-clamping-feature-distribution-tracker.webp` — feature distribution tracker — feature-distribution.mdx:7
- [ ] **REPLACE** `s37-clamping-new-strategy-form.webp` — new strategy form — adding-a-strategy.mdx:13
- [ ] **REPLACE** `s38-clamping-face-buttons-color-states.webp` — face buttons color states — adding-a-strategy.mdx:49
- [ ] **REPLACE** `s40-clamping-expanded-operation-list.webp` — expanded operation list — operations.mdx:7
- [ ] **REPLACE** `s41-clamping-add-feature-panel.webp` — add feature panel — managing-features.mdx:23
- [ ] **REPLACE** `s42-clamping-two-strategies-remaining-decrease.webp` — two strategies, remaining decreases — multiple-strategies.mdx:27
- [ ] **NEW** `s51-clamping-complete-setup-before-after.webp` — Complete Setup before/after — completing-setup.mdx:20
- [ ] **NEW** `s74-clamping-add-pass-dialog.webp` — Add Pass dialog: operation type + machining strategy — managing-passes.mdx
- [ ] **NEW** `s75-clamping-pass-machining-profile.webp` — Expanded pass: machining profile + delete control — managing-passes.mdx

## Step 4: Intelligent tool recommender
- [ ] **NEW** `s53-itr-select-optimal-tools-summary.webp` — Select Optimal Tools + summary bar — overview.mdx:26
- [ ] **NEW** `s52-itr-tool-card-labeled.webp` — full tool card labeled — reading-tool-cards.mdx:7
- [ ] **NEW** `s54-itr-machining-parameters.webp` — RPM / feed / plunge on a tool card — speeds-and-feeds.mdx:7
- [ ] **NEW** `s55-itr-tool-card-edit-mode.webp` — tool card in edit mode + Undo — manual-override.mdx:17

## Step 5: Summary
- [ ] **NEW** `s56-summary-view-full.webp` — full summary: setup panels + strategy + tool cards — summary-view.mdx:38
- [ ] **NEW** 🟡 `s57-summary-cycle-time-estimate.webp` — Cycle Time Estimate panel — cycle-time.mdx:7
- [ ] **NEW** 🟡 `s58-summary-quick-quote-panel.webp` — Quote button + open Quick Quote panel — quote-calculator.mdx:19

## Export to Fusion 360 *(new section)*
- [ ] **NEW** `s59-fusion-roundtrip-diagram.webp` — web-app → Fusion round-trip (optional; can be a graphic) — overview.mdx:24
- [ ] **NEW** 🟡 `s60-fusion-addins-dropdown-app-store.webp` — Utilities → ADD-INS dropdown w/ Fusion App Store — installing.mdx:13
- [ ] **NEW** `s61-fusion-scripts-addins-run-on-startup.webp` — Scripts and Add-Ins, Run on Startup checked — installing.mdx:39
- [ ] **NEW** 🟡 `s62-summary-generate-export-key.webp` — Summary page Generate key control — generating-an-export-key.mdx:16
- [ ] **NEW** `s63-fusion-import-palette.webp` — Neuramill Import palette (key, checkbox, button) — importing-cam-data.mdx:13
- [ ] **NEW** `s64-fusion-cam-browser-toolpaths.webp` — CAM browser with generated toolpaths — after-import.mdx:13
- [ ] **NEW** `s65-fusion-operation-faces-highlighted.webp` — operation selected, faces highlighted — after-import.mdx:19

## Assistant and review *(new section)*
- [ ] **NEW** 🟡 `s66-neurachat-panel-open.webp` — NeuraChat panel open ("How can I help you?") — using-neurachat.mdx:12
- [ ] **NEW** `s67-review-mode-locked-tabs.webp` — review mode with locked tabs + Summary — reviewing-a-completed-job.mdx:7

---

## Pages with no screenshot (nothing to do)
index, getting-started/your-first-job, what-you-need, user-roles, machining-setup/approving-features, direction-of-cut (none beyond above), tool-recommender/tool-source-filters, viewer-toolbar/select-and-pan, viewer-toolbar/units-switcher, fusion-addin/what-gets-imported, summary/finalize, reference/checklist, reference/common-mistakes, reference/glossary
