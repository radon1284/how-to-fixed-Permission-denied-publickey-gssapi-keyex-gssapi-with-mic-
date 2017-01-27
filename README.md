# How to fix Permission denied (publickey,gssapi-keyex,gssapi-with-mic)

# Error details:
***Permission denied (publickey,gssapi-keyex,gssapi-with-mic)***

# Reason:
***The password authentication was disabled on sshd_config file:***

# How To Fix
Go to 
***WHM >> Security Center »SSH Password Authorization Tweak ***

Then, enable the Password Auth. If it is already enabled, you may re-enable it to resolve the error.

Make sure too that `/etc/ssh/sshd_config` ***PermitRootLogin*** set to ***yes***
