# solana-create-token

#https://www.solanazh.com/course/6-5
创建token练习合约

扩充 Token 合约，为 Token 合约增加 Meta 信息，如

icon: 代币图标
name: 代币名称
symbol: 代币符号缩写
home: 代币主页
提示：

增加一个 Token 管理合约
当通过 Token 合约 Mint 新 SPL Token 的时候，同时在这个新合约里面注册 Token 合约地址以及对应的 Meta 信息
用 Mint 的 SPL Token 的地址去这个合约中去查询 Meta 信息
