プラグイン 英文を翻訳したのでバグってるところがあります。なのでわからないプラグインなどがあったら自分で調べてください(使い方なども)
- [LoginSecurity](https://www.spigotmc.org/resources/loginsecurity.19362/) (プレイヤーがサーバーに入るときに一人一人がアカウントを保護するためにパスワードの入力する)
- [LuckPerms](https://luckperms.net/download) (素晴らしい Web UI を備えた権限マネージャー)
- [EssentialsX](https://essentialsx.net/downloads.html) (複製プロジェクトは通常公開されているため、ボット トークンを盗まれたくない場合以外は EssentialsXDiscord を使用しないでください)
- [WorldEdit](https://dev.bukkit.org/projects/worldedit/files/2460562) (ワールド操作プラグイン、非常にクール)
- [worldguard](https://dev.bukkit.org/projects/worldedit/files/880435) (ワールドを保護します)


---
### イーグラークラフトとは何ですか?
Eaglercraft は、ブラウザーで実行するように設計された Minecraft クローンです。 友達と一緒に Minecraft をプレイするのに楽しい場所であり、時間を過ごすのに最適な方法です。

### Eaglercraft 用のサーバーを作成する理由は何ですか?
Eaglercraft のサーバーを作成すると、全員が同じ部屋にいない場合でも、友達や他の Eaglercraft プレイヤーと一緒に Minecraft をプレイできるようになります。 サーバーをカスタマイズし、プラグインを追加して、ゲームプレイをより楽しく、興味深いものにすることができます。

### Replit で Eaglercraft サーバーをセットアップする方法:
#### ステップ 1: Replit アカウントを作成する

まだアカウントを作成していない場合は、[replit.com](https://replit.com) にアクセスしてアカウントを作成してください。 無料で簡単です！

#### ステップ 2: ベースの Replit プロジェクトをフォークする

ログインしたら、[ベース Replit プロジェクト](https://replit.com/@ayunami2000/eaglercraft) に移動し、[フォーク] ボタンをクリックして新しいプロジェクトを作成します。

#### ステップ 3: AuthMeReloaded をインストールして構成する

AuthMeReloaded は、プレーヤーが自分のアカウントを認証し、IP アドレス制限を無視できるようにするプラグインです。 インストールして構成するには、次の手順に従います。
- [このリンク](https://github.com/AuthMe/AuthMeReloaded/releases/download/5.6.0-beta2/AuthMe-5.6.0-beta2.jar) から AuthMeReloaded をダウンロードし、`server/ 内に配置します。 プラグインフォルダー。 次に、サーバーを再起動します。
- `server/plugins/AuthMe/config.yml` にあるプラグインの config.yml ファイルに移動します。
- 「maxRegPerIp」を見つけて、数値を 0 に変更します。
- 「displayOtherAccounts」を見つけて false に設定します。

#### ステップ 4: PlugmanX をインストールする

PlugmanX は、プラグインのロード、アンロード、リロードを簡単に行うことができるプラグインです。 インストールするには、次の手順に従います。
- [このリンク](https://www.spigotmc.org/resources/plugmanx.88135/) から PlugmanX をダウンロードし、`server/plugins` フォルダー内に配置します。 次に、サーバーを再起動します。
- 今後は、サーバーを再起動しなくても、権限を設定した後、サーバー コンソールまたはゲーム内でコマンド `plugman load <プラグイン ファイル名>` を使用することで、ほとんどの新しいプラグインをロードできるようになります。 コマンド「plugman reload <プラグイン名>」を実行してプラグインをリロードすることもできます。

#### ステップ 5: LuckPerms をインストールする

LuckPerms は権限を管理するプラグインです。 インストールするには、次の手順に従います。
- [このリンク](https://luckperms.net/download) から LuckPerms をダウンロードし (「Bukkit」を選択)、`server/plugins` フォルダー内に置きます。 次に、プラグインをロードします。
- インストールしたら、サーバー コンソールでコマンド `lp user <ユーザー名> Permission set luckyperms.* true` を実行し、Web ベースのエディタを使用してゲーム内で `/lp editor` を実行して権限を設定します。

#### ステップ 6: EssentialsX をインストールする

EssentialsX は、便利なコマンドとチャットの書式設定を追加するプラグインです。 インストールするには、次の手順に従います。
- EssentialsX と EssentialsXChat を [このリンク](https://essentialsx.net/downloads.html) からダウンロードし、Vault を [このリンク](https://dev.bukkit.org/projects/vault/files/894359) からダウンロードします。 、それらを「server/plugins」フォルダー内に配置します。 それから、ほら、