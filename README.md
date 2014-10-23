# CloudStack cloudmonkey CLI

_cloudmonkey_ is a command line interface (CLI) tool for CloudStack written in Python. cloudmonkey can be use both as an interactive shell and as a command line tool which simplifies CS configuration and management. It is unofficially distributed by community maintained distribution at the [cheese shop](http://pypi.python.org/pypi/cloudmonkey/) as well as within the git repository in tools/cli/. It can be used with Apache CloudStack 4.0-incubating and above.

![cloudmonkey](https://cwiki.apache.org/confluence/download/attachments/29687935/CLOUDSTACK2.png)

## Quickstart

```bash
docker run -it --rm -v /path/to/config:/data petrhosek/cloudmonkey
```

The `/path/to/config` path should contain a cloudmonkey [configuration file](https://cwiki.apache.org/confluence/display/CLOUDSTACK/CloudStack+cloudmonkey+CLI#CloudStackcloudmonkeyCLI-Configuration).

Use cloudmonkey as a command line tool, by passing args to the container:

```bash
docker run -it --rm -v /path/to/config:/data petrhosek/cloudmonkey list virtualmachines
```

## Contributing

Contributions, both to content and design are welcome and encouraged. To contribute, please submit a [pull request](https://github.com/petrhosek/docker-cloudmonkey/compare/).

## License

Creative Commons Attribution 3.0 Unported (CC BY 3.0)
