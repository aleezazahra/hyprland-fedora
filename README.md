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
<img width="1367" height="768" alt="image" src="https://github.com/user-attachments/assets/7d7c36eb-efa2-4d70-b78a-760fc5567c98" />

<img width="1367" height="769" alt="image" src="https://github.com/user-attachments/assets/55af4d95-efa6-4db7-95c3-e84527538798" />

<img width="1367" height="769" alt="image" src="https://github.com/user-attachments/assets/3773b6dd-bd34-426f-9e4d-184e8583cf8e" />

<img width="1367" height="769" alt="2026-02-03-223226_hyprshot" src="https://github.com/user-attachments/assets/5a6e47ae-9758-4905-b292-2011294dcc8b" />
<img width="1367" height="769" alt="2026-02-03-223252_hyprshot" src="https://github.com/user-attachments/assets/e496b9c8-0c81-4d7d-a811-4469955ceba7" />







