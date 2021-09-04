Gatsby Remark plugin to embed Notion-like card UI about link.

> This is a fork from [gatsby-remark-link-card](https://github.com/JaeYeopHan/gatsby-remark-link-card), 👀 You can preview the description of the link!

## 🚚 Install

```
$ npm install --save gatsby-remark-link-preview
# or
$ yarn add gatsby-remark-link-preview
```

## 🚀 How to use

👉 This plugin requires `gatsby-transformer-remark`.

### in Markdown

```md
[$card](https://github.com/lichin-lin/gatsby-remark-link-preview/)
```

### with Config

```js
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-transformer-remark`,
    options: {
      plugins: [
        {
          resolve: `gatsby-remark-link-preview`,
          options: {
            //...
          }
        }
      ]
    }
  }
];
```

## ⚙ Options

| Property       | Type                                  | Default  | Description                                                |
| -------------- | ------------------------------------- | -------- | ---------------------------------------------------------- |
| `delimiter`       | `string`                              | `$card`      | Title of the link to create a card |
| `image`       | `string`                              | data-uri      | Default og image path |
| `favicon`       | `string`                              | data-uri      | Default favicon image path |
| `timeout`       | `number`                              | 30000      | Default timeout(ms) for puppeteer |
| `error`       | `Object`                              | -      | Default config when error |

## Author

👤 **Lichin Lin**

- Github: [@lichin-lin](https://github.com/lichin-lin)
- Twitter: [@lichinlin](https://twitter.com/lichinlin)

## Inspiration

[gatsby-remark-link-card](https://github.com/JaeYeopHan/gatsby-remark-link-card)

## Show your support

Give a ⭐️ if this project helped you!

