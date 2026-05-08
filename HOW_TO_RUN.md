# ▶️ How to Run InternHub in VS Code

---

## ✅ Method 1 — Quickest (No Setup Needed)

1. Extract the ZIP file
2. Find `InternHub_Final.html`
3. **Double-click** it
4. It opens in your default browser instantly ✅

> Works offline! No internet required (except for loading Google Fonts & Font Awesome icons).

---

## ✅ Method 2 — VS Code + Live Server (Recommended)

### Step 1 — Install VS Code
- Download from: **https://code.visualstudio.com/**
- Install and open it

### Step 2 — Install Live Server Extension
1. Press `Ctrl + Shift + X` to open Extensions
2. Search: `Live Server`
3. Click **Install** on the one by **Ritwick Dey**
4. Wait for installation to complete

### Step 3 — Open the Project Folder
1. In VS Code: **File → Open Folder**
2. Select the `InternHub/` folder you extracted
3. You'll see all files in the left sidebar

### Step 4 — Launch the Portal
- **Option A:** Right-click `InternHub_Final.html` in sidebar → **"Open with Live Server"**
- **Option B:** Press `Alt + L` then `Alt + O`
- **Option C:** Click **"Go Live"** button in the bottom-right status bar

### Step 5 — View in Browser
Your browser will automatically open at:
```
http://127.0.0.1:5500/InternHub_Final.html
```

---

## 🔑 Admin Login

Once the portal is open:

1. Click **Admin** button (top-right) or the shield icon in the left rail
2. Enter credentials:
   - **Username:** `admin`
   - **Password:** `admin123`
3. Click **Login**

---

## 🗂️ Pages & Navigation

| Page | How to Access |
|---|---|
| 🏠 Landing | Default home page |
| 📝 Apply Form | Click "Apply Now" button |
| 🔍 Track Status | Click "Track" button or rail icon |
| ✅ Success | Automatically shown after form submit |
| 🔐 Admin Login | Click "Admin" button |
| 📊 Admin Dashboard | After admin login |

---

## ⌨️ Keyboard Shortcuts (VS Code)

| Shortcut | Action |
|---|---|
| `Ctrl + Shift + X` | Open Extensions panel |
| `Alt + L, Alt + O` | Start Live Server |
| `Alt + L, Alt + C` | Stop Live Server |
| `Ctrl + Shift + P` | Open Command Palette |

---

## 🛠️ Troubleshooting

### Buttons not clicking?
- Make sure you're using the **new** `InternHub_Final.html` (old version had a z-index bug)
- Try a different browser (Chrome recommended)

### Page looks unstyled?
- Fonts load from Google Fonts (needs internet)
- Works fully offline, just fonts may fallback to system fonts

### Live Server not working?
- Make sure the extension is installed and enabled
- Try restarting VS Code
- Check the bottom status bar for "Port: 5500"

### Data not saving?
- Make sure your browser allows **localStorage**
- Don't open the file in Incognito/Private mode (localStorage may be blocked)

---

## 📱 Browser Compatibility

| Browser | Status |
|---|---|
| Chrome 90+ | ✅ Full Support |
| Firefox 88+ | ✅ Full Support |
| Edge 90+ | ✅ Full Support |
| Safari 14+ | ✅ Full Support |
| IE 11 | ❌ Not Supported |

---

*Happy coding! 🚀*
