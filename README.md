# README

課題用のrailsテンプレートです。

## 前提

- dockerが必要です。

## setup

```
docker compose build
```

```
docker compose run --rm web bin/setup
```


```
docker compose run --rm web yarn install
```

## run

```
docker compose up
```

http://localhost:3000

## 備考

- Taskのscaffoldが含まれていますが、CIの動作確認用です。
適宜削除いただければと思います。（そのままでも問題ないです）
