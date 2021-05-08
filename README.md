# bind-ddns-sed
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Simple BASH script to update BIND DNS zone with sed

On internet there are a lot of scripts, providing DNS updating with API for specific providers or BIND-nsupdate. But I don't think it's a good idea to configure TSIG keys and nsupdate for SOHO (Small office and Home) servers. Of course, this method has disadvantages - you can't update DNS from another machine because sript must run on the same machine where dns server is installed.

If you don't want to install BIND-utils for using dig utility, you can change DNS method to http/https(curl or wget), telnet or even FTP. Visit https://unix.stackexchange.com/questions/22615/how-can-i-get-my-external-ip-address-in-a-shell-script to read more.
