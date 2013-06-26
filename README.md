Build this swatch
=================

1. Download Bootswatch
----------------------
Download or clone [Bootswatch](http://bootswatch.com/).

2. Install Bootstrap
--------------------
In a terminal, `cd` to `bootswatch/swatchmaker` and run `make bootstrap` to download the latest stable version of Bootstrap.

3. Install Bootstrap dependencies
---------------------------------
If this was not done before, [install the Node.js Package Manager](https://npmjs.org/). Assuming your terminal is still in the same directory as in the previous step, `cd` to `bootstrap` and run `npm install` to locally install Bootstrap dependencies needed to compile Bootstrap and this swatch.

You will need to add the directory containing the binaries into your PATH. Depending on how your `npm` is configured, the exact procedure for this will vary.

4. Clone this swatch
--------------------
`cd` back to `swatchmaker`, delete the `swatch` directory and then clone this repository. Make sure that the destination folder containing this repository's files is named `swatch`.

5. Customise this swatch
------------------------
If desired, make your changes in `variables.less` and `bootswatch.less` in the `swatch` directory.

6. Build
--------
In the `swatchmaker` directory, run `make bootswatch`. The compiled CSS files will be in `swatchmaker/swatch`.

See also
--------
* [Original bootswatch documentation](https://github.com/thomaspark/bootswatch/tree/gh-pages/swatchmaker)
