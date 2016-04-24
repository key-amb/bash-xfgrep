# NAME

**xfgrep** - Wrapper command of `find ... | xargs grep ...`

# SYNOPSYS

    xfgrep KEYWORD [-i|--ignore IGNORE_FILE_PATTERN] [-d|--dir DIR]

# DESCRIPTION

This wrapper executes following commands:

    find $DIR -type f [ | egrep -v "$IGNORE" ] | xargs egrep -Hn "$KEYWORD"

# AUTHORS

YASUTAKE Kiyoshi <yasutake.kiyoshi@gmail.com>

# LICENSE

The MIT License (MIT)

Copyright (c) 2016 YASUTAKE Kiyoshi
