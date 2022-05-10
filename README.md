# serenityos-icons
### Unofficial SerenityOS Icon Themes 

![WHF Catdog](images/WHF-Catdog-64x64.png)

My humble effort to try and produce icons for SerenityOS. 
All icons are made using SerenityOS's own Pixel Paint application.

### How to install
* Copy the contents of `Base/res/icons/{16x16,32x32}` overwriting
those of $SERENITY_DIR/Base/res/icons/{16x16,32x32}
* Executing $SERENITY_DIR/Meta/serenity.sh run should create an image
`_disk_image` for QEmu to load and run
* Source PixelPaint files are on `pp/` folder, inside the icon-
theme name, i.e. *Songbyrrd*
* It is recommended to try out these icons on a separate branch:
```sh
$ git clone https://github.com/serenityos/serenity
$ cd serenity
$ git pull
$ git clone -b branch-using-custom-icons
```
* Use the branch `branch-using-custom-icons` for example and copy
over the icons into serenity as mentioned above.
* This is still a work-in-progress, and may always remain so even
into the forseeable future. :^)

## Note:
I may only update the PixelPaint source files since one can
easily generate the final icons by exporting it as .png files.

## Songbyrrd Icon Theme pack (work-in-progress)
A SerenityOS (custom) icon theme with flat, minimalist look and
style. This is my initial attempt at Icon Theme creation as I have
zero background/experience making them.

## Compression
You can further optimize disk usage by compressing .png files
using `optipng -nb -nc -np [filename]`
