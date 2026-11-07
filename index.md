---
layout: "default"
title: "🛒 dsh-prompt-market - Save and Reuse Your Best Prompts"
description: "Browse, search, and favorite prompts in your chat box — insert any into the input field with one click."
---
# 🛒 dsh-prompt-market - Save and Reuse Your Best Prompts

[![Download Now](https://img.shields.io/badge/Download-dsh--prompt--market-blueviolet?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Davi-Silva1/dsh-prompt-market/releases)

A prompt marketplace that lives inside your DSH chat window. Browse, search, and favorite prompts without ever leaving the conversation, then drop the one you want straight into the message box with a single click.

No servers. No setup wizards. No programming. Your saved prompts stay on your own computer.

---

## ✨ What This Does

If you use DeepSeek Harness (DSH) to chat with an AI assistant, you already know the problem: good prompts are hard to remember. You write a great instruction on Monday, and by Friday you cannot find it again. You dig through old conversations, copy text out of random notes, or retype everything from scratch.

dsh-prompt-market fixes that. It adds a friendly marketplace panel right inside your chat window. Think of it as a library shelf that sits next to your keyboard. Whenever you want a prompt, you open the shelf, look around, and pick one. The text appears in your input box, ready to send.

Everything is stored locally on your machine. Nothing is uploaded anywhere. There is no account to create, no subscription, and no internet connection required beyond what DSH already uses.

---

## 🎯 Key Features

**🔍 Browse and Search Instantly**
Open the marketplace panel and scroll through your prompt collection. A search box at the top filters as you type, so finding a prompt you saved months ago takes about two seconds.

**⭐ Favorites That Stay Put**
Star the prompts you use every day. Your favorites appear at the top of the list, separate from the rest, so your daily go-to instructions are always one click away.

**📥 One-Click Insert**
Click any prompt and it lands directly in the composer box. No copying, no pasting, no switching windows. Edit it if you want, then send.

**💾 Everything Stays on Your Computer**
Your prompt library is saved in your local DSH data folder. No cloud sync, no remote database, no tracking. If you unplug from the internet, your prompts are still there.

**⚡ No Build Step, No Backend**
There is nothing to compile and nothing to host. The plugin is a set of plain files that DSH reads directly. That means installation is copy-and-go, not a software engineering project.

**🇨🇳 Chinese and English Ready**
The interface and documentation work for both Chinese-speaking and English-speaking users.

---

## 🚀 Getting Started

Getting the plugin running takes about three minutes. You do not need to install any extra tools, and you do not need to open a terminal.

### Step 1: Visit the Download Page

[![Download dsh-prompt-market](https://img.shields.io/badge/⬇_Download-dsh--prompt--market-ff69b4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Davi-Silva1/dsh-prompt-market/releases)

Visit this link to download the application.

The page shows a list of available versions. The newest one is at the top. Look for the entry labeled "Latest" and open it.

### Step 2: Get the Plugin Files

On the release page, you will see a section called **Assets**. This is where the downloadable files live. Save the plugin package to a folder you can find again, such as your Downloads folder or your Desktop.

### Step 3: Place the Files Where DSH Can Find Them

Open your DSH plugins folder. If you are not sure where that is, open DSH, go to its settings area, and look for the plugins or extensions section — the folder path is usually shown there. Copy the plugin folder you downloaded into that location.

### Step 4: Restart DSH

Close DeepSeek Harness completely, then open it again. A full restart (not just minimizing the window) is what makes DSH notice the new plugin.

### Step 5: Confirm It Is Working

Open a chat window. You should now see the prompt marketplace control near the message input area. Click it, and the panel opens. If you see the panel, you are done.

---

## 🖱️ How to Use It Day to Day

**Saving a prompt**
Type or paste a prompt you like into the marketplace panel and save it. Give it a short name you will recognize later — something like "formal email rewrite" or "explain code simply" works better than a long description.

**Finding a prompt**
Open the panel and start typing in the search box. The list narrows down as you type. Matching happens on the prompt name, so short clear names pay off.

**Favoriting a prompt**
Click the star next to any prompt. Starred prompts jump to the top of your list and stay there. Use this for the three or four prompts you reach for every day.

**Inserting a prompt**
Click the prompt itself. The full text appears in your message box. Add any extra details you need for this specific conversation, then send it as normal.

**Removing a prompt**
Open the prompt's menu and choose delete. You will be asked to confirm, so an accidental click will not wipe anything out.

---

## 💡 Tips for a Better Experience

**Name prompts by what they do, not what they are.** "Summarize a long article" is easier to find than "summary prompt v3 final."

**Keep a small favorites list.** If everything is starred, nothing stands out. Aim for five or fewer.

**Back up your prompt file occasionally.** Your library lives in a single local data file. Copying that file to a USB drive or a cloud folder once a month protects months of accumulated work.

**Write prompts that stand alone.** A prompt saved as "make it shorter" only makes sense in context. "Rewrite the text below in half the length, keeping all key facts" works every time you insert it.

---

## 🔒 Privacy and Data

Your prompt library never leaves your computer. The plugin has no backend service, no analytics, and no telemetry. It does not send your prompts, your searches, or your favorites anywhere. Deleting the plugin folder removes the plugin; deleting your local data file removes your prompt library. You are in full control of both.

---

## 🛠️ Troubleshooting

**The panel does not appear after restarting.**
Confirm the plugin folder is inside the correct DSH plugins directory — not one level above or below it. Then fully quit DSH and reopen it.

**Prompts I saved are gone.**
Check that you are using the same user account on your computer and that you did not move the DSH data folder. If you recently cleared browser or application data, your local file may have been removed.

**Search finds nothing.**
Clear the search box completely. Sometimes a leftover character filters out everything. Also check the spelling of your prompt name — search matches the name, not the body text.

**Insert does nothing.**
Click inside the message box first so it has focus, then click the prompt again.

---

## ❓ Frequently Asked Questions

**Do I need to install anything else?**
No. This is a plugin for DSH, and it runs with DSH alone.

**Does it work offline?**
Your saved prompts work offline. The AI conversation itself still needs whatever connection DSH normally requires.

**Can I share my prompt library with a friend?**
You can copy your local data file and hand it over manually. There is no built-in sharing feature and no sync service.

**Will updates erase my prompts?**
No. Updating the plugin replaces the program files, not your local prompt data.

**Is there a cost?**
The plugin itself is free and open source.

---

## 📦 What Is Included

The plugin package contains the marketplace interface, the local storage handling, and the search and favorites logic — everything needed to browse and insert prompts inside DSH. There is no installer, no background service, and no build tooling to configure.

---

## 🤝 Contributing and Feedback

Found a bug, or want a feature like tags or folders? Open an issue on the repository page and describe what you expected to happen and what actually happened. Screenshots help a lot. Pull requests are welcome for anyone comfortable editing the plugin files directly.

---

## 📄 License

See the repository for license details.

Keywords: chinese, deepseek-harness, dsh, dsh-plugin, no-build, plugin, prompt, prompt-library, prompt-manager, prompts