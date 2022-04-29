# Wadorobu
For new clone projects please pull it via the command below
```
git clone --recurse-submodules https://github.com/kuru-studio/wadorobu.git
```

If you've pulled in a normal way and the submodules are missing, please do the commands below
```
git fetch --unshallow --tags --recurse-submodules
git submodule update --init --recursive --remote
```
