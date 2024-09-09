# Set Proxy Of Git

```shell
# set proxy
git config --global http.proxy http://127.0.0.1:7890
git config --global https.proxy http://127.0.0.1:7890

# unset proxy
git config --global --unset http.proxy
git config --global --unset https.proxy
```