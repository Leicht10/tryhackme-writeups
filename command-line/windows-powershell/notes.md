# 📝 Extra Notes — Windows PowerShell

---

## PowerShell vs CMD

- PowerShell uses objects, not just plain text.
- Can run advanced scripts, not just single commands.
- Cmdlets follow Verb-Noun structure (e.g., `Get-Process`, `Set-Date`).

---

## Cmdlet Tips

- `Get-Help <cmdlet>` gives full documentation.
- `Get-Member` lets you inspect the properties/methods of objects.
- `Out-GridView` gives GUI-like output for filtering (useful in forensics).

---

## Execution Policy

- Scripts are blocked by default.
- Use `Set-ExecutionPolicy RemoteSigned` to allow local scripts.
- Run as Administrator for permanent changes.

---

## Reflections

- This room gave me a real intro to PowerShell as a **scripting language**, not just a shell.
- I now understand how to use it to:
  - Enumerate processes and services
  - Run scripts on boot
  - Query system info
  - Start/stop apps
