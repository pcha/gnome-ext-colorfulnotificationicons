# 🎨 Colorful Notification Icons

<div align="center">
  <img src="icon.svg" alt="Extension Icon" width="128px">
</div>


GNOME Shell applies a grayscale (symbolic) filter to notification icons by default.  
This extension disables that behavior, allowing notification icons to keep their original colors.

## ✨ Features
- Removes the grayscale effect from notification icons.
- Works with **GNOME Shell 46 or later**.

## 🔧 Installation
1. Download the extension ZIP file.
2. Move it to `~/.local/share/gnome-shell/extensions/`.
3. Extract the ZIP and ensure the folder name matches the UUID:  
   ```bash
   mv colorfulnotificationicons@pcha.zip ~/.local/share/gnome-shell/extensions/
   cd ~/.local/share/gnome-shell/extensions/
   unzip colorfulnotificationicons@pcha.zip
   ```
4. Enable the extension:
   ```bash
   gnome-extensions enable colorfulnotificationicons@pcha
   ```
5. Restart GNOME Shell (`Alt + F2`, type `r`, and press Enter) or log out and log back in.

## 🛠️ Uninstallation
To remove the extension:
```bash
gnome-extensions disable colorfulnotificationicons@pcha
rm -rf ~/.local/share/gnome-shell/extensions/colorfulnotificationicons@pcha
```

## 📜 License
This project is licensed under the **GNU General Public License v2.0 or later (GPL-2.0-or-later)**.

---

### 📩 Need Help?  
If you have any issues or suggestions, feel free to open an issue on GitHub!

## 🙌 Acknowledgments
Special thanks to **[@EvelynMathews](https://evelynmathews.my.canva.site/portfolio)** for designing the icon for this extension.  
Licensed under **GPL-2.0-or-later**.