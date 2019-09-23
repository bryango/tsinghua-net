# Tsinghua Net Utils
清华校园网辅助脚本，基于 https://github.com/Berrysoft/TsinghuaNet <br/>
请从上述链接获取 TsinghuaNet.CLI, 重命名（或 symlink）为 tsinghua-net 并放置到 PATH 中。

## 脚本参数

- `$TSINGHUA_NET_ACCURATE` - 若存在该变量，则将会定期退出重登录，以刷新流量用量。
- `$TSINGHUA_NET_TIMESTAMP` - 登录时刻的记录文件，默认为 `/tmp/tsinghua-net.timestamp` .
- `$TSINGHUA_NET_TIMEOUT` - 登录过期时限，默认为 `30 * 60` （秒），超时将退出重登录，以刷新流量用量。
