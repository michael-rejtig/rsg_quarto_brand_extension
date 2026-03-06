# Rsg-brand-extension Extension For Quarto

This extension adds a default RSG theme to quarto projects. The brand file applies 
RSG's color palette, logos, and typography.

## Create a quarto project

The brand extension expects a _quarto.yml file in the project root.

If the _quarto.yml does not exist in your project, you can create a Quarto project by running the following terminal command in the project root. 

```bash
quarto create project
```

Then, follow the terminal instructions.

## Install the extension

Run the following terminal command in the project root.

```bash
quarto add RSGInc/rsg_quarto_brand_extension
```

This will install the extension under the `_extensions` subdirectory.

```
project/
├── _quarto.yml
└── _extensions/
```

## Using

This extension installs a [brand.yml](https://posit-dev.github.io/brand-yml/) configuration for RSGInc.


