# Nothing EUICC Force Enabler
eSIM に非対応な Nothing のデバイスでも強制的に eSIM の機能を有効化させます。<br>
**v2.0 でシステム LPA に対応しました! (Qualcomm のデバイスのみ)**

> [!IMPORTANT]
> システム LPA が動作しないと OS 単体での eSIM のダウンロードや切り替えの操作はできません。
>
>  現在、MTK のデバイスでシステム LPA は使用できません。

というかOSをほぼ弄ることも無かったので Nothing OS 以外でも動くと思います。

#### テスト済みデバイス
- Nothing Phone (1)
- Nothing Phone (2)
- Nothing Phone (2a) - **システム LPA は動作しません**
- Nothing Phone (3a) - **SKU の影響でシステム LPA が動作しません (JPN は未確認)**
- CMF Phone 1 - **システム LPA は動作しません**

## サポートしている物理 eSIM
動作報告をいただけると光栄です。
> [!TIP]
> eSTK.me は STK メニューから 「eUICC としてアナウンス」または、ATR Mode 内の「eUICC Mark」を有効化する必要があります。
>
> それを行わないとシステム LPA で eSIM のダウンロードが行えません。
- eSTK.me (eSIM の切り替え、ダウンロード共に使用可能です)
- 5ber eSIM (eSIM の切り替えのみ対応)

## 注意
このモジュールを使用したことでデータの消失などがあったとしても**一切責任は負いません。**

# Note (English)
This forcibly enables eSIM on Nothing devices that do not officially support it.<br>
**v2.0 System LPA Supported! (Qualcomm Devices Only)**

Actually, I barely modified the ROM itself, so I think it should work on systems other than Nothing OS as well.

#### Tested Devices
- Nothing Phone (1)
- Nothing Phone (2)
- Nothing Phone (2a) - **System LPA not work**
- Nothing Phone (3a) - **SKU is causing the LPA system to malfunction (JPN status unconfirmed)**
- CMF Phone 1 - **System LPA not work**

## Supported Physical eSIM
- eSTK.me (Supports both eSIM switching and download)
- 5ber eSIM (Supports eSIM switching only)

## DISCLAIMER
I take no responsibility whatsoever for any data loss or other issues caused by using this module.
