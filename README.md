# unix_to_iso

This is a tiny python script that takes text via STDIN and converts and unix timestamps to iso8601 human readable timestamps.

## Dependencies

Python 3

## Usage
Standard usage takes no args:
```
$ date '+%s' | unix_to_iso
2021-07-16T13:26:49
```

If one wants to insert iso timestamps instead of replace the unix ones use the `-i` flag:
```
$ date '+%s' | unix_to_iso -i
1626463697 (2021-07-16T13:28:17)
```
