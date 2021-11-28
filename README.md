# Azure Chaos Studio Demo

以下のボタンをクリックしてデプロイ。

## リソースのデプロイ

### 1. リソースグループ

### 2. 仮想ネットワーク

### 3. アプリケーションゲートウェイ・仮想マシンなど

### 4. Azure Functions（クライアント）

`client/run.ps1` を修正。

```powershell
・・・
# Access Application Gateway
Invoke-WebRequest http://http://<YOUR_APPLICATION_GATEWAY_PUBLIC_IP_ADDRESS>/
・・・
```