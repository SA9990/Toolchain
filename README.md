#### 📦 AOSP Clang Upload Workflow

---
#### ⏩ checkout more aosp prebuilts
[Android Clang/LLVM Prebuilts](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+/refs/heads/main-kernel)

---

This repository contains a GitHub Actions workflow that automatically downloads AOSP Clang and uploads them to GitHub Releases. This allows kernel developers to easily cache and reuse specific Clang versions without downloading them repeatedly from AOSP.

---

### 🎯 Purpose

- Download specific AOSP Clang kernel versions.
- Upload the downloaded tarballs to GitHub Releases.
- Enable faster and more reliable kernel builds by caching toolchains.

---

### 🔗 Available Clang Versions

| Version |  Download Link  |
|---------|-----------------|
|  **clang-r522817**  | [Download](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+archive/refs/heads/main-kernel/clang-r522817.tar.gz) |
|  **clang-r536225**  | [Download](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+archive/refs/heads/main-kernel/clang-r536225.tar.gz) |
|  **clang-r547379**  | [Download](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+archive/refs/heads/main-kernel/clang-r547379.tar.gz) |
|  **clang-r563880**  | [Download](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+archive/refs/heads/main-kernel/clang-r563880.tar.gz) |
|  **clang-r563880b** | [Download](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+archive/refs/heads/main-kernel/clang-r563880b.tar.gz) |
---

## 🛠️ How It Works

1. The workflow is triggered manually.
2. It downloads the specified Clang tarball directly from AOSP.
3. The tarball is uploaded as GitHub Release for convenient access.

---
