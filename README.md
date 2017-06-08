```
vagrant up
vagrant ssh

# upload over https
asciinema upload /vagrant/below-4k.json
asciinema upload /vagrant/over-4k.json   # <- this one fails

# upload over http
ASCIINEMA_API_URL=http://asciinema.org asciinema upload /vagrant/below-4k.json
ASCIINEMA_API_URL=http://asciinema.org asciinema upload /vagrant/over-4k.json
```
