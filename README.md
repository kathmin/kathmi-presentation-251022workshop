# kathmi-presentation-251022workshop
Stable Diffusion ComfyUIと自作LoRAを触ってみよう！

## このリポジトリは、2025年10月22日に開催されたワークショップ「Stable Diffusion ComfyUIと自作LoRAを触ってみよう！」の教材です。  
生成AIの仕組みを理解しながら、実際に画像生成を体験することを目的としています。
ローカル環境とGoogle Colabの両方に対応しています。
---

## 🎯 目的

- Stable DiffusionとComfyUIの基本操作を学ぶ
- 自作LoRA（Low-Rank Adaptation）を使ってスタイル調整を体験する
- AI生成と著作権・倫理の関係について考える

---

## 👥 対象者

- 生成AIに興味がある初学者〜中級者
- 教育現場でAIを活用したい指導者
- 倫理的なAI活用に関心のあるクリエイター
- 前提知識（基礎的なPC操作経験数年目推奨）

---

## 🖥️ 使用環境

### ローカル環境（Windows / Mac）

Windows（推奨）
- OS：Windows 10/11（64bit）
- GPU：NVIDIA RTX 30〜40シリーズ（VRAM 12GB以上推奨）
- メモリ：16GB以上（学習用途なら32GB以上）
- ストレージ：SSD 512GB以上
  → RTX4090搭載PCでは快適に動作します。

Mac（Intel / M1 / M2）⚠️
- Intel Mac：GPU非搭載のため、Stable Diffusionはほぼ動作しません
- M1/M2 Mac：Metal対応により動作可能ですが、速度や互換性に制限があります
  → Macでのローカル実行は非推奨です。Google Colabの利用をおすすめします


### Google Colab（クラウド環境）
- GPU：T4, P100, V100など（無料枠はT4が多い）
- RAM：12〜25GB（Colab Proで増加）
- 利用条件：Googleアカウント、GPUランタイムの設定
  → モデルファイル（.ckpt, .safetensors など）は都度アップロードが必要です。
  → 商用利用不可のモデルは、使用前にライセンスを確認してください。
  → 長時間の使用や高負荷モデルは制限対象になることがあります
 
  
---

## ⚠️ 注意事項

- この教材は**教育目的での非営利利用に限り許可**されています。
- 商用利用、再配布、改変しての販売は禁止です。
- 使用するLoRAやモデルは、**ライセンスを確認のうえ導入してください**。
- 生成画像の著作権や倫理的配慮については、各自の責任で判断してください。

---

## 📜 ライセンス

この教材は [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) に基づき、  
**クレジット表記を条件に非営利目的での利用を許可**します。

© 2025 Kathmi. All rights reserved.
