# SubGIT + GoGS integration 

| SubGit | Gogs  |
| ------ | ----- |
|  3.2.2 | 0.9.71  |


## [SubGIT]

SubGit is a tool for a smooth, stress-free SVN to Git migration. Create a writable Git mirror of a local or remote Subversion repository and use both Subversion and Git as long as you like. You may also do a fast one-time import from Subversion to Git or use SubGit within Atlassian Bitbucket Server.

[SubGIT]: https://subgit.com/


## [GoGS] - Go Git Service


A painless self-hosted Git service.

[GoGS]: https://gogs.io/

## Why Gogs 0.9.71 (and not the 0.9.97)

The 0.9.97 can't handle correctly first LDAP logon. ( gogits/gogs#3926 )
The latest version can handle it but doesn't allow repository creation in Organistations. ( gogits/gogs#3905 )

The version 0.9.71 doesn't have those regressions.

