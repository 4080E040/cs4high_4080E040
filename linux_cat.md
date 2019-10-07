#cat
```
cat flag

cat .hidden
```
```
lab@29d4cf5af0ab:~$ cat --help
Usage: cat [OPTION]... [FILE]...
Concatenate FILE(s) to standard output.

With no FILE(文件), or when FILE is -, read standard(標準) input(輸入).

  -A, --show-all           equivalent(當量) to -vET
  -b, --number-nonblank    number nonempty(非空) output(輸出) lines, overrides(覆寫) -n
  -e                       equivalent to -vE
  -E, --show-ends          display(顯示) $ at end of each line
  -n, --number             number all output lines
  -s, --squeeze-blank      suppress(壓制) repeated empty output lines
  -t                       equivalent to -vT
  -T, --show-tabs          display TAB characters as ^I
  -u                       (ignored)
  -v, --show-nonprinting   use ^ and M- notation, except for LFD and TAB
      --help     display this help and exit
      --version  output version information and exit

Examples:
  cat f - g  Output f's contents, then standard input, then g's contents.
  cat        Copy standard input to standard output.

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
Report cat translation bugs to <http://translationproject.org/team/>
Full documentation at: <http://www.gnu.org/software/coreutils/cat>
or available locally via: info '(coreutils) cat invocation'

```
