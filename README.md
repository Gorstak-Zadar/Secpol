# 🔒 Secpol

> PowerShell script to **harden privilege rights** via secedit — SeDenyNetworkLogonRight, SeDenyRemoteInteractiveLogonRight, SeDenyRemoteLogonRight for *S-1-5-11 (Users). Clears SeRemoteShutdownPrivilege, SeRemoteLogonRight, etc.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📋 **secedit** | Export cfg, append privilege settings, configure |
| 🚫 **Deny Rights** | Network logon, Remote interactive, Remote logon for Users |
| 🔒 **Clear** | SeRemoteShutdownPrivilege, SeRemoteLogonRight, etc. |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
.\Secpol.ps1
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Hardening</sub>
</p>
