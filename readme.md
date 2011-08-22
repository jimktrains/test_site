Test if a site is up
--------------------
To setup
--------
* Create a config file based on the provided example.
* Add to your crontab (crontab -e in debian and some others)
( * * * * * /home/you/test_sites/test_site /home/you/test_sites/your_site.cfg 2>&1 >> /tmp/test_sites_your_site)
