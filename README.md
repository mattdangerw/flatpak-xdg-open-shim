flatpak-xdg-open-shim
---------------------

This is a small shim that can be built into a flatpak app to get a working
version of xdg-open and xdg-email. Made for electron apps which need both
utilities, but should be suitable for any flatpak app needing those tools.

Other xdg-utils scripts are of dubious value inside the sandbox, and were
not included.

This shim requires the gdbus utility, which is included in the freedesktop
runtime.
