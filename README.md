# How to use this repo

1) Make a fork of the repo.
2) Update build_env according to your OpenWrt release, CPU arch/target/subtarget and vermagic (`opkg list-installed kernel` returns the needed value after dash: `***-{vermagic}`).
3) Commit changes, add a tag like `v*.*.*`
4) Push commit and tags. Wait up to 2 hours while job being exucuted. 
5) Grab packages from release and install locally using OpenWrt web UI -> Software