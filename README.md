# An Ansible role to install and configure OpenSSH on Windows
A playbook to configure OpenSSH on Windows with key-based authentication.

# Folder structure
```openssh_playbook
 ├── configure_openssh.yml
 └── openssh_windows
      ├── tasks
      │   ├── configure_openssh.yml
      │   ├── main.yml
      │   └── set_public_key.yml
      └── vars
          └── main.yml
```

# Features
- Installs and configures OpenSSH client and server.
- Sets a custom port for SSH incoming connections.
- Disables password authentication
- Add a public key for key-based authentication