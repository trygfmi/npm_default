
<h2 class="wp-block-heading">前書き</h2>



<div class="wp-block-group">
<p>このリポジトリは、npmコマンドを実行してデフォルトで生成されるスクリプトを実行します</p>
</div>



<h2 class="wp-block-heading">インストールする必要のあるコマンド</h2>



<div class="wp-block-group">
<ol class="wp-block-list">
<li>git</li>



<li>npm</li>



<li>node</li>
</ol>
</div>



<h2 class="wp-block-heading">クイックスタート</h2>



<div class="wp-block-group">
<p>上記のコマンドをインストール済みの方は、以下のコマンドを実行してリポジトリからダウンロード後、ディレクトリを移動し、npmコマンドを実行して生成されたpackage.jsonに記載されたスクリプトを実行してください</p>



<h3 class="wp-block-heading">ubuntu</h3>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>



<h3 class="wp-block-heading">macos</h3>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>



<h3 class="wp-block-heading">windows</h3>



<div class="wp-block-group">
<h4 class="wp-block-heading">WSL2</h4>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>



<h4 class="wp-block-heading">MSYS2 MINGW64</h4>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>出力結果</summary>
<pre class="wp-block-code has-background" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>
</div>
</div>



<h2 class="wp-block-heading">実行手順</h2>



<div class="wp-block-group">
<h3 class="wp-block-heading">ubuntu</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<div class="wp-block-group">
<p>以下のコマンドを端末に打ち込んでcommand not foundが出なければokです</p>
</div>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git --versionnpm --versionnode --version</code></pre>



<h4 class="wp-block-heading">preinstall</h4>



<div class="wp-block-group">
<p>端末にcommand not foundが出たコマンドを以下のコマンドでインストールしてください</p>
</div>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>sudo apt install gitsudo apt install npm</code></pre>



<h4 class="wp-block-heading">コマンド</h4>



<div class="wp-block-group">
<p>以下のコマンドを端末で実行することで詳細のような文字列が出力されるはずです</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>
</details>



<h3 class="wp-block-heading">macos</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<div class="wp-block-group">
<p>以下のコマンドをターミナルに打ち込んでcommand not foundが出なければokです</p>
</div>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>source ~/bashrc_folder/macports_aliasgit --versionnpm --versionnode --version</code></pre>



<p>※macosはMacPortsパッケージマネージャを使用してコマンドを管理します。もしインストールしていない方は以下のリンクからMacPortsのインストール手順をご覧ください<br>またコマンドに別名を設定して既存の環境と競合しないでコマンドを呼び出せるようにします。<br>初めてこのブログを利用する方は、以下の2つの記事を参考に環境構築してください</p>



[![MacPortsをインストールするまでの手順](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_macports_title_1920_1080_2.png,)](https://ss523971.stars.ne.jp/todo/how-to-install-macports)



[![MacPortsでインストールしたコマンドのエイリアス設定](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_macports2.png,)](https://ss523971.stars.ne.jp/todo/how-to-setup-macports-alias)
</div>



<h4 class="wp-block-heading">preinstall</h4>



<div class="wp-block-group">
<p>ターミナルでcommand not foundが出たコマンドを以下のコマンドでインストールしてエイリアスを設定してください</p>
</div>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>sudo port install gitecho 'alias git="/opt/local/bin/git"' >> ~/bashrc_folder/macports_aliassudo port install npm10echo 'alias npm="/opt/local/bin/npm"' >> ~/bashrc_folder/macports_aliasecho 'alias node="/opt/local/bin/node"' >> ~/bashrc_folder/macports_alias</code></pre>



<h4 class="wp-block-heading">コマンド</h4>



<div class="wp-block-group">
<p>以下のコマンドをターミナルで実行することで詳細のような文字列が出力されるはずです</p>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>
</details>



<h3 class="wp-block-heading">windows</h3>



<details class="wp-block-details"><summary>クリックして詳細を開く</summary>
<h4 class="wp-block-heading">事前確認</h4>



<div class="wp-block-group">
<p>以下のコマンドをプロンプトに打ち込んでcommand not foundが出なければokです</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git --versionnpm --versionnode --version</code></pre>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git --versionnpm --versionnode --version</code></pre>



<p>※windowsはWSL2とMSYS2 MINGW64で確認しています。可能な限りWSL2をインストールしていただいて、もし設定できなかった場合はMSYS2をインストールすることで実行できますが、所々WSL2でしか実行できないコマンドが出てくるかもしれません。WSL2とMSYS2のインストール方法は下記の記事を参考にしてください</p>



[![[windows] msys2をインストールするまでの手順](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/thumbnail_WSL2_1920_1080.png)](https://ss523971.stars.ne.jp/todo/how-to-install-wsl2/)



[![](https://ss523971.stars.ne.jp/todo/wp-content/uploads/2025/10/msys2_thumbnail_1920_1080.png)](https://ss523971.stars.ne.jp/todo/how-to-install-msys2)
</div>



<h4 class="wp-block-heading"><strong>preinstall</strong></h4>



<div class="wp-block-group">
<p>プロンプトでcommand not foundが出たコマンドを以下のコマンドでインストールしてください</p>



<h5 class="wp-block-heading">WSL2</h5>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>sudo apt install gitsudo apt install npm</code></pre>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>
</div>



<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>pacman --sync gitpacman --sync npm</code></pre>



<h4 class="wp-block-heading"><strong>コマンド</strong></h4>



<div class="wp-block-group">
<p>以下のコマンドをプロンプトで実行することで詳細のような文字列が出力されるはずです</p>



<h5 class="wp-block-heading">WSL2</h5>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>



<h5 class="wp-block-heading">MSYS2 MINGW64</h5>



<div class="wp-block-group">
<pre class="wp-block-own-copy-code-line-block wp-block-code has-24292-eff-color has-cyan-bluish-gray-background-color has-text-color has-background has-1-125-rem-font-size"><code>git clone https://github.com/trygfmi/npm_defaultcd npm_defaultcd workDirectory_npm_defaultnpm init -ynpm run testnpm install ../install_npm_defaultcat ../install_npm_default/index.jscat index.jsnode index.js</code></pre>



<details class="wp-block-details"><summary>詳細</summary>
<pre class="wp-block-code has-24292-eff-color has-text-color has-background has-1-125-rem-font-size" style="background-color:#ffeeee"><code>> workdirectory_npm_default@1.0.0 test
> echo "Error: no test specified" &amp;&amp; exit 1

Error: no test specified

hello npm command world</code></pre>
</details>
</div>
</div>
</details>
</div>



<h2 class="wp-block-heading">後書き</h2>



<div class="wp-block-group">
<p>npm init -yの-yで全ての選択をyesにして、生成されたpackage.jsonのscriptsキーに定義されているtestコマンドを実行します<br>またpackage.jsonのmainキーに指定されたindex.jsの挙動を確認するために、install_npm_defaultパッケージをインストール後、index.jsを実行しています</p>



<p></p>
</div>
