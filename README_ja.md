# 概要

- [Deno](https://deno.land/) と [Visual Studio Code](https://code.visualstudio.com/) の拡張機能「[Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)」を使用したサンプルです。

# 開発環境について

- [Visual Studio Code](https://code.visualstudio.com/) 
  - [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)

# 実行
```bash
deno run --allow-net main.ts
```

# 確認
- http://localhost:8080/

![deno2](https://user-images.githubusercontent.com/2668146/82136819-884e7100-984c-11ea-8cd7-d312702d5af7.png)

# テスト

```bash
deno test test.ts
```

# 参考URL
- https://deno.land/
- https://github.com/microsoft/vscode-dev-containers
