### [colorls](https://github.com/athityakumar/colorls)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone git@github.com:bigpick/colorls.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/bigpick/colorls/archive/master.zip) option and unzip them.

#### Activating theme

1. First you need to have installed [colorls](https://github.com/athityakumar/colorls#installation). Ensure you are running the latest release of colorls, as support for hex string values were added as of the [1.4.2 release](https://github.com/athityakumar/colorls/releases/tag/v1.4.2)


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
    # Additionally: alias ls="colorls --dark"
    # or, perhaps more sanely: alias cls="colorls --dark"
    ```
