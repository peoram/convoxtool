# Convox Tool
Due to the nature of the convox CLI, it can take a fair amount of time to query racks. This tool will create cache that will help you easily find applications in racks.

# Requirements
- MacOS
- Convox is installed
`brew install convox`

# Instructions
Link the command to /usr/local/bin
`ln -s convoxtool /usr/local/bin/convoxtool`

Create the cache file
`convoxtool -u`

Search for an app
`convox -a <appname>`

# TODO
- Add functionality to perform rolling updates of all racks
- Brew it