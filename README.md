This repository contains the patches for [SNYK-JS-JQUERY-565129](https://snyk.io/vuln/SNYK-JS-JQUERY-565129) which affects all jQuery versions prior 3.5.0.

Except one patch for `<option>` elements (see https://github.com/DanielRuf/snyk-js-jquery-565129/issues/1). This will be probably added in the next weeks.

These patches were generated with `diff -u original patched > patchfile`.

## Apply the patches

You can apply the patches with [`patch`](http://man7.org/linux/man-pages/man1/patch.1p.html), [`git apply`](https://git-scm.com/docs/git-apply), [`patch-package`](https://github.com/ds300/patch-package) and [`composer-patches`](https://github.com/cweagans/composer-patches).

Please consult the corresponding docs.