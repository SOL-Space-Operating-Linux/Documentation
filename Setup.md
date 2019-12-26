# Setup
## Install repo
On Debian/Ubuntu:
    
    $ sudo apt-get install repo
    
Or, install manually:
    
    $ mkdir -p ~/.bin
    $ PATH="${HOME}/.bin:${PATH}"
    $ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
    $ chmod a+rx ~/.bin/repo
    
## Initialize and Sync
    
    $ mkdir sol
    $ cd sol
    $ repo init -u https://github.com/SOL-Space-Operating-Linux/repo-manifest.git
    $ repo sync
