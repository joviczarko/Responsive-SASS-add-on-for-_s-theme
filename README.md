# Responsive-SASS-add-on-for-_s-theme
Responsive method for the _s theme. 

How it works?

## Installation

Just copy&amp;replace sass folder in the _s theme with this sass folder and you are ready to go.

## Usage

In the variables-site/_structure.scss you can change the values of your break points. Default values are compatible with the Bootstrap's default values so you do not make a breakpoints mess.

If those default values are OK with you, you can start edit files _small.scss, _medium.scss and _large.scss in the responsive folder.

You do not need to pay attention to the media queries since they are called from the main _responsive.scss with media queries, so you just need to start writing regular sass in those empty files.

PLEASE NOTE:
The method is mobile first, which is recommended if you want to do other experiments just edit the queries in the _responsive.scss file.

When you are ready you can compile the sass folder or even better, make it compile on every file save.

## How it works?

It adds a directory with the name "responsive" to the sass folder.

In the responsive folder there is a file called _responsive.scss which calls the individual files for the screen size using media queries which again use break points values from the variables in the variables-site/structure.scss file.

## Default media queries



## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
