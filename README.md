# Hyprland Fedora Config

##### first ever ugly ah rice js how I like em
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

##  Requirements

* Fedora (recommended latest)
* Wayland session
* Hyprland

---

## Packages

Install the required packages:

```bash
sudo dnf install hyprland kitty waybar wofi wlogout wl-clipboard grim slurp
```

You may need additional packages depending on your system.

---

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
```

---

### 2. Copy config files

```bash
cp -r hypr ~/.config/
cp -r kitty ~/.config/
cp -r waybar ~/.config/
cp -r wofi ~/.config/
cp -r wlogout ~/.config/
```

---

### 3. Setup wallpapers

```bash
mkdir -p ~/Pictures/wallpapers
cp -r wallpapers/* ~/Pictures/wallpapers/
```

---

### 4. Make scripts executable

```bash
chmod +x autostart.sh setup.sh setwall.sh
```

---

### 5. (Optional) Run autostart script

```bash
./autostart.sh
```

---

### 6. Start Hyprland

Log out → select **Hyprland** session → log in

---


---

## Notes

* This setup is made for **Fedora + Hyprland (Wayland)**
* Backup your existing configs before copying
* Some elements may require manual tweaking depending on your system

---



## ⭐ Support

If you like this setup, consider starring the repo!



---

## Keybindings

| Action                    | Keybinding               |
|----------------------------|-------------------------|
| Open Wofi Menu             | `Super + D`         |
| Launch Terminal            | `Super + Q`         |
| Change Wallpaper            | `Super + W`         |
| Close Window               | `Super + C`             |
| Switch Workspace           | `Super + 1..9`          |
| Move Window to Workspace   | `Super + Shift + 1..9`  |
| Screenshot                 | `SHift +PrintScreen`          |
| Screen Recording  | `Super + R`  |
| Ending Screen recording  | `Super + Shift + R`  |
---

## Screenshots
<img width="1367" height="768" alt="image" src="https://github.com/user-attachments/assets/7d7c36eb-efa2-4d70-b78a-760fc5567c98" />

<img width="1367" height="769" alt="2026-02-03-222843_hyprshot" src="https://github.com/user-attachments/assets/6e72767a-26ae-48bd-8472-48f213c2c367" />





<img width="1367" height="769" alt="2026-02-03-223147_hyprshot" src="https://github.com/user-attachments/assets/530aed8d-1c37-425e-bb92-445e2f977ea5" />
<img width="1367" height="769" alt="image" src="https://github.com/user-attachments/assets/3773b6dd-bd34-426f-9e4d-184e8583cf8e" />

<img width="1367" height="769" alt="2026-02-03-223226_hyprshot" src="https://github.com/user-attachments/assets/5a6e47ae-9758-4905-b292-2011294dcc8b" />
<img width="1367" height="769" alt="2026-02-03-223252_hyprshot" src="https://github.com/user-attachments/assets/e496b9c8-0c81-4d7d-a811-4469955ceba7" />







