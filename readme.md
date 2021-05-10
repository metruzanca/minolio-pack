<p align="center">
  <a href="#">
    <img alt="pack logo" src="pack.png" width="120" />
  </a>
</p>
<h1 align="center">
  Resourcepack Template
</h1>

If you're a developer and want to make a resource pack, this resourcepack template is for you! Leveraging the power of github actions, this will template will create automatic releases when you push tags.

By default this template ignores the `docs/` folder (*as well as hidden dot prefixed folders*) and packages everything else into the resource pack zip.

This allows you to make a nice readme and store additional pages and assets within the `docs/` folder.

If your pack has multiple sizes (e.g. the faithful pack x32, x64, etc) or different versions, you can easily setup setup separate branches and repeat starting from the checkout step specifying a `ref: '<branch e.g. x32>'`.

## Usage
1. Click the **Use this template** button.
2. Chose a name for your pack
3. Upload your assets either via git CLI or via github's UI with drag and drop.

> If you don't want to include my [LICENSE](./LICENSE) file, feel free to credit this repo in some other form. e.g. the [credits.md](./credits.md)