# [repo](https://github.com/sdrausty/repo)

Add the following line:
```
deb [trusted=yes] https://sdrausty.github.io/repo termux extras
```
To the `sources.list` file so `apt` can access this repository from your device in Termux.

Use `apt list --all-versions` to see what is available for installing via `apt`.

For some unknown reason `pkg list-all` doesn't list what is available for installing from this repository via `pkg`.

To see what is available, please view the `Packages` files. 
