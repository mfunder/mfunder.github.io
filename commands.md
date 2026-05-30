# ls
ls	List directory contents
ls -la	List all with details
ls -lh	Human readable sizes
ls -R	List recursively

# mkdir
mkdir	Create directory
mkdir -p a/b/c	Create nested dirs
touch	Create empty file

# rm
rm	Remove file
rm -rf dir	Remove dir recursively
rmdir dir	Remove empty dir

# heredoc
cat <<EOF
heredoc
EOF
cat <<EOF | sed -z 's/[^A-Za-z]//g'  | md5
heredoc with pipes
EOF

# grep
grep	Search in file
grep -r "text" dir	Search recursively
grep -i "text"	Case insensitive
grep -n "text"	Show line numbers
grep -v "text"	Invert match