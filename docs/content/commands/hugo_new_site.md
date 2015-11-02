---
date: 2015-09-08T22:45:13-06:00
title: "hugo new site"
slug: hugo_new_site
url: /commands/hugo_new_site/
---
## hugo new site

Create a new site (skeleton)

### Synopsis


Create a new site in the provided directory.
The new site will have the correct structure, but no content or theme yet.
Use `hugo new [contentPath]` to create new content.

```
hugo new site [path]
```

### Options

```
  -f, --format="toml": config & frontmatter format
```

### Options inherited from parent commands

```
  -b, --baseURL="": hostname (and path) to the root, e.g. http://spf13.com/
  -D, --buildDrafts[=false]: include content marked as draft
  -F, --buildFuture[=false]: include content with publishdate in the future
      --cacheDir="": filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --config="": config file (default is path/config.yaml|json|toml)
  -d, --destination="": filesystem path to write files to
      --disableRSS[=false]: Do not build RSS files
      --disableSitemap[=false]: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
      --ignoreCache[=false]: Ignores the cache directory for reading but still writes to it
      --log[=false]: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
      --pluralizeListTitles[=true]: Pluralize titles in lists using inflect
      --preserveTaxonomyNames[=false]: Preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-depardieu")
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis[=false]: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /themes/THEMENAME/)
      --uglyURLs[=false]: if true, use /filename.html instead of /filename/
  -v, --verbose[=false]: verbose output
      --verboseLog[=false]: verbose logging
```

### SEE ALSO
* [hugo new](/commands/hugo_new/)	 - Create new content for your site

###### Auto generated by spf13/cobra on 8-Sep-2015