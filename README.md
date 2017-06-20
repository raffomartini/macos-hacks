# macos-hacks

## Set up sublime text as default text editor

Use duti (http://duti.org / https://github.com/moretension/duti).

Run `brew install duti`, save a filetype like this as:

`duti -s com.sublimetext.3 public.plain-text all`

To also change the default application for executable scripts with no filename extension, add a line like this:

`duti -s com.sublimetext.3 public.unix-executable all`
