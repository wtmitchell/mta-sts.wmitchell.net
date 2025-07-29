Trivial repo to host a MTA-STS policy file on Github pages

In addition to the file .well-known/mta-sts.txt, need TXT DNS entries for
* The subdomain _mta-sts to specify that the policy file exists
* The subdomain _smtp._tls to specify where TLS-RPT should be sent
