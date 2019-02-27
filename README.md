

# 試したこと

- eslintにprettier内包
- eslint --fixさせる

# 結果

- インデントが崩れる
- `yarn add prettier@1.14.3 -D`でprettierがvue対応する直前のマイナーバージョンだと綺麗に整形されるしerrorも出ない
- `yarn prettier --write src/App.vue`での整形は貧弱なので使わなくていい
- `eslint-plugin-vue`と`prettier@1.14.3`最高