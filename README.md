![Multigravity](assets/multigravity-logo.jpg)
# Multigravity


**Run multiple Antigravity IDE profiles at the same time — each with its own accounts, settings, and extensions.**

> Note: Multigravity currently only supports macOS.

No more logging in and out. Just switch profiles instantly or use them all at once!

---

## Install

Open the **Terminal** app on your Mac and paste this:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/sujitagarwal/multigravity-cli/main/install.sh)"
```

That's it. Multigravity is now installed.

---

## Getting Started

### 1. Create a profile

Give it any name you like — your name, a project, a client, anything:

```bash
multigravity new work
multigravity new personal
```

This also creates a clickable app shortcut in your `~/Applications` folder.

### 2. Open a profile

```bash
multigravity work
```

Antigravity will open using that profile's isolated settings and accounts.

### 3. See all your profiles

```bash
multigravity list
```

---

## Other Commands

### Rename a profile

```bash
multigravity rename work freelance
```

### Delete a profile

```bash
multigravity delete personal
```

You'll be asked to confirm before anything is deleted.

### Get help

```bash
multigravity help
```

---

## Profile Name Rules

- Letters, numbers, and hyphens only
- Must start with a letter or number
- ✅ `work`, `client-a`, `test1`
- ❌ `-name`, `my_profile`

---

## App Shortcuts

Every profile automatically gets a **clickable app** in `~/Applications` with the Multigravity icon — so you can open profiles directly from Finder or pin them to the Dock, just like any other app.