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
  -s, --squeeze-blank      suppress(壓制) repeated(重複) empty(空的) output lines
  -t                       equivalent to -vT
  -T, --show-tabs          display TAB characters(人物) as ^I
  -u                       (ignored)被忽略
  -v, --show-nonprinting(非印刷)   use ^ and M- notation(符號), except(除了) for LFD and TAB
      --help     display this help and exit
      --version(版本)  output version information(信息) and exit

Examples:
  cat f - g  Output f's contents, then standard input, then g's contents.
  cat        Copy standard input to standard output.

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
Report cat translation bugs to <http://translationproject.org/team/>
Full documentation at: <http://www.gnu.org/software/coreutils/cat>
or available locally via: info '(coreutils) cat invocation'

```
