Assuming out of the box ruleset.

#### Youtube

This worked for me:

    youtube.com apis.google.com * allow
    youtube.com apis.google.com frame allow
    youtube.com googlevideo.com * allow
    youtube.com plus.google.com * allow
    youtube.com plus.google.com frame allow
    youtube.com plus.googleapis.com * allow
    youtube.com plus.googleapis.com frame allow
    youtube.com ytimg.com * allow

Even if you blocked all things Google in the global scope, Youtube will work just find with these rules.