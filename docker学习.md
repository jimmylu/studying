# docker学习

##常用命令

`docker images ` 现实docker镜像列表
---------------
```bash
Usage:	docker images [OPTIONS] [REPOSITORY[:TAG]]

List images

Options:
  -a, --all             Show all images (default hides intermediate images)
      --digests         Show digests
  -f, --filter filter   Filter output based on conditions provided
      --format string   Pretty-print images using a Go template
      --help            Print usage
      --no-trunc        Don't truncate output
  -q, --quiet           Only show numeric IDs
```

`docker ps` 显示容器列表
----------
```bash
Usage:	docker ps [OPTIONS]

List containers

Options:
  -a, --all             Show all containers (default shows just running)
  -f, --filter filter   Filter output based on conditions provided
      --format string   Pretty-print containers using a Go template
      --help            Print usage
  -n, --last int        Show n last created containers (includes all states) (default -1)
  -l, --latest          Show the latest created container (includes all states)
      --no-trunc        Don't truncate output
  -q, --quiet           Only display numeric IDs
  -s, --size            Display total file sizes

```

[**样例**]<br/>

CONTAINER ID|IMAGE|COMMAND|CREATED|STATUS|PORTS|NAMES
-------------|-----|-------|-------|------|-----|-----
8aacc032e6fd|mysql|"docker-entrypoint..."|5 minutes ago|Up 5 minutes|0.0.0.0:3306->3306/tcp|iddd-mysql



