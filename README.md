# go-parrot.live
https://github.com/hugomd/parrot.live, made it with golang

# Try it
```shell
curl parrot.hellp.live
```

# Resolve 502 error bad gateway with nginx
https://stackoverflow.com/a/24830777

```shell
setsebool -P httpd_can_network_connect 1
```