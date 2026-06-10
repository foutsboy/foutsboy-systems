# Stefan Footage — Iconik Framework

*Starting collection for the SkyMD Content Vault*
*Source: SanDisk Extreme SSD — organized by month, 18+ months of footage*

---

## Step 1: Connect Your SSD to Iconik

1. Open Iconik → **Settings → Storage**
2. Add new storage → select **Local Storage / On-Premise**
3. Point it at the Stefan folder on the SanDisk
4. Enable **Auto-scan** so new monthly folders get picked up automatically
5. Turn on **AI Analysis** on the storage — this triggers automatic face, speech, and object tagging on every clip

---

## Step 2: Custom Metadata Fields to Create in Iconik

Go to **Settings → Metadata** and create a custom schema called `SkyMD Stefan`.

| Field Name | Type | Purpose |
|------------|------|---------|
| Location | Dropdown | Where it was filmed |
| Activity | Multi-select | What Stefan is doing |
| Product Visible | Boolean | Is a SkyMD product in the shot |
| Product Action | Dropdown | What's happening with product |
| Vibe | Multi-select | Tone/energy of the clip |
| Usage Count | Number | Track how many times clip has been used |
| Last Used | Date | B-roll rotation tracking |
| Quality Rating | Dropdown | 1–5 stars |
| Has Audio | Boolean | Is Stefan speaking |

---

## Step 3: Keyword Taxonomy

These are the keywords Iconik's AI will auto-generate AND that you can manually add. Use these exact terms so searches are consistent.

### People
- `stefan`
- `stefan-wolf`
- `stefan-talking`
- `stefan-silent` (no dialogue, pure visual)

### Locations
- `office`
- `gym`
- `outdoor`
- `mountains`
- `trail`
- `sauna`
- `cold-plunge`
- `kitchen`
- `car`
- `travel`
- `hotel`
- `medical`
- `events`

### Activities
- `running`
- `trail-running`
- `lifting`
- `training`
- `stretching`
- `mobility`
- `sauna-session`
- `cold-plunge`
- `walking`
- `hiking`
- `cycling`
- `sprinting`
- `working`
- `talking-to-camera`
- `interview-style`

### Product
- `pouring-skymd`
- `mixing-skymd`
- `drinking-skymd`
- `holding-packet`
- `product-close-up`
- `lifestyle-hydration`
- `electrolytes`
- `sleep-formula`
- `hydration-formula`

### Mood / Vibe
- `high-energy`
- `calm`
- `educational`
- `cinematic`
- `raw`
- `motivational`
- `personal`
- `behind-the-scenes`

### Time of Day
- `morning`
- `golden-hour`
- `evening`
- `night`

### Shot Type
- `wide`
- `medium`
- `close-up`
- `b-roll` (no speaking)
- `a-roll` (Stefan speaking, usable dialogue)
- `slow-motion`
- `handheld`
- `stabilized`

---

## Step 4: Collections to Build in Iconik

After AI indexing runs, create these smart collections (saved searches):

| Collection Name | Search Query |
|-----------------|-------------|
| Stefan — All Footage | `stefan` |
| Stefan — Talking (A-Roll) | `stefan` + `a-roll` |
| Stefan — Silent (B-Roll) | `stefan` + `b-roll` |
| Stefan — Mountains | `stefan` + `mountains` |
| Stefan — Running | `stefan` + `running` |
| Stefan — Sauna | `stefan` + `sauna` |
| Stefan — Cold Plunge | `stefan` + `cold-plunge` |
| Stefan — Product Use | `stefan` + `pouring-skymd` OR `mixing-skymd` OR `drinking-skymd` |
| Stefan — Office | `stefan` + `office` |
| Stefan — Golden Hour | `stefan` + `golden-hour` |
| Stefan — Cinematic | `stefan` + `cinematic` |
| Stefan — Never Used | `stefan` + `usage-count: 0` |

---

## Step 5: B-Roll Rotation Workflow

When pulling a clip for an edit:
1. Search the collection
2. Sort by **Usage Count (ascending)** — unused clips bubble to top
3. Pull the clip
4. Update: increment **Usage Count** by 1, set **Last Used** to today

This keeps visuals fresh automatically.

---

## Step 6: Folder Review Process (One-Time)

Since footage is organized by month on the SSD, do a quick pass before AI runs to flag anything obvious:

- Trash clearly unusable clips (shaky, out of focus, accidental) *before* ingesting — saves AI processing time
- Star-rate anything you remember being exceptional so it surfaces first
- Note any clips where Stefan is talking about specific topics (sleep formula, packaging, etc.) — add a `topic` tag manually

Estimated time per month of footage: 30–45 min

---

## Quick Search Reference Card

| I need... | Search in Iconik |
|-----------|-----------------|
| Stefan outdoors moving | `stefan running` or `stefan hiking` |
| Stefan in the sauna | `stefan sauna` |
| Stefan pouring SkyMD | `stefan pouring-skymd` |
| Cinematic mountain shots | `stefan mountains cinematic` |
| Stefan talking on camera | `stefan a-roll` |
| Fresh B-roll (unused) | `stefan usage-count:0` |
| Stefan cold plunge | `stefan cold-plunge` |
| Golden hour footage | `stefan golden-hour` |
