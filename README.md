# volta-node-16


### How to create a project?

```shell
// volta installer
➜  ~ curl https://get.volta.sh | bash

// volta install node
➜  ~ volta install node@16
success: installed and set node@16.15.0 (with npm@8.5.5) as default

➜  ~ volta install yarn
success: installed and set yarn@1.22.18 as default

// u can pin node and package manager version in package.json
➜  volta-node-16 git:(master) ✗ volta pin node@16
success: pinned node@16.15.0 (with npm@8.5.5) in package.json

➜  volta-node-16 git:(master) ✗ volta pin yarn@1.22.18
success: pinned yarn@1.22.18 in package.json

```

### Check the tool chain

```shell

➜  volta-node-16 git:(master) volta list
⚡️ Currently active tools:

    Node: v16.15.0 (current @ /Users/hyxiebackup/volta-node-16/package.json)
    Yarn: v1.22.18 (current @ /Users/hyxiebackup/volta-node-16/package.json)
    Tool binaries available:
        vue (default)
         (default)
        tsc, tsserver (current @ /Users/hyxiebackup/volta-node-16/package.json)

See options for more detailed reports by running `volta list --help`.

```

通过查看工具链，就知道当前项目所使用的工具的版本。进入项目，volta会帮助你自动路由到正确的版本，不需要人为切换环境