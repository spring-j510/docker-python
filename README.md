# docker-python

Personal environment for docker use.

---
---

## dockerに変更がある場合
イメージの作成とbuild
```
docker compose up -d --build
```

コンテナへの接続
```
docker compose exec python3 bash
```


---

## dockerに変更がない場合
↓画像のstartをクリック(vscodeの機能からもできる。)

![screenshot](screenshot.png)

コンテナへの接続
```
docker compose exec python3 bash
```

