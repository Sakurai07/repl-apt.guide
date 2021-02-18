# repl-apt.guide
how to use apt in repl.it

# Steps
```
apt install nano #example
#since repl.it blocks apt
go to https://pkgs.org
wget https://link.to/nano/.deb/
dpkg -e nano.deb
cd usr/bin/
chmod +x nano
nano <file>
nano --help
```

# A pretty bad way of installing apt packages on repl.it
kinda the only way tho
