# スライド例 - /slide Skill

このドキュメントは、良いスライドの具体例を示しています。
生成時の参考にしてください。

---

## 例1: タイトルスライド

```markdown
---
marp: true
theme: default
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-family: 'Noto Sans JP', 'Hiragino Sans', sans-serif;
    padding: 60px 80px;
  }
  h1 { color: #2563EB; font-size: 2.5em; }
  h2 { color: #1E293B; font-size: 1.8em; }
  ul, ol { font-size: 1.3em; line-height: 1.8; }
  strong { color: #2563EB; }
---

<!-- _class: lead -->
<!-- _backgroundColor: #2563EB -->
<!-- _color: white -->

# 🚀 AIで変わる働き方

**2025年、私たちの仕事はこう変わる**

山田太郎 | 株式会社サンプル
2025年1月
```

### ポイント
- 背景色を変えてインパクトを出す
- 絵文字でビジュアルアクセント
- サブタイトルで内容を補足
- 登壇者情報を明記

---

## 例2: 目次スライド

```markdown
---

# 📋 本日のアジェンダ

1. **現状の課題** - なぜ今、変革が必要なのか
2. **AIの可能性** - テクノロジーがもたらす変化
3. **導入事例** - 成功企業から学ぶ
4. **アクションプラン** - 明日からできること

---
```

### ポイント
- 番号付きで全体像を提示
- 各項目にサブ説明を追加
- 適度な情報量（4-5項目）

---

## 例3: 問題提起スライド

```markdown
---

# ⚠️ 日本企業が直面する課題

<div style="display: flex; gap: 40px; margin-top: 40px;">
<div style="flex: 1; text-align: center; padding: 30px; background: #FEF3C7; border-radius: 12px;">

### 📉 生産性の停滞
先進国最下位レベル

</div>
<div style="flex: 1; text-align: center; padding: 30px; background: #FEE2E2; border-radius: 12px;">

### 👴 人手不足
2030年に644万人不足

</div>
<div style="flex: 1; text-align: center; padding: 30px; background: #DBEAFE; border-radius: 12px;">

### 🌍 グローバル競争
デジタル化で後れ

</div>
</div>

---
```

### ポイント
- 3カラムレイアウトで視覚的に整理
- 各カードに異なる背景色
- 数字やデータで説得力を追加

---

## 例4: データ・統計スライド

```markdown
---

# 📊 AI導入の効果

| 指標 | 導入前 | 導入後 | 改善率 |
|:-----|:------:|:------:|:------:|
| 作業時間 | 8時間 | 3時間 | **-62%** |
| エラー率 | 5% | 0.5% | **-90%** |
| 顧客満足度 | 72点 | 91点 | **+26%** |

> 💡 **ポイント**: 単純作業の自動化により、
> 社員はより創造的な業務に集中できるようになった

---
```

### ポイント
- 表形式でデータを整理
- 重要な数字を太字で強調
- 引用ブロックでキーメッセージを追加

---

## 例5: 画像付きスライド

```markdown
---

![bg right:45%](https://images.unsplash.com/photo-xxx)

# 💡 解決策: AIアシスタント

従業員一人ひとりに**専属のAIアシスタント**を

- ✅ 24時間対応可能
- ✅ 瞬時に情報検索
- ✅ ドキュメント自動作成
- ✅ 多言語対応

---
```

### ポイント
- 画像を右側40-50%に配置
- テキストは左側に簡潔に
- チェックマークで箇条書きを視覚化

---

## 例6: ステップ/プロセススライド

```markdown
---

# 🔄 導入までの4ステップ

<div style="display: flex; justify-content: space-between; margin-top: 40px;">

<div style="text-align: center;">
<div style="background: #2563EB; color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.5em; font-weight: bold;">1</div>

**現状分析**
課題の洗い出し
</div>

<div style="text-align: center;">
<div style="background: #2563EB; color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.5em; font-weight: bold;">2</div>

**ツール選定**
要件に合った製品
</div>

<div style="text-align: center;">
<div style="background: #2563EB; color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.5em; font-weight: bold;">3</div>

**パイロット導入**
小規模で検証
</div>

<div style="text-align: center;">
<div style="background: #2563EB; color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.5em; font-weight: bold;">4</div>

**全社展開**
段階的にスケール
</div>

</div>

---
```

### ポイント
- 番号付きステップで流れを可視化
- 円形バッジでステップ番号を強調
- 各ステップに簡潔な説明

---

## 例7: 比較スライド

```markdown
---

# ⚖️ 従来手法 vs AI活用

<div style="display: flex; gap: 60px; margin-top: 30px;">
<div style="flex: 1; padding: 30px; background: #FEE2E2; border-radius: 12px;">

### ❌ 従来の方法

- 手作業でのデータ入力
- 属人的な判断
- 時間がかかる
- ミスが発生しやすい

</div>
<div style="flex: 1; padding: 30px; background: #DCFCE7; border-radius: 12px;">

### ✅ AI活用後

- 自動データ処理
- 一貫した基準
- 即時対応
- 精度99%以上

</div>
</div>

---
```

### ポイント
- 2カラムで対比を明確に
- 色分けで良い/悪いを視覚化（赤 vs 緑）
- 対応する項目を並列に配置

---

## 例8: Q&A / 終了スライド

```markdown
---

<!-- _class: lead -->
<!-- _backgroundColor: #1E293B -->
<!-- _color: white -->

# 🙋 ご質問はありますか？

<div style="margin-top: 60px; font-size: 0.9em;">

📧 contact@example.com
🐦 @example_account
🌐 https://example.com

</div>

---
```

### ポイント
- ダークな背景で締めくくり
- 連絡先を明記
- シンプルに保つ

---

## 避けるべき例（アンチパターン）

### ❌ テキスト過多

```markdown
# 今日のテーマについて

今日は非常に重要なテーマについてお話しします。まず最初に、私たちが直面している
課題について詳しく説明させていただきます。この課題は非常に複雑で、多くの要因が
絡み合っています。具体的には、技術的な問題、組織的な問題、そして人的な問題が
あります。これらの問題を一つ一つ見ていくと、まず技術的な問題としては...
（以下延々と続く）
```

**問題点:**
- 文章が長すぎる
- 箇条書きになっていない
- 読み手が理解しづらい

### ❌ 装飾なし・単調

```markdown
# タイトル

- 項目1
- 項目2
- 項目3
- 項目4
- 項目5
- 項目6
- 項目7
```

**問題点:**
- 視覚的なアクセントがない
- 項目が多すぎる
- 絵文字や強調がない

---

## テンプレート活用のコツ

1. **用途に合わせてパターンを選ぶ**
   - 導入 → タイトルスライド
   - 説明 → コンテンツスライド
   - 比較 → 2カラム
   - 流れ → ステップ

2. **1プレゼンで3-4パターンを組み合わせる**
   - 単調さを避ける
   - 視覚的なリズムを作る

3. **カスタマイズは最小限に**
   - 基本パターンを守る
   - 色やフォントは統一
