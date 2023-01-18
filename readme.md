# alvu-foam-template

A non styled minimal template to use [alvu](https://github.com/barelyhuman/alvu) to publish
a web version for [foambubble/foam](https://github.com/foambubble/foam)

## Usage

0. Make sure you have [alvu](https://github.com/barelyhuman/alvu) installed, an easy way is to use curl to get a custom build for your system.

```sh
curl -sf https://goblin.barelyhuman.xyz/codeberg.org/reaper/alvu@latest |sh
```

1. Clone this repo, or use your existing alvu repo.
2. Make sure your `.vscode/settings.json` has the following line

```json
{
  "foam.edit.linkReferenceDefinitions": "withoutExtensions"
}
```

3. Use foam as you would but everything for foam should be in the `pages` directory.
4. Customize the rendering and everything like you would with a normal alvu project. Refer to the [alvu documentation](https://reaper.codeberg.page/alvu/) on how to customize it.
