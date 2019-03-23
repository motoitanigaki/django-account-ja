# django-account-ja
- Djangoにて会員管理機能を実装したもの
- 特に個人開発などサクッと何かを作りたいときに会員登録やログイン周りを毎回作成しなくても済むために作成

# 機能
- 会員登録
- ログイン
- パスワード変更
- パスワードを忘れた時のメール送信からの再発行
- 退会

# 動作保証環境
```
Python 3.6
Django 2.1.7
django-bootstrap4 0.0.8
```
# 動かす
```
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
python manage.py createsuperuser
```

# ライセンス
このソフトウェアはMITライセンスの下でリリースされています。LICENSEを参照してください。