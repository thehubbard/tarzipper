#  tarzipper

Menu for turning directories into a tar archive and compressing with gzip using a maximum compression level of 9. This only works in current working directory. There are no options yet to combine multiple directories into single tar.gz

## Usage

```
$ ./tarzipper
```
Then use the select menu to turn your directories into *tarballs*.
The ***all*** option loops over all directories individually. The ***quit*** option provides a quick exit. After the *tarballs* are created the script automatically exits.

## Origin
A little help script to speed up transferring HPC simulation directories to tarballs. Written in as a shell script to learn and develop bash scripting skills

## ToDo
 - Add a way to allow directories named all and quit to also be compressed.
 - Remove duplicates in the multiple selection clause
 - Write tests
 - Implement CI/CD
 - [Possible] Allow multiple directories into single tarball.
 - [Possible] Allow different compression methods i.e. bzip2

## Author

* **Michael Hubbard** - *Author/Maintainer* - [thehubbard](https://github.com/thehubbard)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
