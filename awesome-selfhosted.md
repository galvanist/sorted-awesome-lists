# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://img.shields.io/travis/awesome-selfhosted/awesome-selfhosted/master?label=link%20checks)](https://github.com/awesome-selfhosted/awesome-selfhosted/issues/2266)

Self-hosting is the practice of locally hosting and managing applications instead of renting from [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) providers.

This is a list of [Free](https://en.wikipedia.org/wiki/Free_software) Software [network services](https://en.wikipedia.org/wiki/Network_service) and [web applications](https://en.wikipedia.org/wiki/Web_application) which can be hosted locally. Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](.github/CONTRIBUTING.md).

--------------------

- List of Software
  - [Analytics](#analytics)
  - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
  - [Calendaring and Contacts Management](#calendaring-and-contacts-management)
  - [Communication systems](#communication-systems)
    - [Custom communication systems](#custom-communication-systems)
    - [Email](#email)
      - [Complete solutions](#complete-solutions)
      - [Mail Transfer Agents](#mail-transfer-agents)
      - [Mail Delivery Agents](#mail-delivery-agents)
      - [Mailing lists and newsletters](#mailing-lists-and-newsletters)
      - [Webmail clients](#webmail-clients)
    - [IRC](#irc)
    - [SIP/IPBX](#sip)
    - [Social Networks and Forums](#social-networks-and-forums)
    - [XMPP](#xmpp)
      - [XMPP Servers](#xmpp-servers)
      - [XMPP Web Clients](#xmpp-web-clients)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [E-commerce](#e-commerce)
  - [DNS](#dns)
  - [Document Management](#document-management)
  - [E-books and Integrated Library Systems (ILS)](#e-books-and-integrated-library-systems-ils)
  - [Federated Identity/Authentication](#federated-identityauthentication)
  - [Feed Readers](#feed-readers)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
    - [Distributed filesystems](#distributed-filesystems)
    - [File transfer/synchronization](#file-transfersynchronization)
    - [Peer-to-peer filesharing](#peer-to-peer-filesharing)
    - [Object storage/file servers](#object-storagefile-servers)
    - [Single-click/drag-n-drop upload](#single-clickdrag-n-drop-upload)
    - [Web based file managers](#web-based-file-managers)
  - [Games](#games)
  - [Gateways and terminal sharing](#gateways-and-terminal-sharing)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Internet of Things (IoT)](#internet-of-things-iot)
  - [Knowledge Management Tools](#knowledge-management-tools)
  - [Learning and Courses](#learning-and-courses)
  - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
  - [Media Streaming](#media-streaming)
    - [Multimedia Streaming](#multimedia-streaming)
    - [Audio Streaming](#audio-streaming)
    - [Video Streaming](#video-streaming)
  - [Misc/Other](#miscother)
  - [Money, Budgeting and Management](#money-budgeting-and-management)
  - [Monitoring](#monitoring)
  - [Note-taking and Editors](#note-taking-and-editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
    - [Booking and Scheduling](#booking-and-scheduling)
  - [Proxy](#proxy)
  - [Read it Later Lists](#read-it-later-lists)
  - [Resource Planning](#resource-planning)
    - [Enterprise Resource Planning](#enterprise-resource-planning)
  - [Search Engines](#search-engines)
  - [Software Development](#software-development)
    - [Project Management](#project-management)
    - [Bug Trackers](#bug-trackers)
    - [IDE/Tools](#idetools)
    - [Continuous Integration](#continuous-integration)
    - [UX testing](#ux-testing)
    - [FaaS/Serverless](#faasserverless)
    - [API Management](#api-management)
    - [Documentation Generators](#documentation-generators)
    - [Localization](#localization)
  - [Static site generators](#static-site-generators)
  - [Task management/To-do lists](#task-managementto-do-lists)
  - [Ticketing](#ticketing)
  - [URL Shorteners](#url-shorteners)
  - [VPN](#vpn)
  - [Web servers](#web-servers)
  - [Wikis](#wikis)
- [Self-hosting Solutions](#self-hosting-solutions)
- [List of Licenses](#list-of-licenses)
- [External links](#external-links)
- [Contributing](#contributing)
- [License](#license)

--------------------

<!-- BEGIN SOFTWARE LIST -->

## Analytics

**[`^        back to top        ^`](#)**

_For personal analytics/dashboards, see [Personal Dashboards](#personal-dashboards)_

_For everything else, see [awesome-analytics](https://github.com/onurakpolat/awesome-analytics)_


## Archiving and Digital Preservation (DP)

**[`^        back to top        ^`](#)**

_Some [Content Management System](#content-management-systems-cms) solutions also feature archiving and digital preservation._

- **<code>&nbsp;&nbsp;7391</code>** [ArchiveBox](https://archivebox.io/) - Self-hosted "wayback machine" that creates HTML & screenshot archives of sites from your bookmarks, browsing history, RSS feeds, or other sources. ([Source Code](https://github.com/pirate/bookmark-archiver)) `MIT` `Python`
- **<code>&nbsp;&nbsp;2792</code>** [CKAN](https://ckan.org) - CKAN is a tool for making open data websites. ([Source Code](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;224</code>** [Archivematica](https://www.archivematica.org/) - Mature digital preservation system designed to maintain standards-based, long-term access to collections of digital objects. ([Demo](http://sandbox.archivematica.org/administration/accounts/login/), [Source Code](https://github.com/artefactual/archivematica)) `AGPL-3.0-only` `Python`
- **<code>&nbsp;&nbsp;&nbsp;220</code>** [ArchivesSpace](https://archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects. ([Demo](https://archivesspace.org/application/demo/), [Source Code](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;167</code>** [Collective Access: Providence](http://collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. ([Source Code](https://github.com/collectiveaccess/providence)) `GPL-3.0-only` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;138</code>** [Access to Memory (AtoM)](https://www.accesstomemory.org/) - Web-based, open source application for standards-based archival description and access in a multilingual, multi-repository environment. ([Demo](https://demo.accesstomemory.org/), [Source Code](https://github.com/artefactual/atom)) `AGPL-3.0-only` `PHP`

## Automation

**[`^        back to top        ^`](#)**

_See also [Internet of Things (IoT)](#internet-of-things-iot)_

- **<code>&nbsp;29933</code>** [Huginn](https://github.com/huginn/huginn) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby`
- **<code>&nbsp;10158</code>** [n8n](https://n8n.io/) - Free node based Workflow Automation Tool. Easily automate tasks across different services. ([Source Code](https://github.com/n8n-io/n8n)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;9299</code>** [Gekko](https://gekko.wizb.it/) - Gekko is a Bitcoin TA trading and backtesting bot which support multiple exchanges and cryptocurrencies. ([Source Code](https://github.com/askmike/gekko)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;7903</code>** [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - Interface to interact with the aria2 downloader. Very simple to use, just download and open index.html in any web browser. ([Demo](http://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
- **<code>&nbsp;&nbsp;7087</code>** [Leon](https://getleon.ai) - Open-source personal assistant who can live on your server. ([Demo](https://www.youtube.com/watch?v=p7GRGiicO1c), [Source Code](https://github.com/leon-ai/leon)) `MIT` `Node.js`
- **<code>&nbsp;&nbsp;6878</code>** [Zenbot 3](https://github.com/carlos8f/zenbot) - Zenbot is a lightweight, extendable, artificially intelligent trading bot for Bitcoin, Ether, Litecoin, and more. `MIT` `Node.js`
- **<code>&nbsp;&nbsp;5808</code>** [Sonarr](https://sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ([Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- **<code>&nbsp;&nbsp;4701</code>** [Beehive](https://github.com/muesli/beehive) - Flexible event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;4577</code>** [Radarr](https://radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ([Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- **<code>&nbsp;&nbsp;4029</code>** [StackStorm](https://stackstorm.com) - StackStorm (aka "IFTTT for Ops") is event-driven automation for auto-remediation, security responses, troubleshooting, deployments, and more. Includes rules engine, workflow, 160 integration packs with 6000+ actions and ChatOps. ([Source Code](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;3738</code>** [CouchPotato](https://couchpota.to/) - CouchPotato is an automatic Video Library Manager for Movies. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/CouchPotato/CouchPotatoServer)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;3509</code>** [feed2toot](https://feed2toot.readthedocs.io/) - Feed2toot parses a RSS feed, extracts the last entries and sends them to Mastodon. ([Source Code](https://gitlab.com/chaica/feed2toot)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;3244</code>** [Healthchecks](https://healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;2948</code>** [Headphones](https://github.com/rembo10/headphones) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1997</code>** [pyLoad](https://pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. ([Source Code](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1702</code>** [Lidarr](https://lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. ([Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- **<code>&nbsp;&nbsp;1527</code>** [SickRage](http://sickrage.github.io/) - SickRage is an automatic Video Library Manager for TV Shows. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/SickRage/SickRage)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1355</code>** [TriggerHappy](https://trigger-happy.readthedocs.io/en/latest/) - Open source clone of IFTTT, a bridge between your internet services. ([Source Code](https://github.com/foxmask/django-th)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;1312</code>** [Alltube](http://www.alltubedownload.net) - Web interface for [youtube-dl](https://github.com/rg3/youtube-dl), a program to download videos and audio from [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Source Code](https://github.com/Rudloff/alltube)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1188</code>** [Medusa](https://github.com/pymedusa/SickRage) - Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;574</code>** [AmIUnique](https://amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ([Source Code](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
- **<code>&nbsp;&nbsp;&nbsp;488</code>** [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) - Material Design inspired YouTube downloader, based on youtube-dl. Supports playlists, quality select, search, dark mode and much more, all with a clean and modern design. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;343</code>** [ActiveWorkflow](https://github.com/automaticmode/active_workflow) - An intelligent process and workflow automation platform based on software agents. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;317</code>** [Kibitzr](https://kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. ([Source Code](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;297</code>** [nefarious](https://github.com/lardbit/nefarious) - Web application that automates downloading Movies and TV Shows. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;264</code>** [µTask](https://github.com/ovh/utask) - µTask is an automation engine that models and executes business processes declared in yaml. `BSD-3-Clause` `Go`
- **<code>&nbsp;&nbsp;&nbsp;189</code>** [Accelerated Text](https://github.com/tokenmill/accelerated-text) - Automatically generate multiple natural language descriptions of your data varying in wording and structure. `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;157</code>** [Episodes](https://github.com/guptachetan1997/Episodes) `⚠` - Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;107</code>** [HRConvert2](https://github.com/zelon88/HRConvert2) - Drag-and-drop file conversion server with session based authentication, automatic temporary file maintenance, and logging capability. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;81</code>** [betanin](https://github.com/sentriz/betanin/) - Music organization man-in-the-middle of your torrent client and music player. Based on beets.io, similar to Sonarr and Radarr. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;44</code>** [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer is a WSGI (Python3) micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed(Returns Atom, RSS, or JSON). ([Demo](https://mretc.net/feedmixer/json?f=http://hnrss.org/newest&f=http://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;40</code>** [ZeroQueue](https://github.com/thezeroqueue/zeroqueue) - A low-code queue management system that lets you run scheduled jobs for anything. `GPL-3.0` `Node.js`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;25</code>** [homebank-converter](https://github.com/Binnette/homebank-converter) - Web app to convert an export bank file to compatible Homebank csv. ([Demo](http://binnette.github.io/homebank-converter/)) `AGPL-3.0` `HTML5`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;10</code>** [MeTube](https://github.com/alexta69/metube) - Web GUI for youtube-dl, with playlist support. Allows downloading videos from dozens of websites. `AGPL-3.0` `Python/Nodejs/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`

## Blogging Platforms

**[`^        back to top        ^`](#)**

_See also [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) and [WeblogMatrix](http://www.weblogmatrix.org/)_

- **<code>&nbsp;&nbsp;&nbsp;&nbsp;92</code>** [Blog](https://github.com/m1k1o/blog) - Facebook-styled blog. Free, extremely lightweight, single-user and easy to install. ([Demo](https://blog.m1k1o.net/)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;35</code>** [Antville](https://antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ([Source Code](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- Blogotext - Free blog-engine written in PHP and using SQLite. This offers you both an unmatched simplicity during installation and great performances. ([Source Code](https://github.com/timovn/blogotext)) `MIT` `PHP`
- **<code>&nbsp;35309</code>** [Ghost](https://ghost.org/) - Just a blogging platform. ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- **<code>&nbsp;31513</code>** [Hexo](https://hexo.io/) - Fast, simple and powerful blog framework, powered by Node.js. ([Source Code](https://github.com/hexojs/hexo)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;2498</code>** [Canvas](https://cnvs.io) - A Laravel publishing platform. ([Source Code](https://github.com/cnvs/canvas)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;1378</code>** [Plume](https://joinplu.me/) - Federated blogging engine, based on ActivityPub. ([Source Code](https://github.com/Plume-org/Plume)) `AGPL-3.0` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;828</code>** [Known](https://withknown.com/) - Single website for all your content. ([Source Code](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;767</code>** [Bludit](https://www.bludit.com/) `⚠` - Simple application to build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. ([Demo](https://demo.bludit.com/), [Source Code](https://github.com/dignajar/bludit)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;671</code>** [htmly](https://www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog). ([Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;505</code>** [Postleaf](https://www.postleaf.org/) - Open source blogging platform with inline editing, handlebar templates, and a beautiful user interface. ([Source Code](https://github.com/Postleaf/postleaf)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;381</code>** [Dante Stories](https://dante-stories.herokuapp.com/) - Self hosted Medium platform built with Ruby on Rails. ([Source Code](https://github.com/michelson/dante-stories)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;165</code>** [PluXml](http://www.pluxml.org/) - XML-based blog/CMS platform. ([Source Code](https://github.com/pluxml/PluXml)) `GPL-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;132</code>** [Hotglue](https://hotglue.me/) - Freehand CMS which allows to construct websites directly in a web-browser. It uses flat files for storage and provides an intuitive GUI. ([Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;126</code>** [Chyrp Lite](http://chyrplite.net) - Extra-awesome, extra-lightweight blog engine. ([Source Code](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code>** [Cadmus](https://github.com/liamdemafelix/cadmus) - Cadmus is an extremely lightweight, flat-file blogging platform powered by Markdown. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Formtools](https://formtools.org/) - Powerful, flexible, free and open source PHP/MySQL script to manage your forms and data. ([Source Code](https://github.com/formtools)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Dotclear](http://dotclear.org/) - Take control over your blog. ([Source Code](https://hg.dotclear.org/dotclear)) `GPL-2.0` `PHP`


## Bookmarks and Link Sharing

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;4513</code>** [Shiori](https://github.com/RadhiFadlillah/shiori) - Simple bookmark manager built with Go. `MIT` `Go`
- **<code>&nbsp;&nbsp;3236</code>** [Lobsters](https://lobste.rs) - Run your own link aggregation site. ([Source Code](https://github.com/jcs/lobsters)) `BSD-3-Clause` `Ruby`
- **<code>&nbsp;&nbsp;1976</code>** [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform. ([Demo](https://demo.shaarli.org)) `Zlib` `PHP`
- **<code>&nbsp;&nbsp;1604</code>** [Pinry](http://getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages. ([Source Code](https://github.com/pinry/pinry)) `BSD-2-Clause` `Python`
- **<code>&nbsp;&nbsp;1362</code>** [unmark](https://github.com/plainmade/unmark) - Open source to do app for links. `MIT` `PHP`
- **<code>&nbsp;&nbsp;1223</code>** [Reminiscence](https://github.com/kanishka-linux/reminiscence) - Self-Hosted Bookmark And Archive Manager. `AGPL-3.0` `Python`
  - **<code>&nbsp;&nbsp;1176</code>** [Firefox Sync Server](https://github.com/mozilla-services/syncserver) - Sync Firefox bookmarks, passwords, history, tabs, preferences. `MPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;483</code>** [Geekmarks](https://geekmarks.dmitryfrank.com/) - Personal bookmarking service focused on speed and organization using hierarchical tags. ([Source Code](https://github.com/dimonomid/geekmarks)) `BSD-2-Clause` `Go`
- **<code>&nbsp;&nbsp;&nbsp;476</code>** [linkding](https://github.com/sissbruecker/linkding) - Minimal bookmark management with a fast and clean UI. Simple installation through Docker and can run on your Raspberry Pi. ([Demo](https://demo.linkding.link/)) `MIT` `Docker/Python/Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;234</code>** [Espial](https://github.com/jonschoning/espial) - An open-source, web-based bookmarking server. `AGPL-3.0` `Haskell`
- **<code>&nbsp;&nbsp;&nbsp;221</code>** [golinks](https://github.com/prologic/golinks) - Web application that allows you to create smart bookmarks, commands and aliases by pointing your web browser's default search engine at a running instance. Similar to bunny1 or yubnub. ([Demo](https://search.mills.io)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;106</code>** [dyu/bookmarks](https://github.com/dyu/bookmarks) - Single-threaded/process bookmark app powered by leveldb and uWebSockets. Supports importing from Delicious and Chrome. ([Demo](https://dyuproject.com/bookmarks/)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;102</code>** [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ([Source Code](https://github.com/mapio/nofussbm)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ubookmark](https://ungleich.ch/u/projects/ubookmark/) - LDAP enabled bookmarking service. ([Demo](https://ipv6.blog), [Source Code](https://code.ungleich.ch/ungleich-public/ubookmark/)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [xBrowserSync](https://www.xbrowsersync.org) - Open source tool for syncing browser data between browsers and devices. ([Source Code](https://github.com/xBrowserSync)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Firefox Account Server](https://mozilla.github.io/application-services/docs/accounts/welcome.html) - This is the monorepo for Firefox Accounts (formerly separated into Auth and Content). ([Source Code](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs, Java`

## Calendaring and Contacts Management

**[`^        back to top        ^`](#)**

_Some [Groupware](#groupware) solutions also feature calendar/address book editing and synchronization._

_See https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations_

### CalDAV or CardDAV servers

- **<code>&nbsp;&nbsp;1937</code>** [Radicale](http://radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. ([Source Code](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1731</code>** [Baïkal](http://sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. ([Source Code](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1507</code>** [Xandikos](https://www.xandikos.org/) - Open source CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository. ([Source Code](https://github.com/jelmer/xandikos)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1082</code>** [SabreDAV](http://sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. ([Source Code](https://github.com/sabre-io/dav)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;373</code>** [CalendarServer](https://www.calendarserver.org/) - Apple, Inc.'s standards-compliant server implementing the CalDAV and CardDAV protocols shipped with macOS Server. ([Source Code](https://github.com/apple/ccs-calendarserver)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;207</code>** [DecSync CC](https://f-droid.org/packages/org.decsync.cc/) - Serverless contacts, calendar synchronization using your own file syncing method i.e Syncthing, Nextcloud etc. ([Source Code](https://github.com/39aldo39/DecSyncCC)) `GPL-3.0` `Kotlin`
- **<code>&nbsp;&nbsp;&nbsp;143</code>** [EteSync Server](https://www.etesync.com) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. ([Source Code](https://github.com/etesync/server-skeleton)) `AGPL-3.0` `Python/Django`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;26</code>** [Davis](https://github.com/tchapi/davis/) - A simple, dockerizable and fully translatable admin interface for sabre/dav based on Symfony 5 and Bootstrap 4, largely inspired by Baïkal. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [calypso](https://keithp.com/calypso/) - Python-based CalDAV and CardDAV server, forked from Radicale. ([Source Code](https://keithp.com/git/calypso.git)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [DAViCal](https://www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store. ([Source Code](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP`

### CalDAV or CardDAV web-based clients

- **<code>&nbsp;&nbsp;&nbsp;410</code>** [AgenDAV](http://agendav.org/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. ([Source Code](https://github.com/agendav/agendav)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;157</code>** [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync's official Web-based client (i.e., their Web app). ([Demo](https://client.etesync.com/), [Source Code](https://github.com/etesync/etesync-web)) `AGPL-3.0` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - Open source CalDAV/CardDAV web client implementation. ([Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPL-3.0` `Javascript`

## Communication systems

**[`^        back to top        ^`](#)**

### Custom communication systems

- **<code>&nbsp;28613</code>** [Rocket.Chat](https://rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
- **<code>&nbsp;19282</code>** [Mattermost](http://www.mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with Gitlab. ([Source Code](https://github.com/mattermost/mattermost-server)) `AGPL-3.0/Apache-2.0` `Go`
- **<code>&nbsp;14304</code>** [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
- **<code>&nbsp;12717</code>** [Zulip](https://zulip.org) - Zulip is a powerful, open source group chat application. ([Source Code](https://github.com/zulip/zulip)) `Apache-2.0/Other` `Python`
- **<code>&nbsp;&nbsp;6795</code>** [Synapse](http://matrix.org/docs/projects/server/synapse.html) - Server for [Matrix](https://matrix.org/), an open standard for decentralized persistent communication. ([Source Code](https://github.com/matrix-org/synapse)) `Apache-2.0` `Python`
  - **<code>&nbsp;&nbsp;5652</code>** [Element](https://element.io) - Fully-featured Matrix client for Web, iOS & Android. ([Source Code](https://github.com/vector-im/element-web)) `Apache-2.0` `Javascript`
- **<code>&nbsp;&nbsp;5067</code>** [Gotify](https://gotify.net/) - Self-hosted notification server with Android and CLI clients, similar to PushBullet. ([Source Code](https://github.com/gotify/server), [Clients](https://github.com/gotify/android)) `MIT` `Go`
- **<code>&nbsp;&nbsp;4652</code>** [Centrifugo](https://github.com/centrifugal/centrifugo) - Language-agnostic real-time messaging (Websocket or SockJS) server. ([Demo](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go`
- **<code>&nbsp;&nbsp;3507</code>** [Mumble](http://wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ([Source Code](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++`
- **<code>&nbsp;&nbsp;2762</code>** [Kandan](http://getkandan.com/) - Kandan is an Open Source Alternative to HipChat. ([Source Code](https://github.com/kandanapp/kandan)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;2151</code>** [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;2115</code>** [Papercups](https://papercups.io/) - An open source live customer chat web app written in Elixir. ([Demo](https://app.papercups.io/demo), [Source Code](https://github.com/papercups-io/papercups)) `MIT` `Elixir`
- **<code>&nbsp;&nbsp;2084</code>** [TextBelt](https://github.com/typpo/textbelt) `⚠` - Outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. `MIT` `Javascript`
- **<code>&nbsp;&nbsp;1372</code>** [Tox](https://tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. ([Source Code](https://github.com/irungentoo/toxcore)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;1347</code>** [Live Helper Chat](http://livehelperchat.com/) - Live Support chat for your website. ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;1197</code>** [RetroShare](http://retroshare.org) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ([Source Code](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `С++`
- **<code>&nbsp;&nbsp;&nbsp;983</code>** [Spreed](https://www.spreed.me/) - WebRTC audio/video calls, conferencing server, and web client. ([Source Code](https://github.com/strukturag/spreed-webrtc)) `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;818</code>** [Hawkpost](https://hawkpost.co) - HawkPost is a web app that lets you create unique links that you can share with a person that desires to send you important information but doesn't know how to encrypt it. The message is encrypted in their browser and sent to your email address. ([Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;612</code>** [Node-Chat](https://github.com/IgorAntun/node-chat) - Not-so-basic open-source chat with admin features. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;599</code>** [WBO](https://github.com/lovasoa/whitebophir#wbo) -  A web Whiteboard to collaborate in real-time on schemas, drawings, and notes. ([Demo](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- **<code>&nbsp;&nbsp;&nbsp;470</code>** [MiAOU](https://miaou.dystroy.org/login) - Multi-room persistent chat server. ([Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;405</code>** [Mibew](https://mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website. ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;314</code>** [Spectrum 2](http://spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. ([Source Code](https://github.com/hanzz/spectrum2)) `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;295</code>** [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ([Source Code](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;292</code>** [Darkwire.io](https://darkwire.io/) - End-to-end encrypted instant web chat. ([Source Code](https://github.com/darkwire/darkwire.io)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;257</code>** [Rallly](http://rallly.co) - Rallly is a free collaborative scheduling service. ([Source Code](https://github.com/lukevella/Rallly)) `CC-BY-SA-4.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;228</code>** [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server. `GPL-2.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;143</code>** [Shhh](https://github.com/smallwat3r/shhh) - Keep secrets out of emails or chat logs, share them using secure links with passphrase and expiration dates. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;79</code>** [LeapChat](https://github.com/cryptag/leapchat) - Ephemeral, encrypted, in-browser chat rooms. `AGPL-3.0` `JavaScript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;61</code>** [OTS](https://ots.fyi/) - One-Time-Secret sharing platform with a symmetric 256bit AES encryption in the browser. ([Source Code](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;54</code>** [KChat](https://github.com/php-kchat/kchat) - PHP Based Live Chat Application. `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;50</code>** [LibreNews](https://librenews.io/) - Decentralized and secure breaking news notification system. ([Source Code](https://github.com/milesmcc/LibreNews-Server/)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;28</code>** [Freenet](https://freenetproject.org/index.html) - Anonymously share files, browse and publish "freesites" (web sites accessible only through Freenet) and chat on forums. ([Source Code](https://github.com/freenet/fred)) `GPL-2.0` `Java`
  - **<code>&nbsp;&nbsp;&nbsp;&nbsp;25</code>** [Matrix Console Web](http://matrix.org/docs/projects/client/matrix-console.html) - Web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([Source Code](https://github.com/matrix-org/matrix-angular-sdk)) `Apache-2.0` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;15</code>** [ZeroNet](https://zeronet.io/) `⚠` - Open, free, and uncensorable websites, using Bitcoin cryptography and BitTorrent network. ([Source Code](https://github.com/HelloZeroNet/ZeroNet)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;10</code>** [PushBits](https://github.com/eikendev/pushbits) - Self-hosted notification server for relaying push notifications via Matrix, similar to PushBullet and Gotify. `ISC` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Syndie](https://syndie.de) - Syndie is a libre system for operating distributed forums. `CC0-1.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Jami](https://jami.net/) - Free and universal communication platform which preserves the user's privacy and freedoms (formerly GNU Ring). ([Source Code](https://git.ring.cx/savoirfairelinux/ring-project)) `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [GNUnet](https://gnunet.org/) - Free software framework for decentralized, peer-to-peer networking. ([Source Code](https://gnunet.org/git/)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Friends](http://moose-team.github.io/friends/) - P2P chat powered by the web. ([Source Code](https://github.com/moose-team/friends)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Lets-Chat](http://sdelements.github.io/lets-chat/) - Self hosted chat suite written in Node. ([Source Code](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`

### Email

**[`^        back to top        ^`](#)**

#### Complete solutions

_Simple deployment of a mail server, e.g. for inexperienced or impatient admins._

- **<code>&nbsp;&nbsp;6132</code>** [docker-mailserver](https://github.com/tomav/docker-mailserver) - Fullstack but simple mail server (smtp, imap, antispam, antivirus, etc.). Only configuration files, no SQL database. Keep it simple and versioned. Easy to deploy and upgrade. `MIT` `Docker`
- **<code>&nbsp;&nbsp;3338</code>** [Mailcow](https://mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ([Source Code](https://github.com/mailcow/mailcow-dockerized)) `GPL-2.0` `Docker/PHP`
- **<code>&nbsp;&nbsp;2249</code>** [Mailu](https://mailu.io/) - Mailu is a simple yet full-featured mail server as a set of Docker images. ([Demo](https://github.com/Mailu/Mailu/wiki/Demo-server), [Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- **<code>&nbsp;&nbsp;1650</code>** [Modoboa](http://modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. ([Source Code](https://github.com/tonioo/modoboa)) `MIT` `Python`
- **<code>&nbsp;&nbsp;1148</code>** [wildduck](https://wildduck.email/) - Scalable no-SPOF IMAP/POP3 mail server. ([Source Code](https://github.com/nodemailer/wildduck)) `EUPL-1.2` `Node.js`
- **<code>&nbsp;&nbsp;&nbsp;737</code>** [SimpleLogin](https://simplelogin.io) - Open source email alias solution to protect your email address. Comes with browser extensions and mobile apps. ([Source Code](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- **<code>&nbsp;&nbsp;&nbsp;733</code>** [AnonAddy](https://anonaddy.com) - Open source email forwarding service for creating aliases. ([Source Code](https://github.com/anonaddy/anonaddy)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;232</code>** [iRedMail](http://www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. ([Source Code](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- **<code>&nbsp;&nbsp;&nbsp;226</code>** [homebox](https://github.com/progmaticltd/homebox) - Suite of Ansible scripts to deploy a fully functional mail server on Debian. Unobtrusive and automatic as much as possible, focusing on stability and security. `GPL-3.0` `Shell`
- **<code>&nbsp;&nbsp;&nbsp;202</code>** [Inboxen](https://inboxen.org) - Inboxen is a service that provides you with an infinite number of unique inboxes. ([Source Code](https://github.com/Inboxen/Inboxen)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;176</code>** [Ptorx](https://ptorx.com/) - 📩🛡 Email privacy. Anonymously send and receive with alias forwarding. ([Source Code](https://github.com/xyfir/ptorx)) `GPL-3.0` `Node.js`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;66</code>** [Excision Mail](https://github.com/Excision-Mail/Excision-Mail) - Fullstack, security focused mailserver based on OpenSMTPD for OpenBSD using ansible. `ISC` `Shell/Ansible`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;51</code>** [Mail-in-a-Box](https://mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code>** [Qmailtoaster](http://www.qmailtoaster.com/) - Stable, full-featured, easy-to-install mail server based on qmail. ([Source Code](https://github.com/QMailToaster/)) `Multiple` `Linux`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - Complete mailserver solution leveraging the Nix Ecosystem. `GPL-3.0` `Nix`

#### Mail Transfer Agents

_MTAs / SMTP servers_

- **<code>&nbsp;&nbsp;7184</code>** [MailHog](https://github.com/mailhog/MailHog) - Small Golang executable which runs an SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. `MIT` `Go`
- **<code>&nbsp;&nbsp;5118</code>** [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;3725</code>** [Haraka](http://haraka.github.io/) - High-performance, pluginable SMTP server written in Javascript. ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;382</code>** [chasquid](https://blitiri.com.ar/p/chasquid/) - SMTP (email) server with a focus on simplicity, security, and ease of operation. ([Source Code](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;339</code>** [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
- **<code>&nbsp;&nbsp;&nbsp;140</code>** [Slimta](http://slimta.org) - Mail Transfer Library built on Python. ([Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Exim](https://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge. ([Source Code](http://git.exim.org/exim.git)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL-1.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Qmail](https://cr.yp.to/qmail.html) - Secure Sendmail replacement. ([Source Code](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0-1.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA). `Sendmail` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Maildrop](https://gitlab.com/markbeeson/maildrop) - Disposable email SMTP server, also useful for development. `MIT` `Scala`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Courier MTA](http://www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services. ([Source Code](http://www.courier-mta.org/repo.html)) `GPL-3.0` `C`

#### Mail Delivery Agents

_MDAs - IMAP/POP3 software_

- **<code>&nbsp;&nbsp;&nbsp;491</code>** [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. ([Source Code](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C`
- **<code>&nbsp;&nbsp;&nbsp;314</code>** [Cyrus IMAP/POP3](https://www.cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in. ([Source Code](https://github.com/cyrusimap/cyrus-imapd )) `BSD-3-Clause-Attribution` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Piler](http://www.mailpiler.org/wiki/start) - feature-rich open source email archiving solution. ([Source Code](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`

#### Mailing lists and Newsletters

_Mailing lists servers and mass mailing software - one message to many recipients._

- **<code>&nbsp;10070</code>** [Postal](https://github.com/atech/postal) - Fully featured open source mail delivery platform for incoming and outgoing e-mail. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;4525</code>** [Mailtrain](https://mailtrain.org/) - self hosted newsletter application built on Node.js (v5+) and MySQL (v5.5+ or MariaDB). ([Source Code](https://github.com/andris9/mailtrain)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;4170</code>** [Mautic](https://www.mautic.org/) - Mautic is marketing automation software (email, social and more). ([Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;4037</code>** [Listmonk](https://listmonk.app/) - High performance, self-hosted newsletter and mailing list manager with a modern dashboard. ([Source Code](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;3765</code>** [Mail For Good](https://github.com/freeCodeCamp/mail-for-good) `⚠` - Open source email campaign management tool for nonprofits. `BSD-3-Clause` `Javascript`
- **<code>&nbsp;&nbsp;3509</code>** [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - Web user interface to access GNU Mailman. ([Source Code](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;551</code>** [MailyHerald](http://mailyherald.org/) - Self-hosted Mailchimp alternative that you can easily integrate with your site. Helps you send and manage your application mailings. It supports email marketing and conducting the daily stream of notifications you send to your users. ([Source Code](https://github.com/Sology/maily_herald)) `LGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;135</code>** [Sympa](https://www.sympa.org/) - Mailing list manager. `GPL-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;110</code>** [Dada Mail](http://dadamailproject.com/) - Web-based list management system that can be used for announcement lists and/or discussion lists. ([Source Code](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;49</code>** [Mailman](https://www.gnu.org/software/mailman/) - The Gnu mailing list server. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [HyperKitty](https://wiki.list.org/HyperKitty) - Open source Django application to provide a web interface to access GNU Mailman v3 archives. ([Demo](https://lists.mailman3.org/), [Source Code](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Schleuder](https://schleuder.nadir.org/) - GPG-enabled mailing list manager with resending-capabilities. ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [phpList](https://phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. ([Source Code](https://github.com/phpList/)) `AGPL-3.0` `PHP`

#### Webmail clients

- **<code>&nbsp;&nbsp;8237</code>** [Mailpile](https://www.mailpile.is/) - Webmail client with search, filtering, encryption features and more. ([Source Code](https://github.com/mailpile/Mailpile)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;3583</code>** [Roundcube](https://roundcube.net) - Browser-based IMAP client with an application-like user interface. ([Source Code](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;3345</code>** [RainLoop](http://www.rainloop.net/) - Simple, modern and fast webmail with IMAP/SMTP Support and multi accounting. ([Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail)). `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;605</code>** [Cypht](http://cypht.org/index.html) - Feed reader for your email accounts. ([Source Code](https://github.com/jasonmunro/hm3)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;199</code>** [Afterlogic WebMail Lite](http://www.afterlogic.org/webmail-lite) - Fast and easy-to-use webmail front-end for your existing IMAP mail server, Plesk or cPanel. ([Demo](https://lite.afterlogic.com/), [Source Code](https://github.com/afterlogic/webmail-lite)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;126</code>** [MailCare](https://mailcare.io) - Open source disposable email address service. ([Source Code](https://github.com/mailcare/mailcare)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;125</code>** [Isotope Mail](https://blog.marcnuri.com/isotope-mail-client-introduction/) - Microservice based webmail client built with ReactJS and Spring. ([Source Code](https://github.com/manusa/isotope-mail)) `Apache-2.0` `Docker/Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code>** [IMP](https://www.horde.org/apps/imp/) - HORDE application that provides webmail access to IMAP and POP3 accounts. ([Demo](http://demo.horde.org/), [Source Code](https://www.horde.org/download/imp)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [SquirrelMail](http://squirrelmail.org) - Another browser-based IMAP client. ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`

### IRC

**[`^        back to top        ^`](#)**

_[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software_

- **<code>&nbsp;&nbsp;4133</code>** [The Lounge](https://thelounge.github.io/) - Self-hosted web IRC client. ([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/lounge)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1742</code>** [ZNC](http://wiki.znc.in/ZNC) - Advanced IRC bouncer. ([Source Code](https://github.com/znc/znc)) `Apache-2.0` `C++`
- **<code>&nbsp;&nbsp;1077</code>** [Oragono](https://oragono.io) - Modern IRCv3 server written in Go, combining the features of an ircd, a services framework, and a bouncer. ([Source Code](https://github.com/oragono/oragono/)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;803</code>** [InspIRCd](https://www.inspircd.org/) - Modular IRC server written in C++ for Linux, BSD, Windows, and macOS. ([Source Code](https://github.com/inspircd/inspircd)) `GFDL-1.2-only` `C++`
  - **<code>&nbsp;&nbsp;&nbsp;801</code>** [Glowing Bear](https://github.com/glowing-bear/glowing-bear/) - A web frontend for WeeChat. ([Demo](https://www.glowing-bear.org)) `GPL-3.0` `JavaScript`
- **<code>&nbsp;&nbsp;&nbsp;689</code>** [Convos](http://convos.by/) - Always online web IRC client. ([Demo](http://demo.convos.by), [Source Code](http://github.com/nordaaker/convos)) `Artistic-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;570</code>** [Dispatch](https://github.com/khlieng/dispatch) - Self-hosted web IRC client written in Go. ([Demo](https://dispatch.khlieng.com/connect)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;562</code>** [Quassel IRC](http://quassel-irc.org/) - distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. ([Source Code](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;427</code>** [Kiwi IRC](https://kiwiirc.com/) - Responsive web IRC client with theming support. ([Demo](https://kiwiirc.com/nextclient/), [Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;278</code>** [ngircd](https://ngircd.barton.de/) - Free, portable and lightweight Internet Relay Chat server for small or private networks. ([Source Code](https://github.com/ngircd/ngircd)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;11</code>** [Robust IRC](https://robustirc.net/) - RobustIRC is IRC without netsplits. Distributed IRC server, based on RobustSession protocol. ([Source Code](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tiny Tiny IRC](https://tt-rss.org/tt-irc/) - An open source AJAX-powered chat platform with support for IRC ([Source Code](https://git.tt-rss.org/fox/tt-irc)). `GPL-3.0` `PHP/Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Weechat](https://weechat.org/) - Fast, light and extensible chat client. `GPL-3.0` `C`

### SIP

**[`^        back to top        ^`](#)**

_[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software_

- **<code>&nbsp;&nbsp;1246</code>** [Kamailio](http://www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). ([Source Code](https://github.com/kamailio/kamailio)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;989</code>** [FreeSWITCH](https://freeswitch.org/) - Scalable open source cross-platform telephony platform. ([Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;800</code>** [Kazoo](http://2600hz.org/) - KAZOO is an open-source, highly scalable software platform designed to provide carrier-grade VoIP switch functions and features. ([Source Code](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- **<code>&nbsp;&nbsp;&nbsp;751</code>** [Homer](https://www.sipcapture.org/) - Troubleshooting and monitoring VoIP calls. ([Source Code](https://github.com/sipcapture/homer)) `AGPL-3.0` `Angular/C`
- **<code>&nbsp;&nbsp;&nbsp;728</code>** [Routr](https://routr.io) - A lightweight sip proxy, location server, and registrar for a reliable and scalable SIP infrastructure. ([Demo](https://demo.routr.io/login), [Source Code](https://github.com/fonoster/routr)) `MIT` `JavaScript`
- **<code>&nbsp;&nbsp;&nbsp;437</code>** [FusionPBX](https://www.fusionpbx.com/) - Open source project that provides a customizable and flexible web interface to the very powerful and highly scalable multi-platform voice switch called FreeSWITCH. ([Source Code](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;409</code>** [Wazo](http://wazo-platform.org/) - Full-featured IPBX solution built atop Asterisk with integrated Web administration interface and REST-ful API. ([Source Code](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;103</code>** [ASTPP](https://www.astppbilling.org/) - is an Open Source VoIP Billing Solution for Freeswitch. It supports prepaid and postpaid billing with call rating and credit control. It also provides many other features. ([Source Code](https://github.com/iNextrix/ASTPP)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;25</code>** [SipXcom](http://sipxcom.org/) - Open source unified communications system. ([Source Code](https://github.com/sipXcom/sipxecs)) `AGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Freepbx](http://www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk. ([Source Code](http://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - Secure SIP telephony setup with ZRTP encryption. `GPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Asterisk](http://www.asterisk.org/) - Easy to use but advanced IP PBX system, VoIP gateway and conference server. `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [SIP3](https://sip3.io/) - VoIP troubleshooting and monitoring platform. ([Demo](https://demo.sip3.io), [Source Code](https://github.com/sip3io/)) `Apache-2.0` `Kotlin`

### Social Networks and Forums

**[`^        back to top        ^`](#)**

- **<code>&nbsp;31793</code>** [Discourse](http://www.discourse.org/) - Advanced forum / community solution based on Ruby and JS. ([Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)) `GPL-2.0` `Ruby`
- **<code>&nbsp;22151</code>** [Mastodon](https://joinmastodon.org/) - Federated microblogging server, an alternative to GNU social. ([Source Code](https://github.com/tootsuite/mastodon)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;11422</code>** [NodeBB](https://nodebb.org/) - Node.js based forum software built for the modern web. ([Source Code](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;10898</code>** [Flarum](http://flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;5120</code>** [HumHub](https://www.humhub.org/) - Flexible kit for private social networks. ([Source Code](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;4267</code>** [Lemmy](https://dev.lemmy.ml/#/) - A link aggregator / reddit clone for the fediverse. Reddit alternative built in Rust. ([Source Code](https://github.com/dessalines/lemmy)) `AGPL-3.0` `Rust`
- **<code>&nbsp;&nbsp;4199</code>** [Isso](http://posativ.org/isso/) - Lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. ([Source Code](https://github.com/posativ/isso)) `MIT` `Python`
- **<code>&nbsp;&nbsp;3165</code>** [Patchwork](https://github.com/ssbc/patchwork) - Decentralized messaging and sharing app built on top of Secure Scuttlebutt (SSB). `AGPL-3.0-only` `NodeJS`
- **<code>&nbsp;&nbsp;2466</code>** [PixelFed](https://pixelfed.social) - Pixelfed is an open-source, federated platform alternate to Instagram. ([Source Code](http://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP\HTML\Vue`
- **<code>&nbsp;&nbsp;2394</code>** [remark42](https://remark42.com/) - A lightweight and simple comment engine, which doesn't spy on users. It can be embedded into blogs, articles or any other place where readers add comments. ([Demo](https://remark42.com/demo/), [Source Code](https://github.com/umputun/remark)) `MIT` `Go`
- **<code>&nbsp;&nbsp;2240</code>** [Vanilla Forums](https://vanillaforums.org/) - Simple and flexible forum software. ([Source Code](https://github.com/vanilla/vanilla)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;2006</code>** [Bootcamp](http://trybootcamp.vitorfs.com) - Enterprise social network. ([Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
- **<code>&nbsp;&nbsp;1995</code>** [Pump.io](http://pump.io/) - Stream server that does most of what people really want from a social network. ([Source Code](https://github.com/e14n/pump.io)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;1995</code>** [Misago](https://misago-project.org/) - Misago is fully featured modern forum application that is fast, scalable and responsive. ([Source Code](https://github.com/rafalp/Misago)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;1993</code>** [Loomio](https://www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. ([Source Code](https://github.com/loomio/loomio)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;1930</code>** [flaskbb](https://flaskbb.org/) - FlaskBB is forum software written in Python using the microframework Flask. You can easily create new topics, posts and send other users private messages. It also includes basic administration and moderation tools. ([Source Code](https://github.com/sh4nks/flaskbb)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;1520</code>** [Coral](https://coralproject.net/) - A better commenting experience from Vox Media. ([Source Code](https://github.com/coralproject/talk)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;1420</code>** [Elgg](https://elgg.org/) - Powerful open source social networking engine. ([Source Code](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;1366</code>** [Misskey](https://misskey.io/) - Decentralized app-like microblogging server/SNS for the Fediverse, using the ActivityPub protocol like GNU social and Mastodon. ([Source Code](https://github.com/syuilo/misskey)) `AGPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;1356</code>** [twister](http://twister.net.co/) - Fully decentralized P2P microblogging platform leveraging the free software implementations of Bitcoin and BitTorrent protocols. ([Source Code](https://github.com/miguelfreitas/twister-core)) `MIT` `C++`
- **<code>&nbsp;&nbsp;1353</code>** [phpBB](https://www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. ([Source Code](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;1239</code>** [Thredded](https://github.com/thredded/thredded) - Forums, feature-rich and simple. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;1111</code>** [Talkyard](https://www.talkyard.io/) - Create a community, where your users can suggest ideas and get questions answered. And have friendly open-ended discussions and chat (Slack/StackOverflow/Discourse/Reddit/Disqus hybrid). ([Demo](https://www.talkyard.io/forum/latest), [Source Code](https://github.com/debiki/talkyard)) `AGPL-3.0` `Scala`
- **<code>&nbsp;&nbsp;1061</code>** [Movim](https://movim.eu/) - Modern, federated social network based on XMPP, with a fully featured group-chat, subscriptions and microblogging. ([Source Code](https://github.com/movim/movim)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;879</code>** [Friendica](https://friendi.ca/) - Social Communication Server. ([Source Code](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;714</code>** [MyBB](http://www.mybb.com/) - Free, extensible forum software package. ([Source Code](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;653</code>** [OSSN](https://www.opensource-socialnetwork.org/) - Open Source Social Network (OSSN) is a social networking software written in PHP. It allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. ([Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;432</code>** [FluxBB](http://fluxbb.org/) - Fast, light, user-friendly forum software for your website. ([Source Code](https://github.com/fluxbb/fluxbb)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;412</code>** [Scoold](https://scoold.com) - Stack Overflow in a JAR. An enterprise-ready Q&A platform with full-text search, SAML, LDAP integration and social login support. ([Demo](https://live.scoold.com), [Source Code](https://github.com/Erudika/scoold)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;403</code>** [Simple Machines Forum](https://www.simplemachines.org/) - Free, professional grade software package that allows you to set up your own online community within minutes. ([Source Code](https://github.com/SimpleMachines/SMF2.1)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;402</code>** [Satellity](https://satellity.org/) - Yet another open source forum written in Golang, React and PostgreSQL. ([Source Code](https://github.com/satellity/satellity)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;369</code>** [Orange Forum](http://www.goodoldweb.com/) - Orange Forum is an easy to deploy forum that has minimal dependencies and uses very little javascript. ([Source Code](https://github.com/s-gv/orangeforum)) `BSD-3-Clause` `Go`
- **<code>&nbsp;&nbsp;&nbsp;360</code>** [Anahita](https://www.getanahita.com/) - Open Source Social Networking Framework and Platform. ([Source Code](https://github.com/anahitasocial)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;270</code>** [Socialhome](https://socialhome.network) - Federated and decentralized profile builder and social network engine. ([Demo](https://socialhome.network/), [Source Code](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;169</code>** [BuddyPress](https://buddypress.org/about/) - Powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ([Source Code](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;164</code>** [cartulary](https://github.com/daveajones/cartulary) - RSS reader, readability tool, article archiver, microblogger, social graph manager and reading list manager. `CDDL-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;117</code>** [Gosora](https://gosora-project.com/) - Gosora is an ultra-fast and secure forum software written in Go that balances usability with functionality. ([Source Code](https://github.com/Azareal/Gosora)) `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;117</code>** [PPnet](https://github.com/pixelpark/ppnet) - Create and host your own social network. `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;105</code>** [EpochTalk](https://github.com/epochtalk/epochtalk) - Next Generation Forum Software. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;56</code>** [dyu/comments](https://github.com/dyu/comments) - Real-time, markdown-enabled comment engine powered by leveldb. ([Demo](https://dyu.github.io/comments/real-time/)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;54</code>** [Glosa](https://github.com/glosa/glosa-server) - Open source commentary system easy to integrate with static pages. You can import from Disqus. `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;45</code>** [Abilian SBE](https://github.com/abilian/abilian-sbe) - Open Source Collaboration and Social Networking framework and platform. `LGPL-2.1` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;21</code>** [Tokumei](https://tokumei.co/) - Anonymous microblogging platform. ([Source Code](https://gitlab.com/tokumei/tokumei)) `ISC` `rc`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;21</code>** [Zusam](https://zusam.org) - Free and open-source way to self-host private forums for groups of friends or family. ([Demo](https://demo.zusam.org), [Source Code](https://github.com/zusam/zusam)) `AGPL-3.0` `PHP`
  - **<code>&nbsp;&nbsp;&nbsp;&nbsp;12</code>** [rss2twtxt](https://github.com/prologic/rss2twtxt) - An RSS/Atom feed aggregator command-line tool and web service that consumes RSS/Atom and produces twtxt.net feeds for consumption by twtxt clients. ([Demo](https://feeds.twtxt.net)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code>** [twtxt.net](https://twtxt.net) - a Self-Hosted, Twitter™-like Decentralised micro-logging platform. No ads, no tracking, your content, your data. ([Source Code](https://github.com/prologic/twtxt)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Pleroma](https://pleroma.social) - Federated microblogging server, Mastodon, GNU social, & ActivityPub compatible. ([Source Code](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Commento](https://gitlab.com/commento/commento) - Commento is a discussion platform that you can embed on your blog, news articles, and any place where you want your readers to add comments. `MIT` `GO`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ([Source Code](https://github.com/buddycloud)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [GNU social](https://gnu.io/social/) - Social communication software for both public and private communications. ([Source Code](https://notabug.org/diogo/gnu-social)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Hubzilla](https://hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform. ([Source Code](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [bbPress](https://bbpress.org/) - bbPress is forum software with a twist from the creators of WordPress. Easily setup discussion forums inside your WordPress.org powered site. ([Source Code](https://bbpress.trac.wordpress.org/browser/trunk)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [diaspora*](https://diasporafoundation.org/) - Distributed social networking server. ([Demo](https://podupti.me/go.php), [Source Code](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`

### XMPP

**[`^        back to top        ^`](#)**

_[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) software_

#### XMPP Servers

- **<code>&nbsp;&nbsp;4677</code>** [ejabberd](https://www.ejabberd.im/) - XMPP instant messaging server. ([Source Code](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang`
- **<code>&nbsp;&nbsp;2235</code>** [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;1336</code>** [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. ([Source Code](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang`
- **<code>&nbsp;&nbsp;&nbsp;138</code>** [Metronome IM](https://metronome.im/) - Fork of Prosody IM. ([Source Code](https://github.com/maranda/metronome)) `MIT` `Lua`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;57</code>** [Kontalk](http://kontalk.org/) - Kontalk is an Open Source Messenger, similar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server. ([Source Code](https://github.com/kontalk)) `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Prosody IM](http://prosody.im/) - Feature-rich and easy to configure XMPP server. ([Source Code](http://hg.prosody.im/)) `MIT` `Lua`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tigase](http://www.tigase.net/content/tigase-xmpp-server) - XMPP server implementation in Java. `GPL-3.0` `Java`

#### XMPP Web Clients

- **<code>&nbsp;&nbsp;2567</code>** [Converse.js](https://conversejs.org/) - Free and open-source XMPP chat client in your browser. ([Source Code](https://github.com/jcbrand/converse.js)) `MPL-2.0` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code>** [JSXC](https://jsxc.org) - Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. ([Source Code](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Salut à Toi](http://www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralized communication tool. ([Source Code](http://repos.goffi.org/sat)) `AGPL-3.0` `Python`
  - **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Libervia](http://wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi. ([Source Code](http://repos.goffi.org/libervia)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Candy](http://candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ([Source Code](https://github.com/candy-chat/candy)) `MIT` `Javascript`

## Conference Management

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;5743</code>** [BigBlueButton](https://bigbluebutton.org/) - Supports real-time sharing of audio, video, slides (with whiteboard controls), chat, and the screen. Instructors can engage remote students with polling, emojis, and breakout rooms. ([Demo](https://demo.bigbluebutton.org/gl), [Source Code](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;1102</code>** [indico](https://getindico.io/) - A feature-rich event management system, made @ CERN, the place where the Web was born. ([Demo](https://sandbox.getindico.io/), [Source Code](https://github.com/indico/indico)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;636</code>** [osem](http://osem.io/) - Event management tailored to free Software conferences. ([Demo](http://demo.osem.io/), [Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;532</code>** [OpenCFP](https://github.com/opencfp/opencfp) - OpenCFP is a PHP-based conference talk submission system. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;325</code>** [pretalx](https://pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. ([Source Code](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;270</code>** [OpenConferenceWare](http://openconferenceware.org/) - An open source web application for supporting conference-like events. This customizable, general-purpose platform provides proposals, sessions, schedules, tracks, user profiles. ([Source Code](https://github.com/osbridge/openconferenceware)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;192</code>** [Open Conference Systems (OCS)](https://pkp.sfu.ca/ocs/) - is a free Web publishing tool that will create a complete Web presence for your scholarly conference. ([Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [Source Code](https://github.com/pkp/ocs)) `GPL-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Conference Organizing Distribution (COD)](http://usecod.com/) - Create conference and event websites built on top of Drupal. ([Source Code](http://cgit.drupalcode.org/cod)) `GPL-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [frab](https://frab.github.io/frab/) - web-based conference planning and management system. It helps to collect submissions, to manage talks and speakers and to create a schedule. ([Source Code](https://github.com/frab/frab)) `MIT` `Ruby`

## Content Management Systems (CMS)

**[`^        back to top        ^`](#)**

_CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs. See also [Blogging Platforms](#blogging-platforms) and [Static Site Generators](#static-site-generators)_

- **<code>&nbsp;30569</code>** [Strapi](https://strapi.io/) - The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort. ([Source Code](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- **<code>&nbsp;14446</code>** [WordPress](https://wordpress.org/) - World's most-used blogging and CMS engine. ([Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`
- **<code>&nbsp;10305</code>** [october](http://octobercms.com/) - Free, open-source, self-hosted CMS platform. ([Source Code](https://github.com/octobercms/october)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;9486</code>** [Wagtail](https://wagtail.io/) - Django content management system focused on flexibility and user experience. ([Source Code](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;7526</code>** [Directus](http://getdirectus.com/) - Directus is a powerful and intuitive headless CMS for managing SQL databases with custom architectures. Built around a robust and extensible API, this decoupled content management framework is perfect for websites, apps, or multi-client projects. ([Source Code](https://github.com/directus/directus)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;5389</code>** [Pagekit](https://pagekit.com/) - New modern CMS to create and share. ([Source Code](https://github.com/pagekit/pagekit)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;4758</code>** [Cockpit](http://getcockpit.com) - Simple Content Platform to manage any structured content. ([Source Code](https://github.com/agentejo/cockpit)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;4084</code>** [Bolt CMS](https://bolt.cm/) - Open source Content Management Tool, which strives to be as simple and straightforward as possible. ([Demo](https://try.bolt.cm/), [Source Code](https://github.com/bolt/bolt)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;3633</code>** [Joomla!](https://www.joomla.org/) - Advanced Content Management System (CMS). ([Source Code](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;3329</code>** [Pico](http://picocms.org/) - Stupidly simple, blazing fast, flat file CMS. ([Source Code](https://github.com/picocms/Pico)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;3315</code>** [Apostrophe](http://apostrophecms.org/) - Node.js CMS with a focus on extensible in-context editing tools. ([Demo](http://demo.apostrophecms.org/), [Source Code](https://github.com/punkave/apostrophe)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;3132</code>** [Umbraco](https://umbraco.com/) - The friendly CMS. Free and open source with an amazing community. ([Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- **<code>&nbsp;&nbsp;2851</code>** [KeystoneJS](http://keystonejs.com/) - CMS and Web Application Platform. ([Demo](http://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1943</code>** [Pimcore](https://www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ([Source Code](https://github.com/pimcore/pimcore)) `GPL-3.0-or-later` `PHP`
- **<code>&nbsp;&nbsp;1754</code>** [Publify](https://publify.github.io/) - Simple but full featured web publishing software. ([Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;1752</code>** [WriteFreely](https://writefreely.org) - Writing software for starting a minimalist, federated blog — or an entire community. ([Source Code](https://github.com/writeas/writefreely)) `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;1266</code>** [Squidex](http://squidex.io) - Headless CMS, based on MongoDB, CQRS and Event Sourcing. ([Demo](http://cloud.squidex.io), [Source Code](https://github.com/Squidex/squidex)) `MIT` `.NET`
- **<code>&nbsp;&nbsp;1195</code>** [MODX](http://modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ([Source Code](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;763</code>** [Backdrop CMS](https://backdropcms.org/) - Comprehensive CMS for small to medium sized businesses and non-profits. ([Source Code](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;736</code>** [TYPO3](https://typo3.org/) - Powerful and advanced CMS with a large community. ([Source Code](https://github.com/TYPO3/TYPO3.CMS)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;636</code>** [Concrete 5 CMS](http://www.concrete5.org/) - Open source content management system. ([Source Code](https://github.com/concrete5/concrete5)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;632</code>** [ProcessWire](https://processwire.com/) - ProcessWire is an open source content management system (CMS) and web application framework aimed at the needs of designers, developers and their clients. ([Source Code](https://github.com/ryancramerdesign/ProcessWire)) `MPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;548</code>** [Textpattern](http://textpattern.com/) - Flexible, elegant and easy-to-use CMS. ([Demo](http://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;435</code>** [eLabFTW](http://www.elabftw.net) - Online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators…. ([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;392</code>** [PropertyWebBuilder](http://propertywebbuilder.com) - Ultimate Ruby on Rails engine for creating real estate websites. ([Demo](https://propertywebbuilder.herokuapp.com), [Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;359</code>** [Roadiz](https://www.roadiz.io/) -  Modern CMS based on a node system which can handle many types of services. ([Source Code](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;340</code>** [Omeka](http://omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts. ([Demo](http://omeka.org/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;329</code>** [Expressa](https://github.com/thomas4019/expressa) - Content Management System for powering database driven websites using JSON schemas. Provides permission management and automatic REST APIs. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;326</code>** [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. ([Source Code](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;298</code>** [WonderCMS](http://www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008. ([Demo](https://www.wondercms.com/demo), [Source Code](https://github.com/robiso/wondercms)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;278</code>** [CouchCMS](http://www.couchcms.com/) - Simple Open-Source CMS for designers. ([Source Code](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;258</code>** [Subrion](http://www.subrion.org) - Subrion is a free open source content management system that allows you to build websites for any purpose. Yes, from blog to corporate mega portal. ([Demo](http://demos.subrion.com), [Source Code](https://github.com/intelliants/subrion)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;258</code>** [REDAXO](https://www.redaxo.org) - Simple, flexible and useful content management system (documentation only available in German). ([Source Code](https://github.com/redaxo/redaxo)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;238</code>** [Redaxscript](https://redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL. ([Demo](https://demo.redaxscript.com/login), [Source Code](https://github.com/redaxmedia/redaxscript)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;189</code>** [BigTree CMS](https://www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ([Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;159</code>** [Contao](https://contao.org/) - Contao is a powerful open source CMS that allows you to create professional websites and scalable web applications. ([Source Code](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;139</code>** [b2evolution CMS](https://b2evolution.net/) - The most integrated CMS ever: b2evolution includes everything you need to build websites for publishing, sharing and interacting with your community. ([Demo](https://demo.b2evolution.net), [Source Code](https://github.com/b2evolution/b2evolution)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;117</code>** [Typemill](https://typemill.net/) - Author-friendly flat-file-cms with a visual markdown editor based on vue.js. ([Source Code](https://github.com/typemill/typemill)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;81</code>** [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - The open source Enterprise Content Management software that handles any type of content, allowing users to easily share and collaborate on content. ([Source Code](https://hub.alfresco.com/t5/alfresco-content-services-hub/project-overview-repository/ba-p/290502)) `LGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;20</code>** [Neos](https://www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ([Source Code](https://git.typo3.org/Packages/TYPO3.Neos.git)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Noosfero](https://gitlab.com/noosfero/noosfero) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Drupal](https://www.drupal.org/) - Advanced open source content management platform. ([Source Code](http://cgit.drupalcode.org/drupal)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [CMS Made Simple](http://www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [SPIP](http://www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors. ([Source Code](https://core.spip.net/projects/spip/repository)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [SilverStripe](https://www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying. ([Demo](http://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Plone](https://plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `ZPL-2.0` `Python`

### Recipe management

- **<code>&nbsp;&nbsp;&nbsp;424</code>** [OpenEats](https://github.com/open-eats/OpenEats) - Recipe management site that allows users to create, store, share and rate recipes, create grocery lists, and more. ([Demo](https://open-eats.github.io/)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;292</code>** [Recipes](https://github.com/vabene1111/recipes) - Recipes is a Django application to manage, tag and search recipes using either built-in models or external storage providers hosting PDF's, Images or other files. `MIT` `Python`

### E-commerce

- **<code>&nbsp;10739</code>** [Spree Commerce](https://spreecommerce.org) - Spree is a complete, modular & API-driven open source e-commerce solution for Ruby on Rails. ([Demo](http://new-ux.spreecommerce.org/), [Source Code](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- **<code>&nbsp;&nbsp;9445</code>** [Saleor](http://getsaleor.com/) - Django based open-sourced e-commerce storefront. ([Demo](https://demo.getsaleor.com/), [Source Code](https://github.com/mirumee/saleor)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;9066</code>** [Magento](https://magento.com/) - Leading provider of open omnichannel innovation. ([Demo](https://magento.com/schedule-a-demo), [Source Code](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- **<code>&nbsp;&nbsp;6488</code>** [WooCommerce](https://www.woothemes.com/woocommerce/) - WordPress based e-commerce solution. ([Source Code](https://github.com/woothemes/woocommerce)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;6047</code>** [Sylius](http://sylius.org/) - Symfony2 powered open source full-stack platform for eCommerce. ([Demo](http://sylius.org/demo), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;5744</code>** [OpenCart](https://www.opencart.com) - Free open source shopping cart solution. ([Source Code](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;5210</code>** [PrestaShop](https://www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution. ([Demo](http://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- **<code>&nbsp;&nbsp;3026</code>** [Bagisto](https://bagisto.com/en/) - Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features. ([Demo](https://demo.bagisto.com/), [Source Code](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;2992</code>** [Attendize](https://www.attendize.com/) - Ticket selling and event management platform. ([Source Code](https://github.com/attendize/attendize)) `AAL` `PHP`
- **<code>&nbsp;&nbsp;2036</code>** [Sharetribe](https://www.sharetribe.com) - An open source platform to create your own peer-to-peer marketplace, also available with SaaS model. ([Source Code](https://github.com/sharetribe/sharetribe)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;1988</code>** [Open Source POS](https://www.opensourcepos.org/) - Open Source Point of Sale is a web based point of sale system. ([Source Code](https://github.com/opensourcepos/opensourcepos)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;1787</code>** [Microweber](https://microweber.com/) - Drag and Drop CMS and online shop. ([Demo](http://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;1411</code>** [Shuup](https://www.shuup.com/) - Django powered fully customizable open source e-commerce framework for small and large sites. ([Source Code](https://github.com/shuup/shuup)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1079</code>** [Shopware Community Edition](https://shopware.com/community/) - PHP based open source e-commerce software made in Germany. ([Demo](https://www.shopware.com/en/test-demo/), [Source Code](https://github.com/shopware/platform)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;890</code>** [OpenBazaar](https://www.openbazaar.org) - Decentralized marketplace using cryptocurrency. ([Source Code](https://github.com/openbazaar/openbazaar-go)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;743</code>** [Thelia](http://thelia.net/) - Thelia is an open source and flexible e-commerce solution. ([Demo](http://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;631</code>** [Open Food Network](https://openfoodnetwork.org/) - Online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. ([Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;355</code>** [Drupal Commerce](https://drupalcommerce.org) - Drupal Commerce is a popular e-commerce module for Drupal CMS, with support for dozens of payment, shipping, and shopping related modules. ([Source Code](https://github.com/drupalcommerce/commerce)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;263</code>** [Open Classifieds](http://open-classifieds.com/) - Free open-source, self-hosted CMS for classifieds sites. ([Source Code](https://github.com/open-classifieds/openclassifieds2)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;185</code>** [OXID eShop](http://oxidforge.org) - OXID eShop is a flexible open source e-commerce software with a wide range of functionalities. ([Demo](http://demoshop.oxid-esales.com/community-edition/), [Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;178</code>** [CoreShop](https://www.coreshop.org) - CoreShop is a e-commerce plugin for Pimcore. ([Source Code](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Pretix](https://pretix.eu/) - Django based ticket sales platform for events. ([Source Code](https://github.com/pretix)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Reaction Commerce](https://reactioncommerce.com/) - Customizable, real-time reactive, JavaScript commerce platform. ([Source Code](https://github.com/reactioncommerce/reaction)) `GPL-3.0` `Nodejs`

## DNS

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#dns_

- **<code>&nbsp;&nbsp;6724</code>** [CoreDNS](https://coredns.io/) - Plugin driven DNS Server with support for proxying to Google's DNS-over-HTTPS. ([Source Code](https://github.com/coredns/coredns)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;1363</code>** [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - Local ad blocker. Like Pi-hole but local and using your operating system. ([Source Code](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Bash`
- **<code>&nbsp;&nbsp;&nbsp;687</code>** [nsupdate.info](https://www.nsupdate.info/) - nsupdate.info is a dynamic DNS service. ([Demo](https://www.nsupdate.info/account/register/), [Source Code](https://github.com/nsupdate-info/nsupdate.info)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;123</code>** [SPF Toolbox](http://spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. ([Source Code](https://github.com/charlesabarnes/SPFtoolbox)) `MIT` `PHP`

## Document Management

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;7118</code>** [Paperless](https://github.com/danielquinn/paperless) - Scan, index, and archive all of your paper documents. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;779</code>** [Papermerge](https://www.papermerge.com) - Open Source Document Management System focused on scanned documents (electronic archives). Features file browsing in similar way to dropbox/google drive. OCR, full text search, text overlay/selection. ([Source Code](https://github.com/ciur/papermerge)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;660</code>** [Teedy](https://teedy.io/) - (Ex SismicsDocs) Lightweight document management system packed with all the features you can expect from big expensive solutions. ([Source Code](https://github.com/sismics/docs)) `GPL-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;218</code>** [CaseBox](https://www.casebox.org) - Manage all your organization's information in one system. ([Source Code](https://github.com/KETSE/casebox)) `AGPL-3.0` `PHP/Java`
- **<code>&nbsp;&nbsp;&nbsp;176</code>** [Mayan EDMS](http://www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features. ([Source Code](https://gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;122</code>** [Docspell](https://docspell.org) - Auo-tagging document organizer and archive. ([Source Code](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;93</code>** [DOCAT](https://github.com/randombenj/docat) - Host your docs. Simple. Versioned. Fancy. `MIT` `Python/docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;50</code>** [EdPaper](https://github.com/Edraens/EdPaper) - PDF organizer with users management. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;12</code>** [EveryDocs](https://github.com/jonashellmann/everydocs-core/) - A simple Document Management System for private use with basic functionality to organize your documents digitally. `GPL-3.0` `Ruby`

## E-books and Integrated Library Systems (ILS)

**[`^        back to top        ^`](#)**

_Some [Content Management System](#content-management-systems-cms) and [Archiving and Digital Preservation](#archiving-and-digital-preservation-dp) solutions also overlap with library and institutional repository software._

### Personal e-book management software.

  - **<code>&nbsp;&nbsp;3861</code>** [Calibre Web](https://github.com/janeczku/calibre-web) - Web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database. `GPL-3.0` `Python`
  - **<code>&nbsp;&nbsp;1074</code>** [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server) - Lightweight e-book server alternative to Calibre content server or Calibre2OPDS. ([Demo](http://cops-demo.slucas.fr/index.php), [Source Code](https://github.com/seblucas/cops)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;473</code>** [Komga](https://komga.org) - Media server for comics/mangas/BDs with API and OPDS support, a modern web interface for exploring your libraries, as well as a web reader. ([Source Code](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- **<code>&nbsp;&nbsp;&nbsp;391</code>** [Mango](https://github.com/hkalexling/Mango) - Manga server and web reader with a built-in MangaDex downloader. `MIT` `Crystal`
  - **<code>&nbsp;&nbsp;&nbsp;311</code>** [BicBucStriim](http://projekte.textmulch.de/bicbucstriim/) - Provides web-based access to your Calibre Library's e-book collection. ([Source Code](https://github.com/rvolz/BicBucStriim)) `MIT` `PHP`
  - **<code>&nbsp;&nbsp;&nbsp;122</code>** [The Epube](https://tt-rss.org/the-epube) - Self-hosted web EPUB reader using EPUB.js, Bootstrap, and Calibre. ([Source Code](https://git.tt-rss.org/fox/the-epube)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Calibre](https://calibre-ebook.com/) - E-book library manager that can view, convert, and catalog e-books in most of the major e-book formats and provides a built-in Web server for remote clients. ([Demo](https://calibre-ebook.com/demo), [Source Code](https://launchpad.net/calibre)) `GPL-3.0` `Python`

### Enterprise-class library management software.

- **<code>&nbsp;&nbsp;&nbsp;342</code>** [Koha](https://koha-community.org/) - Enterprise-class ILS with modules for acquisitions, circulation, cataloging, label printing, offline circulation for when Internet access is not available, and much more. ([Demo](https://koha-community.org/demo/), [Source Code](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;83</code>** [Evergreen](https://evergreen-ils.org) - Highly-scalable software for libraries that helps library patrons find library materials, and helps libraries manage, catalog, and circulate those materials. ([Source Code](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;23</code>** [RERO ILS](https://rero21.ch/) - Large-scale ILS that can be run as a service with consortial features, intended primarily for library networks. Includes most standard modules (circulation, acquisitions, cataloging,...) and a web-based public and professional interface. ([Demo](https://ils.test.rero.ch/), [Source Code](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Other`

### Institutional repository and digital library software.

- **<code>&nbsp;&nbsp;&nbsp;517</code>** [DSpace](http://dspace.org/) - Turnkey repository application providing durable access to digital resources. ([Source Code](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- **<code>&nbsp;&nbsp;&nbsp;137</code>** [Fedora Commons Repository](https://fedorarepository.org/) - Robust and modular repository system for the management and dissemination of digital content especially suited for digital libraries and archives, both for access and preservation. ([Source Code](https://github.com/fcrepo4/fcrepo4)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;125</code>** [Samvera Hyrax](https://samvera.org/) - Front-end for the Samvera framework, which itself is a Ruby on Rails application for browsing and managing Fedora-based digital repositories. ([Source Code](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;55</code>** [EPrints](https://www.eprints.org/) - Digital document management system with a flexible metadata and workflow model primarily aimed at academic institutions. ([Demo](http://demoprints.eprints.org/), [Source Code](https://github.com/eprints/eprints)) `GPL-3.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code>** [Islandora](https://islandora.ca/) - Drupal module for browsing and managing Fedora-based digital repositories. ([Source Code](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`

## Federated Identity/Authentication

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#identity-management_

## Feed Readers

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;7770</code>** [Winds](https://getstream.io/winds/) `⚠` - Open source and beautiful RSS reader built using React/Redux/Sails/Node and Stream. It showcases personalized feeds powered by the Stream API. ([Demo](https://winds.getstream.io/), [Source Code](https://github.com/GetStream/Winds)) `BSD-3-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;5610</code>** [NewsBlur](http://www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. ([Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- **<code>&nbsp;&nbsp;3228</code>** [Stringer](https://github.com/swanson/stringer) - Work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;2653</code>** [FreshRSS](http://freshrss.org/) - Self-hostable RSS feed aggregator. ([Demo](http://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Clients](https://github.com/Alkarex/EasyRSS)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;2356</code>** [Miniflux](https://miniflux.net/) - Miniflux 2 is a minimalist and open source news reader, written in Go and PostgreSQL. ([Source Code](https://github.com/miniflux/miniflux)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;1937</code>** [Selfoss](http://selfoss.aditu.de/) - New multipurpose rss reader, live stream, mashup, aggregation web application. ([Source Code](https://github.com/SSilence/selfoss)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1749</code>** [CommaFeed](https://www.commafeed.com/) - Google Reader inspired self-hosted RSS reader. ([Source Code](https://github.com/Athou/commafeed)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;517</code>** [FeedHQ](https://feedhq.org/) - FeedHQ is a web-based feed reader. ([Source Code](https://github.com/feedhq/feedhq)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;337</code>** [Sismics Reader](http://sismics.com/reader/) - Free and open source feeds reader, including all major Google Reader features. ([Demo](https://www.sismics.com/reader/#!/demo), [Source Code](https://github.com/sismics/reader)) `GPL-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;310</code>** [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;244</code>** [Feedbin](https://feedbin.com/) - Simple, fast and nice looking RSS reader. ([Source Code](https://github.com/feedbin/feedbin)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;244</code>** [Kriss Feed](http://tontof.net/kriss/feed/) - Simple and smart (or stupid) feed reader. ([Demo](http://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed)) `CC0-1.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;224</code>** [Leselys](https://github.com/socketubs/leselys) - Your very elegant RSS reader. `AGPL-3.0` `Python`
  - **<code>&nbsp;&nbsp;&nbsp;193</code>** [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - Mobile webapp for Tiny Tiny RSS. `AGPL-3.0` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;163</code>** [Reader-Self](http://readerself.com/) - Self-hosted rss reader (php / mysql or sqlite) - Google Reader alternative. ([Source Code](https://github.com/readerself/readerself)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;157</code>** [Leed](https://github.com/LeedRSS/Leed) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. ([Source Code](https://github.com/ldleman/Leed)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;133</code>** [Moonmoon](http://moonmoon.org/) - simple feed aggregator (planet like): it only aggregates feeds and spits them out in one single page. ([Source Code](https://github.com/mauricesvay/moonmoon)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;69</code>** [JARR](http://1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader (fork of Newspipe). ([Demo](https://jarr.info/login?next=%2F), [Source Code](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Python`
  - **<code>&nbsp;&nbsp;&nbsp;&nbsp;45</code>** [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - More features for Tiny Tiny RSS. ([Source Code](https://github.com/nhoening/gritttt-rss)) `BSD-2-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;43</code>** [Temboz](https://github.com/fazalmajid/temboz) - Two-column feed reader emphasizing filtering capabilities to manage information overload. `MIT` `Python`
  - **<code>&nbsp;&nbsp;&nbsp;&nbsp;43</code>** [ttrss-reader](https://github.com/kucrut/ttrss-reader) - Light and responsive client for TTRSS. `GPL-2.0` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;40</code>** [reader](https://github.com/lemon24/reader) - A Python feed reader web app and library (so you can use it to build your own), with only standard library and pure-Python dependencies. `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;29</code>** [Lite-Reader](https://github.com/cubny/lite-reader) - Read your feeds on your own machine with a simple and lite application. ([Demo](http://cubny.com/lite-reader/)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code>** [newsdash](https://github.com/buzz/newsdash) - A news dashboard inspired by iGoogle and Netvibes. `AGPL-3.0` `NodeJS`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tiny Tiny RSS](https://tt-rss.org) - Open source web-based news feed (RSS/Atom) reader and aggregator. ([Demo](http://framanews.org/), [Source Code](https://git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Newspipe](https://git.sr.ht/~cedric/newspipe) - Newspipe is a web news reader. ([Demo](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`

_RSS/Atom automation_

- **<code>&nbsp;&nbsp;2862</code>** [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one. `Unlicense` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;196</code>** [PolitePol](https://github.com/taroved/pol) - Online tool for creation of RSS feeds for any web page. ([Demo](http://politepol.com)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;148</code>** [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;107</code>** [RSS2EMail](https://github.com/rss2email/rss2email) - Fetches RSS/Atom-feeds and pushes new Content to any email-receiver, supports OPML. `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;51</code>** [RSS Fulltext Proxy](https://github.com/Kombustor/rss-fulltext-proxy) - Mirrors RSS feeds to return the full content of the items, extracted from the website. `MIT` `NodeJS`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;51</code>** [Feedpushr](https://github.com/ncarlier/feedpushr) - Powerful RSS aggregator, able to transform and send articles to many outputs. Single binary, extensible with plugins. `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;19</code>** [RSS Merger](https://github.com/taophp/rss-merger) - PHP script which will take multiple RSS / Atom feeds as input and merge them into a single RSS feed. `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Full-Text RSS](https://fivefilters.org/content-only) - Extract article content from news sites and blogs and convert RSS feeds that contain only extracts of stories to full-text feeds. Developed by FiveFilters.org. ([Source Code](https://bitbucket.org/fivefilters/full-text-rss)) `GPL-3.0` `PHP`


## File Sharing and Synchronization

**[`^        back to top        ^`](#)**

_Some [Groupware](#groupware) solutions also feature file sharing and synchronization._

#### Distributed filesystems

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#distributed-filesystems_

#### File transfer/synchronization

- **<code>&nbsp;&nbsp;8128</code>** [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Source Code](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- **<code>&nbsp;&nbsp;7246</code>** [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ([Source Code](https://github.com/owncloud/core), [Clients](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;4480</code>** [SparkleShare](http://sparkleshare.org/) - Self hosted, instant, secure file sync. ([Source Code](https://github.com/hbons/SparkleShare)) `GPL-3.0` `C#`
- **<code>&nbsp;&nbsp;4009</code>** [Kinto](https://kinto.readthedocs.org) - Kinto is a minimalist JSON storage service with synchronisation and sharing abilities. ([Source Code](https://github.com/Kinto)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;1661</code>** [myDrive](https://github.com/subnub/myDrive) - Fully featured online storage solution, upload/download files, photo/video viewer, and more, all through the web client. ([Demo](https://mydrive-demo.herokuapp.com/)) `GPL-3.0` `Node.js`
- **<code>&nbsp;&nbsp;1530</code>** [Syncany](https://www.syncany.org/) - Secure file sync software for arbitrary storage backends, an open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage. `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;895</code>** [Pydio](https://pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers. ([Source Code](https://github.com/pydio/pydio-core)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;140</code>** [Nextcloud](https://nextcloud.com/) - Access and share your files, calendars, contacts, mail and [more](https://apps.nextcloud.com/) from any device, on your terms. ([Demo](https://demo.nextcloud.com/), [Source Code](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Git Annex](https://git-annex.branchable.com/) - File synchronization between computers, servers, external drives. ([Source Code](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Samba](https://www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol. ([Source Code](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [OpenSSH/SFTP](http://www.openssh.com/) - Secure File Transfer Program. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD-2-Clause` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. `GPL-3.0` `OCaml`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Z-Push](http://z-push.org/) - Implementation of Microsoft’s [ActiveSync](https://en.wikipedia.org/wiki/ActiveSync) protocol. ([Source Code](https://stash.z-hub.io/projects/ZP/repos/z-push)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Syncthing](https://syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ([Source Code](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go`

#### Peer-to-peer filesharing

- **<code>&nbsp;22799</code>** [bittorrent-tracker](https://webtorrent.io/) - Simple, robust, BitTorrent tracker (client and server) implementation. ([Source Code](https://github.com/feross/bittorrent-tracker)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;4902</code>** [Transmission](https://transmissionbt.com/) - Fast, easy, Free Bittorrent client. ([Source Code](https://github.com/transmission/transmission)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;4590</code>** [cloud-torrent](https://github.com/jpillora/cloud-torrent) - Torrent Web Client with HTTP retrievable or streamable downloaded files. `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;3148</code>** [FilePizza](http://file.pizza/) - Peer-to-peer file transfers in your browser. ([Source Code](https://github.com/kern/filepizza)) `BSD-3-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;2612</code>** [instant.io](https://github.com/feross/instant.io) - Streaming file transfer over WebTorrent. ([Demo](https://instant.io)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;2482</code>** [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - Search engine that indexes all popular torrent sites. `MIT` `Elixir`
- **<code>&nbsp;&nbsp;2326</code>** [Magnetico](https://github.com/boramalper/magnetico) - Magnetico is the first autonomous (self-hosted) BitTorrent DHT search engine suite that is designed for end-users. `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1131</code>** [peerflix-server](https://github.com/asapach/peerflix-server) - Downloads torrent files and provides a direct link download or a direct link stream. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;167</code>** [rartracker](https://github.com/swetorrentking/rartracker) - Complete private bittorrent tracker. `WTFPL` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;65</code>** [qBittorrent](https://www.qbittorrent.org/) - Free cross-platform bittorrent client with a feature rich Web UI for remote access. ([Source Code](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;28</code>** [Dat Project](https://datproject.org) - Powerful decentralized file sharing applications built from a large ecosystem of modules. ([Source Code](https://github.com/datproject)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Opentracker](http://erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router. ([Source Code](http://erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Send](https://gitlab.com/timvisee/send) - A file sharing experiment which allows you to send encrypted files to other users. ([Clients](https://gitlab.com/timvisee/send/-/tree/master/android)) `MPL-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Torrents.csv](https://gitlab.com/dessalines/torrents.csv) - A self-hostable torrent search engine. `GPL-3.0` `Rust`

#### Object storage/file servers

- **<code>&nbsp;&nbsp;1091</code>** [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer, an open-source Node.js implementation of a server handling the Amazon S3 protocol. ([Source Code](https://github.com/scality/S3)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Minio](https://minio.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. ([Source Code](https://github.com/minio/minio)) `Apache-2.0` `Go`

#### Single-click/drag-n-drop upload

- **<code>&nbsp;&nbsp;4170</code>** [OnionShare](https://github.com/micahflee/onionshare) - Securely and anonymously share a file of any size. `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;1515</code>** [droppy](https://github.com/silverwind/droppy) - droppy is a self-hosted cloud server with an interface similar to desktop file managers and has capabilities to edit files on-the-fly as well as view and playback media directly in the browser. `BSD-2-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;1431</code>** [YouTransfer](http://www.youtransfer.io) - YouTransfer is a simple but elegant self-hosted file transfer and sharing solution. ([Demo](http://demo.youtransfer.io/), [Source Code](https://github.com/remie/YouTransfer)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;1061</code>** [ipfs.pics](https://github.com/ipfspics/server) - ipfs.pics is a distributed image hosting website. `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;915</code>** [linx-server](https://github.com/andreimarcu/linx-server) - Simple file sharing and pastebin with API, auto-expiry, deletion keys, and web seed support. ([Demo](https://demo.linx-server.net/)) `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;682</code>** [Coquelicot](https://coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy. ([Source Code](https://coquelicot.potager.org/gitweb/?p=coquelicot.git)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;682</code>** [Up1](https://github.com/Upload/Up1) - Client-side Encrypted Image Host. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;619</code>** [PsiTransfer](https://github.com/psi-4ward/psitransfer) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. `BSD-2-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;598</code>** [ProjectSend](http://www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ([Source Code](https://github.com/ignacionelson/ProjectSend)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;569</code>** [Plik](https://github.com/root-gg/plik) - Plik is a scalable and friendly temporary file upload system. ([Demo](https://plik.root.gg/)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;531</code>** [PictShare](https://www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ([Source Code](https://github.com/chrisiaut/pictshare)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;491</code>** [Pomf](https://github.com/Pomf/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;491</code>** [Uguu](https://uguu.se/) - Stores files and deletes after X amount of time. ([Source Code](https://github.com/nokonoko/uguu)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;282</code>** [BoZoN](https://github.com/broncowdd/BoZoN) - Minimalist Drag and drop file sharing app. `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;245</code>** [XBackBone](https://github.com/SergiX44/XBackBone) - A simple, fast and lightweight file manager with instant sharing tools integration, like ShareX (a free and open-source screenshot utility for Windows). `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;185</code>** [goploader](https://gpldr.in/) - Easy file sharing with server-side encryption, curl/httpie/wget compliant. ([Source Code](https://github.com/Depado/goploader)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;164</code>** [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image. `AGPL-3.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;122</code>** [imgpush](https://github.com/hauxir/imgpush) - imgpush is a self-hosted file upload service that can easily be integrated into other webapps. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;113</code>** [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter is a self-hosted software that allows you to easily share files over the Internet. ([Demo](http://fileshelter.demo.poupon.io/)) `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;108</code>** [Sharry](https://github.com/eikek/sharry) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. `GPL-3.0` `Scala/Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;56</code>** [fibridge](https://github.com/anderspitman/fibridge-proxy-rs) - Stream huge files out of your browser without having to upload. `MIT` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;49</code>** [uPste](https://u.pste.pw) - Private file hosting application with an emphasis on serving technology communities. ([Source Code](https://github.com/TheReverend403/uPste)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;27</code>** [Share](https://github.com/MrDemonWolf/share) - Simple yet advanced uploader - upload files, images and text with moderation tools for admins. Can be used for friends and family or just for you. Integration with ShareX and more. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;23</code>** [Files Sharing](https://github.com/axeloz/filesharing) - Open Source and self-hosted files sharing application based on unique and temporary links. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [elixire](https://elixi.re) - Simple yet advanced screenshot uploading and link shortening service. ([Source Code](https://gitlab.com/elixire/elixire), [Clients](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Jirafeau](https://gitlab.com/mojo42/Jirafeau) - Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it. ([Demo](http://jirafeau.net/)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [lufi](https://framagit.org/fiat-tux/hat-softwares/lufi) - Let's Upload that FIle, client-side encrypted. ([Demo](https://demo.lufi.io), [Source Code](https://framagit.org/fiat-tux/hat-softwares/lufi/tree/master)) `AGPL-3.0` `Perl`

#### Command-line file upload

- **<code>&nbsp;&nbsp;9908</code>** [transfer.sh](https://transfer.sh) - Easy file sharing from the command line. ([Source Code](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;25</code>** [Beauties](https://github.com/dsx/beauties) - Minimalist file sharing written in Go, to be used primarily from Unix shell (e.g. with curl). Can be built as a Debian package for easy install. `MIT` `Go`

#### Web based file managers

- **<code>&nbsp;&nbsp;4080</code>** [h5ai](https://larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview. ([Demo](https://larsjung.de/h5ai/demo/), [Source Code](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;3606</code>** [Filestash](https://www.filestash.app/) - A web file manager that lets you manage your data anywhere it is located: FTP, SFTP, WebDAV, Git, S3, Minio, Dropbox, or Google Drive . ([Demo](https://demo.filestash.app/), [Source Code](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;1120</code>** [DirectoryLister](http://www.directorylister.com/) - Simple PHP based directory lister that lists a directory and all it's sub-directories and allows you to navigate there within. ([Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;340</code>** [Gossa](https://github.com/pldubouilh/gossa) - Gossa is a light and simple webserver for your files. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;202</code>** [IFM](https://github.com/misterunknown/ifm) - Single script file manager. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;193</code>** [Encode Explorer](http://encode-explorer.siineiolekala.net/) - Encode Explorer is a single page file browser, it is simple and functional. ([Demo](http://encode-explorer.siineiolekala.net/explorer/index.php), [Source Code](https://github.com/marekrei/encode-explorer)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;158</code>** [s3server](https://github.com/jessfraz/s3server) - Simple HTTP interface to index and browse files in a public S3 or Google Cloud Storage bucket. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;85</code>** [goBrowser](https://github.com/xataz/gobrowser) - Simple http file browser. `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;31</code>** [Surfer](https://github.com/nebulade/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code>** [TagSpaces](https://www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud. ([Demo](http://demo.tagspaces.org), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ResourceSpace](https://www.resourcespace.com) - ResourceSpace open source digital asset management software is the simple, fast, and free way to organise your digital assets. ([Demo](https://www.resourcespace.com/trial), [Source Code](https://www.resourcespace.com/svn)) `Other` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Apaxy](https://oupala.github.io/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ([Source Code](https://github.com/AdamWhitcroft/Apaxy)) `Unlicense` `HTML`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [explorer](https://soyuka.github.io/explorer/) - Highly-configurable directory listing made with nodejs. ([Source Code](https://github.com/soyuka/explorer)) `MIT` `Nodejs`

## Games

**[`^        back to top        ^`](#)**

_Games, game servers and control panels._

- **<code>&nbsp;&nbsp;7454</code>** [Lila](https://lichess.org/) - The forever free, adless and open source chess server powering lichess.org, with official iOS and Android client apps. ([Source Code](https://github.com/ornicar/lila)) `AGPL-3.0` `Scala`
- **<code>&nbsp;&nbsp;6303</code>** [Mindustry](https://mindustrygame.github.io/) - Factorio-like tower defense game. Build production chains to gather more resources, and build complex facilities. ([Source Code](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;5520</code>** [Minetest](https://www.minetest.net/) - An open source voxel game engine. Play one of our many games, mod a game to your liking, make your own game, or play on a multiplayer server. ([Source Code](https://github.com/minetest/minetest)) `LGPL-2.1/CC-BY-SA-3.0/Other` `C++`
- **<code>&nbsp;&nbsp;5020</code>** [A Dark Room](https://github.com/doublespeakgames/adarkroom) - Minimalist text adventure game for your browser. ([Demo](http://adarkroom.doublespeakgames.com/)) `MPL-2.0` `HTML5`
- **<code>&nbsp;&nbsp;2606</code>** [Agar.IO Clone](https://github.com/huytd/agar.io-clone) - Agar.io clone written with Socket.IO and HTML5 canvas. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1791</code>** [elevatorsaga](http://play.elevatorsaga.com/) - The elevator programming game. ([Source Code](https://github.com/magwo/elevatorsaga)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;1659</code>** [Hextris](https://github.com/Hextris/hextris) - Fast paced HTML5 puzzle game inspired by Tetris. ([Demo](https://hextris.github.io/hextris)) `GPL-3.0` `HTML5`
- **<code>&nbsp;&nbsp;1485</code>** [Teeworlds](https://www.teeworlds.com) - Open source 2D retro multiplayer shooter. ([Source Code](https://github.com/teeworlds/teeworlds)) `BSD-3-Clause/Other` `C++`
- **<code>&nbsp;&nbsp;&nbsp;423</code>** [Posio](https://github.com/abrenaut/posio) - Geography multiplayer game. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;195</code>** [SourceBans++](https://sbpp.github.io) - Admin, ban, and communication management system for games running on the Source engine. ([Source Code](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;152</code>** [node-virtual-gamepads](https://github.com/jehervy/node-virtual-gamepads) - Turn your smartphone into a game controller, keyboard, or touchpad for a remote Linux OS machine. `MIT` `Nodejs/CoffeScript`
- **<code>&nbsp;&nbsp;&nbsp;136</code>** [TournamentMango](https://github.com/seiyria/tournamentmango) - TournamentMango is an open source tournament bracket and user management system. You can build an archive of players and keep track of all their scores over time as well as their regular characters, games, and aliases. `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;92</code>** [piqueserver](https://github.com/piqueserver/piqueserver) - Server for openspades, the first-person shooter in a destructible voxel world. ([Clients](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;71</code>** [Legend of the Green Dragon](https://github.com/lotgd/core) - Legend of the Green Dragon is a text-based RPG originally developed by Eric Stevens and JT Traub as a remake of and homage to the classic BBS Door game, Legend of the Red Dragon, by Seth Able Robinson. ([Demo](http://lotgd.net/)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;28</code>** [Net64+](https://net64-mod.github.io) `⚠` - Net64 aka SM64O allows playing Super Mario 64 in an online multiplayer mode. Net64+ is the official continuation of the program and features an integrated server list. ([Source Code](https://github.com/Tarnadas/net64plus-server/), [Clients](https://github.com/Tarnadas/net64plus/)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;18</code>** [battlecraft](https://github.com/jbreindel/battlecraft) - Fully distributed multiplayer browser game. `Apache-2.0` `Erlang`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;16</code>** [RconCli](https://github.com/gorcon/rcon-cli) - CLI for executing queries on a remote Valve Source dedicated server using the RCON Protocol. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;15</code>** [QuakeJS](https://github.com/begleysm/quakejs) - QuakeJS is a port of ioquake3 to JavaScript that can be played in a browser. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;11</code>** [Quizmaster](https://github.com/nymanjens/quizmaster) - A web-app for conducting a quiz, including a page for players to enter their answers. `Apache-2.0` `Scala`

## Gateways and terminal sharing

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;5884</code>** [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One is an HTML5 web-based terminal emulator and SSH client. ([Source Code](https://github.com/liftoff/GateOne)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;5461</code>** [OS.js](https://www.os-js.org/) - Desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction. ([Demo](https://demo.os-js.org/), [Source Code](https://github.com/os-js/OS.js)) `BSD-2-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;3886</code>** [tmate](https://tmate.io/) - Instant terminal sharing. ([Source Code](https://github.com/tmate-io/tmate)) `ISC` `C`
- **<code>&nbsp;&nbsp;1661</code>** [asciinema](https://github.com/asciinema/asciinema-server) - Web app for hosting asciicasts. ([Demo](https://asciinema.org/)) `Apache-2.0` `Elixir/Docker`
- **<code>&nbsp;&nbsp;1359</code>** [Neko](https://github.com/nurdism/neko) - A self hosted virtual browser (rabb.it clone) that runs in Docker. `Apache-2.0` `Docker/Go`
- **<code>&nbsp;&nbsp;&nbsp;436</code>** [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty is a SSH and Telnet connector made for the Web. `AGPL-3.0` `Go/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;82</code>** [oneye](https://oneye-project.org/) - Cloud software to access your data from everywhere with any browser. ([Demo](https://wiki.oneye-project.org/0.9:demo), [Source Code](https://github.com/oneye/oneye)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Guacamole](http://guac-dev.org/) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ([Source Code](https://github.com/glyptodon/)) `Apache-2.0` `Java/C`

## Groupware

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;2299</code>** [SuiteCRM](http://www.suitecrm.com/) - The award-winning, enterprise-class open source CRM. ([Source Code](https://github.com/salesagility/SuiteCRM)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;974</code>** [SOGo](https://sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and Web interface. ([Demo](http://demo.sogo.nu/SOGo/), [Source Code](https://github.com/inverse-inc/sogo)) `LGPL-2.1` `Objective-C`
- **<code>&nbsp;&nbsp;&nbsp;727</code>** [Cozy Cloud](https://cozy.io) - Personal cloud where you can manage and sync your contact, files and calendars, and manage your budget with an app store full of community contributions. ([Source Code](https://github.com/cozy)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;681</code>** [EspoCRM](https://www.espocrm.com/) - CRM with a frontend designed as a single page application, and a REST API. ([Demo](http://demo.espocrm.de/basic/), [Source Code](https://github.com/espocrm/espocrm)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;389</code>** [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. ([Source Code](https://openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;245</code>** [Horde](http://www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. ([Demo](http://demo.horde.org/login.php), [Source Code](https://github.com/horde/horde)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;148</code>** [Corteza](https://cortezaproject.org) - CRM including a unified workspace, enterprise messaging and a low code environment for rapidly and securely delivering records-based management solutions. ([Demo](https://latest.cortezaproject.org), [Source Code](https://github.com/cortezaproject/corteza-server)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;122</code>** [egroupware](http://www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. ([Source Code](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;112</code>** [HRCloud2](https://github.com/zelon88/HRCloud2) - Full-featured home hosted Cloud Drive, Personal Assistant, App Launcher, File Converter, Streamer, Share Tool and more. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [BlueMind](https://www.bluemind.net/en/) - Groupware with email, calendar, addressbooks, exchange active sync, exchange "mapi" protocol support. ([Source Code](https://forge.bluemind.net/stash/projects/BM/repos/bluemind-public/browse)) `AGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Kopano](https://kopano.com/) - Groupware suite including e-mail, calendars, tasks, todos and notes. Featuring a modern WebApp, DeskApp and mobile access over Z-Push/ActiveSync. ([Demo](http://demo.kopano.com), [Source Code](https://stash.kopano.io)) `AGPL-3.0` `C/Python/PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Kolab](https://kolab.org/) - Kolab community is a unified communication and collaboration system. ([Source Code](https://git.kolab.org/)) `GPL-2.0/LGPL-2.1/GPL-3.0` `C++/Python/PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Citadel](http://www.citadel.org/doku.php) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more. ([Source Code](http://www.citadel.org/doku.php/installation:source)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tine 2.0](https://www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker. ([Demo](https://demo.tine20.net), [Source Code](https://packages.tine20.com/maintenance/source/)) `AGPL-3.0/Other` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Zimbra Collaboration](https://www.zimbra.com/) - Email, calendar, collaboration server with Web interface and lots of integrations. ([Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`

## Human Resources Management (HRM)

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;&nbsp;620</code>** [TimeOff.Management](https://timeoff.management) - Simple yet powerful absence management software for small and medium size business. ([Demo](https://app.timeoff.management), [Source Code](https://github.com/timeoff-management/application)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;376</code>** [Sentrifugo](http://www.sentrifugo.com/) - Sentrifugo is a HRM system that can be easily configured to meet your organizational needs. ([Source Code](https://github.com/sapplica/sentrifugo)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;321</code>** [IceHrm](https://icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information. ([Demo](https://icehrm.com/demo.php), [Source Code](https://github.com/gamonoid/icehrm)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;108</code>** [admidio](https://www.admidio.org/) - Admidio is a free open source user management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization. ([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise. ([Source Code](https://sourceforge.net/projects/orangehrm/)) `GPL-2.0` `PHP`

## Internet Of Things (IoT)

**[`^        back to top        ^`](#)**

- **<code>&nbsp;36827</code>** [Home Assistant](https://home-assistant.io/) - Open-source home automation platform. ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/home-assistant)) `MIT` `Python`
- **<code>&nbsp;10873</code>** [Node RED](http://nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. ([Source Code](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;7200</code>** [Thingsboard](https://thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization. ([Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;3483</code>** [openHAB](http://www.openhab.org) - Vendor and technology agnostic open source software for home automation. ([Demo](http://demo.openhab.org:8080/), [Source Code](https://github.com/openhab/openhab)) `EPL-2.0` `Java`
- **<code>&nbsp;&nbsp;2772</code>** [Domoticz](https://www.domoticz.com/) - Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. ([Source Code](https://github.com/domoticz/domoticz), [Clients](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++`
- **<code>&nbsp;&nbsp;2355</code>** [Mozilla Gateway](https://iot.mozilla.org/gateway/) - Mozilla WebThings is Mozilla’s open source implementation of the Web of Things, including the WebThings Gateway and the WebThings framework. ([Source Code](https://github.com/mozilla-iot/gateway)) `MPL-2.0` `NodeJS`
- **<code>&nbsp;&nbsp;1459</code>** [Gladys](https://gladysproject.com) - Gladys is an open-source home assistant which runs on your Raspberry Pi. ([Source Code](https://github.com/GladysProject/Gladys)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;250</code>** [Thingspeak](https://thingspeak.com/) - Open source “Internet of Things” application and API to store and retrieve data from things using HTTP. ([Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)) `GPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;226</code>** [DeviceHive](https://www.devicehive.com/) - Open Source IoT Platform with a wide range of integration options. ([Demo](https://playground.devicehive.com/), [Source Code](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [FHEM](https://fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly. ([Source Code](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`

## Knowledge Management Tools

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;2525</code>** [My Mind](https://github.com/ondras/my-mind) - Web application for creating and managing mind maps. ([Demo](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;2052</code>** [Mindmaps](https://github.com/drichard/mindmaps) - Open source, offline capable, mind mapping application. ([Demo](http://drichard.org/mindmaps/)) `AGPL-3.0` `HTML5`
- **<code>&nbsp;&nbsp;&nbsp;406</code>** [Weaviate](https://github.com/semi-technologies/weaviate) - A cloud-native, realtime vector search engine integrating scalable machine learning models (GraphQL and RESTful API's). ([Demo](https://www.semi.technology/documentation/weaviate/current/)) `BSD-3-Clause` `Go`

## Learning and Courses

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;3643</code>** [Canvas LMS](https://www.canvaslms.com/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate. ([Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;3326</code>** [Moodle](https://moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide. ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;672</code>** [Sakai](https://www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration. ([Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)) `ECL-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;505</code>** [Chamilo LMS](https://chamilo.org/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;219</code>** [ILIAS](http://www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it. ([Demo](http://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;117</code>** [OpenOLAT](https://www.openolat.com/?lang=en) - OpenOLAT is a web-based learning management system for teaching, education, assessment and communication. ([Demo](https://learn.olat.com), [Source Code](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;80</code>** [Open eClass](http://www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process. ([Demo](http://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;70</code>** [Mahara](https://mahara.org/) - Open Source fully featured web application to build students electronic portfolio. ([Source Code](https://github.com/MaharaProject/mahara)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;12</code>** [RELATE](https://documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calendar. ([Source Code](https://github.com/inducer/relate)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [RosarioSIS](https://www.rosariosis.org/) - RosarioSIS, free Student Information System for school management. ([Demo](https://www.rosariosis.org/demo/), [Source Code](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [edX](https://www.edx.org/) - The Open edX platform is open-source code that powers edX.org. ([Source Code](https://github.com/edx/)) `AGPL-3.0` `Python`

## Maps and Global Positioning System (GPS)

**[`^        back to top        ^`](#)**

_See also [awesome-gis](https://github.com/sshuair/awesome-gis)._

- **<code>&nbsp;&nbsp;4037</code>** [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - High performance routing engine designed to run on OpenStreetMap data and offering an HTTP API, C++ library interface, and NodeJS wrapper. ([Demo](https://map.project-osrm.org/), [Source Code](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- **<code>&nbsp;&nbsp;1557</code>** [Nominatim](https://nominatim.org/) - Server application for reverse geocoding (address -> coordinates) on OpenStreetMap data. ([Source Code](https://github.com/openstreetmap/Nominatim)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;1512</code>** [OpenTripPlanner](https://www.opentripplanner.org/) - Multimodal trip planning software based on OpenStreetMap data and consuming published GTFS-formatted data to suggest routes using local public transit systems. ([Source Code](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/JavaScript`
- **<code>&nbsp;&nbsp;1190</code>** [OpenStreetMap](https://www.openstreetmap.org/) - Collaborative project to create a free editable map of the world. ([Source Code](https://github.com/openstreetmap/openstreetmap-website), [Clients](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- **<code>&nbsp;&nbsp;1145</code>** [GraphHopper](https://graphhopper.com/) - Fast routing library and server using OpenStreetMap. ([Source Code](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;1106</code>** [TileServer GL](http://tileserver.readthedocs.io/) - Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc. ([Source Code](https://github.com/klokantech/tileserver-gl)) `BSD-2-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;548</code>** [uMap](https://umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ([Source Code](https://github.com/umap-project/umap)) `WTFPL` `Python`
- **<code>&nbsp;&nbsp;&nbsp;470</code>** [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by [OwnTracks](http://owntracks.org/) location tracking apps. `GPL-2.0` `C`/`Lua`
- **<code>&nbsp;&nbsp;&nbsp;421</code>** [TileServer PHP](https://github.com/klokantech/tileserver-php) - Serve map tiles from any PHP hosting. `BSD-2-Clause` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;286</code>** [μlogger](https://github.com/bfabiszewski/ulogger-server) - Collect geolocation from users in real-time and display their GPS tracks on a website. ([Demo](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;245</code>** [Hauk](https://github.com/bilde2910/Hauk) - Easy to setup location sharing platform that lets you temporarily share your location with anyone in real-time. ([Demo](https://github.com/bilde2910/Hauk#demo-server)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;143</code>** [Orion](https://github.com/LINKIWI/orion-web) - Powerful OwnTracks API-compliant location data visualization frontend for the web. ([Demo](https://linkiwi.github.io/orion-web/)) `MIT` `Python/Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;40</code>** [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks. ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;15</code>** [Geo2tz](https://github.com/noandrea/geo2tz) - Get the timezone from geo coordinates (lat, lon). `MIT` `Go/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [OpenGTS](http://www.opengts.org/) - Entry-level fleet tracking system. Supports variety of tracking devices and protocols. Comes with rich web-interface and reporting features. ([Demo](http://track.opengts.org/track/Track), [Source Code](https://sourceforge.net/projects/opengts/files/server-base/)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Traccar](https://www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips. ([Demo](http://demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`

## Media Streaming

**[`^        back to top        ^`](#)**

_See also <https://en.wikipedia.org/wiki/List_of_streaming_media_systems>, <https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems>_

### Multimedia Streaming

- **<code>&nbsp;&nbsp;1301</code>** [NymphCast](http://nyanko.ws/nymphcast.php) - NymphCast is a Chromecast alternative which turns your choice of Linux-capable hardware into an audio and video source for a television or powered speakers. ([Source Code](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- **<code>&nbsp;&nbsp;&nbsp;656</code>** [Gerbera](https://gerbera.io/) - Gerbera is an UPnP Media Server. It allows you to stream your digital media throughout your home network and listen to/watch it on a variety of UPnP compatible devices. ([Source Code](https://github.com/gerbera/gerbera)) `GPL-2.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;517</code>** [homehost](https://github.com/ridhwaans/homehost) `⚠` - Self-hosted React + Redux app that streams your media collection (music, movies, books, podcasts, comics etc). `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;179</code>** [MistServer](http://mistserver.org/) - Streaming media server that works well in any streaming environment. ([Source Code](https://github.com/DDVTECH/mistserver)) `AGPL-3.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;134</code>** [LBRY](https://lbry.com/) - Is a secure, open, and community-run digital marketplace that aims to replace Youtube and Amazon. ([Demo](https://lbry.tv/), [Source Code](https://github.com/lbryio/lbry.com), [Clients](https://github.com/lbryio/lbry-desktop)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;46</code>** [Karaoke Forever](https://www.karaoke-forever.com) - Host awesome karaoke parties where everyone can easily find and queue songs from their phone's web browser. The player is also browser-based with support for MP3+G, MP4 and WebGL visualizations. ([Source Code](https://www.karaoke-forever.com/repo)) `ISC` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;40</code>** [Icecast 2](http://www.icecast.org/) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([Source Code](https://gitlab.xiph.org/xiph/icecast-server), [Clients](http://www.icecast.org/apps/)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;34</code>** [Jellyfin](https://jellyfin.org) - Media server for audio, video, books, comics, and photos with a sleek interface and robust transcoding capabilities. Almost all modern platforms have clients, including Roku, Android TV, iOS, Xbox, and Kodi. ([Demo](https://demo.jellyfin.org/stable), [Source Code](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ReadyMedia](http://sourceforge.net/projects/minidlna/) - Simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. Formerly known as MiniDLNA. ([Source Code](https://sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller. ([Source Code](https://gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [üWave](http://u-wave.net/) `⚠` - üWave is a self-hosted collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud. ([Demo](https://wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Darwin Streaming Server](https://macosforge.github.io/dss/) - High performance server for streaming QuickTime and MPEG-4 media over RTP and RTSP protocols. Originated as Apple’s QTSS. ([Source Code](https://github.com/macosforge/dss)) `APSL-2.0` `C++`


### Audio Streaming

- **<code>&nbsp;11955</code>** [koel](http://koel.phanan.net/) - Personal music streaming server that works. ([Source Code](https://github.com/phanan/koel)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;9688</code>** [Beets](http://beets.io/) - Music library manager and MusicBrainz tagger (command-line and Web interface). ([Source Code](https://github.com/beetbox/beets)) `MIT` `Python`
- **<code>&nbsp;&nbsp;6725</code>** [Mopidy](http://mopidy.readthedocs.org/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([Source Code](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;3340</code>** [Snapcast](https://github.com/badaix/snapcast) - Synchronous multiroom audio server. `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;2529</code>** [Ampache](http://ampache.org/) - Web based audio/video streaming application. ([Demo](http://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;2154</code>** [musikcube](https://musikcube.com/) - Streaming audio server with Linux/macOS/Windows/Android clients. ([Source Code](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++`
- **<code>&nbsp;&nbsp;1755</code>** [Groove Basin](https://github.com/andrewrk/groovebasin) - Music player server with a web-based user interface inspired by Amarok 1.4. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1581</code>** [mStream](http://mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. ([Source Code](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;1517</code>** [Airsonic](https://airsonic.github.io/) - Open-source web-based media streamer and jukebox. A fork of Subsonic's last open-source release, before it switched licenses. ([Source Code](https://github.com/airsonic/airsonic), [Clients](https://airsonic.github.io/docs/apps/)) `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;1125</code>** [Volumio](https://volumio.org/) - A free and open source linux distribution, designed and fine-tuned exclusively for music playback. ([Source Code](https://github.com/volumio/Volumio2)) `GPL-3.0` `NodeJS`
- **<code>&nbsp;&nbsp;1079</code>** [AzuraCast](https://www.azuracast.com/) - A modern and accessible self-hosted web radio management suite. ([Source Code](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;740</code>** [Sonerezh](https://www.sonerezh.bzh/) - Self-hosted, web-based application for stream your music, everywhere. ([Demo](https://www.sonerezh.bzh/demo/), [Source Code](https://github.com/sonerezh/sonerezh)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;634</code>** [Black Candy](https://github.com/aidewoode/black_candy) - Music streaming server built with Rails and Stimulus. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;546</code>** [Polaris](https://github.com/agersant/polaris) - Music browsing and streaming application optimized for large music collections, ease of use and high performance. `MIT` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;545</code>** [Navidrome Music Streamer](https://www.navidrome.org) - Modern Music Server and Streamer, compatible with Subsonic/Airsonic. ([Demo](https://www.navidrome.org/demo), [Source Code](https://github.com/deluan/navidrome), [Clients](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Go/JavaScript`
- **<code>&nbsp;&nbsp;&nbsp;523</code>** [Stretto](https://github.com/benkaiser/stretto) - Music player with Youtube/Soundcloud import and iTunes/Spotify discovery. ([Demo](https://next.kaiserapps.com), [Clients](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
  - **<code>&nbsp;&nbsp;&nbsp;465</code>** [ympd](http://www.ympd.org/) - Standalone MPD Web GUI written in C, utilizing Websockets and Bootstrap/JS. ([Source Code](https://github.com/notandy/ympd)) `GPL-2.0` `C`
  - **<code>&nbsp;&nbsp;&nbsp;427</code>** [Moped](https://github.com/martijnboland/moped) - Responsive HTML5 + Javascript client for the Mopidy music server. `MIT` `HTML5`
  - **<code>&nbsp;&nbsp;&nbsp;380</code>** [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Web Client for Mopidy Music Server. `Apache-2.0` `HTML5`
- **<code>&nbsp;&nbsp;&nbsp;371</code>** [LibreTime](http://libretime.org) - Simple, open source platform that lets you broadcast streaming radio on the web (fork of [Airtime](https://github.com/sourcefabric/Airtime)). ([Source Code](https://github.com/LibreTime/libretime)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;293</code>** [gonic](https://github.com/sentriz/gonic) - Lightweight music streaming server. Subsonic compatible. `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;287</code>** [moOde Audio](https://moodeaudio.org/) - Audiophile-quality music playback for the wonderful Raspberry Pi family of single board computers. ([Source Code](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;227</code>** [LMS](https://github.com/epoupon/lms) - Access your self-hosted music using a web interface. ([Demo](http://lms.demo.poupon.io/)) `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;134</code>** [Audioserve](https://github.com/izderadicka/audioserve) - Simple personal server to serve audio files from directories (audiobooks, music, podcasts...). Focused on simplicity and supports sync of play position between clients. `MIT` `Rust`
  - **<code>&nbsp;&nbsp;&nbsp;&nbsp;85</code>** [Mopidy-Party](https://github.com/Lesterpig/mopidy-party) - Mopidy web extension designed for party! Let your guests manage the sound. `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;72</code>** [Compactd](https://github.com/compactd/compactd) - Remote music player that supports adding content. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;21</code>** [FriendsRadio](https://github.com/xouabita/friends-radio) `⚠` - Share music with your friends from Youtube and Soundcloud. ([Demo](https://friends-radio.herokuapp.com/)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</code>** [KooZic](https://koozic.net/) - Music server with powerful playlist features and Subsonic compatibility. ([Demo](https://demo.koozic.net/public), [Source Code](https://github.com/DocMarty84/koozic)) `LGPL-3.0/MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [GNU FM](https://gnu.io/fm/) - Running music community websites, alternative to last.fm. ([Source Code](http://git.savannah.gnu.org/cgit/librefm.git/)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Funkwhale](https://funkwhale.audio/) - Modern, web-based, convivial, multi-user and free music server. ([Demo](https://demo.funkwhale.audio/), [Source Code](https://code.eliotberriot.com/funkwhale/funkwhale)) `BSD-3-Clause` `Python/Django`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [mpd](http://www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. ([Source Code](https://github.com/MusicPlayerDaemon/MPD), [Clients](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`

### Video Streaming

- **<code>&nbsp;&nbsp;8510</code>** [Streama](https://github.com/streamaserver/streama) - Self hosted streaming media server. `MIT` `Java`
- **<code>&nbsp;&nbsp;7972</code>** [PeerTube](https://joinpeertube.org/en/) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. ([Source Code](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;6718</code>** [VideoLAN Client (VLC)](https://www.videolan.org/) - Cross-platform multimedia player client and server supporting most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols. ([Source Code](https://github.com/videolan/vlc)) `Multiple` `C`
- **<code>&nbsp;&nbsp;3962</code>** [Invidious](https://github.com/omarroth/invidious/) - `⚠` Invidious is an alternative front-end to YouTube. ([Demo](https://invidio.us/)) `AGPL-3.0` `Crystal`
- **<code>&nbsp;&nbsp;2947</code>** [Zoneminder](https://www.zoneminder.com/) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. ([Source Code](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;1020</code>** [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels. ([Demo](http://cytu.be)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;352</code>** [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager) - Fully responsive interface to manage all your favorite media on your HTPC. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;241</code>** [Myflix](https://github.com/pastapojken/Myflix) - Self-hosted, super lightweight Netflix alternative. `MIT` `Shell`
- **<code>&nbsp;&nbsp;&nbsp;142</code>** [Rapidbay](https://github.com/hauxir/rapidbay/) - Self-hosted torrent videostreaming service/torrent client that allows searching and playing videos from torrents in the browser or from a Chromecast/AppleTV/Smart TV. `MIT` `Python/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;57</code>** [Bluecherry](https://www.bluecherrydvr.com/) - Closed-circuit television (CCTV) software application which supports IP and Analog cameras. ([Source Code](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;42</code>** [Radium](https://github.com/Zibbp/Radium) - Synced stream and video playback with VOD capabilities utilizing HLS. Developed for movie nights but has many use cases. ([Demo](https://radium-demo.herokuapp.com)) `MIT` `Nodejs/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;38</code>** [SyncTube](https://github.com/RblSb/SyncTube) - Lightweight and very simple to setup CyTube alternative to watch videos with friends and chat. ([Demo](http://synctube-example.herokuapp.com/)) `MIT` `Nodejs/Haxe`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Open Streaming Platform](https://openstreamingplatform.com) - Self-Hosted alternative to Twitch and Youtube Live for live and on-demand video streaming. ([Source Code](https://gitlab.com/Deamos/flask-nginx-rtmp-manager)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [crtmpserver](https://packages.debian.org/stable/crtmpserver) - High performance RTMP/RTSP streaming server. `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ShinobiCE](https://gitlab.com/Shinobi-Systems/ShinobiCE) - Open Source CCTV software written in Node with both IP and local camera support. `AGPL-3.0/GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Oddworks](https://gitlab.com/oddnetworks/oddworks/core) - Oddworks is an open source video distribution platform built to destroy the barriers to streaming television with SDKs for Roku, Apple iOS/tvOS, Google Android, and Amazon FireTV. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ([Source Code](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tube](https://prologic.github.io/tube) - a Youtube-like (_without censorship and features you don't need!_) Video Sharing App written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed. ([Demo](https://tube.mills.io), [Source Code](https://github.com/prologic/tube)) `MIT` `Go`

## Misc/Other

**[`^        back to top        ^`](#)**

- **<code>&nbsp;53527</code>** [revealjs](https://revealjs.com) - Framework for easily creating beautiful presentations using HTML. ([Demo](https://revealjs.com/), [Source Code](https://github.com/hakimel/reveal.js)) `MIT` `JavaScript`
- **<code>&nbsp;11580</code>** [Cachet](https://cachethq.io/) - An open source status page system for everyone. ([Demo](https://demo.cachethq.io/), [Source Code](https://github.com/CachetHQ/Cachet)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;10449</code>** [CyberChef](https://github.com/gchq/CyberChef) - Perform all manner of "cyber" operations within a web browser such as AES, DES and Blowfish encryption and decryption, creating hexdumps, calculating hashes, and much more. ([Demo](https://gchq.github.io/CyberChef)) `Apache-2.0` `JavaScript`
- **<code>&nbsp;10323</code>** [Monica](https://monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. ([Source Code](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;7170</code>** [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets. ([Demo](https://google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;6249</code>** [CapRover](https://caprover.com/) - Build your own PaaS in a few minutes. ([Demo](https://captain.server.demo.caprover.com/#/login), [Source Code](https://github.com/caprover/caprover)) `Apache-2.0` `Docker/Nodejs`
- **<code>&nbsp;&nbsp;2986</code>** [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB is an open source self hosted AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;2681</code>** [formspree](https://formspree.io/) `⚠` - Just send your form to our URL and we'll forward it to your email. No PHP, Javascript or sign up required. ([Demo](http://test.formspree.io/), [Source Code](https://github.com/formspree/formspree)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;2249</code>** [Ombi](https://ombi.io/) - A content request system for Plex/Emby, connects to SickRage, CouchPotato, Sonarr, with a growing feature set. ([Source Code](https://github.com/tidusjar/Ombi)) `GPL-2.0` `C#`
- **<code>&nbsp;&nbsp;2196</code>** [Reactive Resume](http://rxresu.me/) - A one-of-a-kind resume builder that keeps your privacy in mind. Completely secure, customizable, portable, open-source and free forever. ([Demo](https://rxresu.me/app/dashboard/), [Source Code](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Nodejs`
- **<code>&nbsp;&nbsp;1281</code>** [ytdl-webserver](https://github.com/Algram/ytdl-webserver) - Docker-ready webserver for downloading youtube videos. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1264</code>** [asciiflow](http://asciiflow.com/) - Flow Diagram Drawing Tool. ([Source Code](https://github.com/lewish/asciiflow2)) `GPL-3.0` `Java/JavaScript`
- **<code>&nbsp;&nbsp;1245</code>** [King Phisher](https://github.com/securestate/king-phisher) - King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;1118</code>** [CUPS](https://www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. ([Source Code](https://github.com/apple/cups)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;1083</code>** [cState](https://github.com/cstate/cstate/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+. Best used with Netlify, Docker. ([Demo](https://cstate.mnts.lt/)) `MIT` `Go`
- **<code>&nbsp;&nbsp;1030</code>** [Kimai](http://www.kimai.org/) - Simple time and project tracking. ([Demo](http://www.kimai.org/demo/), [Source Code](https://github.com/kimai/kimai)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;938</code>** [TeslaMate](https://github.com/adriankumpf/teslamate) - A powerful data logger for Tesla vehicles. `MIT` `Elixir`
- **<code>&nbsp;&nbsp;&nbsp;935</code>** [411](https://github.com/etsy/411) - Alert Management Web Application. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;902</code>** [Revive Adserver](https://www.revive-adserver.com/) - World's most popular free, open source ad serving system. Formerly known as OpenX Adserver and phpAdsNew. ([Source Code](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0-or-later` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;842</code>** [Flox](https://github.com/devfake/flox) `⚠` - Self hosted movie, TV series and anime watch list with a 3-point rating system. Uses The Movie Database backend for information. ([Demo](https://flox-demo.pyxl.dev/)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;496</code>** [oTranscribe](http://otranscribe.com/) - Free web app to take the pain out of transcribing recorded interviews. ([Source Code](https://github.com/oTranscribe/oTranscribe)) `MIT` `JavaScript`
- **<code>&nbsp;&nbsp;&nbsp;478</code>** [webtrees](https://www.webtrees.net) - Webtrees is the web's leading on-line collaborative genealogy application. ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;435</code>** [ViMbAdmin](http://www.vimbadmin.net/) - Provides a web based virtual mailbox administration system to allow mail administrators to easily manage domains, mailboxes and aliases. ([Demo](http://www.vimbadmin.net/demo/auth/login), [Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;416</code>** [How Secure Is My Password](https://github.com/howsecureismypassword/hsimp) - Rather than just saying a password is "weak" or "strong", How Secure is My Password? lets your users know how long it would take someone to crack their password. ([Demo](https://howsecureismypassword.net/)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;236</code>** [DomainMOD](https://domainmod.org) - Application to manage your domains and other internet assets in a central location. DomainMOD includes a Data Warehouse framework that allows you to import your WHM/cPanel web server data so that you can view, export, and report on your data. ([Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;198</code>** [Notica](https://notica.us) - Lets you send browser notifications from your terminal to your desktop or phone. No installation or registration is required. ([Source Code](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;152</code>** [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb is an open source genealogy software written in OCaml. It comes with a Web interface and can be used off-line or as a Web service. ([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCAML`
- **<code>&nbsp;&nbsp;&nbsp;137</code>** [Anuko](https://www.anuko.com/time_tracker/index.htm) - Anuko provides simple time and project tracking on a selfhosted basis. ([Demo](https://timetracker.anuko.com/), [Source Code](https://github.com/anuko/timetracker)) `Other` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;135</code>** [blynk](https://blynk.io/) - Platform with iOS and Android apps to control Arduino, ESP8266, Raspberry Pi and similar microcontroller boards over the Internet. ([Source Code](https://github.com/blynkkk/blynk-server)) `AGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;93</code>** [AlertHub](https://github.com/Ardakilic/alerthub) `⚠` - AlertHub is a simple tool to get alerted from GitHub releases. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;71</code>** [Journal](https://github.com/inoda/journal) - Simple journaling with encrypted entries and sharing capabilities. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;61</code>** [Anchr](https://anchr.io) - Anchr is a toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. ([Source Code](https://github.com/n1try/anchr)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;54</code>** [nnmm](https://github.com/Mechazawa/nnmm) - Super tiny pastebin/url minifier "microservice". `Beerware` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;48</code>** [Web fonts repository](https://github.com/Finesse/web-fonts-repository) - Simple webfont hosting. Google Fonts alternative for your own fonts. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;38</code>** [Trello Burndown](https://github.com/swordbeta/trello-burndown) `⚠` - Easy to use SCRUM burndown chart for Trello boards. `MIT` `Go/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;20</code>** [Digital-Currency](https://github.com/Icesofty/Digital-Currency) - Create your own Self-Hosted Digital Currency. ([Demo](https://tonken.glitch.me/)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;12</code>** [graph-vl](https://github.com/verifid/graph-vl) - Identity document verification using Machine Learning and GraphQL. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code>** [2FAuth](https://github.com/Bubka/2FAuth) - A web app to manage your Two-Factor Authentication (2FA) accounts and generate their security codes. ([Demo](https://demo.2fauth.app/)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [SANE Network Scanning](http://sane-project.org/) - Allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ReleaseBell](https://releasebell.com/) - Send release notifications for starred Github repos. ([Source Code](https://git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [MailyGo](https://codeberg.org/jlelse/MailyGo) - MailyGo is a small tool written in Go that allows to send HTML forms, for example from static websites without a dynamic backend, via email. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Musical Artifacts](https://musical-artifacts.com/) - Helping to catalog, preserve and free the artifacts you need to produce music. ([Source Code](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [PassCheck](https://apacketofsweets.github.io/PassCheck/) - A web application featuring some handy password tools, including a password generator, strength checker and HaveIBeenPwned breach checker. ([Source Code](https://github.com/apacketofsweets/PassCheck)) `MIT` `JavaScript`

## Money, Budgeting and Management

**[`^        back to top        ^`](#)**

_See also https://github.com/n1trux/awesome-sysadmin#it-asset-management_

- **<code>&nbsp;&nbsp;5409</code>** [Invoice Ninja](https://www.invoiceninja.org/) - Powerful tool to invoice clients online. ([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
- **<code>&nbsp;&nbsp;5193</code>** [Firefly III](https://firefly-iii.org/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, has an advanced rule engine and can import data from many banks. ([Demo](https://demo.firefly-iii.org/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;3427</code>** [Akaunting](https://akaunting.com/) - Akaunting is a free, online and open source accounting software designed for small businesses and freelancers. ([Source Code](https://github.com/akaunting/akaunting)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1708</code>** [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - Manage quotes, invoices, payments and customers for your small business. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;758</code>** [PartKeepr](https://www.partkeepr.org) - PartKeepr is an electronic part inventory management software. It helps you to keep track of your available parts and assist you with re-ordering parts. ([Demo](https://demo.partkeepr.org/), [Source Code](https://github.com/partkeepr/PartKeepr)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;457</code>** [IHateMoney](http://ihatemoney.org/) - Manage your shared expenses, easily. ([Demo](https://ihatemoney.org/demo/), [Source Code](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;402</code>** [OnTrack](https://github.com/inoda/ontrack) - A simple app to track spend and set goals. `MIT` `Ruby/React`
- **<code>&nbsp;&nbsp;&nbsp;337</code>** [Economizzer](http://www.economizzer.org/) - An easy and secure system for you to manage your personal money and achieve your goals, and can be accessed by computer, tablet or smartphone. ([Demo](https://github.com/gugoan/economizzer#live-demo), [Source Code](https://github.com/gugoan/economizzer)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;272</code>** [Hospital Run](http://hospitalrun.io/) - Hospital Run is offline enabled hospital management software. ([Demo](http://hospitalrun.io/demo/), [Source Code](https://github.com/HospitalRun/hospitalrun-server)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;266</code>** [Inventaire](https://inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. ([Source Code](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;240</code>** [Budget App](https://github.com/paukiatwee/budgetapp) - Budget App is an open source personal budgeting application. `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;196</code>** [SilverStrike](https://silverstrike.org/) - Personal finance management made easy. ([Demo](https://demo.silverstrike.org/), [Source Code](https://github.com/agstrike/silverstrike)) `MIT` `Python/Django`
- **<code>&nbsp;&nbsp;&nbsp;194</code>** [Dot Ledger](https://www.dotledger.com/) - Web-based personal finance management tool. ([Demo](https://demo.dotledger.com/), [Source Code](https://github.com/dotledger/dotledger)) `Apache-2.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;172</code>** [Boodle](https://github.com/manuel-uberti/boodle) - Simple accounting single-page application in Clojure and ClojureScript. `EPL-1.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;169</code>** [Kresus](https://kresus.org/) - Open source personal finance manager. ([Demo](https://kresus.org/en/demo.html), [Source Code](https://github.com/kresusapp/kresus)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;149</code>** [ExMoney](https://github.com/gaynetdinov/ex_money) - Self-hosted personal finance app. `ISC` `Elixir`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;70</code>** [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - Asset Management System. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;34</code>** [GRR](http://grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. ([Source Code](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;14</code>** [Family Accounting Tool](https://github.com/nymanjens/facto) - Web-based finance management tool for partners with partially shared expenses. `Apache-2.0` `Scala`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</code>** [Galette](http://galette.eu/dc/) - Galette is a membership management web application towards non profit organizations. ([Source Code](http://git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [BTCPay Server](https://btcpayserver.org/) - A self-hosted Bitcoin and other cryptocurrencies payment processor. ([Demo](https://mainnet.demo.btcpayserver.org/), [Source Code](https://github.com/btcpayserver/)) `MIT` `C#`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Fava](https://beancount.github.io/fava/) - Fava is the web frontend of Beancount, a text based double-entry accounting system. ([Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [Source Code](https://github.com/beancount/fava)) `MIT` `Python`

## Monitoring

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#monitoring and https://github.com/n1trux/awesome-sysadmin#metric--metric-collection_

## Note-taking and Editors

**[`^        back to top        ^`](#)**

_See also [Wikis](#wikis)_

- **<code>&nbsp;23556</code>** [Markdown Edit](http://georgeosddev.github.com/markdown-edit/) - Online markdown editor/viewer. ([Source Code](https://github.com/georgeOsdDev/markdown-edit)) `MIT` `HTML5`
- **<code>&nbsp;18501</code>** [Joplin](https://joplin.cozic.net/) - Joplin is a note taking application with Markdown editor and encryption support for mobile and desktop platforms. Runs client-side and syncs through self hosted Nextcloud or similar. Consider it like open source alternative to Evernote. ([Source Code](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- **<code>&nbsp;12250</code>** [draw.io](https://draw.io) - Diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams. ([Source Code](https://github.com/jgraph/drawio)) `Apache-2.0` `JavaScript`
- **<code>&nbsp;&nbsp;9690</code>** [Leanote](http://leanote.org/) - Leanote, Not Just A Notepad! Open source cloud notepad. ([Demo](https://leanote.com/note), [Source Code](https://github.com/leanote/leanote)) `GPL-2.0` `Go`
- **<code>&nbsp;&nbsp;9128</code>** [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases. `AGPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;7602</code>** [Paperwork](https://paperwork.cloud) - OpenSource note-taking and archiving alternative to Evernote, Microsoft OneNote and Google Keep. ([Source Code](https://github.com/paperwork/paperwork)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;7452</code>** [Overleaf](https://www.overleaf.com/) - Web-based collaborative LaTeX editor. ([Source Code](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;6886</code>** [dillinger](http://dillinger.io/) - The last Markdown editor, ever. ([Source Code](https://github.com/joemccann/dillinger)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1911</code>** [Dnote](https://www.getdnote.com) - A simple command line notebook with multi-device sync and web interface. ([Source Code](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;1907</code>** [Boostnote](https://boostnote.io/) - The note-taking app for programmers that focuses on markdown, snippets, and customizability. ([Source Code](https://github.com/BoostIO/Boostnote)) `GPL-3.0` `JavaScript`
- **<code>&nbsp;&nbsp;1437</code>** [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote was built to be an open web-based alternative to Microsoft OneNote (T) and EverNote. ([Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5`
- **<code>&nbsp;&nbsp;1203</code>** [CodiMD](https://demo.codimd.org/) - Realtime collaborative markdown notes on all platforms, formerly HackMD CE. ([Source Code](https://github.com/hackmdio/codimd)) `AGPL-3.0` `Node.js`
- **<code>&nbsp;&nbsp;&nbsp;368</code>** [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - Minimalist notepad.cc clone. ([Demo](https://notes.orga.cat/)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;218</code>** [Meemo](https://meemo.minimal-space.de/) - Personal notes stream with Markdown support. ([Source Code](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;195</code>** [Wreeto](https://wreeto.com) - Wreeto is an open source note-taking, knowledge management and wiki system built on top of Ruby on Rails framework. ([Source Code](https://github.com/chrisvel/wreeto_official)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;153</code>** [MiniNote](https://github.com/n1try/mininote) - Simple Markdown note-taking app with persistence. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;108</code>** [DailyNotes](https://github.com/m0ngr31/DailyNotes/) - App for taking notes and tracking tasks on a daily basis in Markdown. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;80</code>** [DocPHT](https://docpht.org/) - With DocPHT you can take notes and quickly document anything and without the use of any database. ([Demo](https://demo.docpht.org/), [Source Code](https://github.com/kenlog/docpht)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;23</code>** [Plainpad](https://alextselegidis.com/get/plainpad/) - A modern note taking application for the cloud, utilizing the best features of progressive web apps technology. ([Demo](https://alextselegidis.com/try/plainpad/), [Source Code](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;16</code>** [savepad](https://github.com/shelltr/textpad) - Minimalist notepad based on notepad.cc. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [BulletNotes](https://bulletnotes.io/) - Workflowy / Dynalist clone with Kanban (Trello) and Calendar functionality. Organize everything. ([Source Code](https://gitlab.com/NickBusey/BulletNotes)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Standard Notes](https://standardnotes.org) - Simple and private notes app. Protect your privacy while getting more done. That's Standard Notes. ([Demo](https://app.standardnotes.org/), [Source Code](https://github.com/standardnotes)) `GPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Turtl](https://turtl.it/) - Totally private personal database and note taking app. ([Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [turndown](https://domchristie.github.io/turndown/) - HTML to Markdown converter written in JavaScript. ([Source Code](https://github.com/domchristie/turndown)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Writing](https://josephernest.github.io/writing/) - Lightweight distraction-free text editor, in the browser (Markdown and LaTeX supported). No lag when writing. ([Source Code](https://github.com/josephernest/writing)) `MIT` `Javascript`

## Office Suites

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;9699</code>** [Etherpad](http://etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time. ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;2518</code>** [EtherCalc](https://ethercalc.net/) - Web spreadsheet. ([Source Code](https://github.com/audreyt/ethercalc)) `CPAL-1.0/Other` `Nodejs`
- **<code>&nbsp;&nbsp;2096</code>** [CryptPad](https://cryptpad.fr/) - CryptPad is the zero knowledge realtime collaborative editor (rich-text, files, source-code, ...). ([Source Code](https://github.com/xwiki-labs/cryptpad)) `AGPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;710</code>** [WebODF](http://webodf.org/) - Tools and libraries to view and edit Open Document Format (ODF) files. ([Source Code](https://github.com/kogmbh/WebODF)) `AGPL-3.0` `HTML5`
- **<code>&nbsp;&nbsp;&nbsp;484</code>** [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - Server for [Gobby](https://github.com/gobby/gobby/wiki), a multi-platform collaborative text editor. ([Source Code](https://github.com/gobby/gobby)) `MIT` `C++`
- **<code>&nbsp;&nbsp;&nbsp;112</code>** [ Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate in your own infrastructure. ([Source Code](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [PHPOffice](https://github.com/PHPOffice) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs`

## Password Managers

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;9314</code>** [keeweb](https://keeweb.info/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ([Source Code](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
- **<code>&nbsp;&nbsp;6291</code>** [Bitwarden](https://bitwarden.com/) `⚠` - Password manager with webapp, browser extension, and mobile app. ([Source Code](https://github.com/bitwarden/core)) `AGPL-3.0` `C#`
- **<code>&nbsp;&nbsp;5255</code>** [bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) - Lightweight Bitwarden server API implementation written in Rust. `GPL-3.0` `Rust`
- **<code>&nbsp;&nbsp;2202</code>** [Passbolt](https://www.passbolt.com/) - Password manager dedicated for managing passwords in a collaborative way on any Web server, using a MySQL database backend. ([Source Code](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1301</code>** [Teampass](http://teampass.net/) - Password manager dedicated for managing passwords in a collaborative way. One symmetric key is used to encrypt all shared/team passwords and stored server side in a file and the database. works on any server Apache, MySQL and PHP. ([Source Code](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;948</code>** [Padloc](https://padloc.app/) - A modern, open source password manager for individuals and teams. ([Source Code](https://github.com/padloc/padloc)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;720</code>** [sysPass](http://www.syspass.org/) - Multiuser password management system. ([Demo](http://demo.syspass.org/), [Source Code](https://github.com/nuxsmin/sysPass)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;415</code>** [PassWall](https://github.com/passwall/passwall-server) - Open source password manager. `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;201</code>** [Shaark](https://github.com/MarceauKa/shaark) - All in one platform for your links, stories, passwords and albums. Built with Laravel and Vue.js. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [PassIt](https://passit.io/) - Simple password manage with sharing features by group and user, but no administration interface. ([Demo](https://app.passit.io/), [Source Code](https://gitlab.com/passit)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Psono](https://psono.com/) - A promising password managers fully featured for teams. ([Demo](https://www.psono.pw), [Source Code](https://gitlab.com/psono)) `Apache-2.0` `Python`

## Pastebins

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;2643</code>** [PrivateBin](https://privatebin.info/) - PrivateBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data. ([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- **<code>&nbsp;&nbsp;1200</code>** [Snibox](https://snibox.github.io/) - Code snippets manager with attractive tag-oriented interface. ([Demo](https://snibox-demo.herokuapp.com/), [Source Code](https://github.com/snibox/snibox)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;984</code>** [0bin](https://github.com/sametmax/0bin) - Client side encrypted pastebin. `WTFPL` `Python`
- **<code>&nbsp;&nbsp;&nbsp;888</code>** [fiche](https://github.com/solusipse/fiche) - Command line pastebin, all you need is netcat. ([Demo](http://termbin.com/)) `MIT` `C`
- **<code>&nbsp;&nbsp;&nbsp;869</code>** [Stikked](https://github.com/claudehohl/Stikked) - Advanced and beautiful pastebin. ([Demo](https://paste.scratchbook.ch/)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;431</code>** [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;348</code>** [mojopaste](http://search.cpan.org/dist/App-mojopaste/) - Perl based pastebin. ([Demo](http://p.thorsen.pm/), [Source Code](https://github.com/jhthorsen/app-mojopaste)) `Artistic-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;280</code>** [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - Very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;262</code>** [NoteHub](https://github.com/chmllr/NoteHub) - Free and Hassle-free Pastebin for Markdown Pages. Simple, clean, password provided, generated-short link. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;188</code>** [Paste](https://phpaste.sourceforge.io/) - Paste is forked from the original source pastebin.com used before it was bought. ([Source Code](https://github.com/jordansamuel/PASTE)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;165</code>** [PurritoBin](https://github.com/PurritoBin/PurritoBin) - Ultra fast, minimalistic, encrypted command line paste-bin, where the server has no knowledge of the paste data. `ISC` `C++`
- **<code>&nbsp;&nbsp;&nbsp;150</code>** [cryptonote](https://cryptonote.me/) - Simple open source web application that lets users encrypt and share messages that can only be read once. ([Source Code](https://github.com/alainmeier/cryptonote)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;104</code>** [filite](https://github.com/raftario/filite) - A simple, light and standalone pastebin, URL shortener and file-sharing service. ([Demo](https://filite.raphaeltheriault.com)) `MIT` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;100</code>** [Fugacious](https://fugacio.us) - Open source short-term secure messaging (OSSSM). ([Source Code](https://github.com/fugacious/fugacious)) `CC0-1.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;88</code>** [bepasty](https://bepasty-server.readthedocs.io/en/latest/) - A pastebin for all kinds of files. ([Source Code](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;71</code>** [bin](https://github.com/w4/bin) - a paste bin. `WTFPL/0BSD` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;46</code>** [pastebin](https://github.com/prologic/pastebin) - Simple pastebin service with convenient api and CLI. ([Demo](https://paste.mills.io)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;44</code>** [snipt](https://github.com/nicksergeant/snipt) - Long-term memory for coders. Share and store code snippets. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;33</code>** [pastebin](https://github.com/mkaczanowski/pastebin) - Simple, fast, feature-rich, standalone pastebin service. `MIT` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;28</code>** [SharpPaste](https://github.com/phonicmouse/SharpPaste) - Cross-platform C# pastebin with client-side AES-256 encryption that just works. `MIT` `C#/NancyFX`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;26</code>** [EdPaste](https://github.com/Edraens/EdPaste) - Self-hosted pastebin written in Laravel (PHP Framework). `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;24</code>** [Hastebin](https://haste.zneix.eu/about.md) - Open source pastebin written in Node.js (This is a fork with extended maintenance). ([Demo](https://haste.zneix.eu), [Source Code](https://github.com/zneix/haste-server)) `MIT` `Node.js`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code>** [Pasty](https://github.com/Lukaesebrot/pasty) - Pasty is a fast and lightweight code pasting server. ([Demo](https://p.kse.li)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code>** [SocksBin](https://github.com/magnumdingusedu/socksbin) - Simple and fast terminal based pastebin, with optional code highlighting. No specific client required, all you need is netcat. [Demo](https://socksbin.magnum.wtf). `GPL-3.0` `Python`

## Personal Dashboards

**[`^        back to top        ^`](#)**

_See also [Monitoring](#monitoring)_

- **<code>&nbsp;&nbsp;7947</code>** [Habitica](https://habitica.com/) - Habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ([Source Code](https://github.com/HabitRPG/habitrpg)) `GPL-3.0/CC-BY-NC-SA-3.0/CC-BY-SA-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;2951</code>** [Organizr](https://github.com/causefx/Organizr) - Organizr aims to be your one stop shop for your Servers Frontend. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;2193</code>** [Heimdall](https://heimdall.site/) - Heimdall is an elegant solution to organise all your web applications. ([Source Code](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;1254</code>** [wger](http://wger.de/) - Web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well. ([Demo](http://wger.de), [Source Code](https://github.com/rolandgeider/wger)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1024</code>** [Tipboard](http://allegro.tech/tipboard/) - In-house, tasty, local dashboarding system. ([Source Code](https://github.com/allegro/tipboard)) `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;991</code>** [Homer](https://github.com/bastienwirtz/homer) - A dead simple static homepage to expose your server services, with an easy yaml configuration and connectivity check. `Apache-2.0` `HTML5`
- **<code>&nbsp;&nbsp;&nbsp;948</code>** [Baby Buddy](https://github.com/cdubz/babybuddy) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time. ([Demo](https://babybuddy.herokuapp.com/)) `BSD-2-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;886</code>** [Personal management system](https://github.com/Volmarg/personal-management-system) - Central point for managing personal data (billings, payments, job holidays, notes etc.). ([Demo](http://personal-management-system.pl/)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;631</code>** [DashMachine](https://github.com/rmountjoy92/DashMachine) - Another web application bookmark dashboard, with fun features. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;214</code>** [Homepage](https://github.com/tomershvueli/homepage) - Simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;196</code>** [simple-dash](https://github.com/kutyla-philipp/simple-dash) - A simple, fully responsive Dashboard to forward to the services of your choice. ([Demo](https://kutyla-philipp.github.io/simple-dash/)) `MIT` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;15</code>** [Hiccup](https://designedbyashw.in/test/hiccup/) - A beautiful static homepage to get to your links and services quickly. It has built-in search, editing, PWA support and localstorage caching to easily organize your start page. ([Source Code](https://github.com/ashwin-pc/hiccup)) `MIT` `HTML5`

## Photo and Video Galleries

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;6730</code>** [PhotoPrism](https://photoprism.org) - Personal photo management powered by Go and Google TensorFlow.  Browse, organize, and share your personal photo collection, using the latest technologies to automatically tag and find pictures. ([Source Code](https://github.com/photoprism/photoprism)) `MIT` `Go`
- **<code>&nbsp;&nbsp;2088</code>** [OwnPhotos](https://github.com/hooram/ownphotos) - Self hosted wannabe Google Photos clone, with a slight focus on cool graphs. `MIT` `Python`
- **<code>&nbsp;&nbsp;1697</code>** [Chevereto Free](https://chevereto.com/free) - Powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. ([Source Code](https://github.com/Chevereto/Chevereto-Free)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1670</code>** [Photo Stream](https://github.com/maxvoltar/photo-stream) - Minimalist self-hosted photo stream. ([Demo](https://maxvoltar.photo/)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;1137</code>** [Piwigo](http://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. ([Demo](http://piwigo.org/demo/), [Source Code](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;644</code>** [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;460</code>** [Lychee](https://lycheeorg.github.io/) - Open source grid and album based photo-management-system. ([Source Code](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;445</code>** [Photonix](https://photonix.org/) - A new web-based photo management application with object recognition, location awareness, color analysis and other ML algorithms. ([Demo](https://demo.photonix.org/), [Source Code](https://github.com/damianmoore/photonix)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;224</code>** [Zenphoto](http://www.zenphoto.org/) - Open-source gallery and CMS project. ([Source Code](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;188</code>** [Photoview](https://github.com/viktorstrate/photoview) - A simple and user-friendly Photo Gallery for personal servers. It is made for photographers and aims to provide an easy and fast way to navigate directories, with thousands of high resolution photos. ([Demo](https://photos.qpqp.dk/)) `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;184</code>** [UberGallery](http://www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ([Source Code](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;123</code>** [Photato](https://github.com/trebonius0/Photato) - Self-hosted photo gallery, accessible through a responsive WebUI. Directly uses and indexes a specific folder in the filesystem. `AGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;102</code>** [Plumi](http://blog.plumi.org/) - Create your own sophisticated video-sharing site. ([Source Code](https://github.com/plumi/plumi.app)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;45</code>** [Quru Image Server](https://quruimageserver.com/) - High performance dynamically resizing image server offering directory based access control cropping, rotation, color management and other tools. ([Demo](https://quruimageserver.com), [Source Code](https://github.com/quru/qis)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;40</code>** [Coppermine](http://coppermine-gallery.net/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albums. ([Demo](http://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;32</code>** [Fussel](https://github.com/cbenning/fussel) - Fussel is a static photo gallery generator. Easily generate a reactive gallery and host the optimized static folder of assets. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;30</code>** [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Mediagoblin](http://mediagoblin.org) - Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc. ([Source Code](https://savannah.gnu.org/projects/mediagoblin)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [CumulusClips](http://cumulusclips.org/) - Your own video sharing website with CumulusClips video sharing script. You can build a YouTube clone where users can upload, rate, comment on videos, and much more. ([Demo](http://demo.cumulusclips.org/)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Photofloat](http://blog.zx2c4.com/567) - Web 2.0 Photo Gallery Done Right via Static JSON and Dynamic Javascript. ([Demo](http://photos.jasondonenfeld.com/)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Gallery CSS](https://benschwarz.github.io/gallery-css/) - Gallery.css is all CSS. Think: Simple, maintainable and understandable galleries without the use of Javascript. ([Source Code](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [PiGallery 2](https://bpatrik.github.io/pigallery2/) - A directory-first photo gallery website, with a rich UI, optimised for running on low resource servers. ([Demo](https://pigallery2.herokuapp.com/), [Source Code](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`

## Polls and Events

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;2450</code>** [Open Event Server](https://github.com/fossasia/open-event-server) - Enables organizers to manage events from concerts to conferences and meet-ups. `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1626</code>** [LimeSurvey](https://www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic. ([Demo](https://demo.limesurvey.org), [Source Code](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;388</code>** [Calagator](http://calagator.org/) - Event aggregator. ([Source Code](https://github.com/calagator/calagator)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;343</code>** [PHPBack](http://www.phpback.org) - The open source feedback system. ([Demo](http://www.phpback.org/demo/), [Source Code](https://github.com/ivandiazwm/phpback)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;226</code>** [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - Online scheduling application. ([Demo](https://dudle.inf.tu-dresden.de/), [Source Code](https://github.com/kellerben/dudle)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;200</code>** [JD Esurvey](https://www.jdsoft.com/jd-esurvey.html) - Open source enterprise survey web application. ([Source Code](https://github.com/JD-Software/JDeSurvey)) `AGPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;192</code>** [hitobito](https://hitobito.com/en) - A web application to manage complex group hierarchies with members, events and a lot more. ([Demo](https://demo.hitobito.com/en/users/sign_in), [Source Code](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;41</code>** [Meetable](https://meetable.org) - Event aggregator. ([Demo](https://events.indieweb.org), [Source Code](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;27</code>** [Kyélà](http://kyela.net/) - Participation polls for group events. ([Demo](https://kyela.net/concert/), [Source Code](https://github.com/abienvenu/Kyela)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;20</code>** [Clerk](https://github.com/chr15m/Clerk) - Simple event logger to keep track of periodic events, habits, etc. as they occur. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Framadate](https://framadate.org/) - Online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision. ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://git.framasoft.org/framasoft/framadate)) `CECILL-B` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Mobilizon](https://mobilizon.org) - A federated tool that helps you find, create and organise events and groups. ([Demo](https://demo.mobilizon.org/), [Source Code](https://framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Feedka](https://github.com/drabkirn/feedka) `⚠` - Open-source web application that can serve as a platform to get authentic, kindful, and constructive feedback from your friends, family, and co-workers. ([Demo](https://feedka.herokuapp.com)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Fider](http://getfider.com) - Open source alternative to UserVoice for customer feedback. ([Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider)) `MIT` `Go`

### Booking and Scheduling

- **<code>&nbsp;&nbsp;1504</code>** [Easy!Appointments](http://easyappointments.org/) - A highly customizable web application that allows your customers to book appointments with you via the web. ([Demo](http://easyappointments.org/demo/), [Source Code](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;826</code>** [Alf.io](https://alf.io/) - The open source ticket reservation system. ([Demo](https://demo.alf.io/authentication), [Source Code](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Booked](https://www.bookedscheduler.com/) - A web-based calendar and resource scheduling system that allows administered management of reservations on any number of resources. ([Demo](https://demo.bookedscheduler.com/Web/), [Source Code](https://sourceforge.net/projects/phpscheduleit/)) `GPL-3.0` `PHP`

## Proxy

**[`^        back to top        ^`](#)**

- **<code>&nbsp;31331</code>** [Traefik](https://traefik.io/) - Træfɪk is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease. It supports several backends (Docker, Swarm, Mesos/Marathon, …) to manage its configuration automatically and dynamically. ([Source Code](https://github.com/containous/traefik)) `MIT` `Go`
- **<code>&nbsp;&nbsp;4198</code>** [Redbird](https://github.com/OptimalBits/redbird) - A modern reverse proxy for node that includes cluster, HTTP2, LetsEncrypt, and Docker support. `BSD-2-Clause` `Javascript`
- **<code>&nbsp;&nbsp;3876</code>** [imgproxy](https://github.com/DarthSim/imgproxy) - Fast and secure standalone server for resizing and converting remote images. It works great when you need to resize multiple images on the fly without preparing a ton of cached resized images or re-doing it every time the design changes. `MIT` `Go/Docker`
- **<code>&nbsp;&nbsp;3528</code>** [iodine](http://code.kryo.se/iodine/) - IPv4 over DNS tunnel solution, enabling you to start up a socks5 proxy listener. ([Source Code](https://github.com/yarrick/iodine)) `ISC` `C`
- **<code>&nbsp;&nbsp;2353</code>** [Tinyproxy](https://tinyproxy.github.io/) - Light-weight HTTP/HTTPS proxy daemon. ([Source Code](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;2340</code>** [Nginx Proxy Manager](https://nginxproxymanager.com/) - Nginx Proxy Manager is an easy way to accomplish reverse proxying hosts with SSL termination. ([Source Code](https://github.com/jc21/nginx-proxy-manager)) `MIT` `Nodejs/Docker`
- **<code>&nbsp;&nbsp;2041</code>** [Pomerium](https://pomerium.io) - An identity-aware reverse proxy, successor to now obsolete oauth_proxy. It inserts an OAuth step before proxying your request to the backend, so that you can safely expose your self-hosted websites to public Internet. ([Source Code](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;1362</code>** [sish](https://github.com/antoniomika/sish) - Open source serveo/ngrok alternative providing HTTP(S)/WS(S)/TCP tunnels to localhost using only SSH. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;537</code>** [PHP-Proxy](https://www.php-proxy.com/) - Web proxy script built specifically to be fast, easy to modify and to support video sites such as YouTube. ([Demo](https://unblockvideos.com/), [Source Code](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;287</code>** [Swiperproxy](https://swiperproxy.github.io/) - Lightning-fast, open source web proxy that is easy for you to run and customize. ([Source Code](https://github.com/swiperproxy/swiperproxy)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;107</code>** [microproxy](https://github.com/thekvs/microproxy) - lightweight non-caching HTTP/HTTPS proxy server. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;23</code>** [http2-serverpush-proxy](https://github.com/n1try/http2-serverpush-proxy) - Reverse proxy that helps to automatically utilize HTTP/2.0's server push mechanism for static websites. Available as middleware and standalone application. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;20</code>** [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - SOCKS5 proxy server with built-in authentication and Telegram-bot for user management and user statistics on data spent (handy when you pay per GB of data). It is dockerised and simple to install. `Apache-2.0` `NodeJS`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;17</code>** [SOCKS5Engine](https://github.com/VeeSecurity/SOCKS5Engine) - Lightweight & resource-efficient SOCKS5 proxy server, optimized for high-load. `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. ([Source Code](https://code.launchpad.net/squid)) `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Pound](http://www.apsis.ch/pound/) - Light-weight reverse proxy and load balancer for HTTP/HTTPS. `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Privoxy](http://www.privoxy.org) - Non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPL-2.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [inlets](https://inlets.dev/) - Expose your local endpoints to the Internet - with a Kubernetes integration, Docker image and CLI available. `MIT` `Go/Docker`

## Read it Later Lists

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;&nbsp;&nbsp;70</code>** [Nunux Keeper](http://keeper.nunux.org/) - Your personal content curation service. ([Source Code](https://github.com/ncarlier/nunux-keeper)) `GPL-3.0` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;38</code>** [Wallabag](https://www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. ([Demo](https://app.wallabag.it/register/), [Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;36</code>** [Readflow](https://readflow.app) - Lightweight news reader with modern interface and features: full-text search, automatic categorization, archiving, offline support, notifications... ([Source Code](https://github.com/ncarlier/readflow)) `MIT` `Go`

## Resource Planning

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;2652</code>** [grocy](https://grocy.info/) - ERP beyond your fridge - grocy is a web-based self-hosted groceries & household management solution for your home. ([Demo](https://en.demo.grocy.info/), [Source Code](https://github.com/grocy/grocy)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;388</code>** [Tania](https://github.com/Tanibox/tania-core) - Tania is a free and open source farming management system for everyone. You can manage your areas, reservoirs, farm tasks, inventories, and the crop growing progress. `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;36</code>** [farmOS](http://farmos.org/) - Web-based farm record keeping application. ([Source Code](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP`

### Enterprise Resource Planning

- **<code>&nbsp;19245</code>** [Odoo](http://odoo.com) - Free open source ERP system. ([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;7027</code>** [ERPNext](https://erpnext.com) - Free open source ERP system. ([Demo](https://demo.erpnext.com), [Source Code](https://github.com/frappe/erpnext)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;2119</code>** [Dolibarr](https://www.dolibarr.org/) - Dolibarr ERP CRM is a modern software package to manage your company or foundation activity (contacts, suppliers, invoices, orders, stocks, agenda, accounting, ...). ([Demo](https://www.dolibarr.org/onlinedemo.php), [Source Code](https://github.com/Dolibarr/dolibarr)) `GPL-3.0-or-later` `PHP`
- **<code>&nbsp;&nbsp;1988</code>** [OSPOS](https://www.opensourcepos.org/) - Open Source Point of Sale is a web based point of sale system. ([Demo](https://demo.opensourcepos.org/), [Source Code](https://github.com/opensourcepos/opensourcepos)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;205</code>** [LedgerSMB](https://ledgersmb.org/) - Integrated accounting and ERP system for small and midsize businesses, with double entry accounting, budgeting, invoicing, quotations, projects, orders and inventory management, shipping and more. ([Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [OFBiz](https://ofbiz.apache.org/) - FOSS enterprise resource planning system with a suite of business applications flexible enough to be used across any industry. ([Source Code](https://svn.apache.org/viewvc/ofbiz/)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tryton](http://www.tryton.org/) - Free open source business solution. ([Demo](http://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)) `GPL-3.0` `Python`

## Search Engines

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;9818</code>** [MeiliSearch](https://meilisearch.com) - Ultra relevant, instant and typo-tolerant full-text search API. ([Source Code](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust`
- **<code>&nbsp;&nbsp;3176</code>** [Typesense](https://typesense.org) - Blazing fast, typo-tolerant open source search engine optimized for developer happiness and ease of use. ([Source Code](https://github.com/typesense/typesense)) `GPL-3.0` `C++`
- **<code>&nbsp;&nbsp;1972</code>** [Yacy](http://yacy.net/en/index.html) - Peer based, decentralized search engine server. ([Demo](http://search.yacy.net/), [Source Code](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java`
- **<code>&nbsp;&nbsp;1595</code>** [Ambar](https://ambar.cloud) - Document Search Engine (OCR, Store & Search). ([Demo](https://app.ambar.cloud/), [Source Code](https://github.com/RD17/ambar)) `MIT` `Nodejs/Python`
- **<code>&nbsp;&nbsp;1168</code>** [Gigablast](http://www.gigablast.com/) - open source search engine. ([Source Code](https://github.com/gigablast/open-source-search-engine)) `Apache-2.0` `C++`
- **<code>&nbsp;&nbsp;&nbsp;203</code>** [sist2](https://github.com/simon987/sist2) - Lightning-fast file system indexer and search tool. ([Demo](https://sist2.simon987.net/)) `GPL-3.0` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Searx](https://asciimoo.github.io/searx/) - Privacy-respecting, hackable metasearch engine. ([Demo](https://searx.me/), [Source Code](https://github.com/asciimoo/searx)) `AGPL-3.0` `Python`

## Software Development

**[`^        back to top        ^`](#)**

### Project Management

_See also [Ticketing](#ticketing), [Task management/To-do lists](#task-managementto-do-lists), [awesome-sysadmin/Code Review](https://github.com/n1trux/awesome-sysadmin#code-review)_

- **<code>&nbsp;35723</code>** [Gogs](https://gogs.io/) - Painless self-hosted Git Service written in Go. ([Demo](https://try.gogs.io/), [Source Code](https://github.com/gogits/gogs)) `MIT` `Go`
- **<code>&nbsp;27684</code>** [UVDesk](https://www.uvdesk.com/) - UVDesk community is a service oriented, event driven extensible opensource helpdesk system that can be used by your organization to provide efficient support to your clients effortlessly whichever way you imagine. ([Demo](https://demo.uvdesk.com/), [Source Code](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- **<code>&nbsp;11803</code>** [Phabricator](http://phabricator.org/) - Collection of web applications that help build better software. ([Demo](https://secure.phabricator.com/), [Source Code](https://github.com/phacility/phabricator)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;7785</code>** [Gitolite](http://gitolite.com/gitolite/index.html) - Gitolite allows you to setup git hosting on a central server, with fine-grained access control and many more powerful features. ([Source Code](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
- **<code>&nbsp;&nbsp;4305</code>** [OpenProject](https://www.openproject.org) - OpenProject is a web-based project management system. ([Source Code](https://github.com/opf/openproject)) `GPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;2791</code>** [Gitlist](http://gitlist.org/) - Web-based git repository browser - GitList allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history and diffs. ([Source Code](https://github.com/klaussilveira/gitlist)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;1838</code>** [Gitblit](http://gitblit.com/) - Pure Java stack for managing, viewing, and serving Git repositories. ([Source Code](https://github.com/gitblit/gitblit)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;1622</code>** [Bonobo Git Server](https://bonobogitserver.com/) - Set up your own self hosted git server on IIS for Windows. Manage users and have full control over your repositories with a nice user friendly graphical interface. ([Source Code](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
- **<code>&nbsp;&nbsp;1296</code>** [Goodwork](https://usegood.work/) - Self hosted project management and collaboration tool powered by Laravel & VueJS. ([Demo](https://github.com/iluminar/goodwork#demo), [Source Code](https://github.com/iluminar/goodwork)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;850</code>** [GitPrep](http://gitprep.yukikimoto.com/) - Portable Github clone. ([Demo](http://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi), [Source Code](https://github.com/yuki-kimoto/gitprep)) `Artistic-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;727</code>** [Git WebUI](https://github.com/alberthier/git-webui) - Standalone web based user interface for git repositories. `Apache-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;673</code>** [Tuleap](https://www.tuleap.org/) - Tuleap is a libre suite to plan, track, code and collaborate on software projects. ([Source Code](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;656</code>** [ZenTao](http://www.zentao.pm/) - An agile(scrum) project management system/tool. ([Demo](http://demo.zentao.pm/user-login.html), [Source Code](https://github.com/easysoft/zentaopms)) `ZPL-1.2` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;583</code>** [Leantime](https://leantime.io) - Leantime is a lean project management system for small teams and startups helping to manage projects from ideation through delivery. ([Source Code](https://github.com/leantime/leantime)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;578</code>** [Klaus](https://github.com/jonashaag/klaus) - Simple, easy-to-set-up Git web viewer that Just Works. `ISC` `Python`
- **<code>&nbsp;&nbsp;&nbsp;513</code>** [Lavagna](http://lavagna.io) - Lavagna is an open-source issue/project management tool designed for small teams. Lightweight, pure Java, easy to install, easy to use. ([Source Code](https://github.com/digitalfondue/lavagna)) `GPL-3.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;308</code>** [Phproject](http://www.phproject.org/) - High performance full-featured project management system. ([Demo](http://demo.phproject.org/), [Source Code](https://github.com/Alanaktion/phproject)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;145</code>** [Titra](https://titra.io/en/free-time-tracking-online/) - Time-tracking solution for freelancers and small teams. ([Demo](https://app.titra.io/try), [Source Code](https://github.com/kromitgmbh/titra)) `GPL-3.0` `JavaScript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;93</code>** [Re:Backlogs](https://github.com/kaishuu0123/rebacklogs) - Project management and collaboration tool powered by Ruby on Rails & VueJS. ([Demo](https://rebacklogs.saino.me/users/sign_up)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;38</code>** [SCM Manager](https://www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories over http. ([Source Code](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;27</code>** [Microgit](https://github.com/microgit-com/microgit) - Git hosting service made in Crystal and Lucky. `MIT` `Crystal`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code>** [Lazylead](https://lazylead.org) `⚠` - Eliminate the annoying work within ticketing systems (Jira, GitHub, Trello). Allows to automate daily actions like tickets fields verification, email notifications by JQL/GQL, meeting requests to your (or teammates) calendar. ([Source Code](https://github.com/dgroup/lazylead)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [ProjeQtOr](https://www.projeqtor.org/) - A complete, mature, multi-user project management system with extensive functionality for all phases of a project. ([Demo](https://demo.projeqtor.org/), [Source Code](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [GitLab](http://gitlab.org/) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis. ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker. `BSD-2-Clause-FreeBSD` `C`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Redmine](http://www.redmine.org/) - Redmine is a flexible project management web application. ([Demo](http://demo.redmine.org/), [Source Code](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [RhodeCode](https://rhodecode.com/) - RhodeCode is an open source platform for software development teams. It unifies and simplifies repository management for Git, Subversion, and Mercurial. ([Demo](https://try.rhodecode.com/), [Source Code](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Kallithea](https://kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface. ([Source Code](https://kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Taiga](https://taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods. ([Source Code](https://github.com/taigaio)) `AGPL-3.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Pagure](https://pagure.io/pagure) - A lightweight, powerful, and flexible git-centric forge with features laying the foundation for federated and decentralized development. ([Demo](https://pagure.io/)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Trac](http://trac.edgewall.org/) - Trac is an enhanced wiki and issue tracking system for software development projects. `BSD-3-Clause` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Octobox](https://octobox.io/) `⚠` - Take back control of your GitHub Notifications. ([Source Code](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Gitea](https://gitea.io) - Community managed fork of Gogs, lightweight code hosting solution. ([Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [gitbucket](https://gitbucket.github.io/gitbucket-news/) - Easily installable GitHub clone powered by Scala. ([Source Code](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`

### Bug Trackers

_See [Ticketing](#ticketing)_

### IDE/Tools

- **<code>&nbsp;36349</code>** [Code-Server](https://coder.com/) - Visual Studio Code in the browser, hosted on a remote server. ([Source Code](https://github.com/cdr/code-server)) `MIT` `Nodejs/Docker`
- **<code>&nbsp;&nbsp;7082</code>** [Regexr](http://regexr.com/) - RegExr is a HTML/JS based tool for creating, testing, and learning about Regular Expressions. ([Source Code](https://github.com/gskinner/regexr)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;6275</code>** [Eclipse Che](http://www.eclipse.org/che/) - Open source workspace server and cloud IDE. ([Source Code](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- **<code>&nbsp;&nbsp;4124</code>** [JS Bin](http://jsbin.com/) - Open source collaborative web development debugging tool. ([Source Code](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;4033</code>** [sourcegraph](https://sourcegraph.com) - Sourcegraph is a fast, open-source, fully-featured code search and navigation engine written in Go. ([Source Code](https://github.com/sourcegraph/sourcegraph)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;3400</code>** [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. ([Source Code](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- **<code>&nbsp;&nbsp;1844</code>** [RequestBin](https://github.com/Runscope/requestbin) - Inspect HTTP requests. Debug webhooks. `MIT` `python`
- **<code>&nbsp;&nbsp;1814</code>** [Koding](http://www.koding.com/) - The simplest way to manage your entire Dev Infrastructure. ([Source Code](https://github.com/koding/koding)) `Apache-2.0` `Nodejs`
- **<code>&nbsp;&nbsp;1491</code>** [ML Workspace](https://github.com/ml-tooling/ml-workspace) - All-in-one web-based IDE for machine learning and data science. `Apache-2.0` `Docker`
- **<code>&nbsp;&nbsp;1227</code>** [ICEcoder](https://icecoder.net/) - ICEcoder is a web IDE / browser based code editor, which allows you to develop websites directly within the web browser. ([Demo](http://demo.icecoder.net/ICEcoder/), [Source Code](https://github.com/icecoder/ICEcoder)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;475</code>** [Judge0 API](https://api.judge0.com) - Open source API to compile and run source code. ([Source Code](https://github.com/judge0/api)) `GPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;284</code>** [Babelfish](https://github.com/bblfsh/bblfshd) - Self-hosted server for source code parsing. It can parse any file, in any supported language, extract an Abstract Syntax Tree from it, and convert it to a Universal Abstract Syntax Tree which can enable further analysis and transformation. `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;187</code>** [Gitpod](https://gitpod.io/) - Online IDE for GitHub and GitLab. ([Demo](https://gitpod.io/#https://github.com/awesome-selfhosted/awesome-selfhosted), [Source Code](https://github.com/gitpod-io/self-hosted)) `EPL-2.0` `Go/Docker`
- **<code>&nbsp;&nbsp;&nbsp;130</code>** [Wakapi](https://github.com/n1try/wakapi) - Tracking tool for coding statistics, compatible with WakaTime. `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;94</code>** [Atheos](https://www.atheos.io) - Web-based IDE framework with a small footprint and minimal requirements, continued from Codiad. ([Source Code](https://github.com/Atheos/Atheos)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;82</code>** [Hakatime](https://github.com/mujx/hakatime) - WakaTime server implementation with analytics dashboard. `Unlicense` `Haskell`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;29</code>** [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - Quickly mock away any webservice using HttPlaceholder. HttPlaceholder lets you specify what the request should look like and what response needs to be returned. `MIT` `C#`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [JupyterLab](http://jupyterlab.github.io/jupyterlab/) - Web-based environment for interactive and reproducible computing. ([Demo](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [Source Code](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`

### Continuous Integration

_See [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/n1trux/awesome-sysadmin#continuous-integration--continuous-deployment)_

### UX testing

- **<code>&nbsp;18954</code>** [Selenoid](http://aerokube.com/selenoid/latest/) - Lightweight Selenium hub implementation launching browsers within Docker containers. ([Source Code](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;66</code>** [Uier](https://github.com/sjoerdvanderhoorn/Uier) - Codeless or low-code User Experience test editing and management using Selenium to perform testing or UI automation. Uier tends to be a free self hostable alternative to Applitools, Endtest, Ghost Inspector, Usetrace, Screenster and many others. `Apache-2.0` `Nodejs`

### FaaS/Serverless

_[Serverless computing on Wikipedia](https://en.wikipedia.org/wiki/Serverless_computing)_

- **<code>&nbsp;27025</code>** [LocalStack](https://localstack.cloud/) - LocalStack is a fully functional local AWS cloud stack. This includes Lambda for serverless computation. ([Source Code](https://github.com/localstack/localstack)) `Apache-2.0` `Python/Other`
- **<code>&nbsp;18638</code>** [OpenFaaS](https://www.openfaas.com/) - Serverless Functions Made Simple for Docker & Kubernetes. ([Source Code](https://github.com/openfaas/faas)) `MIT` `Go`
- **<code>&nbsp;&nbsp;3681</code>** [Appwrite](https://appwrite.io) - End to end backend server for web, native, and mobile developers 🚀. ([Source Code](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `PHP`
- **<code>&nbsp;&nbsp;2802</code>** [IronFunctions](https://github.com/iron-io/functions) - The serverless microservices platform by [iron.io](https://www.iron.io/). `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;1513</code>** [fx](https://github.com/metrue/fx) - fx is a tool to help you do Function as a Service with painless on your own servers. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;85</code>** [Trusted-CGI](https://github.com/reddec/trusted-cgi) - Lightweight self-hosted lambda/applications/cgi/serverless-functions platform. `MIT` `Go`

### API Management

- **<code>&nbsp;24814</code>** [Hoppscotch](https://hoppscotch.io) - A free, fast and beautiful API request builder. ([Source Code](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Vue/Nuxt`
- **<code>&nbsp;19194</code>** [Hasura](https://hasura.io) - Fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events. ([Source Code](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell`
- **<code>&nbsp;&nbsp;5826</code>** [Tyk](https://tyk.io) - Fast and scalable open source API Gateway. Out of the box, Tyk offers an API Management Platform with an API Gateway, API Analytics, Developer Portal and API Management Dashboard. ([Source Code](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go`
- **<code>&nbsp;&nbsp;3247</code>** [KrakenD](https://www.krakend.io/) - Open source High-Performance API Gateway. ([Source Code](https://github.com/devopsfaith/krakend)) `Apache-2.0` `Go`
- **<code>&nbsp;&nbsp;1224</code>** [Kong](https://konghq.com/kong/) - The World’s Most Popular Open Source Microservice API Gateway and Platform. ([Source Code](https://github.com/Kong/kong)) `Apache-2.0` `Lua`
- **<code>&nbsp;&nbsp;1110</code>** [DreamFactory](https://www.dreamfactory.com/) - Turns any SQL/NoSQL/Structured data into Restful API. ([Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;880</code>** [Fusio](http://www.fusio-project.org/) - Open-source API management platform which helps to build and manage REST APIs. ([Demo](http://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;584</code>** [Pizzly](https://github.com/bearer/pizzly) - Open-source API Integrations Manager that provides everything a developer needs to interact with OAuth based APIs. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;361</code>** [Para](http://www.paraio.org) - Flexible and modular backend framework/server for object persistence, API development and authentication. ([Source Code](https://github.com/erudika/para)) `Apache-2.0` `Java`
- **<code>&nbsp;&nbsp;&nbsp;117</code>** [Hapttic](https://github.com/jsoendermann/hapttic) - Simple HTTP server that forwards all requests to a shell script to handle webhooks you receive. `Apache-2.0` `Go`

### Documentation Generators

_See also [Static site generators](#static-site-generators)_

- **<code>&nbsp;&nbsp;6132</code>** [Read the Docs](https://docs.readthedocs.org/en/latest/install.html) - Host documentation, making it fully searchable and easy to find; import your docs using any major version control system, including Mercurial, Git, Subversion, and Bazaar. ([Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/rtfd/readthedocs.org)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;116</code>** [Docstore](http://haldean.org/) - Static document hosting without any server-side processing, does not require you to recompile every time you change an article. Clone the repository and add articles in the text/ directory to get started. ([Source Code](https://github.com/haldean/docstore)) `BSD-3-Clause` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;93</code>** [markdown-tree](https://github.com/mil/markdown-tree) - Serve a hierarchy / tree directory of markdown files. Use intended for small sites built in markdown. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Flatdoc](http://ricostacruz.com/flatdoc/) - Small Javascript file that fetches Markdown files and renders them as full pages. `MIT` `Javascript`

### Localization

- **<code>&nbsp;&nbsp;2119</code>** [Weblate](https://weblate.org) - Web-based translation tool with tight version control integration. ([Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1322</code>** [Pootle](http://pootle.translatehouse.org) - Online translation and localization tool. ([Source Code](https://github.com/translate/pootle)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1297</code>** [Traduora](https://traduora.com) - Translation management platform for teams. ([Source Code](https://github.com/traduora/traduora)) `AGPL-3.0` `Docker/Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;665</code>** [Accent](https://www.accent.reviews/) - Open-source, self-hosted, developer-oriented translation tool. ([Source Code](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir`
- **<code>&nbsp;&nbsp;&nbsp;278</code>** [Zanata](http://zanata.org) - Web-based translation platform for translators, content creators and developers to manage localisation projects. ([Source Code](https://github.com/zanata/zanata-platform)) `GPL-2.0` `Java`

## Static site generators

**[`^        back to top        ^`](#)**

_See https://staticsitegenerators.net and https://www.staticgen.com_

## Task management/To-do lists

**[`^        back to top        ^`](#)**

_See also [Project Management](#project-management) and [Ticketing](#ticketing)._

- **<code>&nbsp;16747</code>** [Wekan](https://wekan.github.io/) - Open-source Trello-like kanban. ([Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;5485</code>** [Kanboard](http://kanboard.net/) - Simple and open source visual task board. ([Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;1611</code>** [Restyaboard](http://restya.com/board/) - Open source Trello-like kanban board. ([Demo](http://restya.com/board/demo.html), [Source Code](https://github.com/RestyaPlatform/board)) `OSL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1147</code>** [TaskBoard](http://taskboard.matthewross.me/) - Kanban-inspired app for keeping track of things that need to get done. ([Demo](https://taskboard.matthewross.me/demo.html), [Source Code](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;967</code>** [Tracks](http://www.getontracks.org/) - Web-based application to help you implement David Allen’s [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) methodology. ([Source Code](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;662</code>** [Planka](https://planka.app/) - Open source Trello alternative. ([Demo](https://plankanban.github.io/planka/#/), [Source Code](https://github.com/plankanban/planka)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;519</code>** [Nullboard](https://github.com/apankrat/nullboard) - Single-page minimalist kanban board; compact, highly readable and quick to use. ([Demo](https://nullboard.io/preview)) `BSD-2-Clause` `Javascript`
- **<code>&nbsp;&nbsp;&nbsp;484</code>** [Tasks](https://github.com/thewhitetulip/Tasks) - Kanban based to-do list manager written in Go. `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;440</code>** [Taskwarrior](https://taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way. ([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
- **<code>&nbsp;&nbsp;&nbsp;100</code>** [Volition](https://github.com/usevolition/volition) - Opinionated open-source task management. `MIT` `Ruby`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;92</code>** [Tasks](https://github.com/m1guelpf/tasks) - Simple tasks and notes manager written in PHP, jQuery and Bootstrap using a custom flat file database. `MPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;73</code>** [todoMini](https://www.todomini.app/) - Mobile friendly zero-feature TODO list web app. Unix philosophy. ([Demo](https://appmini.github.io/todoMini/?demo), [Source Code](https://github.com/appMini/todoMini)) `GPL-3.0` `PHP/Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;55</code>** [todo](https://github.com/prologic/todo) - Simple todo list manager. ([Demo](https://todo.mills.io)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;50</code>** [Tinyissue](https://github.com/satrun77/tinyissue) - Simple Issue Tracking for Teams. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;28</code>** [myTinyTodo](http://www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant. ([Demo](http://www.mytinytodo.net/demo/), [Source Code](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;12</code>** [Kanbana](https://github.com/SrGMC/kanbana) - Create boards to track users and projects from flat markdown files. Forked from Crepido. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;12</code>** [PHP Task/Todo list](https://github.com/lgg/tasks.php) - Simple task/todo list that uses a JSON text file for the tasks. `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code>** [Task Keeper](https://github.com/nymanjens/piga) - List editor for power users, backed by a self-hosted server. `Apache-2.0` `Scala`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Taskfreak](http://www.taskfreak.com/original) - Simple but efficient web based task manager written in PHP. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Vikunja](https://vikunja.io/) - The to-do app to organize your life. ([Demo](https://try.vikunja.io/login), [Source Code](https://kolaente.dev/vikunja/)) `GPL-3.0` `Go`

## Ticketing

**[`^        back to top        ^`](#)**

_See also [Task management/To-do lists](#task-managementto-do-lists) and [Project Management](#project-management)_

- **<code>&nbsp;&nbsp;3287</code>** [Sentry On-Premise](https://github.com/getsentry/onpremise) - A powerful error tracking platform with wide language support and a robust API. ([Source Code](https://github.com/getsentry/sentry)) `BSD-3-Clause` `Python/Django`
- **<code>&nbsp;&nbsp;2327</code>** [Zammad](https://zammad.org/) - Easy to use but powerful open-source support and ticketing system. ([Source Code](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby`
- **<code>&nbsp;&nbsp;1956</code>** [Helpy](https://helpy.io) - Helpy is a modern, open source helpdesk customer support application. Features include knowledgebase, community discussions and support tickets integrated with email. ([Demo](https://demo.helpy.io), [Source Code](https://github.com/helpyio/helpy)) `MIT` `Ruby`
- **<code>&nbsp;&nbsp;1698</code>** [HuBoard](https://github.com/huboard/huboard) `⚠` - Instant project management for your GitHub issues (Connects directly GitHub API). `MIT` `Ruby`
- **<code>&nbsp;&nbsp;1407</code>** [Erxes](https://erxes.io/install/) - Marketing, sales, and customer service platform designed to help businesses attract more engaged customers. ([Demo](https://demo.erxes.io/), [Source Code](https://github.com/erxes/erxes)) `GPL-3.0` `Javascript`
- **<code>&nbsp;&nbsp;1277</code>** [MantisBT](https://www.mantisbt.org/) - Self hosted bug tracker, fits best for software development. ([Demo](https://www.mantisbt.org/bugs/my_view_page.php), [Source Code](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;879</code>** [FreeScout](https://github.com/freescout-helpdesk/freescout) - Open source clone of Help Scout: email-based customer support application, help desk and shared mailbox. `AGPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;742</code>** [OTRS](http://www.otrs.com/) - Trouble ticket system for assigning tickets to incoming queries and tracking further communications. ([Source Code](https://github.com/OTRS/otrs)) `AGPL-3.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;550</code>** [Request Tracker](https://www.bestpractical.com/rt/) - An enterprise-grade issue tracking system. ([Source Code](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;540</code>** [SIT](https://sit.fyi/) - SCM-agnostic, file-based, offline-first, immutable issue tracker. ([Source Code](https://github.com/sit-fyi/sit)) `MIT` `Apache-2.0` `Rust`
- **<code>&nbsp;&nbsp;&nbsp;524</code>** [OpenSupports](https://www.opensupports.com/) - Multi language ticket system with FAQ, role management, metrics and canned response features. ([Demo](https://www.opensupports.com/demo/), [Source Code](https://github.com/opensupports/opensupports)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;450</code>** [TheBugGenie](http://www.thebuggenie.org) - friendly project management and issue tracking tool, with extensive user rights system. ([Source Code](https://github.com/thebuggenie/thebuggenie)) `MPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;322</code>** [Flyspray](http://www.flyspray.org/) - Uncomplicated, web-based bug tracking system. ([Source Code](https://github.com/Flyspray/flyspray)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;48</code>** [DiamanteDesk](http://diamantedesk.com/) - DiamanteDesk is FREE Open Source easy-to-use help-desk solution. ([Demo](http://diamantedesk.com/demo/), [Source Code](https://github.com/eltrino/diamantedesk-application)) `OSL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;26</code>** [Bumpy Booby](http://bumpy-booby.derivoile.fr/) - Simple, responsive and highly customizable PHP bug tracking system. ([Source Code](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;13</code>** [django-todo](http://django-todo.org/) - django-todo is a pluggable, multi-user, multi-group, multi-list todo and ticketing system - a reusable app designed to be dropped into any existing Django project. ([Source Code](https://github.com/shacker/django-todo)) `BSD-3-Clause` `Python/Django`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8</code>** [Bugzilla](https://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. `MPL-2.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [osTicket](http://osticket.com/) - Manage, organize and archive all your support requests and responses in one place. ([Source Code](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`

## URL Shorteners

_Before hosting one, please see [shortcomings](https://en.wikipedia.org/wiki/URL_shortening#Shortcomings) of URL shorteners._

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;6599</code>** [YOURLS](http://yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. ([Source Code](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;4316</code>** [Kutt](https://kutt.it) - A modern URL shortener with support for custom domains. ([Source Code](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;3487</code>** [Polr](https://project.polr.me/) - Modern, minimalist, modular, and lightweight URL shortener. ([Source Code](https://github.com/Cydrobolt/polr)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;571</code>** [Shlink](https://shlink.io) - URL shortener with REST API and command line interface. Includes official progressive web application and docker images. ([Source Code](https://github.com/shlinkio/shlink), [Clients](https://shlink.io/apps)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;156</code>** [Lstu](https://github.com/ldidry/lstu) - _Let's SHorten That Url_ - Lightweight URL shortener. `WTFPL` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;152</code>** [url-shortener](https://github.com/cagataycali/url-shortener) `⚠` - Shitty url shortener, emoji and AI powered. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;66</code>** [shorturl](https://github.com/prologic/shorturl) - Simple URL shortener with very tiny URLs. ([Demo](https://url.mills.io)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;52</code>** [reduc.io](https://github.com/ziyasal/reducio) - URL shortener service written in Scala, using Akka-Http and Redis. `MIT` `Scala`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;47</code>** [gShort](https://github.com/someone-stole-my-name/gShort) - Privacy-friendly self-hosted URL shortener. ([Demo](http://gshort.christiansegundo.com/)) `GPL-3.0` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;42</code>** [liteshort](https://github.com/132ikl/liteshort) - User-friendly, actually lightweight, and configurable URL shortener. ([Demo](https://ls.ikl.sh)) `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;28</code>** [schort](https://github.com/sqozz/schort) - No login, no javascript, just short links. ([Demo](https://s.wx0.de)) `CC0-1.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;20</code>** [ReducePy](https://github.com/abdullahselek/ReducePy) - URL shortener service using Tornado and Redis runs on Docker and Kubernetes. `MIT` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;20</code>** [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL shortener, public or private (with account). Minimalist and lightweight. No dependencies. ([Demo](https://u.azlux.fr)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;18</code>** [Simply Shorten](https://github.com/draganczukp/simply-shorten) - A simple URL shortener that just shortens links. `MIT` `Java`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code>** [URL-Shortener](https://github.com/sapioit/URL-shortener) - Make your long links short and only uses lowercase, so you can write and spell them faster. ([Demo](http://scurtez.cf)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code>** [Link-shortener-bot](https://github.com/tommyku/link-shortener-front-end) `⚠` - URL shortener using a Telegram Bot. ([Demo](http://t.me/GiveMeShortLinkBot)) `MIT` `Ruby`

## VPN

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#vpn_

## Web servers

**[`^        back to top        ^`](#)**

_See https://github.com/n1trux/awesome-sysadmin#web_

## Wikis

**[`^        back to top        ^`](#)**

_See also [Documentation Generators](#documentation-generators), [Wikimatrix](http://www.wikimatrix.org/), [Wiki Engines on WikiIndex](http://wikiindex.org/Category:Wiki_Engine), [List of wiki software on wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software on wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)._

- **<code>&nbsp;11410</code>** [Wiki.js](https://wiki.js.org/) - Modern, lightweight and powerful wiki app built on NodeJS, Git and Markdown. ([Demo](https://docs.requarks.io)) `AGPL-3.0` `Nodejs`
- **<code>&nbsp;11064</code>** [Gollum](https://github.com/gollum/gollum) - Simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby`
- **<code>&nbsp;10025</code>** [Outline](https://www.getoutline.com/) `⚠` - An open, extensible, wiki for your team built using React and Node.js. ([Source Code](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;5598</code>** [BookStack](https://www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion. ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)) `MIT` `PHP`
- **<code>&nbsp;&nbsp;5303</code>** [TiddlyWiki](http://tiddlywiki.com/) - Reusable non-linear personal web notebook. ([Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- **<code>&nbsp;&nbsp;3013</code>** [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - Easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain files, therefore no database is required. ([Source Code](https://github.com/splitbrain/dokuwiki)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;2300</code>** [Raneto](http://raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;1853</code>** [Gitit](https://github.com/jgm/gitit) - Wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPL-2.0` `Haskell`
- **<code>&nbsp;&nbsp;1360</code>** [django-wiki](https://github.com/django-wiki/django-wiki) - Wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models. ([Demo](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- **<code>&nbsp;&nbsp;1194</code>** [Documize](https://documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. ([Source Code](https://github.com/documize/community)) `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;1100</code>** [Zim](https://zim-wiki.org/) - Graphical text editor used to maintain a collection of wiki pages. Each page can contain links to other pages, simple formatting and images. ([Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;971</code>** [jingo](https://github.com/claudioc/jingo) - Git based wiki engine written for node.js, with a decent design, a search capability and good typography. `MIT` `Nodejs`
- **<code>&nbsp;&nbsp;&nbsp;682</code>** [Cowyo](https://github.com/schollz/cowyo) - Cowyo is a feature-rich wiki for minimalists. ([Demo](https://cowyo.com)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;566</code>** [XWiki](http://www.xwiki.org) - Second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture. ([Demo](http://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java`
- **<code>&nbsp;&nbsp;&nbsp;162</code>** [MoinMoin](https://moinmo.in/) - Advanced, easy to use and extensible WikiEngine with a large community of users. ([Source Code](https://github.com/moinwiki/moin-1.9)) `GPL-2.0` `Python`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;85</code>** [wiki](https://github.com/prologic/wiki) - Simple Markdown based wiki engine. ([Demo](https://wiki.mills.io)) `MIT` `Go`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;77</code>** [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - Complete markdown-powered wiki contained in a single PHP file. ([Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;27</code>** [PineDocs](https://github.com/xy2z/PineDocs) - Simple, fast, customizable and lightweight site for browsing files. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month. ([Demo](https://en.wikipedia.org/wiki/Main_Page), [Source Code](https://phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [TWiki](http://twiki.org/) - TWiki is a Perl-based structured wiki application, typically used to run a collaboration platform, knowledge or document management system, a knowledge base, or team portal. ([Demo](http://twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)) `GPL-1.0` `Perl`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [PmWiki](http://www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [WiKiss](http://wikiss.tuxfamily.org/) - Wiki, simple to use and install. ([Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Tiki](https://tiki.org) - Wiki CMS Groupware with the most built-in features. ([Demo](https://tiki.org/Demo), [Source Code](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/)) `LGPL-2.1` `PHP`

## Self-hosting Solutions

**[`^        back to top        ^`](#)**

- **<code>&nbsp;&nbsp;9834</code>** [sovereign](https://github.com/sovereign/sovereign) - Set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more. `GPL-3.0` `YAML/Other`
- **<code>&nbsp;&nbsp;5633</code>** [Sandstorm](https://sandstorm.io/) - Personal server for running self-hosted apps easily and securely. ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Other`
- **<code>&nbsp;&nbsp;1954</code>** [1Backend](https://github.com/1backend/1backend) - Self-host web apps, microservices and lambdas on your server. Advanced features enable service reuse and composition. `AGPL-3.0` `Go`
- **<code>&nbsp;&nbsp;1854</code>** [OpenMediaVault](http://www.openmediavault.org/) - OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. ([Source Code](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- **<code>&nbsp;&nbsp;1682</code>** [FreeNAS](https://www.freenas.org/) - Network-attached storage (NAS) software based on FreeBSD and the OpenZFS file system. Support for SMB, AFP, NFS, iSCSI, SSH, rsync and FTP/TFTP protocols. Advanced features include full-disk encryption and plug-ins. ([Source Code](https://github.com/freenas/freenas)) `BSD-3-Clause` `Python/Other`
- **<code>&nbsp;&nbsp;1167</code>** [NextCloudPi](https://nextcloudpi.com/) - Nextcloud preinstalled and preconfigured, with a text and web management interface and all the tools needed to self host private data. With installation images for Raspberry Pi, Odroid, Rock64, Docker, and a curl installer for Armbian/Debian. ([Source Code](https://github.com/nextcloud/nextcloudpi)) `GPL-2.0-or-later` `Bash/PHP`
- **<code>&nbsp;&nbsp;1101</code>** [DockSTARTer](https://dockstarter.com/) - DockSTARTer helps you get started with home server apps running in Docker. ([Source Code](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- **<code>&nbsp;&nbsp;1003</code>** [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - Build a full-featured home server with this playbook and an Ubuntu box. `MIT` `YAML/Docker`
- **<code>&nbsp;&nbsp;&nbsp;226</code>** [Syncloud](https://syncloud.org/) - Your own online file storage, social network or email server. ([Source Code](https://github.com/syncloud/platform)) `GPL-3.0` `Python/Other`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;72</code>** [Cloud Computer](https://cloud-computer.dev) - A computer in the cloud that deploys with one click and makes applications accessible through a web browser. ([Source Code](https://github.com/cloud-computer/cloud-computer)) `MIT` `Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;67</code>** [WikiSuite](https://wikisuite.org) - The most comprehensive and integrated Free / Libre / Open Source enterprise software suite. ([Source Code](https://wikisuite.org/Source-Code)) `Multiple` `ClearOS`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;35</code>** [DietPi](http://dietpi.com/) - Minimal Debian OS optimized for single-board computers, which allows you to easily install and manage several services for selfhosting at home. ([Source Code](https://github.com/Fourdee/DietPi)) `GPL-2.0` `Shell`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;16</code>** [CharjaBox](https://github.com/CherryKitten/CharjaBox) - Highly configurable Ansible based Homeserver setup using Docker. `GPL-3.0` `YAML/Ansible/Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</code>** [UBOS](http://ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., and other features. `GPL-3.0` `Perl/Other`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [HomelabOS](https://homelabos.com) - Your very own offline-first privacy-centric open-source data-center. Deploy over 100 services with a few commands. ([Source Code](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [Piratebox](https://github.com/PirateBox-Dev) - DIY anonymous offline file-sharing and communications system built with free software and inexpensive off-the-shelf hardware. `GPL-3.0` `Python/Other`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [FLAP](https://www.flap.cloud) - Low maintenance framework to manage self-hosted services. ([Source Code](https://gitlab.com/flap-box/flap)) `AGPL-3.0` `Docker/Shell`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [FreedomBox](https://wiki.debian.org/FreedomBox) - Community project to develop, design and promote personal servers running free software for private, personal, communications. `GPL-3.0` `Python/Other`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [FreedomBone](https://freedombone.net/) - Home server configuration based on Debian. ([Source Code](https://code.freedombone.net/bashrc/freedombone)) `AGPL-3.0` `Shell`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [YunoHost](https://yunohost.org/) - Server operating system aiming to make self-hosting accessible to everyone. ([Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Other`
- **<code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0</code>** [DPlatform](https://dfabric.github.io/DPlatform-Shell/) - Deploy self-hosted apps easily: simple, bloat-free, independent installation. ([Source Code](https://github.com/j8r/DPlatform)) `MIT` `Shell`

<!-- END SOFTWARE LIST -->

--------------------

## List of Licenses

**[`^        back to top        ^`](#)**

- `⚠ ` - Depends on a proprietary service outside the user's control
- `0BSD` - [BSD Zero-Clause Licence](https://opensource.org/licenses/0BSD)
- `AAL` - [Attribution Assurance License](https://opensource.org/licenses/AAL)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
- `AGPL-3.0-only` - [GNU Affero General Public License 3.0 only](https://spdx.org/licenses/AGPL-3.0-only.html)
- `Apache-2.0` - [Apache, Version 2.0](http://www.apache.org/licenses/)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://opensource.org/licenses/APSL-2.0)
- `Artistic-2.0` - [Artistic License Version 2.0](http://opensource.org/licenses/Artistic-2.0)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://opensource.org/licenses/BSD-2-Clause)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://www.freebsd.org/copyright/freebsd-license.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://opensource.org/licenses/BSD-3-Clause)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://fedoraproject.org/wiki/Licensing/BSD_with_Attribution)
- `CC-BY-NC-SA-3.0` - [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-nc-sa/3.0/)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-sa/3.0/)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)
- `CC0-1.0` - [Public Domain](https://creativecommons.org/about/cc0/)
- `CDDL-1.0` - [Common Development and Distribution License](https://opensource.org/licenses/CDDL-1.0)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](http://opensource.org/licenses/CPAL-1.0)
- `DPL` - [Devblocks Public License 1.0](https://cerb.ai/license/)
- `ECL-2.0` - [Educational Community License, Version 2.0 ](http://opensource.org/licenses/ECL-2.0)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://www.eclipse.org/legal/epl-v10.html)
- `EPL-2.0` - [Eclipse Public License, Version 2.0](https://www.eclipse.org/legal/epl-v20.html)
- `EUPL-1.2` - [European Union Public License 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-11-12)
- `GFDL-1.1-only` - [GNU Free Documentation License v1.1](https://spdx.org/licenses/GFDL-1.1-only.html)
- `GFDL-1.1-or-later` - [GNU Free Documentation License v1.1](https://spdx.org/licenses/GFDL-1.1-or-later.html)
- `GFDL-1.2-only` - [GNU Free Documentation License v1.2](https://spdx.org/licenses/GFDL-1.2-only.html)
- `GFDL-1.2-or-later` - [GNU Free Documentation License v1.2](https://spdx.org/licenses/GFDL-1.2-or-later.html)
- `GFDL-1.3-only` - [GNU Free Documentation License v1.3](https://spdx.org/licenses/GFDL-1.3-only.html)
- `GFDL-1.3-or-later` - [GNU Free Documentation License v1.3](https://spdx.org/licenses/GFDL-1.3-or-later.html)
- `GPL-1.0` - [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
- `GPL-2.0` - [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
- `GPL-2.0-or-later` - [GNU General Public License v2.0 or later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- `GPL-3.0-only` - [GNU General Public License v3.0 only](https://spdx.org/licenses/GPL-3.0-only.html)
- `GPL-3.0-or-later` - [GNU General Public License v3.0 or later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- `GPL-3.0` - [GNU General Public License 3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)
- `IPL-1.0` - [IBM Public License](https://opensource.org/licenses/IPL-1.0)
- `ISC` - [Internet Systems Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
- `LGPL-2.1` - [Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
- `LGPL-3.0` - [Lesser General Public License 3.0](http://opensource.org/licenses/LGPL-3.0)
- `MIT` - [MIT License](http://opensource.org/licenses/MIT)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
- `MPL-2.0` - [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
- `Multiple` - Various different licenses, for different components of the project's software.
- `OSL-3.0` - [Open Software License 3.0](https://opensource.org/licenses/osl-3.0.php)
- `Other` - Non-standard license, usually unique to the project itself.
- `Sendmail` - [Sendmail License](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
- `SSPL-1.0` - [Server Side Public License](https://spdx.org/licenses/SSPL-1.0.html)
- `Unlicense` - [The Unlicense](http://unlicense.org/)
- `WTFPL` - [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
- `Zlib` - [Zlib/libpng License](https://opensource.org/licenses/Zlib)
- `ZPL-1.2` - [Zope Public License 1.2](http://zpl.pub/page/zplv12)
- `ZPL-2.0` - [Zope Public License 2.0](http://opensource.org/licenses/ZPL-2.0)

--------------------

## External links

**[`^        back to top        ^`](#)**

- **<code>&nbsp;41589</code>** [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - List of high quality, topic-centric public data sources.
- **<code>&nbsp;11187</code>** [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) - Curated list of amazingly awesome open source sysadmin resources.
- **<code>&nbsp;&nbsp;9394</code>** [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) - Curated list of awesome big data frameworks, resources and other awesomeness.
- Lists of software aimed at privacy and decentralization in some form: [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](http://libreprojects.net/)
- Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- Communities/forums: [/r/selfhosted](https://www.reddit.com/r/selfhosted), [IndieWeb](https://indieweb.org/)
- Mirrors: [GitHub.com](https://github.com/awesome-selfhosted/awesome-selfhosted), [Gitlab.com](https://gitlab.com/awesome-selfhosted/awesome-selfhosted)

--------------------

## Contributing

Contributing guidelines can be found in [.github/CONTRIBUTING.md](.github/CONTRIBUTING.md).

## Authors

The list of authors can be found in [AUTHORS.md](AUTHORS.md).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.