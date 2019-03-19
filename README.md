ansible-template
===

Ansible-template is an Ansible module template generator for task files. Give it a module name and it will output a template for that module which can be edited and used on an Ansible task file.

The output text also provides an explanation for each of the module options, as per the [Ansible documentation page](https://docs.ansible.com/ansible/latest/modules/modules_by_category.html)  .

![](img/demo.png)

**Usage:**

```
$ ansi-template
Usage ansi-template [list|module]
```

**See it in action**

[![asciicast](https://asciinema.org/a/OU5KATKdK9T0nRDbUJ0cr9fY6.svg)](https://asciinema.org/a/OU5KATKdK9T0nRDbUJ0cr9fY6)

Available Modules
---

I'm always trying to add new modules. The currently available modules are:

- archive
- blockinfile
- command
- copy
- fetch
- file
- get_url
- group
- lineinfile
- script
- service
- shell
- synchronize
- systemd
- template
- unarchive
- user


Installation
---

Download `ansible-template.bash` and source it on your `~/.bashrc` or `~/.bash-aliases`.

Requirements
---

+ Bash
+ highlight (optional to display colors)
