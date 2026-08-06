# PTU
***Write Markdown. Export HTML. Nothing more.***

PTU (pronounced "Pee Tee You," sounding like "Pity You") stands for **Plain Text Utopia**—a plain-text HTML editor powered by Markdown.

Named as the opposite of **NVU** ("envy you"), PTU embraces a simple philosophy: Markdown is the source, HTML is the output.

A spiritual successor to projects such as NVU, KompoZer, and BlueGriffon.

## Styling directives

Prefix a Markdown block with one or more directives to style the generated
element. Values can be written directly or inside square brackets.

```md
<bg-color #223344><text-color white><align center># Centered title
<bg-img [https://example.com/paper.png]>A paragraph with an image background.
```

Available directives are `<bg-img URL>`, `<bg-color COLOR>`,
`<text-color COLOR>`, and `<align left|center|right>`.

Put directive-only lines at the very beginning of a document to style the
whole document instead:

```md
<bg-color #111>
<text-color #eee>
<align center>

# My document
```
