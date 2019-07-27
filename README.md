# Ansible Role de NGinx + HTTPS automática gratuita em tempo de execução
**[rascunho público] [Ansible](https://www.ansible.com/) Role que usa o
[OpenResty](https://openresty.org) (fork do NGinx) + [GUI/lua-resty-auto-ssl](https://github.com/GUI/lua-resty-auto-ssl)
para fornecer HTTPS automática e gratúita do
[Let’s Encrypt](https://letsencrypt.org/).**

Ideal para quem quer funcionalidades de obter certificados HTTPS depois de
instalação do servidor de modo semelhante ao que o [Traefik](https://traefik.io/)
e o [CaddyServer](https://caddyserver.com/) fariam, mas que ainda prefere usar
sintaxe de NGinx.

<!--
Arquivos 

- Erros do OpenResty (NGinx, AutoSSL, proxy de entrada...)
    - `/usr/local/openresty/nginx/logs/error.log`
- Acesso do OpenResty (NGinx, AutoSSL, proxy de entrada...)
    - `/usr/local/openresty/nginx/logs/access.log`

-->

Requirements
------------

...

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Public Domain
