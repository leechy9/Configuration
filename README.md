# Individual Configurations

## Git

Initial user information.

`git config --global user.email "you@example.com"`

`git config --global user.name "Your Name"`


Solarized colorscheme fix. Prevents split panes from opening with git commit.

`git config --global core.editor vim`


## SSH

Add to the `~/.ssh/config` file to specify which private key to use for a host.

  host github.com
    HostName github.com
    IdentityFile ~/.ssh/github
