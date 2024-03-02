# to generate app make
```sh
mix phx.new forum --database sqlite2
```

# start server

```sh
mix phx.server
```


# if you walk through this error 

```sh
[error] `inotify-tools` is needed to run `file_system` for your system, check https://github.com/rvoicilas/inotify-tools/wiki for more information about how to install it. If it's already installed but not be found, appoint executable file with `config.exs` or `FILESYSTEM_FSINOTIFY_EXECUTABLE_FILE
```

# you can run

```sh
sudo apt install inotify-tools
```