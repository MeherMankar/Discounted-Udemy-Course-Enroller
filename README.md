<p align="center">
    <img src="https://raw.githubusercontent.com/MeherMankar/Discounted-Udemy-Course-Enroller/refs/heads/master/extra/promo.gif">
    <br/>
    <img src="https://forthebadge.com/images/badges/made-with-python.svg">
    <br/>
    <a href="https://github.com/MeherMankar/Discounted-Udemy-Course-Enroller/graphs/commit-activity"><img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge"></a>
    <a target="_blank" href="https://discord.gg/wFsfhJh4Rh"><img alt="Discord" src="https://img.shields.io/discord/703266580846346361.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge"></a>
    <br/>
    <a href="https://github.com/MeherMankar/Discounted-Udemy-Course-Enroller"><img src="https://cdn.discordapp.com/attachments/823472016999972884/841661124410736710/standard_13.gif"></a>
</p>

# Discounted Udemy Course Enroller

> Software to enroll in available Udemy Paid/Free courses having coupons automatically to your Udemy account.

Everything you need can be on the website: https://MeherMankar.github.io/duce/

## Key Features

- Beautiful GUI
- One click login using Browser cookies.(Supports major browsers)
- One click to add all available courses with coupons to your udemy account
- Uses popular sites for coupons
- Many more features
- CLI version available for automation
- Advanced filters

# Downloads

<table>
<thead >
  <tr>
    <th style="text-align: center">GUI</th>
    <th style="text-align: center">CLI</th>
  </tr>
</thead>
<tbody>
  <tr align="center">
    <td><a href="https://github.com/MeherMankar/Discounted-Udemy-Course-Enroller/releases/latest/download/DUCE-GUI-windows.exe">
         <img alt="GUI Windows exe" src="https://img.shields.io/static/v1?message=Download&logo=windows&labelColor=5c5c5c&color=1182c3&label=%20&style=for-the-badge"
         >
      </a></td>
    <td><a href="https://github.com/MeherMankar/Discounted-Udemy-Course-Enroller/releases/latest/download/DUCE-CLI-windows.exe">
         <img alt="CLI Windows exe" src="https://img.shields.io/static/v1?message=Download&logo=windows&labelColor=5c5c5c&color=1182c3&label=%20&style=for-the-badge">
      </a></td>
    
  </tr>
</tbody>
</table>

## ⚠️ Antivirus False Positives

The pre-built `.exe` files are packaged with [PyInstaller](https://pyinstaller.org/), a standard Python-to-executable tool. **PyInstaller-packed executables frequently trigger antivirus false positives**, including Microsoft Defender (Trojan:Win32/...) and others, because:

- PyInstaller bundles a Python interpreter and all dependencies into a single binary — a pattern common in both legitimate software and malware.
- Microsoft's SmartScreen and Defender flag unsigned executables with low reputation, regardless of content.
- Purchasing a code-signing certificate (required to remove Microsoft's detection) costs hundreds of dollars/year — not feasible for a free open-source project.

**This is NOT malware.** You can verify this yourself:

1. **Check VirusTotal** — upload the `.exe` to [virustotal.com](https://www.virustotal.com) and review which engines flag it and why.
2. **Build from source** — the full source code and [GitHub Actions build workflow](.github/workflows/build.yml) are available. You can fork the repo and trigger the build yourself via GitHub Actions → **Build** → **Run workflow**. The resulting artifact is byte-for-byte identical to the released `.exe`.
3. **Run as a Python script** — instead of using the `.exe`, install Python 3.11+, run `pip install -r requirements.txt`, and launch `python gui.py` or `python cli.py` directly. No AV warnings.

> [!TIP]
> To allow the `.exe` in Windows Defender: **Windows Security → Virus & threat protection → Protection history → find the quarantined item → Allow**.

<h2><details>
<summary>Screenshots of GUI</summary>

![Login](/extra/gui-login.png)

![Discounted Udemy Course Enroller](/extra/gui-main.png)

![Coupon Scraping](/extra/gui-scraping.png)

![Enrolling](/extra/gui-enrolling.png)

</details>

## Disclaimer

![](/extra/disclaimer.png)

<center>
Made with ❤️
</center>

## Credits
This project is a fork of the original [Discounted-Udemy-Course-Enroller by techtanic](https://github.com/techtanic/Discounted-Udemy-Course-Enroller).