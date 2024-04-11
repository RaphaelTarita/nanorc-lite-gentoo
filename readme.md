# nanorc "Lite-Gentoo" Edition

This repository is a fork of [scopatz/nanorc](https://github.com/scopatz/nanorc) with all files except the language files and this readme removed. Additionally, all language-specific files that are already included in the gentoo ebuild  [`app-editors/nano`](https://packages.gentoo.org/packages/app-editors/nano) have been removed as well. Specifically, the following files are **not present** in this fork (unrelated  whether they exist in the upstream repo):

- ada.nanorc
- asm.nanorc
- autoconf.nanorc
- awk.nanorc
- changelog.nanorc
- cmake.nanorc
- c.nanorc
- css.nanorc
- default.nanorc
- elisp.nanorc
- email.nanorc
- fortran.nanorc
- gentoo.nanorc
- go.nanorc
- groff.nanorc
- guile.nanorc
- haskell.nanorc
- html.nanorc
- java.nanorc
- javascript.nanorc
- json.nanorc
- lua.nanorc
- makefile.nanorc
- man.nanorc
- markdown.nanorc
- nanohelp.nanorc
- nanorc.nanorc
- nftables.nanorc
- objc.nanorc
- ocaml.nanorc
- patch.nanorc
- perl.nanorc
- php.nanorc
- po.nanorc
- povray.nanorc
- python.nanorc
- ruby.nanorc
- rust.nanorc
- sh.nanorc
- spec.nanorc
- sql.nanorc
- tcl.nanorc
- texinfo.nanorc
- tex.nanorc
- xml.nanorc
- yaml.nanorc

### Intended usage

The intended usage of this repository is to simply clone it to the desired folder and then include all `*.nanorc` files from the folder in the user-level or global nanorc config