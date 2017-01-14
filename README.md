1dpp lets you "push" and "pull" files to/from OneDrive.

Usage:

    1dpp push file.txt /Documents/file.txt
    1dpp pull /Documents/file.txt file.txt

Needs curl.

To authenticate, visit https://dev.onedrive.com/auth/msa_oauth.htm#try-it-now.
Click "Get Token," then put the header (`Authorization: bearer ...`) in `~/.config/1dpp/authorization`.
