This repository contains the patches for [SNYK-JS-JQUERY-565129](https://snyk.io/vuln/SNYK-JS-JQUERY-565129) which affects all jQuery versions prior 3.5.0.

These patches were generated with `diff -u original patched > patchfile`.

## Apply the patches

You can apply the patches with [`patch`](http://man7.org/linux/man-pages/man1/patch.1p.html), [`git apply`](https://git-scm.com/docs/git-apply), [`patch-package`](https://github.com/ds300/patch-package) and [`composer-patches`](https://github.com/cweagans/composer-patches).

Please consult the corresponding docs.

## Generate minified versions

You can generate the minified versions by applying the patches to the original unminified versions and running `./minify.sh` in a terminal.