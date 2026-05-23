================================================================================
  PRIVFORGE — PRIVACY POLICY & DISCLAIMER
  Last Updated: May 24, 2026
================================================================================

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ENGLISH
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PRIVACY POLICY
==============

Thank you for using PrivForge ("the App"). This Privacy Policy explains how we
handle information in connection with your use of the App. Please read it
carefully.


1. OVERVIEW
-----------
PrivForge is a privacy-first tool that lets you capture key moments from videos
on your Android device and seamlessly transfer them to your PC over a local
Wi-Fi connection. The App is designed to operate entirely within your local
network. No account registration is required, and no personal data is ever
transmitted to external servers or third parties.


2. INFORMATION WE DO NOT COLLECT
----------------------------------
We do not collect, store, or transmit any of the following:

  - Your name, email address, or any other personally identifiable information
  - Location data (GPS or network-based)
  - Device identifiers (IMEI, advertising ID, etc.)
  - Usage analytics or behavioral data
  - Crash reports sent to our servers
  - Any data through third-party analytics or advertising SDKs


3. INFORMATION THAT STAYS ON YOUR DEVICE
------------------------------------------
The following data is generated and stored exclusively on your device or your
local PC, and never leaves your local network:

  a) Video Files
     Videos recorded or processed through the App are saved to a private
     directory on your Android device (/data/data/com.privforge.app/files/
     secure_videos/) or to the designated folder on your PC. These files are
     not accessible to other apps (a .nomedia file is placed in the folder to
     prevent media indexing).

  b) PC Server Connection URL
     The IP address and port of your PC server are stored locally on your
     Android device using the Android Keystore-backed secure storage
     (flutter_secure_storage). This data is encrypted and never transmitted
     outside your device.

  c) PC Server Password
     The password you set for the PC companion application (PrivForge Hub) is
     stored as a SHA-256 hash in a hidden local folder on your PC
     (%LOCALAPPDATA%\SystemNetworkData\). It is never sent over the network
     in plaintext.

  d) Tool Configuration
     If you register CLI tools in PrivForge Hub, the tool definitions
     (names, executable paths, command templates, parameters) are stored
     locally in a JSON file on your PC (%LOCALAPPDATA%\SystemNetworkData\
     tools.json). This data never leaves your PC.

  e) Biometric Data
     If you use biometric authentication (fingerprint, face recognition),
     all biometric processing is handled exclusively by the Android operating
     system's BiometricManager API. PrivForge never accesses, stores, or
     transmits biometric data in any form.


4. LOCAL NETWORK COMMUNICATION
--------------------------------
All communication between the PrivForge Android app and PrivForge Hub occurs
over your local Wi-Fi network (LAN). Data is transferred directly between
your phone and your PC without passing through any external server, cloud
service, or relay infrastructure.

The connection is established by scanning a QR code displayed by PrivForge Hub.
The QR code encodes only your PC's local IP address and port number.


5. PERMISSIONS USED BY THE APP
--------------------------------
The App requests the following Android permissions solely to provide its core
functionality. None of these permissions are used to collect personal data.

  - INTERNET: Required for local Wi-Fi communication with PrivForge Hub.
  - ACCESS_WIFI_STATE / ACCESS_NETWORK_STATE: Used to detect the local
    Wi-Fi connection.
  - CAMERA: Used to scan the QR code displayed by PrivForge Hub.
  - READ_MEDIA_VIDEO / READ_EXTERNAL_STORAGE: Allows you to select videos
    from your device for processing.
  - FOREGROUND_SERVICE / FOREGROUND_SERVICE_MEDIA_PROJECTION: Required to
    run the screen recording service in the background.
  - RECORD_AUDIO: Used only during screen recording, to capture audio.
  - USE_BIOMETRIC / USE_FINGERPRINT: Enables biometric authentication to
    protect access to the App.
  - RECEIVE_BOOT_COMPLETED: Allows the App to restore its state after a
    device restart (if applicable).


6. THIRD-PARTY SERVICES
-------------------------
PrivForge does not integrate any third-party analytics, advertising, or data
collection services (e.g., Firebase Analytics, Google Analytics, Crashlytics,
Facebook SDK, or similar).

The App is distributed through Google Play. Google's own privacy practices
apply to the distribution platform itself. Please refer to Google's Privacy
Policy (https://policies.google.com/privacy) for details.


7. CHILDREN'S PRIVACY
-----------------------
PrivForge is not directed at children under the age of 13 (or the applicable
age of digital consent in your jurisdiction). We do not knowingly collect any
information from children. If you believe a child has used the App, no personal
data would have been collected, as the App does not collect any personal data
from any user.


8. DATA SECURITY
-----------------
Although PrivForge does not transmit personal data, we have implemented the
following security measures to protect locally stored data:

  - Secure storage: Connection URLs are stored using Android Keystore-backed
    encryption.
  - Password hashing: PC server passwords are stored as SHA-256 hashes.
  - Hidden storage: PC-side data is stored in a hidden system folder with
    restricted file attributes.
  - No external exposure: All network activity is limited to your local LAN.


9. CHANGES TO THIS POLICY
---------------------------
We may update this Privacy Policy from time to time. When we do, we will
update the "Last Updated" date at the top of this document. We encourage you
to review this Policy periodically. Continued use of the App after any changes
constitutes your acceptance of the revised Policy.


10. CONTACT
------------
If you have any questions or concerns about this Privacy Policy, please
contact us at:

  xlxlxl352936@gmail.com


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
DISCLAIMER
==========

THE APP IS PROVIDED "AS IS" AND "AS AVAILABLE," WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED.

1. NO WARRANTY
   To the fullest extent permitted by applicable law, the developer of
   PrivForge expressly disclaims all warranties, whether express, implied,
   statutory, or otherwise, including but not limited to:
   - Implied warranties of merchantability, fitness for a particular purpose,
     and non-infringement.
   - Warranties that the App will be uninterrupted, error-free, or free of
     viruses or other harmful components.
   - Warranties regarding the accuracy, reliability, or completeness of any
     content processed by the App.

2. LIMITATION OF LIABILITY
   To the fullest extent permitted by applicable law, the developer shall not
   be liable for any indirect, incidental, special, consequential, exemplary,
   or punitive damages, including but not limited to:
   - Loss of data, videos, or files.
   - Damage to your device, PC, or other hardware.
   - Loss of profits or business interruption.
   - Any damages resulting from unauthorized access to your local network.
   This limitation applies regardless of the legal theory under which such
   damages are claimed, and even if the developer has been advised of the
   possibility of such damages.

3. USER RESPONSIBILITY FOR THIRD-PARTY CLI TOOLS
   PrivForge Hub allows users to register and execute third-party command-line
   interface (CLI) tools ("External Tools"). The developer of PrivForge:
   - Does not review, endorse, or take responsibility for any External Tools
     registered or executed through the App.
   - Is not liable for any damage, data loss, system instability, or security
     vulnerability caused by the execution of External Tools.
   - Makes no representation that any External Tool is safe, legal, or
     appropriate for any purpose.
   Users are solely responsible for ensuring that any External Tool they
   register complies with applicable laws and does not infringe on any
   third-party rights.

4. LOCAL NETWORK SECURITY
   The App communicates over the user's local Wi-Fi network. The developer
   is not responsible for any unauthorized interception of data on the user's
   network, or for any security vulnerabilities in the user's network
   infrastructure.

5. COMPATIBILITY
   The developer does not guarantee that the App will be compatible with all
   Android devices, Android OS versions, PC configurations, or network
   environments. The App is tested on a limited set of configurations, and
   functionality may vary.

6. GOVERNING LAW
   This Disclaimer shall be governed by and construed in accordance with
   applicable law. Any disputes arising in connection with the App that cannot
   be resolved informally shall be subject to the exclusive jurisdiction of
   the competent courts.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  日本語 / JAPANESE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

プライバシーポリシー
====================

PrivForge（以下「本アプリ」）をご利用いただきありがとうございます。本プライバ
シーポリシーは、本アプリのご利用に際して情報をどのように取り扱うかをご説明する
ものです。


1. 概要
-------
PrivForge は、Androidスマートフォンで動画から決定的瞬間をキャプチャし、ローカル
Wi-Fi 経由で PC にシームレスに転送するプライバシー重視のツールです。本アプリは
完全にお客様のローカルネットワーク内で動作するよう設計されています。アカウント登
録は不要であり、外部サーバーや第三者に個人データが送信されることは一切ありません。


2. 収集しない情報
------------------
本アプリは以下の情報を収集・保存・送信しません。

  - 氏名、メールアドレス、その他の個人を特定できる情報
  - 位置情報（GPS・ネットワーク情報を含む）
  - 端末識別子（IMEI、広告IDなど）
  - 利用状況・行動データ（アナリティクス）
  - クラッシュレポートの外部送信
  - 第三者のアナリティクス・広告SDK経由のデータ


3. 端末内にとどまる情報
------------------------
以下のデータは、お客様の端末またはローカルPC上のみに生成・保存され、
ローカルネットワーク外に出ることは一切ありません。

  a) 動画ファイル
     本アプリで録画・処理した動画は、Androidデバイスの非公開ディレクトリ
     (/data/data/com.privforge.app/files/secure_videos/) またはPC上の
     指定フォルダに保存されます。.nomedia ファイルにより、他のアプリから
     メディアとして認識されないよう保護されています。

  b) PCサーバー接続URL
     PCサーバーのIPアドレスとポート番号は、Android Keystoreに裏付けられた
     安全なストレージ（flutter_secure_storage）に保存されます。このデータは
     暗号化されており、端末外に送信されることはありません。

  c) PCサーバーパスワード
     PrivForge Hub に設定したパスワードは、PC上の隠しフォルダ
     (%LOCALAPPDATA%\SystemNetworkData\) に SHA-256 ハッシュとして保存されます。
     平文でネットワーク上に送信されることはありません。

  d) ツール設定
     PrivForge Hub に登録したCLIツールの定義情報（ツール名、実行ファイルパス、
     コマンドテンプレート、パラメーターなど）は、PC上のJSONファイル
     (%LOCALAPPDATA%\SystemNetworkData\tools.json) にローカル保存されます。
     このデータがPC外に送信されることはありません。

  e) 生体認証データ
     指紋・顔認証をご利用の場合、すべての生体認証処理はAndroid OSの
     BiometricManager APIによって完結します。PrivForge が生体認証データに
     アクセスしたり、保存・送信したりすることは一切ありません。


4. ローカルネットワーク通信
-----------------------------
PrivForge（Android）と PrivForge Hub（PC）間の通信は、すべてお客様の
ローカルWi-Fiネットワーク（LAN）上で行われます。データは外部サーバー、
クラウドサービス、中継インフラを経由することなく、直接スマートフォンと
PCの間でやり取りされます。

接続はPrivForge Hubが表示するQRコードを読み取ることで確立されます。
QRコードにはPCのローカルIPアドレスとポート番号のみが含まれます。


5. アプリが使用する権限
------------------------
本アプリは、以下のAndroid権限をコア機能の提供のためにのみ使用します。
これらの権限が個人データの収集に使用されることはありません。

  - INTERNET: PrivForge Hub とのローカルWi-Fi通信に必要
  - ACCESS_WIFI_STATE / ACCESS_NETWORK_STATE: ローカルWi-Fi接続の検出に使用
  - CAMERA: PrivForge Hub が表示するQRコードのスキャンに使用
  - READ_MEDIA_VIDEO / READ_EXTERNAL_STORAGE: 処理する動画の選択に使用
  - FOREGROUND_SERVICE / FOREGROUND_SERVICE_MEDIA_PROJECTION:
    バックグラウンドでの画面録画サービスの実行に必要
  - RECORD_AUDIO: 画面録画時の音声キャプチャに使用
  - USE_BIOMETRIC / USE_FINGERPRINT: アプリへのアクセスを保護する生体認証に使用
  - RECEIVE_BOOT_COMPLETED: 端末再起動後のアプリ状態の復元に使用（該当する場合）


6. 第三者サービス
-----------------
PrivForge は、Firebase Analytics、Google Analytics、Crashlytics、
Facebook SDKなどの第三者のアナリティクス・広告・データ収集サービスを
一切組み込んでいません。

本アプリはGoogle Playを通じて配布されます。配布プラットフォーム自体には
Googleのプライバシーポリシー (https://policies.google.com/privacy) が
適用されます。


7. お子様のプライバシー
------------------------
本アプリは13歳未満（または各国法令が定めるデジタル同意年齢未満）の
お子様を対象としていません。本アプリは一切の個人データを収集しないため、
お子様がご利用になった場合でも個人情報が収集されることはありません。


8. データセキュリティ
---------------------
本アプリは個人データを外部送信しませんが、ローカルデータ保護のために
以下のセキュリティ対策を実施しています。

  - 安全なストレージ: 接続URLはAndroid Keystore暗号化で保護
  - パスワードハッシュ化: PCサーバーのパスワードはSHA-256で保存
  - 隠しフォルダへの保存: PC側データはファイル属性が制限された隠しフォルダに保存
  - 外部への露出なし: すべてのネットワーク通信はローカルLAN内に限定


9. ポリシーの変更
-----------------
本プライバシーポリシーは随時更新されることがあります。更新の際は本文書
冒頭の「最終更新日」を変更します。定期的にご確認いただくことをお勧めします。
変更後も本アプリを継続してご利用いただく場合、改定後のポリシーに同意した
ものとみなします。


10. お問い合わせ
----------------
本プライバシーポリシーに関するご質問・ご不明点は、以下までお問い合わせください。

  xlxlxl352936@gmail.com


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
免責事項
========

本アプリは「現状のまま（AS IS）」「利用可能な状態で（AS AVAILABLE）」
提供されます。明示・黙示を問わず、いかなる保証も行いません。

1. 無保証
   適用法令が許容する最大限の範囲で、本アプリの開発者は以下を含む
   一切の保証を明示的に否認します。
   - 商品性、特定目的への適合性、非侵害性に関する黙示的保証
   - 本アプリが中断なく、エラーなく、ウイルスやその他の有害なコンポーネントなく
     動作するという保証
   - 本アプリが処理するコンテンツの正確性・信頼性・完全性に関する保証

2. 責任の制限
   適用法令が許容する最大限の範囲で、開発者は以下を含む間接的・付随的・
   特別・結果的・懲罰的損害について一切の責任を負いません。
   - データ、動画、ファイルの損失
   - お客様のデバイス、PC、その他のハードウェアへの損害
   - 逸失利益・業務中断による損害
   - お客様のローカルネットワークへの不正アクセスにより生じた損害
   この制限は、そのような損害の可能性を開発者が事前に知らされていた場合を
   含め、いかなる法的理論に基づく請求にも適用されます。

3. 第三者CLIツールに関する免責
   PrivForge Hub では、ユーザーが第三者のコマンドラインツール（以下「外部ツール」）
   を登録・実行できます。本アプリの開発者は以下について責任を負いません。
   - 本アプリを通じて登録・実行される外部ツールの内容の審査・推奨・保証
   - 外部ツールの実行によって生じた損害、データ損失、システム障害、
     セキュリティ上の脆弱性
   - 外部ツールの安全性、合法性、目的適合性に関する一切の表明・保証
   ユーザーは、登録する外部ツールが適用法令に準拠し、第三者の権利を
   侵害しないことを自己責任で確認するものとします。

4. ローカルネットワークのセキュリティ
   本アプリはユーザーのローカルWi-Fiネットワーク上で通信を行います。
   ユーザーのネットワーク上でのデータの不正傍受や、ネットワーク
   インフラのセキュリティ上の脆弱性について、開発者は一切の責任を負いません。

5. 互換性
   開発者は、本アプリがすべてのAndroid端末、AndroidOSバージョン、PC構成、
   またはネットワーク環境に対応することを保証しません。
   動作確認は限定された構成で行っており、環境によって機能が異なる場合があります。

6. 準拠法
   本免責事項は適用法令に従って解釈されるものとします。
   本アプリに関連して生じる紛争で非公式な解決が困難な場合は、
   管轄裁判所の専属的裁判管轄に服するものとします。


================================================================================
  END OF DOCUMENT / 文書終わり
================================================================================
