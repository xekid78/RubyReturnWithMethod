# RubyReturnWithMethod
メソッドでリターンがある場合

## 処理
`multi()`メソッドを作って計算した値をリターンで戻す。

## コード
```
def multi(x, y)
    return x * y
end

puts multi(7, 8)
```
ちなみに
```
def multi(x, y)
    x * y
end

puts multi(7, 8)
```
のように``return``が無くても最後の計算結果が``Ruby``では戻る。


## 出力結果  
```
56
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
