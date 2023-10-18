# Obsidian Vault Template  - Web Application Penetration Tests

This Obsidan vault is a template for making notes and managing a web application pentration test engament or projects. You can and should use this vault **as additonal helper** for managing your notes such documenting session IDs, Payloads, used password lists, etc. This vault is an **extension to your existing documentation tools** (e.g. CherryTree, Microsoft OneNote, PlexTrac, etc.).

## Installation of Obsidian

Download Obsidian from https://obsidian.md/download and follow the instructions on this website.

## Community Plugins

The following community plugins and themes are used in this vault:
- **Dataview** (community plugin)
- **Admonition** (community plugin)
- **Things** (theme)
- **Templater** (community plugin)

## Downloading the Obsidian Vault

**Step 01 -** Clone the repository:

```shell
git clone https://github.com/dennis6400/webapp-notes-vault-template.git && cd webapp-notes-vault-template
```

*<u>Alternative</u>:*

```shell
git clone git@github.com:dennis6400/webapp-notes-vault-template.git && cd webapp-notes-vault-template
```

The command above clone the latest state (master branch) of the repository. Refer to [Alternative Downloads](https://github.com/dennis6400/kali-setup#Alternative%20Downloads) for alternative downloads.

**Step 02 -** Remove not relvant files for the respective penetration test engagement or project:

```shell
rm -r .git/ README.md .gitignore
```

Furthemore, remove the sections which are not relevant for you. Possible **examples**:
1. Findings directory
2. Access Check
3. Issues & Limitations

**Step 03 -** Rename the name of the vault template.

## Alternative Downloads

### Clone Master Branch

**HTTPs:**

```shell
git clone https://github.com/dennis6400/webapp-notes-vault-template.git
```

**SSH:**

```shell
git clone git@github.com:dennis6400/webapp-notes-vault-template.git
```

### Download Master Branch

```
https://github.com/dennis6400/webapp-notes-vault-template/archive/refs/heads/master.zip
```

### Clone Specific Branch/Tag/Release

**HTTPs:**

```shell
git clone --depth 1 --branch 1.0.0 https://github.com/dennis6400/webapp-notes-vault-template.git
```

**SSH:**

```shell
git clone --depth 1 --branch 1.0.0 git@github.com:dennis6400/webapp-notes-vault-template.git
```

### Download Specific Branch/Tag/Release

```
https://github.com/dennis6400/webapp-notes-vault-template/archive/refs/tags/v1.0.0.zip
```