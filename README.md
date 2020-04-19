[//]: # ($FrauBSD: neith00/viotop/README.md 2020-04-19 08:47:44 +0200 neith00 $)

# Welcome to [FrauBSD.org/viotop](https://fraubsd.org/viotop)!

Generate top-like statistics for Linux VFS I/O using bpftrace

## Installation

Replace `viotop_release` value with current release version.

```console
export viotop_release='2.3' && \
cd "$(mktemp -d)" && \
curl -fsSL "https://github.com/FrauBSD/viotop/archive/${viotop_release}.tar.gz" \
-o viotop_${viotop_release}.tar.gz && \
tar -xvf viotop_${viotop_release}.tar.gz && \
sudo mv viotop-${viotop_release}/viotop /usr/local/bin
```

### Requirements

#### Fedora

```console
sudo dnf install bpftool bpftrace  
```
## Usage

```console
viotop
```

## Contributing

The following is required before using `git commit` in this project.

> `$ .git-hooks/install.sh`

This will ensure the FrauBSD keyword is expanded/updated for each commit.
