# Challenge #1 — Basic Navigation & Absolute Paths

## 🎯 Objective

Practice navigating the filesystem, using absolute paths, and viewing system files.

## ✅ Tasks

1. Move into the current user's home directory
2. List the contents of `/etc` using an absolute path
3. Display the contents of `/var/log/dmesg` using an absolute path
4. Move into the root directory `/`
5. List the contents of `/etc` again

---

## 🧠 Commands Used

```bash
# 1. Go to home directory
cd ~

# 2. List /etc directory
ls /etc

# 3. View dmesg log (Linux)
sudo cat /var/log/dmesg

# 4. Go to root directory
cd /

# 5. List /etc directory again
ls /etc
```

> 💡 **macOS note:**  
> `/var/log/dmesg` does not exist on macOS. Use instead:
>
> ```bash
> dmesg | head
> ```

---

## 📄 Output

Output log stored in `output.txt`.

_(Recorded using `script output.txt`)_

---

## 📝 Notes

- `~` = shortcut for user's home directory
- `/` = root filesystem
- **Absolute paths always start with `/`**
- Some log files require `sudo` to read
- macOS handles logs differently than Linux

---

## 🧩 What I Learned

- Difference between absolute & relative paths
- Navigating the Linux/Unix filesystem
- Accessing system log files
- Using `sudo` to view protected files

---

## 💻 Environment

- macOS (Unix-based, Linux-like behavior)
- Terminal used: `zsh`

---

### ✅ Challenge Completed!
