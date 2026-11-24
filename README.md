# Automation Demos (Power Automate)

Small automations that remove repetitive manual work. All examples use **fictional folders, names and files**. No real company data is published.

## Flow 1: Automatic file notification from a shared folder

### The problem

A report file had to be sent by e-mail, as an attachment, to different areas every time it was updated. Each area also needed its own folder, so the same file was stored several times. This was manual, easy to forget, and created multiple copies of the same file.

### The solution

A single shared folder is used by all areas. When a new file is added, a flow runs automatically and e-mails the people who need it, with a **link to the file** instead of an attachment.

### How it works

1. **Trigger:** a file is created or updated in the shared folder.
2. **Action:** get the file link.
3. **Action:** send an e-mail to the right recipients with the link and a short message.

*(Add 1-2 screenshots of the flow here, with real names, folders and addresses removed or blurred.)*

### Results

- One shared folder instead of one folder per area.
- No manual e-mail step.
- No duplicated attachments: everyone opens the same, up-to-date file.
- *(Optional: add a number only if you measured it, e.g. "saves about X minutes per week".)*

### Tools

Power Automate · SharePoint / OneDrive · Outlook

### What I learned

- Triggers and conditions in cloud flows.
- Using a shared link instead of attachments to keep a single source of truth.
- Handling permissions so only the right people can open the file.

---

*More flows coming as I build them.*
