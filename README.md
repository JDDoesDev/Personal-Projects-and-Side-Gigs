# Personal-Projects-and-Side-Gigs
This repo is where I will be storing personal projects that I have been working on and refactoring as well as code for any side jobs that I might pick up.

## leadworks.inc

This file is a "sub-module" that I wrote as part of a larger module.  It takes the fields of a webform, sends them via cURL to a campaign tracking app, and verifies that all of the fields that are mapped to that tool actually exist. If they don't exist, then the user gets a list of fields that don't exist.  If there is an error, the user is informed that there was an error.  If all goes well, they get a congratulations message.

