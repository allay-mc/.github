<p align="center">
  <img
    src="https://github.com/allay-mc/.github/blob/main/profile/allay.gif?raw=true"
    width="25%"
    align="center"
    alt="Animated Allay"
  />
  <h1 align="center">Allay</h1>
  <p align="center">
    Your Personal Creator Assistant
  </p>
</p>

<!-- ANCHOR: description -->
Allay is a command-line application which can be used to create add-ons for
Minecraft: Bedrock Edition. It's goal is to take over the boring work you
would do when manually developing an add-on such as generating UUIDs and
handling localization.
<!-- ANCHOR_END: description -->


## Philosophy

<!-- ANCHOR: philosophy -->
- `allay build` and double-click on the built add-on. It can be that simple.
- We believe that the JSON format should be used by machines and not humans.
  Therefore [TOML](https://toml.io) is used for configuartion and scripts
  can be used to easily convert formats like [YAML](https://yaml.org/) into
  JSON which can be read by Minecraft. The `manifest.json` is generated
  automatically by Allay.
- Generating UUIDs over and over again can be troublesome so Allay fully takes
  care of managing them in your project. For instance the `allay uuid` command
  can be used to get a nice overview of used UUIDs.
- Built-in advanced handling of languages: Translate your project to mexican
  spanish (`es-mx`) and it will be available for *spanish spanish* (`es-es`)
  as well. Allay extends your existing `.lang` file (or creates new ones until
  each language is covered) by adding the appropiate name and description of the
  pack.
- Written in the [Rust programming language](https://www.rust-lang.org/) which
  is *blazingly fast*.[^1]
<!-- ANCHOR_END: philosophy -->


## Where to go from here

Check out the [documentation](https://allay-mc.github.io/docs) to get started
with Allay.

[^1]: or in other terms: "we use rust btw"

---

NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG.
