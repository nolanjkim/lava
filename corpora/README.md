Introduction
============

This a compilation of memory related bugs.  The intent of this list is to address the question of realism in LAVA.  Primarily, we are looking to see if these bugs result from a usage of data that is "dead."

Bugs
====

Data was gathered from https://nvd.nist.gov and https://cve.mitre.org/

Wireshark
---------
* CVE 2011-1591 - 1.4x before 1.4.5 - DECT dissector in epan
* CVE 2011-0024 - 1.2 - Heap overflow in pcapng.c
* CVE 2011-0444 - 1.2-1.2.13 and 1.4.2 - Oveflow in packet-mac-lte.c
* CVE 2010-4538 - 1.4.2 - Buffer overflow in sect_enttec_dmx_da packet -enttec.c
* CVE 2012-4297 - 1.6.x and 1.8.x - packet-gsm_rlcmac.c

Binutils
--------
* CVE 2005-1704 - gdb < 6.3 - Integer overflow in BFD
* CVE 2005-4807 - binutils<20050721 - as_bad() in messages.c
* CVE 2006-2362 - binutils < 20060423 - reset_vars() in config/tc-crx.c
* CVE 2014-8485 - binutils < 2.24 - setup_group() in bfd/srec.c
* CVE 2014-8503 - binutils < 2.24 - ihex_scan() in bfd/ihex.c
* CVE 2014-8504 - binutils < 2.24 - ihex_scan() in bfd/ihex.c

OpenSSH
-------
* CVE 2003-0695 - <3.7.1 - buffer_init() buffer.c, buffer_free() in channels.c
* CVE 2003-0693 - <3.7 - buffer_append_space() in buffer.c
* CVE 2002-0640 - 2.3.1-3.3.0 - sshd buffer overflow PAMAuthenticationViaKdbInt

Eye of Gnome
------------
* libpng

* libjpg