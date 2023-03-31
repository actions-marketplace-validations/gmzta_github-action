# 飞网 GitHub Action

使用GitHub Action 连接 [飞网](https://gmzta.com)
通过将步骤添加到您的工作流中。

```yaml
  - name: 飞网
    uses: gmzta/github-action@v1
    with:
      authkey: ${{ secrets.GMZTA_AUTHKEY }}
```

然后，操作中的后续步骤可以访问飞网中的节点。
