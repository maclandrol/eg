# tail

print the last 10 lines of a file to stdout

    tail files.txt


print the last 20 lines of file1.txt and file2.txt

    tail -n 20 file1.txt file2.txt


print the last 10 bytes of a file

    tail -c 10 file.txt


print a file starting by line 10

    tail +10 file.txt


print and monitor the last lines of a file as it grow

    tail -f file.txt


# Basic Usage

print the last lines of a file

    tail <file>
