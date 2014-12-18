vagrant-otrs
============

Vagrant Box with OTRS deployed on hashicorp/precise32 for development purposes.

1. Run "vagrant up"
2. Go to the OTRS installer at http://localhost:3002/otrs/installer.pl
3. Configure an "Existing Database" with PostgreSQL, credentials: user 'otrs', password 'otrspassword' and database 'otrs'.
4. (Optional) Configure Mail settings
5. Remember OTRS-root user password for first login
6. Login at http://localhost:3002/otrs/index.pl
7. Enjoy. 