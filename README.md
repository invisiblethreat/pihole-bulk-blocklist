# Bulk Upload Blocklists

In the 5.0 release of PiHole, the ability to bulk upload blocklists appears to
have been left behind. This is a small script to generate `adlist.json` which
is then added to a tarball that the teleporter will accept.

## To generate

```
$ ./generate-adlist blocklists
a adlist.json
adlist-generated-2020-05-14T18:49:35.tar.gz has been created and can now be imported via Pihole Teleporter
```

## To upload

Use the 'Teleporter' option in 'Settings'. Decide whether you'd like to clobber your current lists.

![](images/teleporter.png)


