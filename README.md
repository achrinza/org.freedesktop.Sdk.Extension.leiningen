<!-- SPDX-License-Identifier: FSFAP -->

# Flatpak SDK Extension for Leiningen

To build and install it:

```sh
# Remove all `--user` to install system-wide

$ flatpak --user install org.flatpak.Builder
$ flatpak --user run org.flatpak.Builder \
    --force-clean \
    --sandbox \
    --user \
    --install \
    --ccache \
    builddir \
    org.freedesktop.Sdk.Extension.leiningen.yaml
```

## License

[FSFAP](./LICENSES/FSFAP)

