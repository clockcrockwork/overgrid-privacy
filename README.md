# OVERGRID — Privacy Policy / プライバシーポリシー

最終更新日 / Last updated: **2026-09-05**

<!--
  この上下の注記は公開ページには出ない (HTML コメント)。ここから下が、
  どこにホストしてもそのまま貼れる本文。掲載場所の決定は docs/DISTRIBUTION.md D3。
  貼り付け先を問わないよう、本文からリポジトリ内文書への参照は外してある。
-->

---

## 日本語

OVERGRID (Chrome 拡張) は、ユーザーの情報を収集しません。

- **収集するデータ: なし。** OVERGRID はアクセス解析・利用状況の収集・広告のいずれも行いません
- 設定した都市、登録したクイックリンク、書いたメモ、配色などの表示設定は、すべて
  Chrome の `chrome.storage.local` にこの端末上でのみ保存されます。これらのデータは
  拡張の外に送信されることはなく、開発者を含む誰の手にも渡りません
- OVERGRID が実行時に行う外部通信は **1 種類だけ** です: ユーザーが設定した都市の
  天気を取得するために、その都市の緯度経度を `api.open-meteo.com` へ送信します。
  これは天気を表示する機能そのものに必要な通信で、それ以外の目的には使われません。
  open-meteo 側のプライバシーについては同サービスの方針に従います
- クイックリンクのアイコン (favicon) は Chrome ブラウザ自身が内部で保持しているキャッシュ
  から表示しており、これによる外部への通信は発生しません
- 拡張はリモートのコードを一切実行しません。同梱されているコードのみで動作します

設定を別の端末へ引き継ぎたい場合は、設定パネルの EXPORT / IMPORT 機能で JSON ファイルを
自分で持ち運んでください。この JSON ファイルのやり取りに OVERGRID や開発者は関与しません。

**お問い合わせ:** clockcrockwork@gmail.com

---

## English

OVERGRID (a Chrome extension) does not collect any user data.

- **Data collected: none.** OVERGRID does not run analytics, does not track usage, and
  shows no ads
- Your configured cities, saved quick links, memo text, and display preferences (colors,
  etc.) are stored only in `chrome.storage.local`, on your own machine. This data is
  never sent anywhere and is never seen by anyone, including the developer
- OVERGRID makes exactly **one** kind of outbound request at runtime: to fetch weather
  for the city you configured, it sends that city's latitude and longitude to
  `api.open-meteo.com`. This request exists solely to display the weather feature and is
  used for no other purpose. Open-Meteo's own privacy practices govern that request on
  their end
- Quick-link icons (favicons) are shown from Chrome's own internal favicon cache; this
  does not cause any request to leave your machine
- OVERGRID never executes remote code — it runs only on the code shipped inside it

To move your settings to another machine, use the EXPORT / IMPORT feature in the
settings panel to carry a JSON file yourself. OVERGRID and its developer are not
involved in that transfer.

**Contact:** clockcrockwork@gmail.com
