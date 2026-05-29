# 📦 ScottsTechX Tar

<p align="center">
  <img src="https://img.shields.io/badge/tar-Archive-Utility-00ff88?style=for-the-badge&logo=linux&logoColor=black" alt="tar"/>
  <img src="https://img.shields.io/badge/Open-Source-00ff88?style=for-the-badge&logo=github&logoColor=black" alt="Open Source"/>
</p>

> **Archive utility — create and extract .tar, .tar.gz, .zip files.**

---

## ⚡ What It Does

tar creates and extracts tape archive files — bundle multiple files, compress with gzip/bzip2, and extract cleanly. Essential for packaging and backups.

## 🚀 Quick Usage

```bash
# Create archive
tar -cvf archive.tar file1 file2 file3

# Create compressed archive
tar -cvzf archive.tar.gz directory/

# Extract archive
tar -xvf archive.tar

# Extract gzipped archive
tar -xvzf archive.tar.gz

# List contents
tar -tvf archive.tar
```

## 📡 Common Patterns

```bash
# Extract to specific directory
tar -xvzf archive.tar.gz -C /target/dir

# Create .zip
zip -r archive.zip directory/

# Extract .zip
unzip archive.zip
```

---

MIT © 2026
