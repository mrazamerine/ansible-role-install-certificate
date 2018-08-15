# Ansible role – Install Certificate

Ansible role for installing SSL certificates on remote machines.


## Variables

* **backup\_original\_files** – Back-up files on remote machines being copied (bool) [false]

* **cert\_name** – Name of the certificate (string)

* **cert\_local\_path** – Local path of the certificate (string)

* **privkey\_local\_path** – Local path of the certificate private key (string)

* **chain\_local\_path** – Local path of the certificate chain (string)

* **full\_chain\_local\_path** – Local path of the full certificate chain (string)
