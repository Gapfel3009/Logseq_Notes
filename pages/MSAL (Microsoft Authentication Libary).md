- **Was ist MSAL?**
	- MSAL steht für Microsoft Authentication Library, MSAL ist eine Code-Library von Microsoft die dabei hilft, sich bei Microsoft-Diensten anzumelden, wie Office 365 oder Azure. Falls man in seiner Web app beispielsweise eine Word Integration haben möchte, braucht man MSAL damit man sich mit Microsoft anmeldet und zugriff bekommt.
-
- **Wie Funktioniert MSAL grob:**
	- Anfrage: Die Application bemerkt dass du nicht angemeldet bist und öffnet die Anmeldung.
	- Anmeldung: MSAL zeigt dir ein Anmelde fester dass du mit deinen Microsoft-Anmeldedaten füllst.
	- Token: Wenn die Anmeldung durch ist werden die daten Überprüft. Sind alle Daten korrekt wird ein Token für dich generiert den sich dein PC merkt.
	- Zugriff: Der Token wird nun immer genutzt wenn du einen Microsoft dienst nutzen möchtest, anstatt dich permanent anzumelden. Nach einer gewissen zeit läuft dein Token aber ab und dann musst du dich wieder anmelden.