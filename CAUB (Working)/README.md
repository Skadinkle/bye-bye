# How to Use:
## 1. Main Method
- Download the folder and open `index.html` _(Use `old.html` if it doesn't work for you.)_
- Head to [chrome://network#state](chrome://network#state).
- Click the + next to the network you mainly use (For me, I use my school's guest network.)
- Copy all of the text that pops up below.
- Head back to CAUB and paste the text in the textbox below.
- Click 'generate and download onc file'.
- Head to [chrome://network#general](chrome://network#general) and scroll down to 'Import ONC File'.
- Click `Choose File` and import the one you downloaded.
- Enjoy.

<br>

## 2. Manual Method _(You need a text editor.)_
- Download the template scripts from the repository.
- Head to [chrome://network#state](chrome://network#state).
- Click the **+** next to the network you mainly use _(For me, I use my school's guest network.)_
- Replace `NETWORKGUID` with the `GUID` content under `ConnectionState`. _(Ex. `41eabyde-h3r2-7gcr-h371-25u7i7e6543g`.)_
- Replace `NETWORKNAME` with the `Name` content under `Metered`. _(Ex. `School_Guest`.)_
- Replace `NETWORKSSID` with the `SSID` content under `PasspointMatchType`. _(Ex. `School_Guest`.)_
- Save the text file.
- Head to [chrome://network#general](chrome://network#general) and scroll down to 'Import ONC File'.
- Click `Choose File` and import the one you created.
- Enjoy.