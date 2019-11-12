NNG Meson Patch

clone to same dir name as nng:

```
git clone https://github.com/argylelabcoat/nngpp-meson-patch nngpp-nng-v1.1.1
```

build release zip:

```
zip -r9 ../nngpp-nng-patch-v1.1.1.zip ./ -x *.git* build/\* README.md nngpp.wrap
sha256sum ../nngpp-nng-patch-v1.1.1.zip
```
