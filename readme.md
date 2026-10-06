```markdown
<div align="center">

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/joystick.svg" width="80" height="80" alt="Controller" />

# Legacy Los Santos

### Installation Guide for PC, Android, KeyListener ASI, and open.mp

<img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />
<img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
<img src="https://img.shields.io/badge/Game-GTA%20San%20Andreas-000000?style=for-the-badge&logo=rockstargames&logoColor=white" alt="GTA SA" />
<img src="https://img.shields.io/badge/Client-SA--MP%20%7C%20open.mp-2C2C2C?style=for-the-badge" alt="SA-MP" />
<img src="https://img.shields.io/badge/License-Free-4CAF50?style=for-the-badge" alt="License" />

<br />

**Server Address**

```

45.127.35.54:7063

```

**Discord Community**

```

https://discord.gg/45m9Tcwrh

```

</div>

---

## Table of Contents

| Icon | Section | Language |
|:----:|:--------|:---------|
| <img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/windows.svg" width="16" /> | [PC Installation](#pc-installation) | English |
| <img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/android2.svg" width="16" /> | [Android Installation](#android-installation) | English |
| <img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/key.svg" width="16" /> | [KeyListener ASI](#keylistener-asi-installation) | English |
| <img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/plus-circle.svg" width="16" /> | [open.mp Client](#openmp-client-installation) | English |
| <img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/translate.svg" width="16" /> | [Panduan Bahasa Indonesia](#panduan-bahasa-indonesia) | Indonesia |
| <img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/wrench-adjustable.svg" width="16" /> | [Troubleshooting](#troubleshooting) | Both |

---

## PC Installation

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/windows.svg" width="24" /> **Platform:** Windows 10 or Windows 11 (64-bit recommended)

### Step 1 - Install GTA San Andreas

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Install **GTA San Andreas** from Steam, Rockstar Launcher, or a legitimate retail copy.

- Recommended version: **v1.0 US** (most compatible with SA-MP and open.mp)
- Do **not** use the Definitive Edition

</td>
</tr>
</table>

### Step 2 - Install SA-MP 0.3.7 R5 Client

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Download the **SA-MP 0.3.7 R5** client from the official mirror.

1. Run the installer as Administrator
2. Point the installer to your GTA San Andreas folder:

```

C:\Program Files (x86)\Rockstar Games\GTA San Andreas\

```

3. Confirm installation and wait until it completes

</td>
</tr>
</table>

### Step 3 - Install CLEO Library

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

CLEO is required for most SA-MP mods including HUDs and visual enhancements.

1. Download **CLEO 4.3** or **CLEO 5.0**
2. Extract the archive
3. Copy all files into the GTA San Andreas folder
4. A new folder named `CLEO` will be created automatically

</td>
</tr>
</table>

### Step 4 - Install ASI Loader

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

The ASI Loader allows the game to read `.asi` plugin files.

1. Download `vorbisFile.dll` and `vorbisHooked.dll` from the ASI Loader package
2. Place both files into the GTA San Andreas folder
3. Overwrite when prompted

</td>
</tr>
</table>

### Step 5 - Install Legacy Los Santos Mods

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/5-circle-fill.svg" width="32" /></td>
<td>

1. Download the Legacy Los Santos mod pack from the Discord release channel
2. Extract all `.txd` and `.dff` files into `models\generic\` inside the GTA SA folder
3. Place any `.asi` files directly in the GTA SA root folder
4. Place any `.cs` or `.cleo` files inside the `CLEO` folder

</td>
</tr>
</table>

### Step 6 - Connect to the Server

Launch `samp.exe`, then connect to:

```

45.127.35.54:7063

```

---

## Android Installation

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/android2.svg" width="24" /> **Platform:** Android 8.0 or higher

### Step 1 - Install the Game

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Install **GTA San Andreas** from Google Play Store or side-load the APK and OBB files manually.

- Place the OBB file at: `Android/obb/com.rockstargames.gtasa/`
- Ensure the game runs once before installing any client mod

</td>
</tr>
</table>

### Step 2 - Install SA-MP Mobile

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Install one of the following clients:

| Client | Package | Compatibility |
|:-------|:--------|:--------------|
| SA-MP Mobile | `com.samp.mobile` | Android 9+ |
| Alyn SA-MP Mobile | `ro.alynsampmobile.launcher` | Android 7+ |
| SA-MP Launcher | `com.samp.launcher` | Android 8+ |

Download the APK from the official Discord channel and allow installation from unknown sources.

</td>
</tr>
</table>

### Step 3 - Install CLEO for Android

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

1. Download **CLEO Android** version 2.0.1.0 or newer
2. Install the APK
3. Grant storage permission on first launch

</td>
</tr>
</table>

### Step 4 - Copy Mod Files

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

Place the Legacy Los Santos mod files in the following directories:

```

/sdcard/Android/data/com.rockstargames.gtasa/files/
models/generic/          <- .txd and .dff files

/sdcard/CLEO/                <- .cs and .cleo files

```

Use a file manager such as **MT Manager** or **Zarchiver** to move files.

</td>
</tr>
</table>

### Step 5 - Connect

Open the SA-MP Mobile client and add the server:

```

45.127.35.54:7063

```

---

## KeyListener ASI Installation

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/key.svg" width="24" /> The KeyListener plugin allows custom hotkeys inside the game, useful for opening the Legacy Los Santos menu, interactive HUD, or roleplay commands.

### Requirements

- SA-MP 0.3.7 R5 or newer
- ASI Loader already installed (see PC Installation Step 4)
- Microsoft Visual C++ Redistributable 2015-2022

### Installation Steps

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Download **KeyListener.asi** and **KeyListener.ini** from the official source.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Place both files inside the GTA San Andreas root folder, next to `samp.exe`.

```

C:\Program Files (x86)\Rockstar Games\GTA San Andreas
    KeyListener.asi
KeyListener.ini
samp.exe
gta_sa.exe

```

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

Open `KeyListener.ini` with Notepad and configure the hotkeys.

```ini
[Keys]
Menu=0x4D
Chat=0x54
Inventory=0x49
Phone=0x50
```

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

Save the file and launch samp.exe. If the game crashes, verify that the ASI Loader is properly installed and that the Visual C++ Redistributable is up to date.

</td>
</tr>
</table>

Common Key Codes

Key Hex Code Function
F1 0x70 Help panel
F2 0x71 Server info
M 0x4D Menu
T 0x54 Chat
I 0x49 Inventory
P 0x50 Phone

---

open.mp Client Installation

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/plus-circle.svg" width="24" /> **open.mp** is a modern open-source alternative to SA-MP. It supports both SA-MP and open.mp servers.

Step 1 - Download open.mp Launcher

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Visit the official website at open.mp and download the latest launcher for Windows.

Alternatively, download directly from GitHub:

```
https://github.com/openmultiplayer/launcher/releases/latest
```

</td>
</tr>
</table>

Step 2 - Install the Launcher

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

1. Run the installer as Administrator
2. Select your GTA San Andreas installation folder
3. Allow the installer to patch the game files

Important Note for Windows 7, 8, and older Windows 10:
If WebView2 is not installed, you must use the setup file from the releases section. WebView2 comes preinstalled on newer Windows 10 and Windows 11 systems.

</td>
</tr>
</table>

Step 3 - Add the Server

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

1. Open the launcher
2. Click Add Server
3. Enter the following details:

```
Name     : Legacy Los Santos
Address  : 45.127.35.54:7063
```

4. Click Connect

</td>
</tr>
</table>

Step 4 - Verify Connection

Once connected, the Legacy Los Santos login screen will appear. Enter your UCP credentials that were registered through the Discord panel.

---

Panduan Bahasa Indonesia

Persyaratan Umum

Icon Komponen Keterangan
<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/windows.svg" width="16" /> Windows 10 atau 11 Sistem operasi yang direkomendasikan
<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/file-earmark-zip.svg" width="16" /> WinRAR atau 7-Zip Untuk mengekstrak file mod
<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/hdd.svg" width="16" /> Ruang kosong 6 GB Untuk game dan seluruh mod

Instalasi di PC

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Pasang GTA San Andreas

Gunakan versi v1.0 US. Versi ini paling kompatibel dengan SA-MP dan mod. Hindari versi Definitive Edition.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Pasang SA-MP 0.3.7 R5

Jalankan installer sebagai Administrator, arahkan ke folder GTA San Andreas, lalu tunggu hingga selesai.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

Pasang CLEO 4.3 atau 5.0

Ekstrak semua file CLEO ke folder GTA San Andreas. Folder CLEO akan otomatis terbentuk.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

Pasang ASI Loader

Salin vorbisFile.dll dan vorbisHooked.dll ke folder GTA San Andreas. Timpa file jika diminta.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/5-circle-fill.svg" width="32" /></td>
<td>

Pasang Mod Legacy Los Santos

Letakkan file .txd dan .dff di folder models\generic\. Letakkan file .asi di root folder GTA. Letakkan file .cs atau .cleo di folder CLEO.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/6-circle-fill.svg" width="32" /></td>
<td>

Sambungkan ke Server

Buka samp.exe lalu masukkan alamat berikut:

```
45.127.35.54:7063
```

</td>
</tr>
</table>

Instalasi di Android

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Pasang GTA San Andreas

Unduh dari Google Play Store atau pasang APK dan OBB secara manual. Letakkan file OBB di Android/obb/com.rockstargames.gtasa/.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Pasang SA-MP Mobile

Unduh APK SA-MP Mobile dari kanal resmi Discord. Aktifkan opsi pemasangan dari sumber tidak dikenal pada pengaturan Android.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

Pasang CLEO Android

Unduh dan pasang CLEO versi 2.0.1.0 atau lebih baru. Berikan izin penyimpanan pada saat pertama kali dibuka.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

Salin File Mod

Letakkan file .txd dan .dff ke folder models/generic/. Letakkan file .cs atau .cleo ke folder CLEO. Gunakan aplikasi seperti MT Manager atau Zarchiver.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/5-circle-fill.svg" width="32" /></td>
<td>

Sambungkan ke Server

Buka SA-MP Mobile, tambahkan server dengan alamat 45.127.35.54:7063, lalu tekan Connect.

</td>
</tr>
</table>

Instalasi KeyListener ASI

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Unduh KeyListener.asi dan KeyListener.ini dari sumber resmi.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Letakkan kedua file tersebut di folder GTA San Andreas, sejajar dengan samp.exe.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

Buka KeyListener.ini dengan Notepad dan atur tombol hotkey sesuai kebutuhan.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

Simpan file lalu buka samp.exe. Jika game crash, periksa kembali ASI Loader dan pastikan Visual C++ Redistributable 2015-2022 sudah terpasang.

</td>
</tr>
</table>

Instalasi open.mp

<table>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/1-circle-fill.svg" width="32" /></td>
<td>

Unduh open.mp Launcher dari situs resmi open.mp atau dari GitHub releases.

```
https://github.com/openmultiplayer/launcher/releases/latest
```

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/2-circle-fill.svg" width="32" /></td>
<td>

Jalankan installer sebagai Administrator dan pilih folder GTA San Andreas. Izinkan installer menambal file game.

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/3-circle-fill.svg" width="32" /></td>
<td>

Buka launcher, tekan Add Server, lalu isi:

```
Name     : Legacy Los Santos
Address  : 45.127.35.54:7063
```

</td>
</tr>
<tr>
<td width="50" align="center"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/4-circle-fill.svg" width="32" /></td>
<td>

Tekan Connect untuk masuk ke server. Masukkan kredensial UCP yang sudah didaftarkan melalui panel Discord.

</td>
</tr>
</table>

---

Troubleshooting

<table>
<thead>
<tr>
<th align="left"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/exclamation-triangle.svg" width="16" /> Problem</th>
<th align="left"><img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/lightbulb.svg" width="16" /> Solution</th>
</tr>
</thead>
<tbody>
<tr>
<td>Game crashes on startup</td>
<td>Verify ASI Loader installation, update Visual C++ Redistributable, and remove conflicting mods</td>
</tr>
<tr>
<td>Cannot connect to server</td>
<td>Check your internet connection and firewall settings, then verify the address <code>45.127.35.54:7063</code></td>
</tr>
<tr>
<td>Mods not appearing</td>
<td>Ensure CLEO is installed correctly and files are placed in the right folders</td>
</tr>
<tr>
<td>KeyListener not responding</td>
<td>Confirm <code>.asi</code> file is in the GTA root folder and the <code>.ini</code> file has correct key codes</td>
</tr>
<tr>
<td>open.mp launcher error</td>
<td>Run as Administrator and ensure the GTA SA folder is not read-only. Install WebView2 if using older Windows</td>
</tr>
<tr>
<td>Server shows as offline</td>
<td>Server may be under maintenance. Check the Discord announcement channel</td>
</tr>
</tbody>
</table>

---

Support

<div align="center">

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/discord.svg" width="24" /> **Discord Support Server**

```
https://discord.gg/45m9Tcwrh
```

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/globe2.svg" width="24" /> **Server Address**

```
45.127.35.54:7063
```

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/shield-check.svg" width="24" /> **Registered through the Legacy Los Santos Discord panel**

</div>

---

<div align="center">

<img src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/icons/c-circle.svg" width="14" /> Legacy Los Santos Community. All rights reserved.

<img src="https://img.shields.io/badge/Made%20with-Pawn-2C2C2C?style=flat-square" alt="Pawn" />
<img src="https://img.shields.io/badge/Powered%20by-open.mp-4D96FF?style=flat-square" alt="open.mp" />
<img src="https://img.shields.io/badge/Community-Legacy%20Los%20Santos-FFD166?style=flat-square" alt="Community" />

</div>
```

