# Exercise #8 - Adding to your Bolt Plan

## Steps

  - Open plans/build_webserver.yaml

  - Add a “message of the day”, aka logon message / legal notice text.

  - Under the last IIS resource, add the motd class

  - Set your title and content parameters.

  - Save the file

  - Run the following: `bolt plan run -t www boltshop::build_webserver `

  - You should see resources changed. Now RDP to your server.

  - If successful, after auth you should be prompted with the MOTD.
