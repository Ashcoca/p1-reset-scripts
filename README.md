# Platform One Workshop Reset Scripts

## Usage

1. Download and unzip Reset-Scripts file
2. Open in your IDE
3. Create a Access Token on GitLab and add to scripts where specified.
4. Uncomment line 45 in `resetEmp.js` (you will need to comment out this line for future resets)
5. In terminal execute `./reset.sh`

This will execute all 5 scripts

1. Unprotecting all branches
2. Resetting `master` branch
3. Resetting `employee2` branch
4. Deleting any additional branches created by students
5. Protecting all branches

You may execute these scripts individually as needed as well.

If you have any questions reach out to @ash.coca on Slack
