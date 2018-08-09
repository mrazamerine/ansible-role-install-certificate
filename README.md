# Ansible role – Install Certificate

Ansible role for installing SSL certificates on remote machines.


## Variables

* **backup_original_files** – Back-up files on remote machines being copied (bool) [false]

* **cert_name** – Name of the certificate (string)

* **cert_local_path** – Local path of the certificate (string)

* **privkey_local_path** – Local path of the certificate private key (string)

* **chain_local_path** – Local path of the certificate chain (string)

* **full_chain_local_path** – Local path of the full certificate chain (string)
