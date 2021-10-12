# Iosevka Carrot

**Iosevka Carrot** is an *open source, sans-serif, monospace + quasi‑proportional* typeface family, customised from the original [Iosevka](http://be5invis.github.io/Iosevka).  
TTF files of **2 variants** with **all** weights, slopes and widths are available for download in the [Release Page]().

## Font Variants

### Iosevka Carrot

![](images/Screenshot_20211012_163849.png)
![](images/Screenshot_20211012_164045.png)


### Iosevka Carrot Extended



### Iosevka Carrot Mono



### Iosevka Carrot Mono Extended



## Demo

### Iosevka Carrot Extended



### Iosevka Carrot Mono Extended

![](images/Pasted%20image%2020211011222027.png)
![](images/Pasted%20image%2020211011222008.png)
![](images/Pasted%20image%2020211011215512.png)
![](images/Pasted%20image%2020211011215519.png)

## Download and Installation

Download the fonts from the [Release Page]() in this repository. Unzip and open the folder `/iosevka-carrot`.

- **Instructions for Linux**: Copy the TTF files to your fonts directory, usually in your Home directory `~/.local/share/fonts/` . Then, run `sudo fc-cache -f -v`. For refreshing Font Cache in your system.
- **[Instructions for macOS](http://support.apple.com/kb/HT2509)**: Right click on TTF font files, and install it with FontBook App.
- **Instructions for Windows**: Download the fonts from the [Releases Page](), select the font files and right click, then click “Install for all users” (RECOMMENDED) or “Install”.
  - Since Windows 10 1809, the default font installation is per-user, and it may cause compatibility issues for some applications, mostly written in Java. To cope with this, right click and select "Install for all users" instead. [Reference](https://youtrack.jetbrains.com/issue/JRE-1166?p=IDEA-200145)

## Settings for Code Editors



## Customised Build

To create a custom build of Iosevka, you need:

1. Clone the source of [Iosevka](https://github.com/be5invis/Iosevka).

2. Copy `private-build-plans.toml` file in this repository and place it into the build source.

3. Ensure that [`nodejs`](http://nodejs.org) (≥ 12.16.0) and [`ttfautohint`](http://www.freetype.org/ttfautohint/) are present, and accessible from `PATH`.

4. Run `npm install`. This command will install **all** the NPM dependencies, and will also validate whether external dependencies are present.
   
5. Run `npm run build -- contents::<your plan name>` and the built fonts would be available in `dist/`. Aside from `contents::<plan>`, other options are:

   1. `contents::<plan>` : TTF (Hinted and Unhinted), WOFF(2) and Web font CSS;
   2. `ttf::<plan>` : TTF;
   3. `ttf-unhinted::<plan>` : Unhinted TTF only;
   4. `webfont::<plan>` : Web fonts only (CSS + WOFF2);
   5. `woff2::<plan>` : WOFF2 only.

Refer to [Iosevka/README.md](https://github.com/be5invis/Iosevka#customized-build) for more information.

## Thank You


