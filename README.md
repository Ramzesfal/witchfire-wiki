If you download this repo, don't forget to include the wiki_account_me.json in your .gitignore!



# ORIGINAL

## About
Example wiki creation / updating scripts, using [mwcleric](https://github.com/RheingoldRiver/mwcleric)

SORCERER the game: https://sorcerer.river.me/

SORCERER wiki: https://sorcererbyriver.wiki.gg/wiki/Main_Page

## Files included

<code>create.py</code> is an example new-page-creation script.
<code>update.py</code> is an example wiki updating script.

Because there may be user content that you don't want to overwrite (e.g. trivia, strategy sections, etc) a different method is needed for updating.

For the sake of example, these two scripts are self-contained, but in reality you would probably want much of the logic to be handled in a shared formatter class.
