# Email Changed Files

Simple bash script to email list of changed files within the past day, with configuration options to ignore defined folders & files.

---

Use-case
-

**Email Changed Files** is meant as a security script to assist in server monitoring. Use at your discretion and make sure to use many other forms of security and monitoring to make sure your systems are locked-down and safe from intruders (and if not, what they are tinkering with).

*"The best defense is a good offense."*

---

## Install

> **NOTE:** .You should have fundamental understanding of Bash and Systems Administration before attempting to install and use.

#### via FTP

1. Clone this repository to your Desktop.
2. Change the configuration variable at the beginning of the script to your needs.
2. Upload `email_cheanged_files` script to `/bin/` folder in your user's home directory (not root).
3. Right-click on uploaded file and CHMOD to `755`.
4. Proceed to Step 5 of the command-line instructions.

#### via Command-line

1. From the user's account, traverse to `/bin/` folder under user's home directory. 
2. Create a new file and copy `email_changed_files` script to new file.
3. Change the configuration variable at the beginning of the script to your needs. save and quit.
3. Run the command `$ chmod 755 <name of script>` to change the permission.
4. Ensure that the user's `/bin/` folder is in the `$PATH` environment variable so the script is executable by alias.
5. Set up as daily cron-job and check your emails! =)
