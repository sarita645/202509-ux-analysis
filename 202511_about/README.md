# Company Profile (0225)

樣式管理與 Sass 編譯

- 使用 Sass 管理樣式，來源檔放在 `scss/`
- 編譯後的 CSS 放在 `assets/css/main.css`
- 專案使用 Bootstrap 5.3.8

快速開始

1. 安裝依賴

```bash
npm install
```

2. 編譯一次 Sass

```bash
npm run build:sass
```

3. 開發時監看檔案自動編譯

```bash
npm run watch:sass
```

注意事項

- `.cursorrules` 要求：縮排 2 個空格、支援 Chrome 144+、使用 Bootstrap 5.3.8。
- 若要改動主要變數，請修改 `scss/_all.scss` 頂端的 `:root` 變數。