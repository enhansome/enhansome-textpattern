# Awesome textpattern with stars

h1. Awesome Textpattern <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" /></a>

A curated list of amazingly awesome "Textpattern CMS":<http://textpattern.com> plugins, resources and shiny things.

*This list is for the latest version of Textpattern (v4.7.x).* For Textpattern v4.6.x see the "txp-4.6 branch":<https://github.com/drmonkeyninja/awesome-textpattern/tree/txp-4.6> ⭐ 87 | 🐛 4 | 📅 2020-10-05.

h2. Contributing

This list is for the community and curated by it, so please contribute. See "CONTRIBUTING":<https://github.com/drmonkeyninja/awesome-textpattern/blob/master/CONTRIBUTING.textile> ⭐ 87 | 🐛 4 | 📅 2020-10-05 for details.

h2. Contents

* "Plugins":#plugins
  \*\* "Admin":#admin
  \*\* "Comments":#comments
  \*\* "Content":#content
  \*\* "Embedding":#embedding
  \*\* "Forms":#forms
  \*\* "Images":#images
  \*\* "Navigation":#nav
  \*\* "Performance":#performance
  \*\* "SEO":#seo
  \*\* "Social":#social
  \*\* "Miscellaneous":#misc
* "Plugin Development":#development
* "Themes":#themes
  \*\* "Back-end":#back-end
  \*\* "Front-end":#front-end
* "Resources":#resources
  \*\* "Official resources":#resources-official
  \*\* "Migration":#migration
  \*\* "Web development software integration":#software-integration
* "Community":#community
  \*\* "Core team":#core-team
  \*\* "Plugins developers":#plugins-dev
  \*\* "Blogs":#blogs
* "Related":#related
* "License":#license

h2(#plugins). Plugins

h3(#admin). Admin

* "hak\_tinymce":<https://github.com/hakjoon/hak_tinymce> ⚠️ Archived - TinyMCE integration for Textpattern.
* "spf\_codemirror":<https://github.com/spiffin/spf_codemirror> ⭐ 6 | 🐛 2 | 🌐 PHP | 📅 2018-01-13 - CodeMirror syntax-highlighting and Emmet code-completion for Pages, Forms, Styles, etc.
* "tom\_image\_grid":<https://github.com/Sacripant/tom_image_grid> ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2017-09-18 - Provides a more compact grid interface for the image admin panel.
* "rah\_privileges":<https://github.com/gocom/rah_privileges> ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2025-07-16 - Configure Textpattern's admin-side user-group privileges through the Preferences panel.
* "spf\_js":<https://github.com/spiffin/spf_js> ⭐ 4 | 🐛 1 | 🌐 PHP | 📅 2022-08-08 - JavaScript management (similar to Presentation → Styles).
* "yab\_copy\_to\_new":<https://github.com/trenc/yab_copy_to_new> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2017-02-14 - Allows for easy copying of articles from the Write panel.
* "jbx\_multiple\_image\_upload":<https://github.com/jbach/jbx_multiple_image_upload> ⚠️ Archived - Multiple image upload.
* "cbe\_frontauth":<https://github.com/ClaireBrione/cbe_frontauth> - Manage backend connections from frontend and protect content from non-logged in users.

h3(#comments). Comments

* "rah\_comments":<https://github.com/gocom/rah_comments> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2015-03-23 - Paginated article comments.
* "rah\_comment\_spam":<https://github.com/gocom/rah_comment_spam> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2025-07-16 - Comment anti-spam plugin.
* "arc\_admin\_comment\_preview":<https://github.com/drmonkeyninja/arc_admin_comment_preview> ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2017-01-20 - Adds a comment preview to admin.
* "jnm\_recent\_comments\_unique":<https://github.com/juanjonavarro/jnm_recent_comments_unique> ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2014-03-07 - Show latest comments.

h3(#content). Content

* "glz\_custom\_fields":<https://github.com/gerhard/glz_custom_fields> ⚠️ Archived - Unlimited custom fields.
* "smd\_tags":<https://github.com/Bloke/smd_tags> ⭐ 7 | 🐛 5 | 🌐 PHP | 📅 2025-03-24 - Unlimited, structured taxonomy across content types.

h3(#embedding). Embedding

* "arc\_youtube":<https://github.com/drmonkeyninja/arc_youtube> ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2018-05-17 - Easily embed YouTube videos.
* "oui\_instagram":<https://github.com/NicolasGraph/oui_instagram> ⭐ 5 | 🐛 1 | 🌐 PHP | 📅 2017-05-28 - Easily embed Instagram recent images galleries.
* "oui\_player":<https://github.com/NicolasGraph/oui_player> ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2018-10-09 - Easily embed customizable players from a growing providers list.
* "oui\_embed":<https://github.com/NicolasGraph/oui_embed> ⭐ 2 | 🐛 1 | 🌐 PHP | 📅 2017-01-19 - Embed any information from any web page using "Embed":<https://github.com/oscarotero/Embed> ⭐ 2,140 | 🐛 73 | 🌐 PHP | 📅 2026-07-08.
* "arc\_vimeo":<https://github.com/drmonkeyninja/arc_vimeo> ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2018-05-17 - Easily embed Vimeo videos.

h3(#forms). Forms

* "zem\_contact\_reborn":<https://github.com/Bloke/zem_contact_reborn> ⭐ 26 | 🐛 16 | 🌐 PHP | 📅 2025-12-21 - Contact forms.

h3(#images). Images

* "smd\_thumbnail":<https://github.com/Bloke/smd_thumbnail> ⭐ 9 | 🐛 2 | 🌐 PHP | 📅 2025-06-01 - Multiple image thumbnails of arbitrary dimensions.
* "smd\_imagery":<https://github.com/Bloke/smd_imagery> ⭐ 5 | 🐛 3 | 🌐 PHP | 📅 2016-10-07 - Article images management.

h3(#nav). Navigation

* "etc\_pagination":<https://github.com/etc-plugins/etc_pagination> ⭐ 4 | 🐛 1 | 🌐 PHP | 📅 2020-12-10 - Paginate everything.
* "smd\_horizon":<https://github.com/Bloke/smd_horizon> ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2019-10-22 - Advanced next/previous links.
* "adi\_menu":<http://www.greatoceanmedia.com.au/txp/?plugin=adi_menu> - Section hierarchy, section menu and breadcrumb trail.

h3(#performance). Performance

* "asy\_jpcache":<https://github.com/netcarver/asy_jpcache> ⭐ 8 | 🐛 1 | 🌐 PHP | 📅 2018-11-04 - Full page caching.
* "etc\_cache":<https://github.com/etc-plugins/etc_cache> ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2022-04-01 - Events-driven cache solution for Textpattern CMS.
* "rah\_cache":<https://github.com/gocom/rah_cache> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2019-03-29 - Cache dynamic pages as flat files.
* "rah\_memcached":<https://github.com/gocom/rah_memcached> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2025-07-16 - Store parts of Textpattern templates in "Memcached":<http://memcached.org>.
* "rah\_cache\_minify":<https://github.com/gocom/rah_cache_minify> ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2013-07-30 - HTML compressor module for rah\_cache plugin.
* "aks\_cache":<http://textpattern.org.ua/plugins/aks_cache> - Partially cache parts of a Textpattern template via tags.
* "rvm\_css":<https://vanmelick.com/txp/rvm_css.php?help> - Static CSS caching.

h3(#seo). SEO

* "rah\_sitemap":<https://github.com/gocom/rah_sitemap> ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2025-07-16 - XML sitemap generator.
* "arc\_meta":<https://github.com/drmonkeyninja/arc_meta> ⭐ 5 | 🐛 1 | 🌐 PHP | 📅 2017-01-20 - Meta tags to improve site SEO and social marketing.
* "arc\_redirect":<https://github.com/drmonkeyninja/arc_redirect> ⭐ 4 | 🐛 1 | 🌐 PHP | 📅 2017-05-08 - URL redirect plugin.
* "wcz\_utf8\_url":<https://github.com/wcz-txp/Unicode-url-for-Textpattern> ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2015-04-01 - UTF-8 permlinks instead of transliterated ones.

h3(#social). Social

Plugins that add social features to Textpattern.

* "TXP Tweet":<https://github.com/drmonkeyninja/TXP-Tweet> ⭐ 11 | 🐛 4 | 🌐 PHP | 📅 2018-02-05 - Twitter-Textpattern integration.
* "arc\_social\_share":<https://github.com/drmonkeyninja/arc_social_share> ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2018-05-16 - Social bookmarking.
* "pat\_article\_social":<https://github.com/cara-tm/pat_article_social> ⭐ 4 | 🐛 1 | 🌐 PHP | 📅 2017-09-13 - Social bookmarking with share counts.

h3(#misc). Miscellaneous

* "textpattern-installer":<https://github.com/gocom/textpattern-installer> ⭐ 6 | 🐛 1 | 🌐 PHP | 📅 2022-11-19 - Textpattern plugin and theme installer for Composer.
* "rah\_backup":<https://github.com/gocom/rah_backup> ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2014-04-01 - Takes backups from Textpattern CMS installations.
* "oui\_cookie":<https://github.com/NicolasGraph/oui_cookie> ⭐ 4 | 🐛 2 | 🌐 PHP | 📅 2019-10-21 - Set, read, reset or delete cookies manually or through URL variables.
* "pat\_if\_amp":<https://github.com/cara-tm/pat_if_amp> ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2019-12-15 - Serve Google's Accelerated Mobile Pages (AMP) in Textpattern.
* "pat\_eu\_cookies\_law":<https://github.com/cara-tm/pat_eu_cookies_law> ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2020-08-16 - EU Cookie Law compliance: A Textpattern CMS plugin for third-party cookies.
* "rah\_terminal":<https://github.com/gocom/rah_terminal> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2014-05-09 - Terminal interface emulator.
* "upm\_pending\_notify":<https://github.com/wcz-txp/upm_pending_notify> ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2015-04-06 - Pending article notifications.
* "fly\_excerpt":<https://github.com/brachycera/fly_excerpt> ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2016-09-28 - Truncate the article excerpt.
* "oui\_quote":<https://github.com/NicolasGraph/oui_quote> ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2017-01-19 - Pull and display a quote from "Quotes on design":<http://quotesondesign.com/>, "They said so":<https://theysaidso.com/>, "Le figaro":<http://evene.lefigaro.fr/citations> or "Le Monde":<http://dicocitations.lemonde.fr/citations-mot-monde.php>.
* "rah\_flat":<https://github.com/NicolasGraph/rah_flat> ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2017-06-26 - Edit Textpattern's database contents and page templates as flat files.
* "rvm\_maintenance":<https://vanmelick.com/txp/rvm_maintenance.php?help> - Shows a maintenance page to all visitors who are not logged in on the admin side.
* "smd\_if":<http://stefdawson.com/sw/plugins/smd_if> - A generic 'if condition' tester.

h2(#development). Plugin Development

* "Plugin template repo":<https://github.com/textpattern/textpattern-plugin-template> ⭐ 18 | 🐛 2 | 🌐 PHP | 📅 2024-12-01 - A starter package for plugin developers.
* "ied\_plugin\_composer":<https://github.com/Bloke/ied_plugin_composer> ⭐ 7 | 🐛 6 | 🌐 PHP | 📅 2022-04-01 - Create, publish and edit plugins.
* "MassPlugCompiler":<https://github.com/gocom/MassPlugCompiler> ⭐ 6 | 🐛 0 | 🌐 PHP | 📅 2025-09-27 - Compiles Textpattern's plugin installer packages from separate source files.

h2(#themes). Themes

h3(#back-end). Back-end

* "Hive theme design patterns":<http://design-patterns.textpattern.io/docs/> - Core designer guidelines for themes and plugins developers.
* "jQuery UI theme repo":<https://github.com/textpattern/textpattern-jquery-ui-theme> ⭐ 15 | 🐛 0 | 🌐 SCSS | 📅 2026-07-31 - The jQuery UI theme used within the Textpattern admin-side.

h3(#front-end). Front-end

* "Default theme repo":<https://github.com/textpattern/textpattern-default-theme> ⭐ 61 | 🐛 6 | 🌐 HTML | 📅 2026-08-16 - The theme that ships as standard with Textpattern CMS.

h2(#resources). Resources

Various resources, such as books, websites and articles, for improving your Textpattern skills and knowledge.

h3(#resources-official). Official resources

* "Official website":<https://textpattern.com/> - Download link, features description and information.
* "Textpattern Documentation":<https://docs.textpattern.com> - The Textpattern user guidelines.

h3(#migration). Migration

* "WP to Txp":<https://github.com/NicolasGraph/wp-to-txp> ⭐ 1 | 🐛 0 | 📅 2018-10-23 - WordPress developer helpful references.

h3(#software-integration). Web development software integration

* "Textpattern for Panic Coda":<https://github.com/philwareham/Textpattern-for-Panic-Coda> ⭐ 7 | 🐛 1 | 🌐 Perl | 📅 2017-04-03 - Handy elements for use with Panic Coda 2 on a Mac.

h2(#community). Community

* "@textpattern on Twitter":<https://twitter.com/textpattern>
* "Google+":<https://plus.google.com/u/0/communities/111366418300163664690>
* "Textpattern Forum":<https://forum.textpattern.com/>

h3(#core-team). Core Team

* Stef Dawson aka "Bloke":<https://forum.textpattern.com/profile.php?id=8181> on "GitHub":<https://github.com/Bloke>.
* Oleg Loukianov aka "etc":<https://forum.textpattern.com/profile.php?id=96820> on "Github":<https://github.com/bloatware>.
* Phil Wareham aka "philwareham":<https://forum.textpattern.com/profile.php?id=39206> on "GitHub":<https://github.com/philwareham>.
* Robert Wetzlmayr aka "wet":<https://forum.textpattern.com/profile.php?id=5463> on "GitHub":<https://github.com/rwetzlmayr>.

h3(#plugins-dev). Plugins developers

Alphabetical order by author prefixes

* adi aka "gomedia":<https://forum.textpattern.com/profile.php?id=15145> on "GitHub":<https://github.com/gomedia-adi>
* arc aka "monkeyninja":<https://forum.textpattern.com/profile.php?id=18747> (Andy Carter) on "Github":<https://github.com/drmonkeyninja>.
* bot aka "redbot":<https://forum.textpattern.com/profile.php?id=8379> on "Github":<https://github.com/redbotxx>.
* cbe aka "CeBe":<https://forum.textpattern.com/profile.php?id=76735> (Claire Brione) on "Github":<https://github.com/ClaireBrione>.
* goe aka "goechsler":<https://forum.textpattern.com/profile.php?id=173137> on "Github":<https://github.com/goechsler>.
* jcr aka jools-r on "Github":<https://github.com/jools-r>.
* mkp aka "michaelkpate":<https://forum.textpattern.com/profile.php?id=109> (Michael K Pate) on "Github":<https://github.com/michaelkpate>.
* oui aka "NicolasGraph":<https://forum.textpattern.com/profile.php?id=15445> (Nicolas Morand) on "Github":<https://github.com/NicolasGraph>.
* pat aka "Pat64":<https://forum.textpattern.com/profile.php?id=7660> (Patrick Lefevre) on "Github":<https://github.com/cara-tm>.
* rah aka "Gocom":<https://forum.textpattern.com/profile.php?id=9632> (Jukka Svahn) on "Github":<https://github.com/gocom>.
* smd aka "Bloke":<https://forum.textpattern.com/profile.php?id=8181> (Stef Dawson) on "Github":<https://github.com/Bloke>.

h3(#blogs). Blogs

* "Textpattern Tips":<http://www.textpattern.tips/> - Tips, tutorials and code examples to help build better Textpattern sites.

h2(#related). Related

* "Awesome PHP":<https://github.com/ziadoz/awesome-php> ⭐ 32,665 | 🐛 86 | 📅 2026-07-13 - A curated list of amazingly awesome PHP libraries, resources and shiny things.

h2(#license). License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Awesome Textpattern</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://andy-carter.com" property="cc:attributionName" rel="cc:attributionURL">Andy Carter</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-21._
