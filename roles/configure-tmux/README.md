configure-tmux
=========

Moves my tmux configuration file from `/configure-tmux/files/` to my home directory.

Requirements
------------

tmux

Example Playbook
----------------
    hosts: localhost
    connection: localhost
      roles:
         - role: "roles/configure-tmux"
