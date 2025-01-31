### 第 5 章 データにまつわる処理を分離する「リポジトリ」

- 要点:

  - リポジトリは、永続化の詳細をドメインモデルから隠蔽する
  - エンティティの集約を一元管理し、トランザクションの境界を明確にする
  - インフラストラクチャの実装の詳細から、ドメインモデルを保護する

- 重要な引用:

  - "リポジトリは、コレクションのようにふるまうインターフェースを提供する"
  - "永続化の詳細を隠蔽することで、ドメインモデルの純粋性を保つ"

- 考察:
  - データベースアクセスの複雑さをドメインモデルから分離できる
  - テスト時にはモックに置き換えやすく、ドメインロジックのテスタビリティが向上する
  - インフラストラクチャの変更に強い設計が可能になる
