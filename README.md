node-red-contrib-deduplicate
============================

Node-RED node that removes duplicate messages.

Copy of https://github.com/peterstrapp/node-red-contrib-deduplicate with minimal change (key Property at msg level).

Added Key Property to specify the property in the payload to compare for de-duplication.
Payload is the default key property. You can use other property of msg object. For example "_msgid".

![Example](example.png)