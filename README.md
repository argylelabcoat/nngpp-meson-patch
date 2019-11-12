NNG Meson Patch

clone to same dir name as nng:

```
git clone https://github.com/argylelabcoat/nngpp-meson-patch nngpp-nng-v1.1.1
```

build release zip:

```
cd ..
zip -r9 nngpp-nng-patch-v1.1.1.zip ./nngpp-nng-v1.1.1 -x *.git* build/\* README.md nngpp.wrap
sha256sum nngpp-nng-patch-v1.1.1.zip
```
