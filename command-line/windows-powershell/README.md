# TryHackMe — Windows PowerShell  
🔗 https://tryhackme.com/room/windowsps

---

## 📘 Room Summary

This room introduces **Windows PowerShell**, a task automation and configuration management framework built on .NET.

PowerShell is more powerful than CMD due to its scripting capabilities and use of objects instead of plain text.

---

## 🧠 Key Concepts Learned

- PowerShell uses **cmdlets** (e.g., `Get-Process`, `Set-ExecutionPolicy`)
- Can run `.ps1` scripts and pass objects between commands
- Supports variables, logic, and scripting
- Powerful for sysadmin and red team tasks

---

## 🔧 Tools / Cmdlets Used

| Cmdlet                | Description                           |
|-----------------------|---------------------------------------|
| `Get-Help`            | Shows command documentation           |
| `Get-Command`         | Lists all available cmdlets           |
| `Get-Process`         | Lists running processes               |
| `Get-Service`         | Lists system services                 |
| `Start-Process`       | Starts a process                      |
| `Set-ExecutionPolicy` | Allows script execution               |
| `Get-ChildItem`       | Lists files (like `ls` or `dir`)      |

---

## 💬 Reflections

PowerShell felt different from both CMD and Bash — but incredibly powerful.  
I now understand how attackers or sysadmins use it to automate tasks, run scripts, and access deep system info.

It’s definitely something I’ll practice more, especially scripting for automation or red team use cases.
