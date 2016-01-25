# mark2-ansible

A collection of ansible roles to bootstrap a minecraft hosting environment on a Debian system.

*Tested on Debian 8 "Jessie" and Ubuntu 14.04 LTS*

I plan to make this easier, but you're gonna want to adjust the options in the security task, especially the SSH keys. I don't recommend this if you're a novice user.

Roles
-----
- `mark2` -> Install [mark2](https://github.com/gsand/mark2), a phenomenal minecraft wrapper maintained by [gsand](https://github.com/gsand).
- `java` -> Install Oracle Java 8.
- `security` -> Secure system with key-only authentication, this is optional but highly recommended.

