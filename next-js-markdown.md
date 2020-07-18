# Next Js Markdown

[Example on github](https://github.com/vercel/next.js/tree/canary/examples/blog-starter)

## Setting the Markdown

```js
export default function PostBody({ content }) {
  return (
    <div className="max-w-2xl mx-auto">
      <div
        className={markdownStyles['markdown']}
        dangerouslySetInnerHTML={{ __html: content }}
      />
    </div>
  )
}
```