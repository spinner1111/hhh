# 7️⃣ Driver Blocklist

### _<mark style="color:yellow;">Cette page vous aidera à désactiver la liste noire des pilotes vulnérables dans Windows.</mark>_

{% hint style="info" %}
reg add HKLM\SYSTEM\CurrentControlSet\Control\CI\Config /v VulnerableDriverBlocklistEnable /t REG\_DWORD /d 0x000000
{% endhint %}

Il peut vous être demandé d'écraser/créer une nouvelle clé de registre, pour laquelle vous pouvez également taper "y" ou "oui" pour confirmer.&#x20;

Redémarrez votre PC après avoir effectué ces modifications.

<figure><img src="broken-reference" alt=""><figcaption></figcaption></figure>
