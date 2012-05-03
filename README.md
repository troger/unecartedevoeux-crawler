# uncartedevoeux-crawler

## Overview

This scripts crawls the given URL from [unecartedevoeux](http://unecartedevoeux.com/) to extract messages and post them to the specified SosMessage API URL.

Sample usage:

    ./unecartedevoeux-crawler.rb -u http://unecartedevoeux.com/messages/bonne-annee -s http://localhost:3000 -c 4f6a4f80744e34609b3c8127

Full options:

    Usage: unecartedevoeux-crawler.rb [options]
    -u, --messages-url URL           The unecartedevoeux category url
    -s, --sosmessage-url URL         The SosMessage API url
    -c, --category-id CATEGORY_ID    The category id where to post the messages
    -m, --max-characters MAX         MAX characters of the message
    -n, --dry-run                    Don't actually post the messages, only display them
    -h, --help                       Display this screen
