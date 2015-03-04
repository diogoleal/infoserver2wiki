# infoserver2wiki
List some operating system information and creates a text file in the format dokuwiki

## Created functions:
* FQDN and hostname
* Number of CPUS
* Total Memory
* Enabled processes in the operating system boot (RHEL6, Ubuntu e Gentoo)
* Iptables rules
* Interfaces and the network address
* Mounted partitions
* Show crontab
* Normal users and users system


## Install dependencies
Dependencies are psutils and pyhon-iptables

To facilitate:

```
pip install -r requirements.txt
```

## Display order:
Change the order on display_function() to sort the report display.


## ToDo
Soon I will implement:
* List groups that are not system
* Configured routes
* Repositories configured

And then:
* Record information directly to dokuwiki
* Options for more than one type of wiki mediawiki like, for example.
