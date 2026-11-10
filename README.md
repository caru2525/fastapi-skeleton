# My System

このリポジトリは Python + FastAPI を使ったシンプルな Web API の雛形です。

## 構成
- `main.py` : FastAPI アプリのエントリーポイント
- `requirements.txt` : 必要パッケージ (fastapi, uvicorn)
- `.gitignore` : Python 開発で不要なファイルを除外

## ローカル実行手順
```powershell
# 仮想環境作成
python -m venv venv
# アクティベート
.\venv\Scripts\Activate.ps1
# 依存パッケージインストール
pip install -r requirements.txt
# サーバ起動
uvicorn main:app --reload
```

## デプロイ
ローカルで動作確認したら、GitHub に push して CI/CD 等でデプロイできます。
