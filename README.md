# 飞网工作流

使用Action连接 [飞网](https://www.gmzta.com)

将如下代码集成到您的工作流中。

```yaml
  - name: 飞网
    uses: gmzta/github-action@v2
    with:
      authkey: ${{ secrets.GMZTA_AUTHKEY }}
```

完成上述步骤后，您已经接入到飞网中，并可以访问飞网中的资源。
