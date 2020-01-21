﻿# AZ-500 Azure Security

- **あなたはMCTですか？** - [MCT 用 GitHub ユーザーガイド](https://microsoftlearning.github.io/MCT-User-Guide/)を確認してください
- **ラボの手順を手動でビルドする必要がありますか？** - 手順は[MicrosoftLearning/Docker-Build](https://github.com/MicrosoftLearning/Docker-Build) リポジトリで利用できます

> [MCTコースウェアフォーラム](https://www.microsoft.com/en-us/learning/mct-central.aspx)を必ず利用して、コースの内容に関する提案や一般的なコメントを行ってください。また、バグとコースエラーについては[コースウェアサポートフォーラム](https://trainingsupport.microsoft.com/ja-jp)で報告することができます。
 
新しい変更をサポートするために、2019年11月1日から新しい AZ-500 GitHub リポジトリを導入しました。その時点で、すべての AZ-500 ラボはこのリポジトリに置き換えられました。

**私たちがしていることとは何でしょうか？**

*	コース作成者と MCT の間の対話を可能にするために、GitHub でラボの指示とラボ ファイルを公開しています。Azure プラットフォームの変更に伴って、コンテンツを最新にしておくのに役立つことを願っています。

*	これは、Microsoft Azure セキュリティコースの AZ-500 用の GitHub リポジトリです。 

*	各リポジトリには、Instructions フォルダーに Markdown 形式のラボガイドがあります。必要に応じて、ラボを完了するために必要な追加ファイルも Allfiles\Labfiles フォルダー内にあります。すべてのコースに対応するラボファイルがあるわけではありません。 

*	毎回の配信に、トレーナーは GitHub から最新のファイルをダウンロードする必要があります。トレーナーは、「問題」 タブでもチェックして、他の MCT がエラーを報告したかどうかを確認する必要があります。  

*	ラボのタイミングの見積もりは提供されますが、トレーナーは、受講者に基づいて正確であることを確認する必要があります。

*	ラボを行うには、インターネット接続と Azure サブスクリプションが必要となります。Cloud Shell の利用に関する詳細については、『インストラクター準備ガイド』を参照してください。 

**私たちが行っていることはどうですか？**

*	これらのコースを教えている間に、改善すべきところを特定する場合は、「問題」 タブを使用してフィードバックを提供してください。変更を反映するための新しいファイルを定期的に作成します。 


* Azure Cloud Shell を初めて起動すると、Azure ファイル共有を作成して Cloud Shell ファイルを保持するように求められる場合があります。その場合、通常はデフォルトを受け入れることができます。これにより、自動生成されたリソースグループにストレージアカウントが作成されます。そのストレージアカウントを削除すると、これが再び発生する可能性があることに注意してください。

* テンプレートベースの展開を実行する前に、テンプレートで参照されているリソースタイプのプロビジョニングを処理するプロバイダーを登録する必要がある場合があります。これは、Azure Resource Manager テンプレートを使用して、これらのリソースプロバイダーによって管理されるリソースをデプロイするときに必要な1回限りの操作（サブスクリプションごと）です（これらのリソースプロバイダーがまだ登録されていない場合）。登録は、Azure ポータルのサブスクリプションのリソースプロバイダーブレードから、または Cloud Shell を使用して Register-AzResourceProvider PowerShell コマンドレットまたはazプロバイダーの Azure CLI コマンドを実行することで実行できます。

この GitHub リポジトリを使用すると、ラボにコラボレーションへの意識がもたらされ、ラボ体験の品質全般が向上することを願っています。 

よろしくお願いいたします。
*Azure アーキテクトコースウェアチーム*