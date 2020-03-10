# KDB_My_Admin
A Simple Database Mangerment Website for KDB

# Install

1. Upload to server

2. Edit `kdbmyadmin_config.php`

```
// User Config

$username = "username"; //Login Username
$password = md5("password"); // Login Password MD5 Hash
```
```
// System Config
$kdbmyadmin_config_dir = "../kdb/"; // Default Dir for kdb files
$kdbmyadmin_config_ex = "kdb"; // Default Extension
$kdbmyadmin_config_lock = true; // Lock config on login
```

3. Visit `https://SERVER-IP/kdbmyadmin/index.php` and enjoy !

# Demo

[https://api.krunk.cn/kdbmyadmin/kdbmyadmin/index.php](https://api.krunk.cn/kdbmyadmin/kdbmyadmin/index.php)



![demo image](https://api.krunk.cn/kdbmyadmin/demo.png)
