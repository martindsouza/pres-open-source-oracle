## Popular Oracle Open Source Projects

Note:
- This section includes videos which will only play in Chrome.</br>
- If you do not have Chrome, the files are in the `www/video` folder.

new-slide-vertical
# Logger

</br>
### PL/SQL Instrumentation Tool

new-slide-vertical

<video class="stretch" src="www/video/logger.mp4" controls></video>

new-slide-vertical
# Logger
</br>
<p class="no-bullet"></p>
- <i class="fa fa-github"></i>  [github.com/OraOpenSource/Logger](https://github.com/OraOpenSource/Logger)
- <i class="fa fa-book"></i> [Documents](https://github.com/OraOpenSource/Logger/tree/master/docs)
- <i class="fa fa-rss"></i> [Blog](http://www.oraopensource.com/blog/?category=Logger)


new-slide-vertical

# OXAR

Build script to generate VM with:
- Oracle XE
- APEX
- ORDS
- Node.js
  - Oracle Node.js driver (node-oracledb)
  - Bower

Notes:
- All demos for this presentation were built from an OXAR built machine.


new-slide-vertical

<video class="stretch" src="www/video/oxar.mp4" controls></video>

Notes:
- Visit the [project page](https://github.com/OraOpenSource/oxar) for all options.</br>
- In this demo used a custom script that edit config.</br>
- Need to copy the files over to the VM Oracle licensing prevents including them.</br>
- Can also reference files on network or provide URL to file.


new-slide-vertical

# OXAR

<p class="no-bullet"></p>
- <i class="fa fa-github"></i> [github.com/OraOpenSource/oxar](https://github.com/OraOpenSource/oxar)
- <i class="fa fa-video-camera"></i> [Install Demo Video](https://www.youtube.com/watch?v=RfIp4Mmj3rA&list=PLEaM1tilka8pSMzT-1rLaGTX5n6iwfcqf)
- <i class="fa fa-rss"></i> [Blog](http://www.oraopensource.com/blog/?category=OXAR)



new-slide-vertical


# APEX-Diff

- Exports APEX in JSON format
- Easily compare two APEX applications

Notes:
- This has been a huge pain for APEX.<br>
- Though can't do a direct restore can see all the changes from one version to next.

new-slide-vertical

<video class="stretch" src="www/video/apex-diff.mp4" controls></video>

Notes:
- Script takes time to run. For demo purposes cut out wait time.

new-slide-vertical

# APEX-Diff

<i class="fa fa-github"></i> [github.com/OraOpenSource/apex-diff](https://github.com/OraOpenSource/apex-diff)

Notes:
- Read the pre-requisites section (solve 90% of issues people have reported).</br>
- Usage: run after once a day for simple code reviews by tech lead.


new-slide-vertical


# OOS Utils

<i class="fa fa-github"></i> [github.com/OraOpenSource/oos-utils](https://github.com/OraOpenSource/oos-utils)

Notes:
- Common developer utility tools
- Still in Alpha Phase

new-slide-vertical

<!-- .slide: data-background="#000" -->
# <span class="white">Live Demo</span>

new-slide-vertical

## PL/SQL Documentation

</br>
[OOS Utils Docs](https://github.com/OraOpenSource/oos-utils/tree/master/docs)

new-slide-vertical

## PL/SQL to Markdown

new-slide-vertical

<!-- .slide: data-background="#000" -->
# <span class="white">Live Demo</span>

new-slide-vertical

## PL/SQL to Markdown

</br>
<i class="fa fa-github"></i> [github.com/OraOpenSource/plsql-md-doc](https://github.com/OraOpenSource/plsql-md-doc)

</br>
[Docs](https://github.com/OraOpenSource/plsql-md-doc/tree/master/docs)

new-slide-vertical

## APEX Front-End Boost

new-slide-vertical

<!-- .slide: data-background="#000" -->
# <span class="white">Live Demo</span>

new-slide-vertical

## APEX Front-End Boost

</br>
<i class="fa fa-github"></i> [github.com/OraOpenSource/apex-frontend-boost](https://github.com/OraOpenSource/apex-frontend-boost)

[Webinar](https://insum.webex.com/mw3100/mywebex/default.do?nomenu=true&siteurl=insum&service=6&rnd=0.4128747654387145&main_url=https%3A%2F%2Finsum.webex.com%2Fec3100%2Feventcenter%2Fevent%2FeventAction.do%3FtheAction%3Dlandingfrommail%26confViewID%3D1924220431%26%26EMK%3D4832534b00000002397442b1476e124fb5307150cdc9500e5dbfb56d191d5909a5bbe014733b51b3%26email%3Dchristian.larocque%2540gmail.com%26encryptTicket%3DSDJTSwAAAAI6GfyXDd7RSWWPHRXBJxlRnlHgop_exoEz473Ggg-Zfw2%26%26SourceId%3DTwitter%26siteurl%3Dinsum) Thursday, May 5, 2016 5:00 pm (Berlin)


new-slide-vertical

## OMonAPEX

new-slide-vertical

<!-- .slide: data-background="#000" -->
# <span class="white">Live Demo</span>

[Link](http://vcentos:10080/ords/f?p=500)

new-slide-vertical

## OMon APEX

</br>
<i class="fa fa-github"></i> [github.com/OraOpenSource/omonapex](https://github.com/OraOpenSource/omonapex)


new-slide-vertical

# APEX Plugins

New home for all plugins: [apex.world](https://apex.world/ords/f?p=100:700)


Notes:
- All management is done on each plugin separately.<br>
- Ex: Issues, bugs, etc are managed by the developer and not by apex.world.


new-slide-vertical

<video class="stretch" src="www/video/apex-plugins.mp4" controls></video>

Notes:
- Highlights apex.world plugin directory</br>
- Look at [Select2 plugin](https://github.com/nbuytaert1/apex-select2) from [Nick Buytaert](https://apexplained.wordpress.com/)



new-slide-vertical

# Oracle

- [Oracle](https://github.com/oracle/)
  - Official Oracle GitHub account
- [DB Tools](https://github.com/oracle/Oracle_DB_Tools)
  - Code samples for SQLcl, ORDS, REST, etc


new-slide-vertical

<!-- .slide: data-background="#fc3f00" -->

<i class="white fa fa-exclamation-triangle fa-5x"></i>


Notes:
- The following demos have not been used, tested, or vetted by me.</br>
- They were suggestions provided by the community.</br>
- Can not comment on their stability, effectiveness, security, etc.</br>
- Not saying that they're bad, I just haven't used them.</br>

new-slide-vertical
# PL/SQL

- [tePLSQL](https://github.com/osalvador/tePLSQL)
  - Template Engine for PLSQL
- [tapiGen2](https://github.com/osalvador/tapiGen2)
  - PL/SQL Table API Generator for Oracle
- [plsqlstarter](https://github.com/bcoulam/plsqlstarter)
  - PL/SQL Starter application framework
- [Alexandria](https://github.com/mortenbra/alexandria-plsql-utils)
  - PL/SQL Utility Library
