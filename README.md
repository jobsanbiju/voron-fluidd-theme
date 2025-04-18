# Custom Voron Fluidd Theme

This repository contains a custom theme for the Fluidd web interface, tailored for Voron users. The theme includes a modern blurred background and optional support for logo customization via CSS. It is based on the Voron Community Theme but without the default logo.

## Features

- **Blurred Background:** Enhances UI aesthetics.
- **Custom Background Support:** By replacing the included `background.png` with your own image, you can personalize it however you want to.

---



## Installation Instructions 

### Step 1: Access the Configuration Page. 

1. Open your Fluidd web interface.
2. Navigate to the **Config** section.

### Step 2: Create the `.fluidd-theme` Directory. 

1. In the **Config** section, create a new directory named `.fluidd-theme`.

![Create .fluidd-theme Directory Screenshot](https://github.com/jobsanbiju/voron-fluidd-theme/raw/main/screenshots/config%20screenshot.png)

### Step 3: Upload Theme Files.  

1. Inside the `.fluidd-theme` directory:
   - Upload `background.png` for the background image.
   - Upload `custom.css` for the blurred theme settings.

![Upload Theme Files Screenshot](https://github.com/jobsanbiju/voron-fluidd-theme/raw/main/screenshots/fluid-theme%20screenshot.png)

### Step 4: Refresh Fluidd

1. Save the configuration and refresh the Fluidd web interface.
2. The new theme will be applied automatically.

---

## Final Look

After following the steps above, your Fluidd interface should look like this:

![Final Theme Look](https://github.com/jobsanbiju/voron-fluidd-theme/raw/main/screenshots/main%20page.png)

---

## File Structure

```
.
├── .fluidd-theme/
│   ├── background.png
│   ├── custom.css
├── README.md
```

---

## Troubleshooting

- If the theme doesn’t apply, ensure the `.fluidd-theme` folder is correctly placed and contains both `background.png` and `custom.css`.
- Restart Moonraker and refresh the Fluidd interface.

---

## License

[MIT License](https://opensource.org/license/mit)

Feel free to customize and share this theme!

---
