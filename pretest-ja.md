※このページは[pretest.md](https://github.com/slashtu/frontend-hq/blob/master/pretest.md)の内容を日本語に翻訳した文章です。

## 関連リンク

- デモ: [https://sta-vmo.17.media/pretest](https://sta-vmo.17.media/pretest)
- データ: https://webcdn.17app.co/campaign/pretest/data.json

## プロジェクト概要

10人のライバーが参加するイベントが開催されました。競争は激しく、ライバーが獲得するポイントはランキング上で毎秒更新されます。
上記[デモ](http://event.17.media/pretest)のように、獲得ポイントのデータがランダムに更新されるランキングを作成して、作成したランキングページとコードをご提出ください。(乱数生成に使用するライブラリは[Math.random](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Global_Objects/Math/random)を使用してください)


## 必須要件と提出方法

- レンダリングには[React](https://reactjs.org)を使用し、スタイル管理には[styled-components](https://www.styled-components.com)を使用してください。その他のライブラリは使用禁止とします。TypeScriptで functional component とフックAPIを使用して構築することをお勧めします。
- [create-react-app](https://github.com/facebook/create-react-app) のようなスターターキットを使用して構いません。環境構築に貴重な時間を無駄にしないようにしましょう。 
- 以下を実装時に意識してください。
  - スコア更新アニメーション (元のスコアと最終スコアの間の値の遷移)
  - 順位が更新される際のアニメーション (元の位置と最終位置の間の位置の遷移)
- 要件さえ満たせていればどのような実装でも可能です。
- アニメーションの動きと一貫性に注意してください。アニメーションがスムーズに動くようにしましょう。
- 追加で独自のアニメーションや視覚効果が実装されていると。
- 作成したアプリは最新バージョンのChromeで正常に実行されるようにしてください。
- ソースコードをクリーンに整理し、モジュール化された状態にしてください。コードが綺麗に整理されている状態を重視します。
- コードレビュー時には、作成されたコンポーネントとレイアウトデザインを確認し、書かれたコードから意図を推測するようにします。
- テストはボーナスであり、必須ではありません。
- 完了したら作成したアプリまたはそのコードを[CodeSandbox](https://codesandbox.io/)にアップロードしてください。プレビューでもアプリが正常に動作することを確認してください。何らかの理由でアプリを実行できない場合は、アプリを[GitHub](https://github.com/)、[GitLab](https://gitlab.com/)、または[Bitbucket](https://bitbucket.org/)にプッシュし、プロジェクトをこちらで確認できるように権限を設定してください。
- 上記の操作で公開したアプリケーションのリンクをメールでご連絡ください。このコードテストを提出した後はコードの編集を行わないでください。
