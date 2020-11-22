# Bug Reports
Found a bug or exploit with Anti Ghost Ping? Report it here by creating an issue!

# List of bugs I wont/cant fix

**Bug:** If a user other than the author of the message deletes the message containing a ping the bot will respond.

**Reason:** Discords api doesnt really show who deleted the message, which means the bot would have to check the audit logs and figure out which message was the one with the ghost ping and see who deleted it. Its very possible that the bot could mess up with that method aswell. All invite links to the bot should have the audit logs permission and I added that because if discord ever adds capability to see who deletes the message, it will be easier to implement into the bot.
