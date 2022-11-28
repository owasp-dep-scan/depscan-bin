# depscan-bin

Repository containing the binaries for [depscan](https://github.com/AppThreat/dep-scan) - the dependency scanning tool. depscan is also available on [PyPI](https://pypi.org/project/appthreat-depscan/)

![Depscan logo](dep-scan.png)

## Single binary executables

Download the executable binary for your operating system from the [releases page](https://github.com/ngcloudsec/depscan-bin/releases). These binary bundle the following:

- dep-scan with Python 3.10
- cdxgen with Node.js 18
- cdxgen binary plugins

On Linux
```
curl -LO https://github.com/ngcloudsec/depscan-bin/releases/download/v3.2.1/depscan-linux-amd64
chmod +x depscan-linux-amd64
./depscan-linux-amd64 --help
```

On Windows

```
curl -LO https://github.com/ngcloudsec/depscan-bin/releases/download/v3.2.1/depscan.exe
.\depscan.exe --help
```
