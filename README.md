
<img width="720" height="200" alt="logomaxui" src="https://github.com/user-attachments/assets/a30600ae-5d68-4cd7-a706-1d869885a7a4" />

## Credits & Attribution

This project stands on the shoulders of giants. Special thanks to:

* **[Shauninman](https://github.com):** For the incredible base architecture of MinUI.
* **[JELOS Team / Just Enough Linux OS](https://github.com):** For their major contributions to the underlying system code, scripts, and hardware optimization that made this fork possible on the RGB30.

# MaxUI

MaxUI is a reinterpretation of MinUI for the RGB30.






## Features

- Game Switcher
- Cheat support
- RetroAchievements (online and offline)
- Music Player
- File transfer via SSH and HTTP
- Minarch-style menu for Pico-8 and Nintendo DS
- Mouse emulation for Pico-8
- MinUI Sleep and auto-resume support for all systems
- Home screen with dedicated sections for MinUI, RetroAchievements, and Pico-8
- Screenshot viewer
- Automatic time sync
- Bluetooth audio support
- Save State Manager




## Screenshots

| Game Switcher | Cheats | Time Zone |
| --------- | --------- | --------- |
| <img width="360" height="360" alt="20261026-183801" src="https://github.com/user-attachments/assets/3fa1282c-ceb3-44b0-8475-9a6cb1bda985" /> | <img width="360" height="360" alt="20261026-183811" src="https://github.com/user-attachments/assets/87032897-64c4-4be3-b02c-5e7c24fdcb39" /> | <img width="360" height="360" alt="20261026-183853" src="https://github.com/user-attachments/assets/1d620cef-b1ee-4053-a123-217993d1baad" /> |


<table>
  <tr>
    <th colspan="3" align="center">RetroAchievements</th>
  </tr>
  <tr>
    <td align="center">
    <img width="360" height="360" alt="20261027-034330" src="https://github.com/user-attachments/assets/beae4132-3290-435b-a0ef-ac3a0e68f70d" />
    </td>
    <td align="center">
      <img width="360" height="360" alt="20261027-092947" src="https://github.com/user-attachments/assets/33eb3eef-ffe2-4222-ab6b-0ae0e5250cff" />
    <td align="center">
    <img width="360" height="360" alt="20261027-093002" src="https://github.com/user-attachments/assets/614091d5-7916-45ca-afb5-facc599a2f36" />
  </tr>
</table>

<table>

  <tr>
    <th colspan="3" align="center">Music Player & Image Viewer</th>
  </tr>

  <tr>
    <td align="center">
   <img width="360" height="360" alt="20261026-184146" src="https://github.com/user-attachments/assets/b7107aed-4593-48c6-b7c7-ec5dc21d9306" />
   </td>
    <td align="center">
     <img width="360" height="360" alt="20261026-184117" src="https://github.com/user-attachments/assets/91d29ce3-0d68-487c-b6c7-9aed6223da17" />
    </td>
    <td align="center">
    <img width="360" height="360" alt="20261027-004334" src="https://github.com/user-attachments/assets/5464336b-3d27-4ec3-afbc-8d84b5f6ec4c" />
  </tr>
</table>

> [!TIP]
> The Media Player runs MP3s and images from the "Music" and "Screenshots" folders on the SD card in slot 2.

| MinUI Mode | Pico-8 Mode | RA Mode |
| --------- | --------- | --------- |
| <img width="360" height="360" alt="20261023-035832" src="https://github.com/user-attachments/assets/3bd49446-d325-4d47-8bbd-6ae5bb991171" />| <img width="360" height="360" alt="20261026-183944" src="https://github.com/user-attachments/assets/00a752f0-4a5c-4f54-834f-71574eeb904f" />| <img width="360" height="360" alt="20261026-185144" src="https://github.com/user-attachments/assets/6f6769f0-0178-4f5b-ac29-4df5264e3b77" />|
> [!NOTE]
>  - **MinUI:**  Classic home screen layout.
>  - **Pico-8:**  Automatically downloads your favorite Splore games and shows them in a grid. 
>  - **RA:**  Your RetroAchievements profile details.

<table>

  <tr>
    <th colspan="3" align="center">Options</th>
  </tr>

  <tr>
    <td align="center">
   <img width="360" height="360" alt="20261026-183831" src="https://github.com/user-attachments/assets/d6f971ba-eeaf-4b0c-b939-fc8ec98b7e77" />
    </td>
    <td align="center">
    <img width="360" height="360" alt="20261026-183909" src="https://github.com/user-attachments/assets/17385ee2-a16a-4c03-8f5b-38357e6fbfa1" />
    </td>
    <td align="center">
    <img width="360" height="360" alt="20261026-183903" src="https://github.com/user-attachments/assets/d634a546-9ce1-4a5a-802b-11e94ea6b926" />


</table>

<table>

  <tr>
    <th colspan="3" align="center">HTTP File Transfer</th>
  </tr>

  <tr>
    <td align="center">
   <img width="722" height="503" alt="Captura de pantalla 2026-10-26 a la(s) 6 47 40 PM@2x" src="https://github.com/user-attachments/assets/1d249d35-31b6-4dec-b3ee-995dfe8a5152" />
    </td>
    <td align="center">
    <img width="722" height="503" alt="Captura de pantalla 2026-10-26 a la(s) 6 47 51 PM@2x" src="https://github.com/user-attachments/assets/89f24d75-9d5d-49a3-9b20-40a381bf6598" />
    </td>
    <td align="center">
    <img width="722" height="503" alt="Captura de pantalla 2026-10-26 a la(s) 6 48 34 PM@2x" src="https://github.com/user-attachments/assets/57655765-1554-42dc-8471-f53eafbe34f6" />

</table>

> [!IMPORTANT]
> ## Installation
> 1. **Format the Slot 1 SD card** and flash the `MOSS-RGB30-MaxUI.img.gz` image using a tool like **Balena Etcher**.
> 2. **Format the Slot 2 SD card** and copy the `MaxUI.zip` file to its root directory. (Also, add your copy of the Raspberry Pi version of the Pico-8 `.zip` file, purchased from [Lexaloffle](https://lexaloffle.com), to the root directory).
> 3. **Insert both SD cards** into the console and power it on. The installation process may take a few minutes, and the console will reboot automatically.
> 4. **Once on the home screen**, you can start configuring the frontend by pressing **L3** or **R3** to access the **MaxUI Options** menu.

---
> [!NOTE]
>#### Setting up RetroAchievements (RA Mode)
>To use RA Mode, you need to configure your internet connection and account details:
>1. **Connect to Wi-Fi:** Go to `Connectivity` > `Wi-Fi` and set up your network.
>2. **Link your Account:** Go to the `RetroAchievements` menu and configure your profile.
>3. **Enter your API Key:** You must enter your RetroAchievements API key via the web-based File Transfer tool.
   >* To enable it, navigate to `Connectivity` > `Wi-Fi` > `File Transfer`.
   >* Once activated, press **(A)** to view the connection details and access it from your computer's browser.

> [!TIP]
> #### Adding Cheats
>To add cheats to your games, simply extract the `Cheats.zip` file directly to the root directory of the **Slot 2 SD card**.
