## Host Blocklisten (0.0.0.0-Format) - Für PiHole, Windows und Co.
***Weitere Formate: [Domains](https://github.com/Zelo72/rpi) | [AdGuard/AdBlock](https://github.com/Zelo72/adguard)***

### ***DNS-Sperrlisten*** (Black-/Blocklists)

#### Basislisten (empfohlen)

[**Multi**](https://raw.githubusercontent.com/Zelo72/hosts/main/multi.txt) - Zelo's "persönliche" Blockliste: ***Werbung, Tracking, Phishing, Malware, Coins und sonstiger "Mist" aus dem Netz***. Eine All-in-One Blockliste die keine zwingend benötigten "Funktionen" blockiert - kein striktes Blocken. Dead-Hosts (Hosts-Adressen die nicht mehr existieren) wurden aus dieser Liste entfernt. Sie kann als alleinige Blockliste verwendet werden und nach Wunsch durch Hinzufügen der Erweiterungslisten (siehe unten) erweitert werden. ***(Empfehlung)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/hosts/main/multi.txt
> 
> ***Quellen:*** [Stats](https://github.com/Zelo72/hosts/blob/main/multi.stats)

[**Fake**](https://raw.githubusercontent.com/Zelo72/hosts/main/fake.txt) - Zelo's "anti Abzock" Blockliste: ***Fake-Shops, -Streaming, Abzocke und Co***. Auf Basis verschiedener Verbaucherseiten, Warnungen und anderen Fake-Listen. Als empfohlener Zusatz zur Multi-Blockliste, die Domains aus der Fakeliste sind nicht in der Multiliste enthalten. ***(Empfehlung)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/hosts/main/fake.txt
> 
> ***Quellen:*** *Verbraucherzentralen, Trusted Shops, Watchlist Internet, zelo72* - [Stats](https://github.com/Zelo72/hosts/blob/main/fake.stats)

#### Erweiterungslisten (bei Bedarf - als Erweiterung zur Multi-Liste)

[**Privacy**](https://raw.githubusercontent.com/Zelo72/hosts/main/privacy.txt) - Zelo's "Privacy" Blockliste: ***Blockt Telemetrie & Metriken von Endgeräten, Diensten und Systemen diverser Hersteller (OEM)***. ***(Optional - als Erweiterung zur Multiliste)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/hosts/main/privacy.txt
> 
> ***Quelle:*** *zelo72*

[**Affiliate&Tracking**](https://raw.githubusercontent.com/Zelo72/hosts/main/affiliatetracking.txt) - Zelo's "Affiliate & Tracking" Blockliste: ***Blockt Affiliate, Analytics & Tracking Links***.  **Hinweis:** Durch diese Blockliste werden Z.B. auch Links, die in der Google-Suche als Anzeige markiert sind oder Affiliate-Links in Mailangeboten, geblockt. ***(Optional - als Erweiterung zur Multiliste)***  

> ***Link:*** https://raw.githubusercontent.com/Zelo72/hosts/main/affiliatetracking.txt
> 
> ***Quelle:*** [Stats](https://github.com/Zelo72/hosts/blob/main/affiliatetracking.stats)

---

### ***DNS-Sperrlisten*** (Black-/Blocklists) - Sonstige

***Folgende Listen sind NICHT in der Multi-Liste enthalten!***

[**CryptoScamDB**](https://raw.githubusercontent.com/Zelo72/hosts/main/cryptoscamdb.txt) - CryptoScamDB von https://cryptoscamdb.org/ umgewandelt + Erweiterung um mögliche WWW-Domains. Bereinigt von toten und falsch positiven Domains. **Trotz der Bereinigung kann die Liste falsch positve Domains enthalten!** - Quelle: [CryptoScamDB](https://api.cryptoscamdb.org/v1/blacklist) - [Stats](https://github.com/Zelo72/hosts/blob/main/cryptoscamdb.stats)

---

### ***DNS-Freigabeliste*** (Whitelist)

[**White**](https://raw.githubusercontent.com/Zelo72/hosts/main/white.list) - Zelo's Whitelist: ***Domains die man nicht blocken sollte***. Die in der Whitelist aufgeführten Domains wurden **gegen die Multi- und Fake-Blockiste geprüft und sind in diesen Blocklisten nicht mehr enthalten**.

> ***Quelle:*** *zelo72*

---

### ***Hinweis***

***Die Blocklisten wurden zur rein persönlichen, privaten Nutzung erstellt. Die Blocklisten wurden aus vorhandenen Quellen und eigenen Blacklisten unter Berücksichtigung von Whitelisten wie Dead-Hosts (Hosts-Adressen die nicht mehr existieren) und Toplisten (DE:Top 50 - Welt:Top 50) zusammen gestellt.***

**Die Blocklisten werden täglich aktualisiert.**

---
