#PokemonGo trainer activator - don't bother to login to accept ToS and pick codename!

Usage guide:

1. Make sure you've latest node.js and npm!
2. Download .zip or clone
3. Run this inside directory: `npm install`
4. Rename `accounts.csv.example` to `accounts.csv`
5. Input data in `accounts.csv` in `auth,username,password,lat,lng,codename` format
6. run `node pogo.js`

Known issues:

1. It doesn't inform if it fails to get desired codename.

Todo:

* Better informing of failed steps
* Tell which codenames didnt get picked