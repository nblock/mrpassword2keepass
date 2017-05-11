MrPassword2KeepassX
===================

Connect to a MrPassword instance and import all passwords into a Keepass
database (kdbx). This script uses an existing Keepass database and updates it
with the passwords from a MrPassword instance.

Usage
-----

After installing the dependencies listed in ``requirements.txt``::

  mrpassword2keepass \
    --mrpassword-url="https://your-mrpassword-instance" \
    --mrpassword-username="USERNAME" \
    --mrpassword-password="PASSWORD" \
    --keepass-path="/path/to/the/keepass/file" \
    --keepass-password="KEEPASS PASSWORD"
