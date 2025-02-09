# Laravel

# WSL2 環境構築 (with `node.js`, `git`, `docker-desktop`)

検索して出てきたWindowsターミナルを右クリックし、**管理者権限で**開く。

![Windowsターミナル](https://gist.github.com/assets/131662659/09299299-edfe-4bd9-a182-488b3814a36f)

```powershell
wsl --install
```

- ユーザー名

今回はバージョン管理に[Volta](https://volta.sh)を使用する。  
以下のコマンドに従ってインストールする。

```bash
curl https://get.volta.sh/ | bash
```


Docker Desktop を WSL より先に導入していた場合は [#(以前からDockerdesktopを使用していた人向け)DockerDesktopの設定](#以前から-dockerdesktop-を使用していた人向け-dockerdesktop-の設定) を参照。

> [!NOTE]
> ArmのCPUが入ったPCの場合は下の`Docker Desktop for Windows - Arm (Beta)`よりダウンロードする。  
> なお、最新のSnapdragonXが搭載されたSurfaceなどでない限り、特に気にする必要はない。

> ユーアーアカウント制御 このアプリがデバイスに変更を加えることを許可しますか？

"信頼済みの発行元"が`Docker Inc`であることを確認し、はいを選択する



これにて**インストールは完了**。



