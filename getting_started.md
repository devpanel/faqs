### Q: Can I create a copy of my site for development purpose only?

> **YES.** You may clone any site into your server and set it to `DEVELOPMENT MODE`.

- - -

### Q: How do I *"mirror"* or *sync* a copy of my production site?

> **YES!** -- by cloning your production site into a new site-environment *(aka virtual-host)*.

#### CLONING a site or application
1. **APPS > [Clone App]** -- (from _menu bar_)
1. Provide a unique [**NAME**] to help you identify the new copy on your APPS list.
1. [**SOURCE**] -- the site to be copied/cloned
1. [**TARGET**] -- the server where you will deploy the site's copy

> **TIP:** make use of **['Add a tag']** to associate keywords to a site _(examples: '`dev`', '`testing`', '`for_review`', '`Drupal 7`', '`migration`', etc.)_ that will help you (or your team) easily identify them.

- - -

### Q: Is it possible to deploy any copy of a site for production?

> **YES.** Staging or setting a site for production can be achieved by doing the methods listed below.

1. **Assign or add a domain** to your existing site.
	* if you already have a site ready for prime-time!
1. **Clone** a development/staging site-copy **into your production server**. Then, assign a domain.
1. **Import** a *production-ready* version of source-code or database from another into your existing production site. 

> **REMEMBER:** turn off all development features *(debugging scripts, plugins or modules)* once your site is the production copy.

- - -

### Q: Can I make as many copies of my site into the same server?
> **YES -- BUT KEEP IN MIND** the available resources: `disk-space` and `memory` will be shared by sites hosted in the same server.

If you run out of server-resources, it may lead to data-loss if important system-services (mysql, apache, nginx) don't have enough room to write new records of data.

Use your DevPanel site's [**STATS**] tab to check how much disk or memory space is currently being used.

- - -

### Q: Would I be able to push changes between environments?

**Absolutely!** As a matter of fact - any site can be a SOURCE of
```markdown
A) CODE
B) DATABASE
```

... which you can "push" or deploy  into ANOTHER _(target)_ site.

> **BE CAREFUL!** always consider the consequences (data loss) of pushing between environments. *OVERWRITING important or new FILES / DATA* is very imminent. **REMEMBER TO BACK-UP!**

- - -

### Q: Is it possible to deploy a site from a backup?
Whether it's a **FULL site-backup** or separate **CODE-ONLY** / **DATABASE-ONLY** backups -- you may deploy them using the RESTORE tools.

- - -

### Q: How is DevPanel different from Acquia Cloud or Pantheon (and pricing)?

- - -

### Q: Can I use DevPanel to work either Acquia Cloud (which also uses AWS) or Pantheon?
