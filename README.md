Conference engine
=========


Originally it was created for support [LVEE conference](http://lvee.org)

Now it is been rewriting to support running any conference.




Installation
------------


System:
    sudo apt-get install git curl


RVM (Ruby Version Manager):

    gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
    curl -sSL https://get.rvm.io | bash -s stable
    source ~/.rvm/scripts/rvm


Source code, Ruby, Gems:

    git clone https://github.com/lvee-conference/lvee/
    cd ./lvee/
    rvm install $(cat .ruby-version)
    rvm use $(cat .ruby-version)
    bundle install




License
------------


[GPL v.2](https://gnu.org/licenses/old-licenses/gpl-2.0-standalone.html)
