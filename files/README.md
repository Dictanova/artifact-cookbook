Use a custom build for `nexus_cli` to fix compatibility with Chef 14 / Ruby 2.5
See RiotGamesMinions/nexus_cli#123 issue.

```
git clone https://github.com/mbakhoff/nexus_cli 
git checkout no-chozo
cat "4.1.2-dictanova0" > VERSION
rake install
```

