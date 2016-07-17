# systemd-init-scripts
some systemd init scripts for some applications

# why
Welp I work on a Gentoo Linux OS, and I don't like to install 3rd party portage repositories just for application that I can fetch their sources online and they only miss an systemd init script. 
so I created these.

#includes

- couchpotato
- sickbeard

#please read the init scripts first
the init scripts assumes that you created a user and group for each application (usually users that you don't want to be able to login you point their home directory to `/dev/null`)
just read the init scripts and modify as required. they're pretty simple to understand.