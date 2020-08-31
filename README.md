# treediff
A simple tool to compare files in 2 directory trees

I needed a tool that could compare copied folders from multiple backups.  I wanted to be sure the two directory trees included the same exact files, with no exceptions.

This tool simply takes 2 directories as input arguments, walks both trees, calculates sha256 hashes for every file, and checks if the file is in both trees.

It doesn't matter if the file is in another location in the tree, as long as it exists.

The output shows the files that only exist in one tree of the other.
