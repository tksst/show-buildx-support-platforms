# setup-buildx-action only

If you simply do `setup-buildx-action`, you get:

```
Platforms: linux/amd64,linux/amd64/v2,linux/amd64/v3,linux/amd64/v4,linux/386
```

# With setup-qemu-action

With setup-qemu-action before setup-buildx-action, you get:
```
Platforms: linux/amd64,linux/amd64/v2,linux/amd64/v3,linux/arm64,linux/riscv64,linux/ppc64le,linux/s390x,linux/386,linux/mips64le,linux/mips64,linux/arm/v7,linux/arm/v6
```

# How to get it yourself

Fork this repository and run the Action "Show container platforms"

To learn more about how it works, see [setup-buildx-action](https://github.com/docker/setup-buildx-action#quick-start) and [action](.github/workflows/show-platforms.yml).

# setup-buildx-action だけの場合

If you simply do `setup-buildx-action`, you get:

```
Platforms: linux/amd64,linux/amd64/v2,linux/amd64/v3,linux/amd64/v4,linux/386
```

# setup-qemu-action を使った場合

With setup-qemu-action before setup-buildx-action, you get:
```
Platforms: linux/amd64,linux/amd64/v2,linux/amd64/v3,linux/arm64,linux/riscv64,linux/ppc64le,linux/s390x,linux/386,linux/mips64le,linux/mips64,linux/arm/v7,linux/arm/v6
```

# 自分で取得する方法

このリポジトリをクローンして、"Show container platforms"というアクションを実行する。

詳しく知りたい場合は[setup-buildx-action](https://github.com/docker/setup-buildx-action#quick-start)と[action](.github/workflows/show-platforms.yml)を見てください。
