# **AeroutV4Tweaks**

**Created by [RealAero](https://github.com/wrealaero)**

🚀 **AeroutV4Tweaks** is a simple and powerful tool that helps your Mac run faster, smoother, and better—especially for gaming!

---

## 🌟 **What It Does**

This script does smart things behind the scenes to make your Mac perform better:

* Deletes junk files to free up space
* Speeds up your internet with better DNS
* Makes animations quicker so things feel snappier
* Lets you choose between saving battery or getting max speed
* Has a **Game Mode** that boosts Roblox, Steam, and other games

---

## 📥 **How to Download & Use It**

### ✅ **Option 1: Easiest Way (Releases)**

1. Go to the [Releases Page](https://github.com/wrealaero/AeroutV4Tweaks/releases)
2. Download the newest `.zip` file
3. Unzip it and open **Terminal**
4. Drag the file called `aeroutv4free.sh` into Terminal and hit **Enter**

Easy! That’s it.

---

### 💻 **Option 2: Power User Setup (One-Time Command Setup)**

If you like using Terminal and want to run it anytime with a simple command:

```bash
# Step 1: Download the script
curl -O https://raw.githubusercontent.com/wrealaero/AeroutV4Tweaks/main/aeroutv4free.sh

# Step 2: Make it executable
chmod +x aeroutv4free.sh

# Step 3: Move it so it works anywhere
mkdir -p ~/bin
mv aeroutv4free.sh ~/bin/aerout

# Step 4: Add it to your path
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc

# Step 5: Reload Terminal
source ~/.zshrc
```

Now you can just type `aerout` in Terminal to run it anytime. 😎

---

### 🖱️ **Option 3: Clickable Desktop Shortcut**

Don’t like typing commands? Try this:

```bash
# Replace YOURUSERNAME with your Mac username
echo '#!/bin/bash
/Users/YOURUSERNAME/Downloads/aeroutv4free.sh' > ~/Desktop/AEROUT.command

chmod +x ~/Desktop/AEROUT.command
```

Now you can double-click `AEROUT.command` on your desktop to run it!

---

## 🔧 **What Each Tweak Does**

### 🧹 **1. Clean System**

* **Quick Clean** – Removes junk files (safe!)
* **Deep Clean** – Gets even more junk (asks for password)
* **Browser Clean** – Clears browser data (Chrome, Safari, Firefox)

### 🌐 **2. Speed Up Internet**

* **Flush DNS** – Fixes slow websites
* **Change DNS** – Makes loading faster (Cloudflare, Google, etc.)
* **Gaming Mode** – Reduces lag for online games

### 🖥️ **3. Smoother Mac**

* **Faster Animations** – Speeds up how apps open
* **Dock Boost** – Makes the Dock more responsive
* **Fast Finder** – Quicker to find and open files

### 🔋 **4. Save Battery**

* **Balanced Mode** – Good speed and battery life
* **Max Battery** – Saves the most power
* **Performance Mode** – More speed (uses more battery)

### 🚀 **5. High Performance Tweaks**

* **Free Up RAM** – Makes more memory available
* **App Launch Boost** – Apps open faster
* **System Speed-Up** – General Mac performance boost

### 🎮 **6. Game Mode**

* **Roblox Optimizer** – Better FPS in Roblox
* **Steam Optimizer** – Smoother gameplay in Steam games
* **Game Boost** – Improves performance in all games

### ↩️ **7. Undo Tweaks**

* **Reset All** – Restores everything back to normal

---

## ⚠️ **Warnings & Tips**

* **Always back up your Mac** before using system tweaks
* Some tweaks ask for your **password** (don’t worry, it’s safe)
* **Game Mode** turns off after you restart your Mac—run it again to re-enable

---

## 💬 **Need Help?**

If something’s not working, open an [Issue](https://github.com/wrealaero/AeroutV4Tweaks/issues) on GitHub or message me! [maybeaero on DC]

---

Made with ❤️ by **[RealAero](https://github.com/wrealaero)**
