# HyprMode

HyprVim is a **keybinding layer for [Hyprland](https://github.com/hyprwm/Hyprland)** that emulates the modal editing style of **Vim/Vi/Helix** and the shortcuts from **Emacs**.
---

## ✨ Features

* Easy to switch between Vim, Emacs, and Helix keybinding layers.
* Configurable via simple Hyprland configuration files.

---

## 📦 Installation

Clone this repository:

```bash
git clone https://github.com/offGustavo/HyprVim
```

### Fork Instructions

1. Go to the project page on GitHub:
   [https://github.com/offGustavo/HyprVim](https://github.com/offGustavo/HyprVim)

2. Click the **"Fork"** button in the top-right corner.
   This will create a copy of the repository under your GitHub account.

3. Clone your fork locally:

   ```bash
   git clone https://github.com/<your-username>/HyprVim
   ```

   Replace `<your-username>` with your GitHub username.

4. (Optional) Add the original repository as a remote to keep your fork up to date:

   ```bash
   cd HyprVim
   git remote add upstream https://github.com/offGustavo/HyprVim
   ```

5. You can now work on your fork, create branches, and push changes.
   To sync with the original repo later:

   ```bash
   git fetch upstream
   git merge upstream/main
   ```

---

## 🔀 Choosing a Mode

Switch to the branch that matches the keybinding style you want to use:

```bash
# Vim/Vi motions
git switch vim-mode

# Emacs keybindings
git switch emacs-mode

# Helix motions (WIP)
git switch helix-mode
```

Then copy the configuration snippets into your Hyprland config.

---

## ⚠️ Limitations

* Some motions may behave differently due to native keybinding system.
* Advanced motions (like text-objects or registers) are not supported.

---

## 🤝 Contributing

* If you find behavior that doesn’t match the original Vim/Vi/Helix/Emacs keybindings, feel free to **open an issue** or **submit a pull request**.
* Keep in mind some motions cannot be perfectly replicated due to Hyprland limitations.

---
