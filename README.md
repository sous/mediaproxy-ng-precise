This is an apt repository.

It can be cloned locally and referred to directly:

    git clone https://github.com/sous/mediaproxy-ng-precise
    ( echo deb file://`pwd`/mediaproxy-ng-precise precise main
      echo deb-src file://`pwd`/mediaproxy-ng-precise precise main ) > /etc/apt/sources.list.d/mediaproxy-ng-precise.list

Either way, the gpg key for this repo can be imported using:

    curl https://raw.github.com/sous/mediaproxy-ng-precise/master/apt-key.gpg | sudo apt-key add

Alternatively, this is codified in this chef cookbook: https://github.com/sous/mediaproxy-ng-cookbook

