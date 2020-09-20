# strongswan

[![Build Status](https://travis-ci.com/1mr/ansible-role-rc_local.svg?branch=master)](https://travis-ci.com/1mr/ansible-role-rc_local)

This role helps to configure rc.local.

## Requirements

This role requires ansible 2.5 or higher.

## Role Variables

* `rc_local` (default: `[]`): entries to add to `/etc/rc.local`

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - { role: 1mr.rc_local, tags: rc_local }

## License

MIT

## Author Information

This role was created by Stas Stavnichuk.
