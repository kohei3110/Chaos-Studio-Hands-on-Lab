# Azure Chaos Studio Demo

以下のボタンをクリックしてデプロイ。

## リソースのデプロイ

### 1. リソースグループ

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkohei3110%2FChaos-Studio-Hands-on-Lab%2Fmaster%2Ftemplates%2F01-resource-group%2Fresource-group.json)

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
