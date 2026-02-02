# DataSmith2 — File Name Transformer

DataSmith2 is a lightweight desktop tool for transforming and cleaning file names.  
It is designed for creators, developers, archivists, and anyone who works with large batches of files and needs fast, predictable renaming logic.

Built with **Avalonia** for full cross‑platform support (Windows, Linux, macOS).

---

## ✨ Features (Free Version 1.x)

### 🔤 Smart File Name Filters
Apply instant transformations to file names:

- Remove numbers  
- Remove lowercase letters  
- Remove uppercase letters  
- Remove spaces  
- Remove symbols (keeps A–Z, a–z, 0–9, `_` and `-`)  
- Add a custom prefix (invalid characters are automatically removed)

All filters update the preview **in real time**.

---

## 📁 File Input

You can load files in multiple ways:

- Drag & drop files directly into the window  
- Select individual files  
- Select an entire folder  

Images display a small thumbnail; other files show a document icon.

---

## 👀 Live Preview

The preview grid shows:

| Original | Transformed |
|----------|-------------|

Every change to filters or prefix updates the preview instantly.

---

## 📤 Export Options

Export the transformation results in multiple formats:

- **TXT** — simple readable list  
- **CSV** — spreadsheet‑friendly  
- **JSON** — structured data for automation  

Exports can be saved:

- to a chosen file  
- or automatically into the user's AppData folder

---

## 🧩 Cross‑Platform

DataSmith2 is built on **Avalonia**, meaning it runs on:

- Windows  
- Linux  
- macOS  

No installation required — just run the executable.

---

## 🚧 Roadmap

DataSmith2 is actively evolving.  
Upcoming features planned for version **2.0** include:

- Modernized UI  
- Visual export (PNG, JPG, PDF)  
- Persistent settings  
- Additional filters and automation tools  

---

## 🛠 Development

### Requirements
- .NET 8 SDK  
- Avalonia 11.x  

### Build
```bash
dotnet build
