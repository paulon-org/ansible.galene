# Examples
```
- hosts: <hosts>
  vars:
    galene:
      folder: /srv/galene
      domains:
        - galene.paulon.org
      certname: galene.paulon.org
      address: localhost
      port: 8443
  roles:
    - galene
```
