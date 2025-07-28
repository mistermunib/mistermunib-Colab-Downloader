# 🚀 GDrive Cloner & Downloader

An all-in-one Google Colab notebook that helps you easily clone folders from Google Drive or download files from direct links — straight to your own Drive!

---

## 🔗 Open in Google Colab

Click the badge below to open the tool in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mistermunib/mistermunib-Colab-Downloader/blob/main/mistermunib-Colab-Downloader.ipynb)

---

## ✅ Features

* 🔁 Clone Google Drive folders or files
* 🌐 Download files from direct links (.zip, .rar, .exe, etc.)
* 🧠 Auto-skips files/folders already in your Drive
* 📊 Built-in progress bars for real-time feedback
* 💾 Resume interrupted downloads (if supported)
* 📂 Clean output folders and safe filenames

---

## 🛠️ How to Use (in Colab)

1. **Click** the "Open in Colab" button above.
2. **Press `Ctrl + F9`** to run all cells.
3. The notebook will ask you to **mount your Google Drive**.
4. Choose operation mode:

   * Type `1` → Clone from Google Drive link
   * Type `2` → Download from direct file link
5. Paste your link when prompted.
6. Sit back and let it do the work ✅

---

## 📁 Example Links

### Google Drive folder/file:

```
https://drive.google.com/drive/folders/1A2b3CdEfGhIjKlmNOPq
```

### Direct file link:

```
https://example.com/somefile.zip
```

---

## 📌 Download Location

Your downloads are saved to:

```
/content/drive/MyDrive/Downloads
```

You can change this location inside the notebook if needed.

---

## ⚙️ Dependencies (auto-installed)

* `PyDrive2`
* `google-api-python-client`
* `tqdm`
* `requests`

---

## 👤 Author

Made with ❤️ by [@mistermunib](https://github.com/mistermunib)

---

## ⭐ Support

If this project helped you, consider giving it a ⭐ on GitHub and sharing it with friends!

---