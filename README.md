sing-box文件夹中的规则为1.8制作的
sing-box1.9文件夹的规则适配了1.9新的domain_suffix规则

官方介绍如下：

domain_suffix 行为更新
由于历史原因，sing-box 的 domain_suffix 规则匹配字面前缀，而不与其他项目相同。

sing-box 1.9.0 修改了 domain_suffix 的行为：如果规则值以 . 为前缀则行为不变，否则改为匹配 (domain|.+\.domain)。
