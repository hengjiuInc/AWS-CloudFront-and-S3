<a href="https://www.hengjiu.jp">
    <img src="https://www.hengjiu.jp/img/retina/header_logo@2x.jpg" alt="hengjiu logo" title="hengjiu" align="right" height="50" />
</a>

# [CFnTemplate] CloudFront + S3

## 構成図
<div align="center">
<img src="./img/architecture.png" alt="属性" title="architecture">
</div>


## 概要
- CloudFrontとS3の構成です。
- ドメインはオリジナルドメインを利用するため事前にACMで証明書を用意する必要があります。


---
##### 関連URL
- <a href="https://docs.aws.amazon.com/ja_jp/AmazonCloudFront/latest/DeveloperGuide/using-managed-cache-policies.html" target="_blank">管理キャッシュポリシーの使用</a>

