# custom-eagle-lbr

Custom components (symbols and footprints) for Eagle PCB.

To install (on Moc OS):

1. Open Eagle and select `Options` > `Directories`.
2. Append `$HOME/Documents/eagle/lbr` to the `Libraries` field. Additional paths are separated by `:`.
3. Click `OK` to save changes. If the path doesn't exist, Eagle will prompt to create the directory.
4. Clone this repository in `$HOME/Documents/eagle/lbr`, i.e.,
```bash
  $ cd $HOME/Documents/eagle/lbr && git clone git@github.com:cnuahs/custom-eagle-lbr.git ./shaunc.git
```
5. Restart Eagle. The library should appear at (or near) the top of the list as '00shaunc'.

## License
[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)<br />This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
