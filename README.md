## 🍣 Spitch Omakase Connect v1.2  

GoogleColabでVOICEVOXとRVCの環境構築  

ローカルのほうが圧倒的に早いのでお試し程度  
か、ローカルPCがガンバっていて厳しいときに  

RVCはcolabに課金していないと強制切断されます  
無課金の方はRVCはローカルで使ってください  

### Setting up VOICEVOX and RVC on Google Colab

* **For Trial Use Only:** Since local environments are significantly faster, use this Colab setup mainly for testing or as a backup when your local PC is struggling to keep up.

* **RVC Usage Warning:** Please be aware that RVC often triggers a **forced disconnection** on Google Colab if you are using a free account.

* **Free Tier Users:** If you do not have a paid Colab subscription, it is strongly recommended to run RVC locally instead.

⭐ [スター](https://github.com/neon-aiart/spitch-omakase-connect/tree/main)をポチッとお願いします✨ (Please hit the [Star] button!)  

<br clear="right">  

下のボタンを押してGoogle Colabで実行してください  
Click the button below to open the script in Google Colab and start transcribing!  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neon-aiart/spitch-omakase-connect/blob/main/spitch-omakase-connect%20v1.2.ipynb)  

<details>
<summary><b>[JP]</b></summary>

* **長時間の接続しっぱなしは危険**  
* **RVCはcolabに課金が必要**  
* **マジックリンクは`neon-spitch-link v8.4` 以降で利用可能**  

#### 目安時間 (VOICEVOXのみ)  

| | CPU | GPU | ローカル |
| --- | --- | --- | --- |
| **準備の時間** | 1 分 | 2 分 | 数秒 |
| **話し出すまでの時間** | 35 秒 | 25 秒 | 5 秒 |
</details>

<details>
<summary><b>[EN]</b></summary>

* **Continuous connection for long periods is risky.**  
* **A paid Colab plan is required to use RVC.**  
* **Magic links are supported in neon-spitch-link v8.4 and later.**  

#### Estimated Time (VOICEVOX only)

| Action | CPU | GPU | Local |
| --- | --- | --- | --- |
| **Setup Time** | 1 min | 2 mins | a few sec |
| **Time to Speech** | 35 sec | 25 sec | 5 sec |
</details>

<details>
<summary><b>🪄 クイック設定同期 / Quick Configuration Sync</b></summary>

ローカル環境（localhost）を使用する場合や、設定を初期値に戻したい時は、以下のリンクをクリックしてください  
Geminiが開き、自動的に設定が同期されます  
If you are using a local environment (localhost) or want to reset the settings to default, click the links below.  
Gemini will open and automatically sync the configuration.  

* ✨ **[VOICEVOXを同期 (Sync VOICEVOX)](https://gemini.google.com/#sync_v_eyJ2diI6ICJodHRwOi8vbG9jYWxob3N0OjUwMDIxIiwgInJ2YyI6ICIiLCAidHMiOiAxNzQwOTM5NjAwfQ==)**  
  `vv: http://localhost:50021`  

* ✨ **[RVCを同期 (Sync RVC)](https://gemini.google.com/#sync_v_eyJ2diI6ICIiLCAicnZjIjogImh0dHA6Ly9sb2NhbGhvc3Q6Nzg5NyIsICJ0cyI6IDE3NDA5Mzk2MDB9)**  
  `rvc: http://localhost:7897`  

* ✨ **[両方を一括同期 (Sync Both)](https://gemini.google.com/#sync_v_eyJ2diI6ICJodHRwOi8vbG9jYWxob3N0OjUwMDIxIiwgInJ2YyI6ICJodHRwOi8vbG9jYWxob3N0Ojc4OTciLCAidHMiOiAxNzQwOTM5NjAwfQ==)**  
  `Both Localhost URLs`  


> [!Note]  
> * **UserScript:** `neon-spitch-link` v8.4以降で利用できます  
> (Available on `neon-spitch-link` v8.4 or later)  

</details>

---

## 🛡️ ライセンスについて (License)

このユーザースクリプトのソースコードは、ねおんが著作権を保有しています。  
The source code for this application is copyrighted by Neon.

* **ライセンス / License**: **[PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)** です。（LICENSEファイルをご参照ください。）  
  Licensed under PolyForm Noncommercial 1.0.0. (Please refer to the LICENSE file for details.)
* **個人利用・非営利目的限定 / For Personal and Non-commercial Use Only**:
  * 営利目的での利用、無断転載、クレジットの削除は固く禁じます。  
    Commercial use, unauthorized re-uploading, and removal of author credits are strictly prohibited.
* **再配布について / About Redistribution**:
  * 本スクリプトを改変・配布（フォーク）する場合は、必ず元の作者名（ねおん）およびクレジット表記を維持してください。  
    If you modify or redistribute (fork) this script, you MUST retain the original author's name (Neon) and all credit notations.  

---

## 開発者 (Author)  

**ねおん (Neon)**  
<pre>
<img src="https://www.google.com/s2/favicons?domain=bsky.app&size=16" alt="Bluesky icon"> Bluesky       :<a href="https://bsky.app/profile/neon-ai.art/">https://bsky.app/profile/neon-ai.art/</a>
<img src="https://www.google.com/s2/favicons?domain=github.com&size=16" alt="GitHub icon"> GitHub        :<a href="https://github.com/neon-aiart/">https://github.com/neon-aiart/</a>
<img src="https://neon-aiart.github.io/favicon.ico" alt="neon-aiart icon" width="16" height="16"> GitHub Pages  :<a href="https://neon-aiart.github.io/">https://neon-aiart.github.io/</a>
<img src="https://www.google.com/s2/favicons?domain=greasyfork.org&size=16" alt="Greasy Fork icon"> Greasy Fork   :<a href="https://greasyfork.org/ja/users/1494762/">https://greasyfork.org/ja/users/1494762/</a>
<img src="https://www.google.com/s2/favicons?domain=sizu.me&size=16" alt="Sizu icon"> Sizu Diary    :<a href="https://sizu.me/neon_aiart/">https://sizu.me/neon_aiart/</a>
<img src="https://www.google.com/s2/favicons?domain=ofuse.me&size=16" alt="Ofuse icon"> Ofuse         :<a href="https://ofuse.me/neon/">https://ofuse.me/neon/</a>
<img src="https://www.google.com/s2/favicons?domain=www.chichi-pui.com&size=16" alt="chichi-pui icon"> chichi-pui    :<a href="https://www.chichi-pui.com/users/neon/">https://www.chichi-pui.com/users/neon/</a>
<img src="https://www.google.com/s2/favicons?domain=iromirai.jp&size=16" alt="iromirai icon"> iromirai      :<a href="https://iromirai.jp/creators/neon/">https://iromirai.jp/creators/neon/</a>
<img src="https://www.google.com/s2/favicons?domain=www.days-ai.com&size=16" alt="DaysAI icon"> DaysAI        :<a href="https://www.days-ai.com/users/lxeJbaVeYBCUx11QXOee/">https://www.days-ai.com/users/lxeJbaVeYBCUx11QXOee/</a>
</pre>

---