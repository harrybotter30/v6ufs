# v6ufs
Learning of the Unix v6 filesystem

## Utilities

- [v6fs2tar](./v6fs2tar)
    - convert v6 devicefile to tar archive
    - usage: v6fs2tar \[-o output\] \[-z|-j|-J|-t gz|bz2|xz\] devicefile \[inode ...\]
- [itree](./itree)
    - print directory tree by i-nodes
    - usage: itree devicefile \[inode ...\]
- [icat](./icat)
    - print files by i-nodes
    - usage: icat devicefile \[inode ...\]
- [inodes](./inodes)
    - report i-node information
    - usage: inodes \[devicefile ...\]
- [superblock](./superblock)
    - report superblock information
    - usage: superblock \[devicefile ...\]

## References

- [The Unix Heritage Society](https://www.tuhs.org/)
- [The Unix Tree / Sixth Edition Unix](https://minnie.tuhs.org/cgi-bin/utree.pl?file=V6)

### Lions' Commentary

- [Commentary on the Sixth Edition UNIX Operating System](http://www.lemis.com/grog/Documentation/Lions/)
- [A COMMENTARY ON THE SIXTH EDITION UNIX OPERATING SYSTEM](https://warsus.github.io/lions-/)

## Original License

Original Source code License

- https://www.tuhs.org/Archive/Caldera-license.pdf
