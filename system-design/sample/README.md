# リファクタリングの実行サンプル

`domain-refactering-agent.md`を使った実行サンプルです。

このサンプルでは、ScalarDB/ScalarDLを用いた改ざん検知機能を持ったファイルシステムをモジュラーモノリスで作ったものを対象に解析した結果をサンプルとしています。
なお、読み込ませたソフトウェアは、ドキュメントとコードの両方を解析しています。

## 実行手順
Gemini CLI を用いて、以下のように実行します。
1. Gemini CLIを起動
2. `domain-refactering-agent.md`を Gemini に読ませる
3. 分析対象のディレクトリを指定し、レポートを出力するように指示する

## 実行結果
![Before/After](./before-after.png)

* [ドメイン分析](./01_domain_analysis.md)
* [システムマッピング](./02_system_mapping.md)
* [ターゲットアーキテクチャ](./03_target_architecture.md)
* [移行計画](./04_transformation_plan.md)
* [オペレーションとフィードバック](./05_operations_and_feedback.md)
* [モジュール成熟度指数](./06_mmi_overview.md)
* [モジュールとドメインごとのモジュール成熟度指数](./07_mmi_by_module_and_domain.md)
* [モジュール成熟度改善計画](./08_mmi_improvement_plan.md)

