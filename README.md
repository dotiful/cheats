Cheatsheets for [navi](https://github.com/denisidoro/navi).

By running `navi` for the first time, you'll be suggested to download [community-sourced cheatsheets](https://github.com/denisidoro/cheats). By running `navi` again, these cheatsheets will appear.

In order to add your own repository as a featured cheatsheet repo, edit [this file](https://github.com/denisidoro/cheats/edit/master/featured_repos.txt).
This list will be displayed when `navi repo browse` is run.

To add cheatsheats from separate local paths containing `.cheat` files, set `NAVI_PATH` environment variable, for example:

```bash
export NAVI_PATH="$(/bin/ls -d ~/code/cheats/*/ | tr "\n" ":")"
```


Read the `navi` [cheatsheets syntax](https://github.com/denisidoro/navi#cheatsheet-syntax)
