# CopyScript
This is python script to synchronize two file directories. The script will get the directory names as input, let’s say source, and destination. Sync using the following logic:

●  If a file exists in the source but not in the destination, copy the file over.
●  If a file exists in the source, but has a different name than in the destination, rename the destination file to match.
●  If a file exists in the destination but not in the source, remove it.          

For the second criterion, there is to use to detect renames. For inspect the content of file, there is to use a hashing function MD5.

