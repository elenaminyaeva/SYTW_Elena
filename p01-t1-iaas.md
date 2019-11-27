# Práctica_1 
## Instalar/Upgrade `git`
`MacBook-Pro-Elena:~ elenaminyaeva$ brew upgrade node` <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ git --version
git version 2.21.0`
## Instalar/Upgrade `node`
`MacBook-Pro-Elena:~ elenaminyaeva$ brew upgrade node` <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ node --version
v13.2.0`
## Instalar `nvm`
`MacBook-Pro-Elena:~ elenaminyaeva$ brew install nvm` <br/>
`echo "source $(brew --prefix nvm)/nvm.sh" >> .bash_profile` <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ nvm --version
0.35.1` <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ nvm ls-remote` <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ nvm install v13.2.0` <br/>
`Checksums matched! Now using node v13.2.0 (npm v6.13.1)`
## Instalar `rvm`
`MacBook-Pro-Elena:~ elenaminyaeva$ which ruby
/usr/bin/ruby` <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ ruby -v` <br/>
`ruby 2.3.7p456 (2018-03-28 revision 63024) [universal.x86_64-darwin17]` <br/>
El primer paso para instalar `rvm` es el *mpapis public key* <br/>
`MacBook-Pro-Elena:~ elenaminyaeva$ brew upgrade gnupg` <br/>
  gpg --keyserver hkp://keys.gnupg.net
