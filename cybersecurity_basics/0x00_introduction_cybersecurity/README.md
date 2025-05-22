<div align="center">

# 🛡️ Introduction to Cyber Security  
### *By: Yosri Ghorbel*

![Cyber Security](https://camo.githubusercontent.com/7c23294a8c1f8a42412a8fd42193d8bb0026d0540733bf77765608b32d223ebd/68747470733a2f2f6d656469612e6c6963646e2e636f6d2f646d732f696d6167652f4335363132415146494175744e494c634b70512f61727469636c652d636f7665725f696d6167652d736872696e6b5f3630305f323030302f302f313630333236333330383236373f653d3231343734383336343726763d6265746126743d444f796e4f59313369534c4633724e654539456f75724a386d6271734745764f442d68554d74384a69794d)

</div>

---

## 📚 Tasks

### 0. 🚀 Did you install Kali?
Write a bash script that displays the distributor ID in a concise single-line output.  
- Must be one line only and include a newline.
- Do **not** use `awk`.

**Example Output:**
```bash
$ ./0-release.sh
Kali
```

---

### 1. 🔐 We always need strong passwords
Create a Bash script that generates a strong random password.
- Script should be < 3 lines
- Accepts password length as an argument
- Uses `/dev/urandom` and `[:alnum:]` character classes

**Example Output:**
```bash
$ ./1-gen_password.sh 20
MkPpprPyC3i6navUB3Lj
```

---

### 2. ✅ Verify the integrity of a file
Create a Bash script to validate the integrity of a file using SHA256.
- Must be < 3 lines
- You **can** use `echo`

**Example Output:**
```bash
$ ./2-sha256_validator.sh test_file e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
test_file: OK
```

---

### 3. 🔑 We need an SSH key pair!
Create a Bash script that generates a 4096-bit RSA SSH key pair using OpenSSH.

**Example Output:**
```bash
$ ./3-gen_key.sh new_key
Generating public/private rsa key pair.
Your identification has been saved in new_key
Your public key has been saved in new_key.pub
...
```

---

### 4. 📡 Let's Monitor root activity
Create a Bash script that monitors all processes started by a specific user.
- Accepts user as 1st argument
- Use `grep -v` to exclude 0-value VSZ/RSS processes
- Uses `ps` command

**Example Output:**
```bash
$ ./4-root_process.sh root
root    1   0.0   0.0  /sbin/init splash
...
```
## AUTHOR
Youssef Saad
