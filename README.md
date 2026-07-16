# 🌌 CustomizableTyufunTheme

A fully customizable, modern, and transparent Discord theme built for **Vencord**, **BetterDiscord**, and other client modifications. It features deep transparency effects, custom background images, personalized font integrations, Spotify player fine-tuning, and dynamic layout adjustments.

![Theme Preview](https://raw.githubusercontent.com/TYUFUN/CustomizableTyufunTheme/main/preview.png)

---

## ✨ Features

- **🖼️ Dual Background System:** Configure different background images for your main client screen and your settings overlay.
- **✨ Full Transparency Control:** Fine-tune alpha channels (`rgba`) for the main workspace, Spotify player, control panel, message input, and context menus.
- **🔤 Custom Typography Support:** Seamlessly import any web font (such as Google Fonts) and apply it globally.
- **🎵 Built-in Spotify Panel Support:** Adjust the height and opacity of your Vencord Spotify player.
- **📱 Server List Layouts:** Arrange your server list into multiple columns and custom slot sizes.
- **🎨 Personalized Accents:** Custom styling for scrollbars, hover states, mentions, and even the Private Messages (DM) icon.

---

## 🚀 Installation

1. Download the `CustomizableTyufunTheme.css` file from this repository.
2. Move the downloaded file into your client's themes folder:
   - **Vencord:** Settings -> Themes -> Open Themes Folder.
   - **BetterDiscord:** Settings -> Themes -> Open Themes Folder.
3. Enable **CustomizableTyufunTheme** in your client settings toggles.

---

## 🛠️ Customization Guide (For Beginners)

If you are new to editing CSS files, open the `.css` file in any text editor and follow this quick guide to tweak the settings inside the `:root { ... }` block:

### 1. Understanding Transparency and Colors (`rgba`)
Colors in this theme are configured using the **RGBA** format: `rgba(red, green, blue, alpha)`.
- `red`, `green`, `blue` values range from `0` to `255` (representing the color mix).
- `alpha` (the last number) controls the transparency and ranges from `0` (completely invisible) to `1` (solid color).
- **Example:** `rgba(0, 0, 0, 0.3)` is a black color block with `30%` opacity, allowing your custom background image to beautifully show through. You can use any online color picker to get these values.

### 2. Using Custom Backgrounds
You can use any image from public image hosting platforms (like **GitHub**, **Imgur**, **Codeberg**, or **GitLab**) as your background.
- Make sure your link is a direct link to the image and ends with a proper file extension (such as `.png`, `.jpg`, `.jpeg`, or `.gif`).
- **Example format:** `url([https://i.imgur.com/YOUR_IMAGE_ID.jpeg](https://i.imgur.com/YOUR_IMAGE_ID.jpeg))`

### 3. Activating Your Custom Font
1. Go to [Google Fonts](https://fonts.google.com/) or another hosting platform and choose a font.
2. Copy the `@import` link they provide and paste it at the top of your theme configuration file.
3. Update the `--font` variable with the exact name of your font:
```css
--font: 'Your Imported Font Name';

```
## 🤝 Contribution & Feedback

If you find any bugs or have feature requests, feel free to open an **Issue** or submit a **Pull Request** in this repository[cite: 1]!

Created with ❤️ by **[TYUFUN](https://github.com/TYUFUN)**.