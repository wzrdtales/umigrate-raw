[![Dependency Status](https://david-dm.org/wzrdtales/umigrate-raw.svg)](https://david-dm.org/wzrdtales/umigrate-raw)
[![devDependency Status](https://david-dm.org/wzrdtales/umigrate-raw/dev-status.svg)](https://david-dm.org/wzrdtales/umigrate-raw#info=devDependencies)

# Ultimate Migrate Raw Driver

This is a raw "database" driver for
[ultimate-migrate](https://github.com/wzrdtales/node-ultimate-migrate).
It uses instead of the database, the migration files to build the schema.
To accomplish this we directly pass through this driver to db-migrate, as we
have data bindings on the umigrate side we don't explicitly provide a driver
for db-migrate, but utilize the driver require feature of db-migrate.

This driver is splitted in to two parts:
The umigrate driver which are simply function which return the build collections
and the db-migrate driver which provides all functions of db-migrate and write
the data into the collections. 

## Donate

If you like my work and it is helping you, please consider making a donation to
help me keeping the development and support up. Thanks :)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=H4CEDA2UTTP5A)

[![Donate Bitcoin to 1M7kvaeGGwRurRSkNfKdnsX26qaGF7bthp](https://blockchain.info//Resources/buttons/donate_64.png)](https://wizardtales.com/donate.html)

[![Donate via Gratipay](https://avatars1.githubusercontent.com/u/1744073?v=3&s=200)](https://gratipay.com/wzrdtales/)

## Contact

You may contact me via mail or xmpp( jabber ).

I prefer xmpp, it's safe if wished OTR is also available.

xmpp:tobi@wizardtales.com

[![View Testresults](https://xmpp.net/badge.php?domain=wizardtales.com)](https://xmpp.net/result.php?domain=wizardtales.com&type=client)

# License

[MIT](https://github.com/wzrdtales/umigrate-raw/blob/master/LICENSE)
