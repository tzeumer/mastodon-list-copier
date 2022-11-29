## Mastodon List Copier
### About
Mastodon has no option integrated to share or copy lists between accounts. While all followers are migrated when moving an account to another instance, this does not apply to lists. Lists have to be recreated by hand (as of November 2022). With some simple vanilla Javascript list copying can be done. Everything runs locally, no data is shared.

By the way. If people listed your old account, you will vanish from their lists too. But nothing else but informing your followers can be done about it (as of November 2022).

Be aware, this is just quick & dirty spaghetti code. It probably could be condensed to much less code (albeit usually harder to read and follow). It is very little tested and no guarantees are given (far from it). But unless you don't accidentily hit "Delete all exisiting lists" and accidentily also confirm it, nothing can break. The worst case is, it doesn't work. But I can't give any support.

### How to use
I don't have a beautiful domain for it, but it's online here: [attach.verweisungsform.de/mastodon-list-copier](https://attach.verweisungsform.de/mastodon-list-copier/index.html). Or just download the html file and put it on a web server (locally it won't run).

Fill in a token for the source and one for the target account. You can add strings that will be appended and/or prepended to the original list name. This might make it easier to only find/check the migrated lists.

## Source
### Changelog
* 2022-11-29: Created Github repository [mastodon-list-copier](https://github.com/tzeumer/mastodon-list-copier)
* 2022-11-26: v0.0.1 Initial version

### Todo
* Prevent running out of api calls (should only happen with very, very large followings or when playing a lot with this tool)
* Check that number of list limit is not hit (you can only create xy lists)
* Use CTRL+F "@todo" in source ;)

### License
Umm, do whatever you want with it. CC0 or whatever. 

Anyway, if you improve it, I'd be happy if you drop me a message at https://openbiblio.social/@vform

