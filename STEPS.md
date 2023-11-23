## **Installing Github Credential Manager GCM**
Reference URLs:
[git-credential-manager/docs/install.md at release · git-ecosystem/git-credential-manager · GitHub](https://github.com/git-ecosystem/git-credential-manager/blob/release/docs/install.md)
[git-credential-manager/docs/credstores.md at release · git-ecosystem/git-credential-manager · GitHub](https://github.com/git-ecosystem/git-credential-manager/blob/release/docs/credstores.md)

**Perform this on your Ubuntu machine:**

    wget https://github.com/git-ecosystem/git-credential-manager/releases/download/v2.4.1/gcm-linux_amd64.2.4.1.deb
    sudo dpkg -i gcm-linux_amd64.2.4.1.deb
    git config --global credential.credentialStore gpg
    git config --global credential.credentialStore cache
    git config --global credential.credentialStore plaintext
    git-credential-manager configure
