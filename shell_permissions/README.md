su switches current user to betty
The whoami command prints the effective username of the current user
touch hello creates an empty file named hello if it does not already exist and executes by chmod +x <4-empty>
chmod u+x hello adds execute permission for the owner of the file hello.
chmod ug+x,o+r hello adds execute permissions for the owner and group owner, and read permissions for others.
chmod 751 hello sets the file permissions to -rwxr-x-wx. The numeric representation 751 is used to set these permissions.
