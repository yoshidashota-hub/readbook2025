### 第 7 章 柔軟性をもたらす「依存関係のコントロール」

- 要点:

  - 依存関係逆転の原則（DIP）を活用し、ドメイン層の独立性を保つ
  - インターフェースを介して、実装の詳細から核となるドメインモデルを保護
  - DI コンテナを使用して、依存関係を外部から注入する

- 重要な引用:

  - "抽象に依存し、具象に依存しない設計により、システムの柔軟性が向上する"
  - "依存関係の方向を制御することで、ドメインモデルの純粋性を守る"

- 考察:
  - 適切な依存関係の設計により、テスタビリティと保守性が向上する
  - ドメインモデルが外部の実装詳細に依存しないことで、変更に強い設計になる
  - レイヤー間の境界を明確にし、責務の分離を促進する
