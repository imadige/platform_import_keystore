# Platform Import Keystore
My own version of [keytool-importkeypair](https://github.com/getfatday/keytool-importkeypair)

**A script which takes platform.x509.pem and platform.pk8 files and creates a new keystore (with given keystorepass and keypass)**

This script doesn't need a keystore pre created counter to keytool-importkeypair

# Installing
Add platform_import_keystore to your PATH

# Usage
<pre>
usage: platform_import_keystore [-k keystore pass] [-p key pass] [-a key alias]
</pre>

# Note

If your certificat (.x509.pem) or private key (.pk8) are not nammed "platform.x509.pem" or "platform.pk8" you can edit the field in the script directly.

Don't esistate to pull request this project if you want to add improvment. 
