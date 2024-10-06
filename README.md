> [!WARNING]
> Tool discontinued. Do not use it.

# Patch Tool

Tool for patching RawBerry source code.

## Instructions

You need to copy `gen_patch.sh` and `build.py` into the RawBerry project root directory. 

Then you can generate patches by running `bash gen_patch.sh -o [original file] -m [modified file] -n [patch name]`.

After this you can apply patches and make other changes by running `python build.py -c`.

To build RawBerry with patches and changes run `python build.py -b`.

To run it run `qemu-system-x86_64 -cdrom [iso name]`.
