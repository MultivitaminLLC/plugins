
## Plugin description format

**debug** {boolean} set _true_ to hide plugin from marketplace, omit for production ready plugins

**id** {string} plugin id from PluginIds.ts

**title** {string} plugin name 

**icon** {string} relative path to plugin icon

**images** {Array<string>} list of relative paths to preview images

**overview** {string} short text description

**description** {string} html description

**tags** {Array<string>} list of categories

**availableAccountTypes** {Array<string>|'*'} List of available plans. ex: \['PAID_TEAM', 'NEW_PREMIUM'\]. '\*' means plugin available in all plans.

**hasSettings** {boolean} flag for settings button

**oauthLink** {string} optional link to oAuth installation