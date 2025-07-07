# Colab All-In-One Downloader

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nanfenggushi/colab-all-in-one-downloader/blob/main/colab_all_in_one_downloader.ipynb)

A stable, reliable, and powerful Google Colab notebook designed to download files from various sources directly to your Google Drive. Tired of other Colab downloaders breaking? This one is built to last, with clean code and a focus on stability.

一个稳定、可靠且功能强大的 Google Colab 笔记本，旨在将各种来源的文件直接下载到您的 Google Drive。厌倦了其他 Colab 下载器频繁失效？这个版本代码清晰，专注于稳定性，为您提供持久的解决方案。

---

## ✨ Key Features (主要特性)

*   **🚀 Stable & Reliable (稳定可靠):** Built with version-specific packages to avoid breaking due to Colab environment updates.
*   **🎛️ User-Friendly GUI (图形化界面):** No need to touch the code! An intuitive tabbed interface allows you to simply paste links and click buttons.
*   **🔗 All-in-One Solution (功能全面):**
    *   **HTTP/HTTPS:** Multi-threaded downloading for direct links using `aria2c`.
    *   **BitTorrent:** Download from Magnet links efficiently using `libtorrent`.
    *   **YouTube & More:** Download videos from YouTube and hundreds of other sites with `yt-dlp`.
*   **☁️ Direct to Drive (直存云盘):** All files are downloaded directly to your specified Google Drive folder. Set it and forget it!

## 🚀 Quick Start (快速上手)

Follow these simple steps to get started:

1.  **Open in Colab:** Click the "Open In Colab" badge at the top of this page.
2.  **Save a Copy:** To save your work, go to **File -> Save a copy in Drive**. All subsequent use should be from your own copy.
3.  **Run the Cells:** Run the code cells sequentially from top to bottom by clicking the "Play" button on each.
    *   **Step 1:** Installs all necessary tools.
    *   **Step 2:** Connects to your Google Drive (you will be asked for authorization).
    *   **Step 3:** Launches the user-friendly GUI.
4.  **Start Downloading:** Use the tabbed interface that appears in Step 3 to paste your links, check the save path, and start your downloads!

 
*(提示: 您可以自己截图并替换此处的图片链接)*


## 🔧 Troubleshooting (问题排查)

*   **`ModuleNotFoundError: No module named 'libtorrent'`**
    *   **Cause:** This happens if the Colab session didn't correctly load the newly installed libraries.
    *   **Solution:** Simply go to the menu **Runtime -> Restart session**, then run all cells again from the top. This solves the issue 99% of the time.

*   **Stuck on "Connecting" or "Allocating"...**
    *   **Cause:** Colab resources might be temporarily unavailable, or your browser cache is causing issues.
    *   **Solution 1 (Quick):** Go to **Runtime -> Change runtime type**, switch the hardware accelerator to `T4 GPU`, save, and then switch it back to `None`. This forces Colab to assign a new machine.
    *   **Solution 2 (Effective):** Open the notebook in your browser's **Incognito/Private mode**. This bypasses cache and extension conflicts.

## 📄 License (许可证)

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as you see fit. See the `LICENSE` file for more details.

---
*This notebook was crafted to be a robust tool for cloud downloading. Enjoy!*