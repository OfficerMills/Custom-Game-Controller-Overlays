 <div align="center" style="width: 100%; border: 1px solid #444; border-radius: 8px; overflow: hidden;">

  <div style="background-color: #1f1f1f; color: #ffffff; padding: 12px 16px; font-weight: bold; font-size: 16px; border-bottom: 1px solid #444;">
    NIXSTAH | OBS CONTROLLER OVERLAY
  </div>

  <img
    src="https://github.com/user-attachments/assets/293763d9-3ca3-4fc8-b1a2-6572723d6bf7"
    alt="NIXSTAH OBS Controller Overlay"
    width="100%"
    style="display: block; width: 100%; max-width: 100%; height: auto;"
  />

</div>

# 🎮 Custom Game Controller Overlays

Custom game controller overlays designed exclusively for **OBS Studio**. These overlays display your controller inputs on stream, allowing viewers to see your button presses and other inputs in real time.

This repository includes custom overlay designs and their configuration files. They run through the third-party [Input Overlay](https://github.com/univrsal/input-overlay) plugin, which **must be installed in OBS Studio** before these overlays can be used.

> **📌 Important:** These overlays require OBS Studio and the Input Overlay plugin. They are not standalone applications and are not designed for other streaming software.

> [**▶️ SEE EXAMPLES**](https://github.com/OfficerMills/Custom-Game-Controller-Overlays/blob/main/README.md#-youre-all-set)

## 📥 Installation Instructions

### Step 1 — Download the Files

1. Download this repository as a ZIP file.
2. Extract the ZIP file to a location of your choice.

### Step 2 — Install the Input Overlay Plugin

1. Open **Folder `A`**.
2. Run the included `.exe` installer.
3. Follow the installation prompts to install the Input Overlay plugin.
4. Restart OBS Studio if required by the installer.

> **Note:** Input Overlay is a third-party OBS plugin developed by [UNIVRSAL](https://github.com/univrsal). Refer to the [official Input Overlay repository](https://github.com/univrsal/input-overlay) for documentation, releases, and licensing information.

### Step 3 — Install the Custom Controller Overlay

1. Open **Folder `B`**.
2. Locate and copy the folder named `Controller Overlay NIXSTAH`.
3. Paste it into the location where you store your custom OBS overlay assets.

**Important:** Keep the `.png` image and matching `.json` configuration file together in the same folder. Both files are required for the overlay to function correctly.

### Step 4 — Add the Overlay to OBS Studio

1. Open OBS Studio.
2. Select the scene where you want the controller overlay to appear.
3. In the **Sources** panel, click **`+`**.
4. Select **Input Overlay**.
5. In the source properties window:
   - Click **Browse** for the image field and select the overlay's `.png` file.
   - Click **Browse** for the configuration field and select the matching `.json` file from the same folder.
6. Apply the settings.
7. Position and resize the overlay within your OBS scene to suit your stream layout.

![Input Overlay source configuration](image.png)

## ⚙️ Additional Settings

The Input Overlay plugin also provides additional settings directly within OBS Studio.

To access them, open the **Tools** menu at the top of OBS Studio and select the Input Overlay settings option.

![Input Overlay settings menu](image-1.png)

## ✅ You're All Set!

Your custom NIXSTAH controller overlay should now be ready to use in your OBS Studio scene.

Customize its position and size to fit your layout, then test your controller inputs to verify that everything displays correctly.

If the overlay does not appear or function as expected, check the following:

- The Input Overlay plugin is installed correctly.
- You selected the correct `.png` image file.
- You selected the matching `.json` configuration file.
- Both files remain together in the same folder.
- OBS Studio has been restarted if required after plugin installation.

### 🎬 Overlay Examples

See the overlays in action:

<div align="center">
  <table>
    <tr>
      <td>
        <video src="https://github.com/user-attachments/assets/8f4a8c69-a899-4374-bb58-5563f0f86e51" width="400" controls></video>
      </td>
      <td>
        <video src="https://github.com/user-attachments/assets/dd66200b-0de9-469b-94e9-5c6e85b18a77" width="400" controls></video>
      </td>
    </tr>
  </table>
</div>

---

## 📜 Credits & Third-Party Software

### Input Overlay

This project uses **Input Overlay**, an OBS Studio plugin developed by **[UNIVRSAL](https://github.com/univrsal)**.

Input Overlay provides the underlying functionality for displaying keyboard, mouse, and gamepad inputs within OBS Studio. The custom overlay designs and their associated configuration files included in this repository are my own contributions, unless otherwise indicated.

- **Original project:** [univrsal/input-overlay](https://github.com/univrsal/input-overlay)
- **Original author:** [UNIVRSAL](https://github.com/univrsal)
- **Original license:** [GNU General Public License v2.0 (GPL-2.0)](https://github.com/univrsal/input-overlay/blob/master/LICENSE)

All credit for the original Input Overlay plugin belongs to its original author. This repository is an independent project and is not affiliated with, endorsed by, or officially associated with UNIVRSAL or the Input Overlay project.

The original plugin remains subject to its own copyright notices and license terms. Please refer to the [official repository](https://github.com/univrsal/input-overlay) for its source code, releases, documentation, and complete licensing information.
