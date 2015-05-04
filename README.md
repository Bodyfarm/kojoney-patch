# kojoney-patch
https://code.google.com/p/kojoney-patch/
(however Google code is set to Expire soon , 
I have some gentoo Ebuilds that reffrance this old code) 
so I am making a mirror of it before it dies

Kojoney is a low level interaction honeypot that emulates a SSH server. The daemon is written in Python using the Twisted Conch libraries.Please visit Kojoney Project home page

Changelog in 0.0.5.2

    Fix XMPP send message after connection breaks.
    Change XMPP ping frequency from 3600 to 60 seconds.
    Other minor fixes. 

Changelog in 0.0.5.1

    Add logging to DB (mySQL, PostgreSQL, Oracle, SQLite)
    Add external IP detection
    Add ASN lookup (Using MaxMind)
    Add Geo-IP-PurePerl 1.25
    Upgrade IP2Country lookup
    Upgrade Kojreport
    Upgrade INSTALL.sh script
    Upgrade Pycrypto-2.6 (Python Cryptography Toolkit)
    Upgrade Pyasn1-0.1.3
    Upgarde Gmplib 5.0.5
    Fix Public/Private key authentication
    Other minor fixes. 

Changelog in 0.0.5.0

Warning!: we have changed the original log format to something else.Please check download section for sample.

Some interesting features:

    Add Support Python 2.4, 2.5, 2.6, 2.7
    Add Support XMPP Messaging Protocol (Thanks JabberBot Thomas Perl)
    Add Support IP to Country/City (Using MaxMind)
    Add Support P0F - OS fingerprinting tools (>= 2.0.8)
    Add Support of local syslog server
    Change log format (remove TimeZone and add Milisecond)
    Support 32bit and 64bit systems (RHEL, Fedora, CentOS, Ubuntu ...)
    Upgraded Twisted engine 11.0.0
    Upgraded TwistedConch-11.0.0
    Upgraded Zope interface-3.8.0
    Upgraded Pycrypto-2.4.1 (Python Cryptography Toolkit)
    Upgraded IP-Country to 2.27.
    Upgraded Geography-Countries-2009041301.
    Upgrade the reporting tools to report passwords, clientSoftware and compresssion methods.
    Upgrade shell prompts.
    Add send message to any Jabber account
    Add gmp-5.0.2 (fix bug PowmInsecureWarning: Not using mpz_powm_sec.)
        (You should rebuild using libgmp >= 5 to avoid timing attack vulnerability.) 
    Add password log to find passwords used by attackers in login attempts.
    Add client software log to find client software used by attacker.
    Add compression log to find compression type may used by attackers.
    Add connection duration log. (Attack Duration)
    Corrections to the install and uninstall scripts.
    Corrections to the init.d script.
    Username & password file updated from 23752 combinations to 40748.
    Other minor fixes. 

Requirements

Software required:

    An operating system (tested on Ubuntu, CentOS, Fedora)
    Python 2.5+
    Python-devel
    Python-setuptools
    Python-pyasn1
    Python-xmpp
    Python-dns
    Perl
    Geo::IP::PurePerl perl module
    P0f 
