# Sourcetreeのチュートリアル
Unityでの使用想定  
〇リモートリポジトリ  
・アカウントを追加  
・Host/ホスティングサービスを「Github」に  
・OAuthトークンを読み込み  

〇Create a repository  
・保存先のパスにUnityプロジェクトを参照し、作成  
・GithubのRepositories/New  
・Repository nameを※Unityプロジェクト名に  
・Add .gitignore/.gitignore templateを「Unity」に  
・Create repository  
・Sourcetreeの設定/追加  
・必要な情報/リモート名を※Unityプロジェクト名に  
・必要な情報/「URL/パス」をGithubで作成したリポジトリのURLに  
・外部サービスとの拡張統合オプション/Remote AccountをGithubアカウントに  
・プル/更新し、プルするリモートブランチを「main」に、プル  
※推奨する命名方式

〇コミット : 前回からの変更内容をコメントをつけて保存  
・コミット/全てインデックスに追加  
・コミットコメントを記述し、コミット

〇リポジトリ  
・フェッチ : リモートで変更された内容をローカルに保存  
・プッシュ : ローカルで変更された内容をリモートに保存  
　リモートブランチのプッシュ先を選択し、プッシュ  
　Githubアカウントを選択し、プッシュ  
・プル : フェッチとプッシュを行う  
　プル/プルするリモートブランチを選択し、プル

〇ブランチ  
・マージ : 今の作業内容を保存しているブランチを「main」に統合  
※その後、必ずpushする
