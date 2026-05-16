# mac-setup
![actions](https://img.shields.io/github/workflow/status/dskst/mac-setup/CI?label=actions&logo=github&style=flat-square)

Setup for mac. Use ansible.

## Usage

1. make workspace
2. install homebrew
3. install homebrew cask
4. install ansible

```
$ ansible-playbook ./playbooks/mac.yml --ask-become-pass
```

```
$(brew --prefix)/opt/fzf/install
```
