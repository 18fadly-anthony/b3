# b3

- because sometimes stupid simple is better
- <40 line bash script
- a successor, not to [backr2](https://github.com/18fadly-anthony/backr2) but to the original backr.py script
- no advanced incremental backups, just make tarballs

## Usage

```
$ cd /foo/bar
$ b3
```
or
```
$ b3 /path/to/file-or-dir
```

## How it stores data

- ~/b3/basename-hash/datetime.tar.gz

```
$ tree ~/b3
~/b3
├── b3-7c46f90
│   └── 2022-07-30T22:06:20-07:00.tar.gz
└── Documents-05bc32d
    ├── 2022-05-25T14:38:16-07:00.tar.gz
    └── 2022-06-01T20:51:05-07:00.tar.gz
```
