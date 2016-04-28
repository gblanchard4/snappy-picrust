# Troubleshooting

## Python.h
Numpy compilation would not find `Python.h` haders located at `./parts/picrust/install/usr/include/python2.7/Python.h`

Modified the python2 plugin located at:
`/usr/lib/python3/dist-packages/snapcraft/plugins/python2.py`
to create a python2dev plugin.

## scalartypes.c
WTF?
