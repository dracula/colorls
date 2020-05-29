### [colorls](https://github.com/athityakumar/colorls)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone git@github.com:bigpick/colorls.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/bigpick/colorls/archive/master.zip) option and unzip them.

#### Activating theme

1. First you need to have installed [colorls](https://github.com/athityakumar/colorls#installation).
2. (Optionally) Make a backup of your current dark colorscheme:

    ```bash
    mv ~/.config/colorls/dark_colors.yaml ~/.config/colorls/dark_colors.yaml.backup
    ```
3. Copy the [`dark_colors.yaml`](./dark_colors.yaml) file to the dark color scheme location for colorls:

    ```bash
    cp dark_colors.yaml ~/.config/colorls/dark_colors.yaml
    ```
4. Use the `--dark` option when utilizing `colorls`:

    ```bash
    colorls --dark
    # Optionally: alias ls="colorls --dark"
    ```

If after installing and copying the config file you see issues with `colorls` complaining about missing color names, you may need to use the pre-release gem until the hex color support is released as an official bundle:

    ```bash
    gem update --pre colorls
    ```

