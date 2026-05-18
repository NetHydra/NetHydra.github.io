---
layout: tools-doc-only-sonar
title: MISP
permalink: /doc/tools/sonar-tools-misp
comments: true
tool-icons: /assets/graphics/tools_graphics/misp.svg
tool-version: blank
packages-name: misp
tools-command: misp-start
whoupdate: Joe
userupdate: https://github.com/me-joe
categories: M
update: 2026-05-18 06:20:00 +0700
author: Joe
editpage: https://github.com/hydrapwk/hydrapwk.github.io/blob/main/content/_tools/hydrapwk-tools-netexec.md
---

Open Source Threat Intelligence and Sharing Platform

## starting MISP

for the first time to starting MISP in `SONAR` you need to initialize `MISP`.

```
──(sonar@sonar)─[~]                                                                                                                          
└─── $ sudo misp-init
[...]
```

that command will setup every dependencies we need for MISP.

you may get prompt like:

```
Do you trust "php-http/discovery" to execute code and wish to enable it now? (writes "allow-plugins" to composer.json) [y,n,d,?] y
```

you need type `y` then enter

after a few moments after all dependencies has been downloaded you'll get message box

you will get `2 options` to setup `auto setup` or `manual`.

after you choose one of them you can follow the instruction like setup creds, password, mail, etc.

after everything was done you will get last output like:

```
[*] Generating password for you..

[*] setting up GnuPG for MISP...
gpg: keybox '/var/www/MISP/app/.gnupg/pubring.kbx' created
gpg: /var/www/MISP/app/.gnupg/trustdb.gpg: trustdb created
gpg: directory '/var/www/MISP/app/.gnupg/openpgp-revocs.d' created
gpg: revocation certificate stored as '/var/www/MISP/app/.gnupg/openpgp-revocs.d/7B54EF0B04E9C0A433CC9FEE30910C6AEE070DA5.rev'
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEagfbTBYJKwYBBAHaRw8BAQdAbfYI9Wa8aB/zVRSAk+y03btjgdjQrIYjUJ6w
oR4rcFW0EWdudXBnQGdudXBnLmxvY2FsiJAEExYKADgWIQR7VO8LBOnApDPMn+4w
kQxq7gcNpQUCagfbTAIbAwULCQgHAgYVCgkICwIEFgIDAQIeAQIXgAAKCRAwkQxq
7gcNpbFwAP9mjpHtBNGAFK+cHF3rEfZmYgnW8quLWfJxLWZGX3FWpwEA2utLFCR6
psD8NDYtyvlHEn9tZooyHVdC+X7TbyQnuwi4OARqB9tMEgorBgEEAZdVAQUBAQdA
Y4QJc3LFlcscjtnbHAVPb3PGOZK2GCDlxUH2c916Cn8DAQgHiHgEGBYKACAWIQR7
VO8LBOnApDPMn+4wkQxq7gcNpQUCagfbTAIbDAAKCRAwkQxq7gcNpeTYAP4jLJWV
tyYK8nTb/Q3z46JTJSOwIjqDF0K58a4Tx617vAD/U/L5CtVpAqt++w2M14RKNlyh
i4P6BB57jWSlV6kkvgc=
=ToX4
-----END PGP PUBLIC KEY BLOCK-----
User created.
Password for misp@misp.local changed.
==========

Your MISP login creds

MAIL= misp@misp.local
PASSWORD= NaezohCeim1aovia

==========
Your MISP creds has been saved to /etc/misp/misp@misp.local.pass

If browser didn't showing in 5 second please open this address into your browser

http://127.0.0.1

──(sonar@sonar)─[~]                                                                                                                               
└─── $
```
_the output of the gpg will differrent_

And here is! you should can be access MISP login page in `http://127.0.0.1` (for the `The manual setup` the address maybe will different depends on what youre set)

![MISP Setup creds for the first time](/assets/graphics/post_graphics/nethydra-2026.02/sonar-misp-setup-creds.png)

once you need to start MISP again you only need to type `misp-start`
