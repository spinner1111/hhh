# 3️⃣ Hyper-V

***

Cette page vous aidera à désactiver Hyper-V dans Windows.

Pour désactiver Hyper-V dans Windows, commençons par ouvrir un Windows Powershell en tant qu'ADMIN. Ceci peut être fait en tapant powershell dans votre recherche Windows, puis en appuyant sur "Exécuter en tant qu'administrateur" à côté. Maintenant que Powershell est ouvert, COPIEZ CECI ET COLLEZ-LE DANS LE TERMINAL (Ctrl+C > Ctrl+V)&#x20;

{% hint style="info" %}
bcdedit /set hypervisorlaunchtype off Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All
{% endhint %}

Recevoir une erreur disant "Disable-WindowsOptionalFeature : Le nom de fonction Microsoft-Hyper-V-All est inconnu." ci-dessus est tout à fait normal, cependant, obtenir un message de réussite est également normal.

Une fois cela fait, redémarrez votre PC pour que les modifications prennent effet.

***

<figure><img src="../../.gitbook/assets/spaces_4ealdnDHwi2un9yaLwWN_uploads_TnSv4q8FkXykqX5t7Yd3_image (1).webp" alt=""><figcaption></figcaption></figure>
