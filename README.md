<img src="https://user-images.githubusercontent.com/3092618/136671575-dae8cb93-d5ec-44d5-bfb9-c882a8fba516.png" width=700/>

Hosted at https://arxcis.github.io/flatstat/


## How to generate the stats
```
GITHUB_PERSONAL_ACCESS_TOKEN=<token> make all
```

## Folder structure

```
# Run commands
Makefile

# Commands that generate data
cmd/
    make-apps.js
    make-changelog.js
    make-count.js
    make-metafiles.js

# Data-folder contains generated data
data/
    apps.json
    changelog.json
    count.json
    metafiles.json

# Shared javascript files
lib/

# HTML Pages
about/index.html
library/index.html
graphs/index.html
index.html
```
