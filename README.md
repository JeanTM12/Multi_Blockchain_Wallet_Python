# Multi_Blockchain_Wallet_Python

Set up 
1. hd_wallet_derive set up in new Dir "wallet".
    
cd wallet
git clone https://github.com/dan-da/hd-wallet-derive
cd hd-wallet-derive
php -r "readfile('https://getcomposer.org/installer');" | php
php -d pcre.jit=0 composer.phar install

Creating a symlink called derive:
    ln -s hd-wallet-derive.php derive
    ./derive

using mnemonic :
    ./derive -g --mnemonic="gun taste melt afraid grab expose couch artwork shiver member drum scrub" --cols=path,address,privkey,pubkey

setting mnemonic:
mnemonic = os.getenv("MNEMONIC", "gun taste melt afraid grab expose couch artwork shiver member drum scrub")


added in code in wallet py.

tested in testnet ( screen shot can be found in folder)

changes done to nodes and applied in eth.