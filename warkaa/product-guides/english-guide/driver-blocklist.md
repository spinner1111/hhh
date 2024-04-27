# 7️⃣ Driver Blocklist

## _<mark style="color:yellow;">This page will help you disable the Vulnerable Driver Blocklist in Windows.</mark>_

### Start by opening a Command Prompt as ADMIN. Once open, copy and paste the following line of code, then type "y" or "yes" to confirm the changes

{% hint style="info" %}
### reg add HKLM\SYSTEM\CurrentControlSet\Control\CI\Config /v VulnerableDriverBlocklistEnable /t REG\_DWORD /d 0x000000
{% endhint %}

Once this is done, restart your PC for the changes to take affect.

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>
