# tracker.janky.solutions

Ansible playbooks to setup an opentracker cluster. Assumes hostnames of `xxxX.tracker.janky.solutions`.
`vars/secrets.yml` should look like:


```yaml
---
  digital_ocean_token: XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
  do_ssh_keys:
    - XXXXXXX
  ssh_keys:
    - ssh-ed25519 AAAAAABLAHWHATEVEROMGLOL user@host
```
