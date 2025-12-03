# IPv6 Address Processing Results

## 更新信息
- **最后更新时间**: 2025-12-03 10:10:47 UTC
- **源配置文件**: [best_cf_ipv6.txt](best_cf_ipv6.txt)
- **处理后文件**: [ipv6_dealwith_ips.txt](ipv6_dealwith_ips.txt)

## 统计信息
- 最终IPv6地址数: 11

## 处理详情
[URL] https://raw.githubusercontent.com/ymyuuu/IPDB/refs/heads/main/BestCF/bestcfv6.txt -> 10 地址
[直接IP] 2606:4700:0:6ce2:e496:d046:beb3:7cd6

## 文件格式示例
### 源配置文件格式
```
# 支持多种格式，每行一个源
"https://raw.githubusercontent.com/example/ipv6.txt"  # 带引号的URL
https://raw.githubusercontent.com/example/ipv6.txt   # 不带引号的URL
2400:cb00::/32                                        # 直接IPv6地址
2606:4700::/32
# 注释行会被忽略
```

### 处理后格式
```
  [2606:4700:0:4e1c:cc70:3755:fb4c:9c2d]:443
  [2606:4700:0:4eb8:5783:b4b4:c9df:e188]:443
  [2606:4700:0:6ce2:e496:d046:beb3:7cd6]:443
  [2606:4700:0:8ca4:10b:c62:9ae5:2556]:443
  [2606:4700:0:8ca4:1ba2:735f:2808:44b1]:443
```

## 使用场景
1. **代理配置**: 用于 Clash、V2Ray 等代理软件的规则配置
2. **防火墙规则**: 用于配置防火墙的允许/拒绝规则
3. **网络测试**: 用于测试 IPv6 连接

## 自动更新
此文件由 GitHub Actions 自动更新，更新频率为每6小时一次。
