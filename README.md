# backup

Backs up files to a given location. Edit `$backup` to the back-up file name and `$backup_loc` to the back-up directory.

## Usage

    backup [-g] [-n] [FILE]...

      -g: Perform backup copying after adding
      -n: Do not sort/uniq backup file after adding

## Examples

    backup ~/.Xresources ~/.vim
    backup -g
