<div align="center">
  <img src="https://user-images.githubusercontent.com/90096971/205478716-f86669d1-ef24-4d50-bb16-6dac1fe2fccf.png" width="500" />

# <!DOCTYPE HTML>
My name is AWeirdDev. Call me `awd` if you want, I think.

</div>

## `<head>`
This is my head, and I'm gonna do some styling before continuing. Hold please!

`<style>`
```css
body {
  background: #121212;
  color: white;
  display: flex;
  flex-direction: column;
  min-height: 100%;
  justify-content: center;
  align-items: center;
}
```
`</style>`

Looking better now. So, here's what I'm currently learning:

```py
Python
HTML, CSS, Javascript # perfect
React # oh wait
C++ # maybe?
Bash # almost dying
```
> Note that I'm also on Scratch. [Yes, please.](https://scratch.mit.edu)

`</head>`

## `<body>`
And here are some of my projects!
```jsx
export default function Projects() {
  const proj = [
    { title: "LINELIB", description: "Cool & useful LINE Bot maker.", installation: "pip install linelib" },
    { title: "dischook", description: "Fast & Light Discord webhook module.", installation: "pip install git+https://github.com/AWeirdScratcher/dischook.git" },
    { title: "ur mom", description: "ur mom", installation: "echo ur mom has been installed" }
  ]
  return <ul>
    { ...proj.map( (item, id) => (
      <li>
        <h3>{item.title}</h3>
        <br />
        <p>{item.description}</p>
        <b>Installation</b><br />
        <code>{item.installation}</code>
      </li>
    )) }
  </ul>
}
```

OK. Let me inject it.

`<Projects />`

### [LINELIB](https://github.com/AWeirdScratcher/linelib)
Cool & useful LINE Bot maker.

**Installation**
```bash
pip install linelib
```

### [dischook](https://github.com/AWeirdScratcher/dischook)
Fast & Light Discord webhook module.

**Installation**
```bash
pip install git+https://github.com/AWeirdScratcher/dischook.git
```

### [urmom](https://google.com/search?q=urmom)
urmom

**Installation**
```bash
echo ur mom has been installed
```

`</body>`

## `<!-- What now? -->`
Go try them out! They're really worth trying -- trust me.
