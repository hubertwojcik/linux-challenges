# Challenge #2 — Absolute and Relative Paths

## 🎯 Objective

Practice using absolute and relative paths with various Linux commands.

## ✅ Tasks

1. Move into the current user's home directory using the cd command and an absolute path
2. List the contents of the current directory using the ls command and a relative path
3. List the contents of `/home` using the ls command and an absolute path
4. List the contents of `/home` using the ls command and a relative path
5. List the contents of `/etc` using the ls command and an absolute path
6. List the contents of `/etc` using the ls command and a relative path
7. Display the contents of `/var/log/dmesg` using the cat command and an absolute path
8. Display the contents of `/var/log/dmesg` using the cat command and a relative path

---

## 🧠 Commands Used

```bash
# 1. Move into the current user's home directory using the cd command and an absolute path
cd ~
# 2. List the contents of the current directory using the ls command and a relative path
ls .
# 3. List the contents of `/home` using the ls command and an absolute path
ls /home
# 4. List the contents of `/home` using the ls command and a relative path
ls .
# 5. List the contents of `/etc` using the ls command and an absolute path
ls /etc
# 6. List the contents of `/etc` using the ls command and a relative path
ls etc
# 7. Display the contents of `/var/log/dmesg` using the cat command and an absolute path
sudo cat /var/log/dmesg
# 8. Display the contents of `/var/log/dmesg` using the cat command and a relative path
cat var/log/dmesg
```

---

## 📄 Output

Output log stored in `output.txt`.

_(Recorded using `script output.txt`)_

---

## 📝 Notes

- `~` is an absolute path shortcut that refers to the user's home directory
- `.` represents the current directory when used as a relative path
- Absolute paths always start with `/` and don't depend on your current location
- Relative paths are interpreted based on your current working directory
- For task 4, using `ls .` while in `/home` will list `/home` contents (relative path)
- For task 6, using `ls etc` from the root directory (`/`) is equivalent to `ls /etc`
- When navigating, you need to be in the correct directory for relative paths to work
- Some files like `/var/log/dmesg` may require `sudo` to read (depending on permissions)

---

## 🧩 What I Learned

- **Absolute paths** start with `/` and always point to the same location regardless of where you are
- **Relative paths** depend on your current working directory (PWD)
- `~` is a special shortcut for the home directory (absolute path equivalent to `/home/username`)
- `.` means current directory, `..` means parent directory
- The same file can be accessed using different path types depending on your location
- Understanding your current directory is crucial when using relative paths
- Absolute paths are more reliable in scripts since they don't depend on execution context

---

## 💻 Environment

- macOS (Unix-based, Linux-like behavior)
- Terminal used: `zsh`

---

### ✅ Challenge Completed!
