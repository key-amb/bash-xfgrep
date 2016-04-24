# NAME

**xfgrep** - Wrapper command of `find ... | xargs grep ...`

# SYNOPSYS

    xfgrep KEYWORD [-i|--ignore IGNORE_FILE_PATTERN] [-d|--dir DIR] [-f|--file FILE]

    # version
    xfgrep -v|--version
    # help
    xfgrep -h|--help

# DESCRIPTION

This wrapper executes following commands:

    find $DIR -type f -name "$FILE" [ | egrep -v "$IGNORE" ] | xargs egrep -Hn "$KEYWORD"

# SEE ALSO

[https://github.com/key-amb/bash-xfperl-pie](https://github.com/key-amb/bash-xfperl-pie)

# AUTHORS

YASUTAKE Kiyoshi <yasutake.kiyoshi@gmail.com>

# LICENSE

The MIT License (MIT)

Copyright (c) 2016 YASUTAKE Kiyoshi
