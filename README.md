# mtgxml
automated releases for cockatrice format xmls from mtgjson

<hr/>

### use in oracle
the cockatrice card updater "oracle" is either run from cockatrice through help>check for card updates or by manually searching for and starting the oracle executable installed with cockatrice.

when running the card updater:
- click next until the "Source selection" page
- there select the "Download URL" field and empty it
- right click and copy [this link](../../releases/latest/download/mtg.xml.xz)
- paste it into the "Download URL" field
<img width="500" alt="image" src="https://github.com/user-attachments/assets/8c2c3240-2387-488c-8c81-66e5b868a1e9" />

- click next and continue until the wizard completes

<hr/>

### use in automatic updates
```
NOTE:
this feature only works on cockatrice releases released after october 2025!
if you are using 2.10.2 or earlier you won't be able to use this!
```
cockatrice can be configured to always update in the background with this url, which is very fast and does not use a lot of resources:
- after using the updater at least once with the new url go to the settings in cockatrice
- change option to check for card updates to always update in the background
- optionally change the update frequency, updates with this url will take about 10 seconds and happen in the background, setting it to daily will guarantee your cards are always as up to date as they can be
<img width="600" alt="image" src="https://github.com/user-attachments/assets/e7aed667-9e10-431c-a766-0d519405d813" />

- click ok, it will automatically run the next time cockatrice is restarted, you can see when it was last updated in the same page of the settings

<hr/>

[legal disclaimer](./fancontentpolicy.md)
