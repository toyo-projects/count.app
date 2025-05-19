# count.app
🧮 Flutterカウントアプリ（カウントツール）
Flutterを用いて開発した、基本機能から状態管理・UI改善までを取り入れたカウントアプリです。
ポートフォリオ用の学習成果として、以下の構成と技術的工夫を含んでいます。

#🚀 主な機能
✅ カウントアップ・カウントダウン・リセット機能

🌙 ダークモード自動対応（端末設定に準拠）

🔢 好きな数値を手動で設定可能（TextField入力）

💾 数値の永続保存（SharedPreferences使用）

🔄 画面遷移に対応し、セカンド画面でもリアルタイムで数値表示

🎯 Provider＋ChangeNotifier による状態管理

🎓 AnimatedSwitcher によるスムーズな数値切り替え表示

💬 SnackBar と AlertDialog によるユーザー通知・確認ダイアログ

🧼 入力フィールドのメモリ管理（dispose）

# 🛠️ 使用技術
UI構築・アプリ全体構成：Flutter

プログラミング言語：Dart

Provider：アプリ内状態管理（ChangeNotifier）

shared_preferences：データ永続化（カウント値の保存と読み込み）

Material Design：Flutter標準のスタイルとテーマ構成

# 📂 ファイル構成（主要）
lib/

// アプリ起動・画面構成

　 main.dart                       

 // 状態管理クラス
 
models/
　counter_model.dart         

// メイン画面（カウント操作）

screens/
　first_screen.dart         

// 詳細画面（数値表示）

second_screen.dart         

// 共通ボタンウィジェット

widgets/
　custom_count_button.dart   

// 確認ダイアログの共通化

utils/
　dialog_helper.dart         

    
#🎯 学習目的
・FlutterでのUI設計とアーキテクチャ構成の基礎理解
