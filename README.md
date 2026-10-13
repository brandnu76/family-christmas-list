# Family Christmas List

Kids and grandkids add wishes. Parents claim items and mark them bought. Purchase status stays hidden from the kids.

Open the site: https://brandnu76.github.io/family-christmas-list/

Wishes sync through the private data repo (`family-christmas-list-data`), not this public site. Bought, claimed, price, and parent notes stay encrypted with the parent passcode.

## Store key rule

- One key, for `family-christmas-list-data` only. No other repos, no extra permissions.
- Give that key to parent phones. Avoid putting it on a kid's phone if that phone can still add wishes another way.
- If a kid's phone must connect, that phone can read and change the list file. It still cannot read bought, claimed, or hidden items without the parent passcode.
- If a phone is lost, revoke the key on GitHub and connect the remaining phones with a new one.
- This is not a login. Do not add a real account system unless the family asks for one.

Chrome on Android may say the app is already installed because other sites on `brandnu76.github.io` are installed. Use **Create shortcut** if Install is blocked.
