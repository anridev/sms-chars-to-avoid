# sms-chars-to-avoid
SMS characters to avoid your message being encoded in UCS2 and their safe replacements

Various special characters encoded differently and once a single character is detected that can not be encoded with a basic character set (ASCII / GSM7) - the whole message length will shrink from 160 to 70 characters (or 67 characters if longer text is used). So in order to avoid unintentionally high SMS charges it's always better to stick to the characters from the basic character set. See table below for an easy-to-miss characters and their appropriate twins from the basic character set.
