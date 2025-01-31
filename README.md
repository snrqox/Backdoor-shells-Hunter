# Backdoor-shells-Hunter

This Python script scans websites for known admin panels, backdoors, and web shells by checking a list of predefined paths. It supports multithreading, making it highly efficient even when scanning a single site.

Key Features:
✅ Fast & Parallel Scanning: Uses 100 threads to check multiple paths simultaneously for each site.
✅ Automatic URL Handling: Ensures URLs are properly formatted (http:// or https://).
✅ Admin Page Detection: Identifies login pages based on common keywords (login, username, password, admin).
✅ Live Results & Logging: Found pages are displayed in real-time and saved to valids.txt.
✅ Error Handling: Gracefully handles connection failures and redirects.

This tool is useful for security researchers and pentesters looking to identify exposed admin panels or potential vulnerabilities in websites. 🚀


WATCH THE TUTORAIL FROM HERE ON HOW IT WORKS- https://youtu.be/c2Jte4xyri8

Libraries to be installed- 

'pip install requests'

USAGE-

python <main.py> <sites-list.txt>

dev- @temuworkerhere on Telegram- https://t.me/Temuworkerhere
