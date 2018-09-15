# melcma.git

Ubuntu 16.04 and Ubuntu 18.04 supported

Define application dictionary and import it, example:

    applications:
      myapp.com:
        repository: git@gitlab.com:user/myapp.com.git

You will also need to put global and local git config files:

    files/gitconfig - global
    files/.gitconfig - local