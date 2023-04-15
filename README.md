React NativeとExpoを使用して初期セットアップを行う方法については、以下の手順に従ってください。

■ Node.jsのインストール（推奨バージョン: 12.x 以上）
---------------
Node.jsをインストールするには、以下の手順を実行します。

Windowsの場合：

公式ウェブサイト（https://nodejs.org/en/）から最新版のNode.jsインストーラーをダウンロードします。
ダウンロードしたインストーラーを実行します。
ウィザードに従い、インストール手順を実行します。
インストールが完了したら、コマンドプロンプトまたはPowerShellを開き、以下のコマンドを実行して、Node.jsのバージョンを確認します。
node -v

macOSの場合：

Homebrewをインストールします。これは、macOS用のパッケージマネージャーです。ターミナルで以下のコマンドを実行します。
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Homebrewを使用して、Node.jsをインストールします。ターミナルで以下のコマンドを実行します。
brew install node

インストールが完了したら、以下のコマンドを実行して、Node.jsのバージョンを確認します。
node -v

Linuxの場合：

ディストリビューションのパッケージマネージャーを使用して、Node.jsをインストールします。例えば、Ubuntuの場合は、以下のコマンドを実行します。
sudo apt-get install nodejs

インストールが完了したら、以下のコマンドを実行して、Node.jsのバージョンを確認します。
node -v

Node.jsのインストール方法には他にもさまざまな方法がありますが、最新バージョンを手軽にインストールするには、上記の方法を使用することがお勧めです。
--------------------
Node.jsのアップデート
sudo npm install -g n
sudo n stable
--------------------

■ スマートフォンにExpo Goアプリをインストール（iOSおよびAndroid）

■ 本リポジトリを入れるディレクトリに移動

■ 本リポジトリをクローン
git clone git@github.com:giftedagent/ouchipod-frontend.git

■ リポジトリ内に移動
cd ouchipod-frontend

■ Expo CLIのインストール: コマンドプロンプトまたはターミナルを開いて、以下のコマンドを実行してExpo CLIをインストールします。
npm install -g expo-cli

■ Expoの開発サーバーの起動
expo start

これにより、ブラウザでExpo Developer Toolsが開かれます。

■ スマートフォンでアプリを実行する
スマートフォンでExpo Goアプリを開き、QRコードリーダーを使ってコマンドラインに表示されているQRコードをスキャンします。
これにより、アプリがスマートフォン上で実行されます。

これでReact NativeとExpoの初期セットアップが完了し、アプリの開発を開始できます。
開発中にソースコードを変更すると、Expo Goアプリで自動的にリロードされ、変更が反映されます。


