Ansible Role for installing Wordpress
+++++++++++++++++++++++++++++++++++++

This Ansible Role installes Wordpress on a Debian / Ubuntu system as
it is described in `Debian Wordpress`_

.. _`Debian Wordpress`: https://wiki.debian.org/WordPress

History
=======

My first attempt was to use the official Wordpress installation.
After doing *some* work I realized that many of exactly the work that
needs to be done for a secure and easy to maintain version was already
done by the Debian maintainers - like multiple sites using one
Wordpress installation or multiple database schemes.  Therefore I
switched to using the Debian way of handling things.

One drawback is, that the Debian version is not really the newest one.
