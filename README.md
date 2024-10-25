# test-snapd-debug-tools

Snap carryign a selection of tools for debugging snapd and Ubuntu Core.
Specifically in the case of Ubuntu Core, a lot of useful tools aren't part of
the base snap due to size constraints.

## Usage

The snap likely needs to be installed with `--devmode` as there simply may not
be interfaces that cover all the required functionality.

Run tools with:

```sh
test-snapd-debug-tools.tool <tool-name>

```

Eg. invoke `keyctl`:

```
test-snapd-debug-tools.tool keyctl show
```
## Tools

See [snapcraft.yaml](snapcraft.yaml)
