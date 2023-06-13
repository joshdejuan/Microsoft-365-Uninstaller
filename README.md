# Microsoft-365-Uninstaller

![Logo Microsoft 365](https://blog.goptg.com/hs-fs/hubfs/Logos/microsoft-office-365-icon-3.png?width=70&name=microsoft-office-365-icon-3.png)

A PowerShell script that uninstalls all Microsoft 365 applications that come pre-installed by default on certain PCs.

It first enables the script execution policy in PowerShell (`Set-ExecutionPolicy Unrestricted -Force`) and then searches for all applications containing ``*Microsoft 365*`` and uninstalls them.

Very useful for IT administrators.

Based on: 
<!-- [Script To Silently Uninstall Built-In Office 365 ClickToRun](https://www.reddit.com/r/sysadmin/comments/jjtpnp/script_to_silently_uninstall_builtin_office_365/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) -->

<blockquote class="reddit-embed-bq" style="height:316px" data-embed-height="316">      <a href="https://www.reddit.com/r/sysadmin/comments/jjtpnp/script_to_silently_uninstall_builtin_office_365/">Script To Silently Uninstall Built-In Office 365 ClickToRun</a><br> by      <a href="https://www.reddit.com/user/timurleng">u/timurleng</a> in      <a href="https://www.reddit.com/r/sysadmin/">sysadmin</a>    </blockquote>