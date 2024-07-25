# Hello, this repository is only for fans

The command ls -al , ls -la , ls -l all have the same output
Their output contains six characters

# File access permissions:

To interpret the information contained in the file access permissions column, it is necessary to know that the sequence of characters in this column consists of four parts. For example, consider the first file named checklist.txt in the image above. The contents of the access permissions column for this file, like other files, contains 10 characters. We can see that the full expression for the checklist.txt file is "-rw-rw-r--". The four parts that make up this phrase are as follows:

The first character from the left indicates the file type. The value of this character will be -  for normal files, d  for directories and i  for links (shortcut files that refer to another file). We can see that in the case of the checklist.txt file, the value of this character is equal to -, which means that this file is a normal file.

The second to fourth characters from the left indicate the file owner's access permissions. These three characters represent read r, write w, and executex permissions for a file, respectively. If the owner of the file has any of these permissions, the corresponding character will be placed in the position related to that license, and otherwise, the -  character will be inserted in the corresponding position, meaning that the file does not have that specific license. For example, in the case of the checklist.txt file, we can see that the value of this section is equal to rw-, and it is interpreted as the owner of this file has permission to read and write on the file, but does not have permission to execute the file.

The fifth to seventh characters from the left display the access permissions of the file owner's group. These three characters are also interpreted as in the second part. The permissions specified in this section apply to users who do not own the file, but are members of the group to which the file belongs.

The eighth to tenth characters from the left or in other words the last three characters indicate the access levels of other users. For example, in the case of the checklist.txt file, the value of this section is equal to r-- . As a result, users who do not own this file and are not members of the file owner group can only read the file information and do not have permission to write on it or execute it.

# Number of links pointing to a file:

This column displays the number of files that refer to the same content. The value of this column is at least 1 for all normal files and at least 2 for all directories. Find out by checking this column
You will see if more links have been created that point to the file under review.

# File owner user and group:

In this column, we see the file owner user and file owner group respectively. Carefully, in the example above, we can see that the root-owned-file.txt file belongs to the user named root and the group named soroosh. The information in this column is useful for checking security settings.

# Size:

This column displays the size of the file in bytes.

# The date of the last modification of the file:

In this column, we can see the last time each file was edited.

# File name and additional information:

In this column, in addition to the file name, if one file is a shortcut to another file, we can also see this issue. In the above example, pay attention to the Postman Agent file. After entering the file name, it is found that this file is actually a shortcut that points to the contents of another file with the path app/"Postman Agent".
