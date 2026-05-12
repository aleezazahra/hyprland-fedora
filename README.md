# 🌸 Hyprland Fedora Dotfiles

---

## Features

- Pywal Integration(waybar nd terminal)
- Waybar
- Wofi menu
- Kitty terminal
- Wallpapers - swww
- Screenshotting -grim
- Screenrecording - wf-recorder
- shell - zsh


---
# How to use these files



## Installation

### 1. Clone the repository

```bash
git clone https://github.com/aleezazahra/hyprland-fedora.git
cd hyprland-fedora
```

---

### 2. Install dependencies

```bash
sudo dnf install hyprland kitty waybar wofi wlogout fastfetch wl-clipboard grim slurp pywal
```

---

### 3. Copy config files

```bash
mkdir -p ~/.config

cp -r hypr ~/.config/
cp -r kitty ~/.config/
cp -r waybar ~/.config/
cp -r wofi ~/.config/
cp -r wlogout ~/.config/
cp -r fastfetch ~/.config/
```

---

### 4. Setup wallpapers

```bash
mkdir -p ~/Pictures/wallpapers
cp -r wallpapers/* ~/Pictures/wallpapers/
```

---

### 5. Make scripts executable

```bash
chmod +x autostart.sh setup.sh setwall.sh
```

---

### 6. Run setup script (optional coz it's for symlinks hm)

```bash
./setup.sh
```

---

### 7. Start Hyprland

Log out → select **Hyprland session** → log in

---

(I will make a proper script for downloading these files after exams heh)

If you have any questions leave a message on this discord server
https://discord.gg/pfZY7DASk

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V71ZEYNY)


## Notes

* Made for **Fedora + Hyprland (Wayland)**
* Backup your old configs before copying
* Some configs may need minor tweaks depending on your system




## Keybindings

| Action                    | Keybinding               |
|----------------------------|-------------------------|
| Open Wofi Menu             | `Super + D`         |
| Launch Terminal            | `Super + Q`         |
| Change Wallpaper            | `Super + W`         |
| Close Window               | `Super + C`             |
| Switch Workspace           | `Super + 1..9`          |
| Move Window to Workspace   | `Super + Shift + 1..9`  |
| Screenshot                 | `Shift +PrintScreen`          |
| Screen Recording  | `Super + R`  |
| Ending Screen recording  | `Super + Shift + R`  |
---



### If you like this setup, consider starring the repo! <3



## Screenshots
(MIKU MIKU MIKU MIKU )
<img width="1361" height="769" alt="image" src="https://github.com/user-attachments/assets/2b03de0d-73cd-4b89-96fb-b9eef9a295c8" />

<img width="1366" height="769" alt="image" src="https://github.com/user-attachments/assets/f2e9ed2e-7836-49aa-8ebe-e45f36471ddb" />



<img width="1367" height="769" alt="image" src="https://github.com/user-attachments/assets/55af4d95-efa6-4db7-95c3-e84527538798" />


<img width="1367" height="769" alt="2026-02-03-223226_hyprshot" src="https://github.com/user-attachments/assets/5a6e47ae-9758-4905-b292-2011294dcc8b" />









