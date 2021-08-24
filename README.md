# Bug Reports
Found a bug or exploit with Anti Ghost Ping? Report it here by creating an issue!

# List of bugs I wont/cant fix

**Bug:** If a user other than the author of the message deletes the message containing a ping the bot will respond.

**Reason:** Discord's API does not show who deleted the message, which means the bot would have to check the audit logs and match which audit log entry was the message delete that contained the ghost ping. This can get risky as the bot could match incorrectly, and send a ghost ping alert at wrong occasions.
