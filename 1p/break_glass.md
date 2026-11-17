set up yubikey:

brew install gpg

echo "reader-port Yubico Yubi" > ~/.gnupg/scdaemon.conf

gpg --edit-card
gpg/card> fetch

gpg --decrypt 1p.md 
