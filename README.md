# Дивовижне системне адміністрування
Список дивовижних відкритих (open source) ресурсів для системного адміністрування.

Ориґінальний репозиторій англійською мовою: https://github.com/kahun/awesome-sysadmin

## Співпраця
Перш ніж додавати ПЗ прочитайте [CONTRIBUTING](./CONTRIBUTING.md).

## Зміст
* [Дивовижне системне адміністрування](#дивовижне-системне-адміністрування)
  * [Резервне копіювання](#резервне-копіювання)
  * [Автоматизація збірки](#автоматизація-збірки)
  * [ChatOps](#chatops)
  * [Клонування](#клонування)
  * [Cloud Computing](#cloud-computing)
  * [Хмарні сховища](#хмарні-сховища)
  * [Розгляд коду](#розгляд-коду)
  * [Кооперативне ПЗ](#кооперативне-пз)
  * [Бази даних керування конфіґурацією](#бази-даних-керування-конфіґурацією)
  * [Керування налаштуваннями](#керування-налаштуваннями)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Панелі керування](#панелі-керування)
  * [Deployment Automation](#deployment-automation)
  * [Створення діаграм](#створення-діаграм)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS](#dns)
  * [Редактори](#редактори)
  * [IT Asset Management](#it-asset-management)
  * [LDAP](#ldap)
  * [Керування лоґами](#керування-лоґами)
  * [Поштові сервери](#поштові-сервери)
  * [Листування](#листування)
  * [Моніторинг](#моніторинг)
  * [Metric & Metric Collection](#metric--metric-collection)
  * [Керування конфіґурацією мережі](#керування-конфґурацією-мережі)
  * [Новинні листи](#новинні-листи)
  * [NoSQL](#nosql)
  * [Пакування](#пакування)
  * [Queuing](#queuing)
  * [RDBMS](#rdbms)
  * [Безпека](#безпека)
  * [Service Discovery](#service-discovery)
  * [Контейнери](#Контейнери)
  * [SSH](#ssh)
  * [Статистика](#Статистика)
  * [Сторінки стану](#сторінки-стану)
  * [Системи квитків](#системи-квитків)
  * [Вирішення проблем](#вирішення-проблем)
  * [Керування проєктами](#керування-проєктами)
  * [Контроль версій](#контроль-версій)
  * [Віртуалізація](#віртуалізація)
  * [VPN](#vpn)
  * [Веб](#веб)
  * [Вебпошта](#вебпошта)
  * [Вікі](#вікі)
* [Ресурси](#ресурси)
  * [Блоґи](#блоґи)
  * [Книжки](#книжки)
  * [Новинні листи](#новинні-листи)
  * [Репозиторії](#репозиторії)
  * [Вебсайти](#вебсайти)


## Резервне копіювання

*ПЗ для резервного копіювання.*

* [Amanda](http://www.amanda.org/) - засіб для резервного копіювання з клієнт-серверною моделлю.
* [Attic](https://attic-backup.org) - програма для резервного копіювання без дублювання даних, написана на Python.
* [Bacula](http://www.bacula.org) - інший засіб для резервного копіювання з клієнт-серверною моделлю.
* [Bareos](http://www.bareos.org) - засіб резервного копіювання, гілка від проєкту Bacula.
* [Barman](http://www.pgbarman.org) - Backup and Recovery Manager for disaster recovery of PostgreSQL servers.
* [Backupninja](https://labs.riseup.net/code/projects/backupninja) - Lightweight, extensible meta-backup system.
* [BackupPC](https://backuppc.github.io/backuppc/) - клієнт-серверний засіб резервного копіювання, який працює за схемою зливання файлів.
* [Brebis](http://brebisproject.org) - повністю автоматизована перевірка резервних копій
* [Bup](https://github.com/bup/bup) - Incremental backups with rolling checksums, git packfiles, de-duplication, and a FUSE filesystem.
* [Burp](http://burp.grke.org/) - програма для резервного копіювання і відновлення через мережу.
* [Duplicati](http://www.duplicati.com) - Multiple backends, encryption, web-ui and multi-OS backup tool.
* [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
* [FreeFileSync](http://www.freefilesync.org) - засіб для порівняння і синхронізації тек.
* [Lsyncd](https://github.com/axkibe/lsyncd) - File Monitor which spawns a process to synchronize the changes (rsync by default).
* [restic](https://github.com/restic/restic) - швидка, безпечна, ефективна програма для резервного копіювання.
* [Rsnapshot](http://www.rsnapshot.org/) - утиліта для часового зрізу файлової ситеми.
* [SafeKeep](http://safekeep.sourceforge.net/) - Centralized pull-based backup using `rdiff-backup`.
* [Snebu](http://www.snebu.com/) – Snapshot backup with global multi-client deduplication and transparent compression.
* [UrBackup](http://www.urbackup.org/) - інша клієнт-серверна система резервного копіювання.
* [ZBackup](http://zbackup.org/) - універсальний засіб резервного копіювання без дублювання даних.

*Бібліотеки для резервного копіювання.*

* [Backup](https://github.com/meskyanichi/backup) - Provides an elegant DSL in Ruby for performing backups on UNIX-like systems.
* [DREBS](https://github.com/dojo4/drebs) - AWS EBS backup script that supports strategies.

## Автоматизація збірки

*Засоби для автоматизації збірки.*

* [Apache Ant](https://ant.apache.org/) - автоматизований засіб збірки, схожий на make, написаний на Java.
* [Apache Maven](http://maven.apache.org/) - засіб автоматизованої збірки в основному для Java.
* [GNU Make](http://www.gnu.org/software/make/) - найпопулярніший засіб автоматизованої збірки для різних цілей.
* [Gradle](http://gradle.org/) - інша відкрита система автоматизованої збірки.

## ChatOps

*Conversation-driven development & management.*

* [CloudBot](https://github.com/CloudBotIRC/CloudBot) - простий, швидкий, розширюваний, відкритий IRC-бот на Python.
* [Eggdrop](http://www.eggheads.org/) - The world's most popular Open Source IRC bot, designed for flexibility and ease of use.
* [Err](http://errbot.net/) - A plugin based chatbot designed to be easily deployable, extensible and maintainable.
* [Hubot](https://hubot.github.com/) - A customizable, life embetterment robot.
* [Lazlo](https://github.com/djosephsen/lazlo) - A chatops automation framework in Go.
* [Lita](https://www.lita.io/) - A robot companion for your company's chat room.
* [KeyBase](https://www.keybase.io/) - шифрований чат, хмара і git.

## Клонування

*ПЗ для клонування.*

* [Clonezilla](http://clonezilla.org/) - програма для створення образів/клонування дисків і розділів.
* [Fog](http://www.fogproject.org/) - інше рішення компʼютерного клонування.
* [Redo Backup](http://redobackup.org/) - легке резервне копіювання і відновлення даних.

## Cloud Computing

* [AppScale](http:/github.com/AppScale/appscale) - Open source cloud software with Google App Engine compatibility.
* [Archipel](http://archipelproject.org/) - Manage and supervise virtual machines using Libvirt.
* [CloudStack](http://cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services.
* [Cobbler](http://cobbler.github.io) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments.
* [Eucalyptus](https://www.eucalyptus.com/) - Open source private cloud software with AWS compatibility.
* [Mesos](http://mesos.apache.org/) - Develop and run resource-efficient distributed systems.
* [OpenNebula](http://opennebula.org/) - An user-driven cloud management platform for sysadmins and devops.
* [Openshift Origin](https://www.openshift.org/) - Open source upstream of OpenShift, the next generation application hosting platform developed by Red Hat.
* [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
* [The Foreman](http://theforeman.org/) - Foreman is a complete lifecycle management tool for physical and virtual servers. FOSS.
* [Tsuru](http://www.tsuru.io/) - Tsuru is an extensible and open source Platform as a Service software.
* [Terraform](https://terraform.io) - Terraform allows you to practice infrastructure as code and is commonly used for AWS/GCE.

## Cloud Orchestration

* [BOSH](http://docs.cloudfoundry.org/bosh/) -  IaaS orchestration platform originally written for deploying and managing Cloud Foundry PaaS, but also useful for general purpose distributed systems.
* [Ansible](http://www.ansible.com) - Contains modules for controlling many types of cloud resources.
* [Cloudify](http://cloudify.co/) -  Open source TOSCA-based cloud orchestration software platform written in Python and YAML.
* [consul](http://www.consul.io/) - It is a tool for discovering and configuring services in your infrastructure.
* [doozerd](https://github.com/ha/doozerd) - Doozer is a highly-available, completely consistent store for small amounts of extremely important data.
* [etcd](https://github.com/coreos/etcd) - A highly-available key value store for shared configuration and service discovery.
* [Juju](https://juju.ubuntu.com/) - Cloud orchestration tool which manages services as charms, YAML configuration and deployment script bundles.
* [MCollective](http://puppetlabs.com/mcollective) - Ruby framework to manage server orchestration, developed by Puppet labs.
* [Overcast](http://andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH.
* [Rundeck](http://rundeck.org/) - Simple orchestration tool.
* [Salt](http://www.saltstack.com/) - Fast, scalable and flexible systems management software written in Python/ZeroMQ.
* [serf](http://www.serfdom.io/) - Serf is a tool for cluster membership.
* [StackStorm](http://stackstorm.com/) - Event Driven Operations and ChatOps platform for infrastructure management. Written in Python.
* [zookeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Хмарні сховища

* [git-annex assistant](http://git-annex.branchable.com/assistant/) - синхронізована тека на всіх ваших компʼютерах OSX та Linux, пристроях Android, портативних пристроях, застосуваннях NAS і хмарних сервісах.
* [nextCloud](https://nextcloud.com) - надає доступ до ваших файлів через веб-інтерфейс.
* [ownCloud](https://owncloud.org) - надає універсальний доступ до ваших файлів через веб-інтерфейс, компʼютер чи мобільний пристрій.
* [Seafile](http://seafile.com) - ще одне рішення відкритого хмарного сховища.
* [SparkleShare](http://sparkleshare.org/) - надає хмарне сховище і сервіси синхронізації файлів. За замовчуванням працює на Git.
* [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.
* [Syncthing](http://syncthing.net/) - система з відкритим кодом для приватного, шифрованого і автентифікованого розповсюдження даних.

## Розгляд коду

*Системи кооперативного розгляду коду на основі Web.*

* [Gerrit](https://code.google.com/p/gerrit/) - на основі системи контролю версій Git, дозволяє розробникам ПЗ розглядати вихідний код, підтверджувати або відхиляти зміни.
* [Phabricator](http://phabricator.org/) - засіб огляду коду розроблений facebook, який використовують WikiMedia, FB, dropbox тощо. В комплект входять вбудована вікі, відстеження помилок, контроль версій та інтерфейс командного рядка, що називається arcanist.
* [Review Board](https://www.reviewboard.org/) - засіб кооперативного огляду коду на осонові Web.

## Кооперативне ПЗ

*Collaborative software or groupware suites.*

* [Citadel/UX](http://www.citadel.org/) - Collaboration suite (messaging and groupware) that is descended from the Citadel family of programs.
* [EGroupware](http://www.egroupware.org/) - Groupware software written in PHP.
* [Horde Groupware](http://www.horde.org/apps/groupware) - PHP based collaborative software suite that includes email, calendars, wikis, time tracking and file management.
* [Kolab](https://www.kolab.org) - Another groupware suite.
* [SOGo](https://www.sogo.nu/) - Collaborative software server with a focus on simplicity and scalability.
* [Zimbra](https://www.zimbra.com/community/) - Collaborative software suite, that includes an email server and web client.

## Бази даних керування конфіґурацією

*ПЗ для баз даних керування конфіґурацією (CMDB).*

* [Clusto](https://github.com/clusto/clusto) - Helps you keep track of your inventory, where it is, how it's connected, and provides an abstracted interface for interacting with the elements of the infrastructure.
* [Collins](http://tumblr.github.io/collins) - At Tumblr, it's the infrastructure source of truth and knowledge.
* [i-doit](http://www.i-doit.org/) - відкрита IT-документація і CMDB.
* [iTop](http://www.combodo.com/-Overview-.html) - Complete open source, ITIL, web based service management tool.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Sicekit](https://github.com/sicekit/sicekit) - The systems & infrastructure encyclopaedia toolkit (based on MediaWiki).

## Керування налаштуваннями

*Засоби керування конфіґурацією.*

* [Ansible](http://www.ansible.com/) - написаний на Python і керує вузлами через SSH.
* [CFEngine](http://cfengine.com/) - легкий системний аґент. Стан конфіґурації визначається через декларативну мову.
* [Chef](http://www.opscode.com/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
* [mgmt](https://github.com/purpleidea/mgmt) - керування налаштуваннями наступного рівня, написано на Go.
* [Pallet](http://palletops.com/) - Infrastructure definition, configuration and management via a Clojure DSL.
* [Puppet](http://puppetlabs.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.
* [(R)?ex](https://www.rexify.org/) - написаний на Perl і використовує чистий Perl, через SSH без аґента.
* [Salt](http://www.saltstack.com/) - написаний на Python.
* [Slaughter](http://steve.org.uk/Software/slaughter/) - написаний на Perl.

## Continuous Integration & Continuous Deployment

*Continuous integration/deployment software.*

* [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration.
* [Drone](https://github.com/drone/drone) - Continuous integration server built on Docker and configured using YAML files.
* [GitLab CI](https://www.gitlab.com/gitlab-ci/) - Based off of ruby. They also provide GitLab, which manages git repositories.
* [Go](http://www.go.cd/) - Open source continuous delivery server.
* [Jenkins](http://jenkins-ci.org/) - An extendable open source continuous integration server.
* [Concourse CI](https://concourse.ci/) - A pipeline-based CI system written in Go.
* [Spinnaker](http://www.spinnaker.io/) - Open source, multi-cloud continuous delivery platform for releasing software changes.
* [TeamCity](https://www.jetbrains.com/teamcity/) - Powerful Continuous Integration out of the box

## Панелі керування

*Панелі для контролю серверів і вебхостингів.*

* [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD.
* [Cockpit](http://cockpit-project.org/) - New multi-server web interface for Linux servers written in C.
* [Feathur](http://feathur.com) - VPS Provisioning and Management Software.
* [Froxlor](http://www.froxlor.org/) - Easy to use panel for Linux with Nginx and PHP-FPM support.
* [ISPConfig](http://www.ispconfig.org) - Hosting control panel for Linux.
* [Sentora](http://sentora.org/) - Control panel for Linux, BSD, and Windows based on ZPanel.
* [VestaCP](http://www.vestacp.com/) - Hosting panel for Linux but with Nginx.
* [Virtualmin](http://www.virtualmin.com/) - Control panel for Linux based on webmin.
* [Webmin](http://www.webmin.com/) - Linux server control panel.
* [ZPanel](http://www.zpanelcp.com/) - Control panel for Linux, BSD, and Windows.

## Deployment Automation

*Tools and scripts to support deployments to your servers.*

* [Capistrano](http://www.capistranorb.com) - Deploy your application to any number of machines simultaneously, in sequence or as a rolling set via SSH (rake based).
* [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.
* [Mina](http://nadarei.co/mina/) - Really fast deployer and server automation tool (rake based).
* [Rocketeer](http://rocketeer.autopergamene.eu/) - PHP task runner and deployment tool.
* [Vlad the Deployer](http://rubyhitsquad.com/Vlad_the_Deployer.html) - Deployment automation (rake based).

## Створення діаграм

*Засоби для створення діаграм мереж.*

* [drawthe.net](http://go.drawthe.net/) - Draws network diagrams dynamically from a text file describing the placement, layout and icons.

## Distributed Filesystems

*Network distributed filesystems.*

* [Ceph](http://ceph.com/) - Distributed object store and file system.
* [DRBD](http://www.drbd.org/) - Distributed Replicated Block Device.
* [LeoFS](http://leo-project.net) - Unstructured object/data storage and a highly available, distributed, eventually consistent storage system.
* [GlusterFS](http://www.gluster.org/) - Scale-out network-attached storage file system.
* [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
* [Lustre](http://lustre.opensfs.org/) -  A type of parallel distributed file system, generally used for large-scale cluster computing.
* [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
* [MogileFS](http://mogilefs.org/) - Application level, network distributed file system.
* [OpenAFS](http://www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.

## DNS

*Сервери DNS.*

* [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
* [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
* [Designate](https://wiki.openstack.org/wiki/Designate) - DNS REST API that support several DNS servers as its backend.
* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - A lightweight service providing DNS, DHCP and TFTP services to small-scale networks.
* [Knot](https://www.knot-dns.cz/) - High performance authoritative-only DNS server.
* [NSD](http://www.nlnetlabs.nl/projects/nsd/) - Authoritative only, high performance, simple name server.
* [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
* [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.
* [Yadifa](http://yadifa.eu/) - Lightweight authoritative Name Server with DNSSEC capabilities powering the .eu top-level domain.

## Редактори

*Відкриті редактори коду.*

* [Atom](https://atom.io/) - налаштовуваний текстовий редактор від GitHub.
* [Brackets](http://brackets.io/) - відкритий редактор коду для вебдизайнерів і front-end-розробників.
* [Eclipse](http://eclipse.org/) - IDE написане на Java з розширюваною системою втулок.
* [Geany](http://www.geany.org/) - текстовий редактор на базі GTK2.
* [GNU Emacs](http://www.gnu.org/software/emacs/) - розширюваний, налаштовуваний текстовий редактор і більше.
* [Haroopad](http://pad.haroopress.com/) - редактор Markdown з живим переглядом.
* [ICEcoder](http://icecoder.net) - чудеса радактора коду, в комплект входять основні мови веб-розробки.
* [IntellijIDEA](https://github.com/JetBrains/intellij-community) - вправне та ерґономічне IDE, написане на Java, має багато втулок.
* [jotgit](https://github.com/jdleesmiller/jotgit) - Git-backed real-time collaborative code editing.
* [Light Table](http://www.lighttable.com/) - редактор коду наступного покоління.
* [Lime](http://limetext.org/) - Aims to provide an open source solution to Sublime Text
* [SciTE](http://www.scintilla.org/SciTE.html) - текстовий редактор на основі SCIntilla.
* [TextMate](https://github.com/textmate/textmate/) - текстовий редактор з графічним інтерфейсом для OS X.
* [Vim](http://www.vim.org) - A highly configurable text editor built to enable efficient editing.
* [Nano](http://https://www.nano-editor.org/) - популярний текстовий редактор, часто входить у найпоширеніші дистрибутиви Linux.
* [Visual Studio Code](https://code.visualstudio.com/) - швидкий, налаштовуваний, багатоплатформовий редактор коду від Microsoft.

## IT Asset Management

*IT Assets Management software.*

* [GLPI](http://www.glpi-project.org/spip.php?lang=en) - Information Resource-Manager with an additional Administration Interface.
* [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Enables users to inventory their IT assets.
* [Netbox](https://github.com/digitalocean/netbox) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.
* [RackTables](http://racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Snipe IT](http://snipeitapp.com/) - Asset & license management software.
* [OpenDCIM](http://www.opendcim.org/) - A web based Data Center Infrastructure Management application.

## LDAP

*Сервери LDAP.*

* [389 Directory Server](http://port389.org) - розроблений Red Hat.
* [Apache Directory Server](http://directory.apache.org/) - проєкт від Apache Software Foundation написаний на Java.
* [Fusion Directory](http://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
* [OpenDJ](http://opendj.forgerock.org/) - гілка від OpenDS.
* [OpenDS](https://opends.java.net/) - інший сервер каталогів написаний на Java.
* [OpenLDAP](http://openldap.org/) - розроблений проєктом OpenLDAP.

*Керування LDAP.*

* [Apache Directory Studio](https://directory.apache.org/studio/) - клієнт каталогів і оглядач LDAP на основі Eclipse

## Керування лоґами

*Засоби керування лоґами: збирання, розпізнавання, візуалізація ...*

* [Echofish](http://www.echothrust.com/projects/echofish) - A web based real-time event log aggregation, analysis, monitoring and management system.
* [Elasticsearch](http://www.elasticsearch.org/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
* [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper.
* [Flume](https://flume.apache.org/) - Distributed log collection and aggregation system.
* [Graylog2](http://graylog2.org/) - Pluggable Log and Event Analysis Server with Alerting options.
* [Heka](http://hekad.readthedocs.org/en/latest/) - Stream processing system which may be used for log aggregation.
* [Kibana](http://www.elasticsearch.org/overview/kibana/) - Visualize logs and time-stamped data.
* [Logstash](http://logstash.net/) - Tool for managing events and logs.
* [Octopussy](http://www.octopussy.pm) - Log Management Solution (Visualize / Alert / Report).

## Поштові сервери

*Mail Delivery Agents (ПЗ для IMAP/POP3).*

* [Courier IMAP/POP3](http://www.courier-mta.org/imap/) - Fast, scalable, enterprise IMAP and POP3 server.
* [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in.
* [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind.
* [Qpopper](http://www.eudora.com/products/unsupported/qpopper/) - One of the oldest and most popular server implementations of POP3.

*Mail Transfer Agents (сервери SMTP).*

* [Exim](http://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.
* [Haraka](http://haraka.github.io/) - A high-performance, pluginable SMTP server written in JavaScript.
* [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development.
* [Maildrop](https://github.com/m242/maildrop) - Open Source disposable email SMTP server, also useful for development.
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.
* [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement.
* [Qmail](http://cr.yp.to/qmail.html) - Secure Sendmail replacement.
* [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA).

*Комплектні рішення.*

* [Mail-in-a-Box](https://mailinabox.email/) - Take back control of your email with this easy-to-deploy mail server in a box.
* [iRedMail](http://www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot.

## Листування

*Сервери XMPP.*

* [ejabberd](http://www.ejabberd.im/) - XMPP instant messaging server written in Erlang/OTP.
* [Metronome IM](http://www.lightwitch.org/metronome) - гілка від Prosody IM.
* [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Fullstack real-time mobile messaging platform (XMPP+REST) in Erlang
* [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server.
* [Prosody IM](http://prosody.im/) - сервер XMPP написаний на Lua.
* [Tigase](https://projects.tigase.org/projects/tigase-server) - реалізація сервера XMPP на Java.

*Вебклієнти XMPP.*

* [Candy](http://candy-chat.github.io/candy/) - багатокористувацький клієнт XMPP написаний на Javascript.
* [Kaiwa](http://getkaiwa.com/) - Web based chat client in the style of common paid alternatives.

*Вебчати.*

* [Lets-Chat](http://sdelements.github.io/lets-chat/) - A self hosted chat suite written in Node.

## Моніторинг

*ПЗ для моніторингу.*

* [Alerta](https://github.com/guardian/alerta) - Distributed, scaleable and flexible monitoring system.
* [Canopsis](http://www.canopsis.org) - Opensource Hypervision and Data Aggregation Software
* [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
* [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty.
* [Centreon](http://www.centreon.com) - IT infrastructure and application monitoring for service performance.
* [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
* [Flapjack](http://flapjack.io/) - Monitoring notification routing & event processing system.
* [Icinga](https://www.icinga.org/) - гілка від Nagios.
* [LibreNMS](https://github.com/librenms/librenms/) - гілка від Observium.
* [Monit](http://mmonit.com/monit/#home) - Small Open Source utility for managing and monitoring Unix systems.
* [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
* [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
* [Nagios](http://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
* [Node-Bell](https://github.com/eleme/node-bell) - Real-time anomalies detection for periodic time series, metrics monitor.
* [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
* [Opsview](http://www.opsview.com/solutions/core) - Based on Nagios 4, Opsview Core is ideal for small IT and test environments.
* [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis.
* [Sensu](http://sensuapp.org/) - Open source monitoring framework.
* [Sentry](https://getsentry.com/) - Application monitoring, event logging and aggregation.
* [Serverstats](https://sourceforge.net/projects/serverstats.berlios/) - A simple tool for creating graphs using rrdtool. ([source on github](https://github.com/ddanier/serverstats))
* [Seyren](https://github.com/scobal/seyren) - An alerting dashboard for Graphite.
* [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
* [Xymon](http://www.xymon.com/) - Network monitoring inspired by Big Brother.
* [Zabbix](http://www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.
* [Zenoss](http://community.zenoss.org) - Application, server, and network management platform based on Zope.

*Monitoring dashboards.*

* [Adagios](http://adagios.org/) - інтерфейс конфіґурування Nagios на базі Web.
* [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
* [Thruk](http://www.thruk.org/) - Multibackend monitoring web interface with support for Naemon, Nagios, Icinga and Shinken.
* [Uchiwa](https://uchiwa.io) - Simple dashboard for the Sensu monitoring framework.

*Monitoring distributions.*

* [OMD](http://omdistro.org/) - The Open Monitoring Distribution.

## Metric & Metric Collection

*Metric gathering and display software.*

* [Collectd](http://collectd.org/) - System statistic collection daemon.
* [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
* [~~dashing~~](http://dashing.io/) - __No Longer Maintained__ - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms.
* [Smashing](https://github.com/Smashing/smashing) - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms. Fork of Dashing.
* [Diamond](https://github.com/BrightcoveOS/Diamond) - Python based statistic collection daemon.
* [Facette](http://facette.io) - Time series data visualization and graphing software written in Go.
* [Freeboard](https://github.com/Freeboard/freeboard) - A damn-sexy front-end real-time dashboard. Transforms raw JSON into delicious UI.
* [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
* [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
* [Graphite](http://graphite.readthedocs.org/en/latest/) - Open source scalable graphing server.
* [InfluxDB](http://influxdb.com/) - Open source distributed time series database with no external dependencies.
* [KairosDB](https://code.google.com/p/kairosdb/) - Fast distributed scalable time series database, fork of OpenTSDB 1.x.
* [NetData](http://my-netdata.io) - Distributed real-time performance and health monitoring.
* [OpenTSDB](http://opentsdb.net/) - Store and server massive amounts of time series data without losing granularity.
* [Packetbeat](http://packetbeat.com/) - Captures network traffic and displays it in a custom Kibana dashboard for easy viewing.
* [Prometheus](http://prometheus.io/) - Service monitoring system and time series database.
* [RRDtool](http://oss.oetiker.ch/rrdtool/) - Open source industry standard, high performance data logging and graphing system for time series data.
* [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.

## Керування конфіґурацією мережі

*Засоби для керування конфіґурацією мережі.*

* [GestióIP](http://www.gestioip.net/) - An automated web based IPv4/IPv6 IP Address Management tool.
* [NOC Project](http://nocproject.org/) - Scalable, high-performance and open-source [OSS](http://en.wikipedia.org/wiki/Operations_support_system) system for ISP, service and content providers.
* [Netbox](https://github.com/digitalocean/netbox) - IP address management (IPAM) and data center infrastructure management (DCIM) tool.
* [Oxidized](https://github.com/ytti/oxidized) - A modern take on network device configuration monitoring with web interface and GIT storage.
* [phpIPAM](http://phpipam.net/) - Open source IP address management with [PowerDNS](https://www.powerdns.com/) integration.
* [RANCID](http://www.shrubbery.net/rancid/) - Monitors network device's configuration and maintain history of changes.
* [rConfig](http://www.rconfig.com/) - Another network device configuration management tool.
* [trigger](https://github.com/trigger/trigger) - Robust network automation toolkit written in Python.


## Новинні листи

*ПЗ для керування новинними листами.*

* [DadaMail](http://dadamailproject.com/) - керівник поштової розсилки, написаний на Perl.
* [phpList](http://www.phplist.com/) - керівник новинних листів написаний на PHP.

## NoSQL

*Column-Family.*

  * [Apache HBase](http://hbase.apache.org/) - Hadoop database, a distributed, big data store.
  * [Cassandra](http://cassandra.apache.org/) - Distributed DBMS designed to handle large amounts of data across many servers.
  * [Hypertable](http://hypertable.org/) - C++ based BigTable-like DBMS, communicates through Thrift and runs either as stand-alone or on distributed FS such as Hadoop.

*Document Store.*

  * [CouchDB](http://couchdb.apache.org/) - Ease of use, with multi-master replication document-oriented database system.
  * [ElasticSearch](http://www.elasticsearch.org/) - Java based database, popular with log aggregation, and email archiving projects.
  * [MongoDB](http://www.mongodb.org/) - Another document-oriented database system.
  * [RavenDB](http://ravendb.net/) - Document based database with ACID/Transactional features.
  * [RethinkDB](http://www.rethinkdb.com/) - Open source distributed document store database, focuses on JSON.

*Graph.*

  * [FlockDB](https://github.com/twitter/flockdb) - Twitter's distributed, fault-tolerant graph database.
  * [Neo4j](http://www.neo4j.org/) - Open source graph database.

*Ключ-Значення.*

  * [Couchbase](http://www.couchbase.com/) - In-memory, replicated, peristent key/value datastore.
  * [LevelDB](https://github.com/google/leveldb) - Google's high performance key/value database.
  * [Redis](http://redis.io/) - Networked, in-memory, key-value data store with optional durability.
  * [Riak](http://basho.com/riak/) - Another fault-tolerant key-value NoSQL database.

## Пакування

* [fpm](https://github.com/jordansissel/fpm) - Versatile multi format package creator.
* [omnibus-ruby](https://github.com/opscode/omnibus-ruby) - Full stack, cross distro packaging software (Ruby).
* [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).
* [tito](https://github.com/dgoodwin/tito) - Builds RPMs for git-based projects.

## Queuing

*Queuing software.*

* [ActiveMQ](http://activemq.apache.org/) - An open source message broker written in Java together with a full JMS client.
* [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
* [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform.
* [Kafka](http://kafka.apache.org/) - A high-throughput distributed messaging system.
* [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
* [RabbitMQ](http://www.rabbitmq.com/) - Robust, fully featured, cross distro queuing system.

*Queuing libraries.*

* [ZeroMQ](http://zeromq.org/) -  High-performance asynchronous messaging library.

## RDBMS

*Реляційні DBMS.*

* [Firebird](http://www.firebirdsql.org/) - True universal open source database.
* [Galera](http://galeracluster.com/) - Galera Cluster for MySQL is an easy-to-use high-availability solution with high system up-time, no data loss, and scalability for future growth.
* [MariaDB](https://mariadb.org/) - Community-developed fork of the MySQL.
* [MySQL](http://dev.mysql.com/) - найпопулярніший сервер RDBMS.
* [Percona Server](http://www.percona.com/software) - Enhanced, drop-in MySQL replacement.
* [PostgreSQL](http://www.postgresql.org/) - Object-relational database management system (ORDBMS).
* [PostgreSQL-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based database cluster.
* [SQLite](http://sqlite.org/) - Library that implements a self-contained, serverless, zero-configuration, transactional SQL DBS.

## Безпека

*Засоби безпеки.*

* [Blackbox](https://github.com/StackExchange/blackbox) - Safely store secrets in Git/Mercurial. Provides tooling to automatically encrypt secrets like passwords.
* [Denyhosts](http://denyhosts.sourceforge.net/) - Thwart SSH dictionary based attacks and brute force attacks.
* [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) - Scans log files and takes action on IPs that show malicious behavior.
* [fwknop](https://www.cipherdyne.org/fwknop/) - Protects ports via Single Packet Authorization in your firewall.
* [Glastopf](http://glastopf.org/) - A low-interaction web application honeypot to emulate vulnerabilities and gather attack data.
* [Kippo](https://github.com/desaster/kippo) - A medium-interaction SSH honeypot, mostly used as a standalone SSH daemon with a configurable Filesystem sandbox.
* [OSSEC](http://ossec.net) - OSSEC is a HIDS that performs log analysis, FIM, rootkit detection, and much more.
* [OSQuery](https://osquery.io/) - Query your servers status and info using a SQL like interface.
* [pfSense](https://www.pfsense.org/) - Firewall and Router FreeBSD distribution.
* [Snort](https://www.snort.org/) - Snort is a free and open source network intrusion prevention system (NIPS) and network intrusion detection system (NIDS) created by Martin Roesch in 1998.
* [SpamAssassin](https://spamassassin.apache.org/) - A powerful and popular email spam filter employing a variety of detection technique.
* [BounCA](https://bounca.org/) - BounCA is a personal SSL / Certificate Authority Key management tool. Create self-signed SSL certificates via your browser. ([Source Code](https://github.com/repleo/bounca)) `Apache` `Python`

## Service Discovery

* [Consul](http://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [Doozerd](https://github.com/ha/doozerd) - Doozer is a highly-available, completely consistent store for small amounts of extremely important data.
* [ZooKeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Контейнери

*Віртуалізація на рівні операційної системи.*

* [Bitnami](https://bitnami.com/) - Produces open source installers or software packages for web applications and development stacks as well as virtual appliances.
* [Docker](http://www.docker.com/) - Open platform for developers and sysadmins to build, ship, and run distributed applications.
* [LXC](https://linuxcontainers.org/lxc/) -  Userspace interface for the Linux kernel containment features.
* [LXD](https://linuxcontainers.org/lxd/) - LXD is a container "hypervisor".
* [OpenVZ](http://openvz.org) - Container-based virtualization for Linux.
* [Docker Compose](https://docs.docker.com/compose/) - швидке, ізольоване середовище розробки через Docker.
* [Singularity](http://singularity.lbl.gov/) - Flexible containers without root.

## SSH

*Засоби SSH.*

* [Advanced SSH config](https://pypi.python.org/pypi/advanced-ssh-config/) - Enhances ssh_config file capabilities, completely transparent.
* [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn ssh session after network interruption.
* [Cluster SSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
* [DSH](http://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer's shell / distributed shell - Wrapper for executing multiple remote shell commands from one command line.
* [Mosh](http://mosh.mit.edu/) - мобільна оболонка.
* [parallel-ssh](http://code.google.com/p/parallel-ssh/) - Provides parallel versions of OpenSSH and related tools.
* [pdsh](https://code.google.com/p/pdsh/) - Pdsh is a high-performance, parallel remote shell utility.
* [SSH Power Tool](http://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.
* [sshrc](https://github.com/Russell91/sshrc) - sources ~/.sshrc on your local computer after logging in remotely.
* [stormssh](http://stormssh.readthedocs.org) - засіб командного рядка для керування зʼєднаннями SSH.

## Статистика

*ПЗ для аналітики.*

* [Analog](http://www.web42.com/analog/) - Logfile Analyser.
* [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically.
* [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal.
* [Open Web Analytics](http://www.openwebanalytics.com/) - Add web analytics to websites using JS, PHP or REST APIs.
* [Piwik](http://piwik.org/) - Web analytics application.
* [Webalizer](http://www.webalizer.org/) - Fast, free web server log file analysis program.

## Сторінки стану

* [Cachet](https://cachethq.io) - відкрита система сторінок стану написана на PHP.

## Системи квитків

*Системи квитків на основі Web.*

* [Bugzilla](http://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project.
* [Cerb](http://www.cerberusweb.com/) - Group-based e-mail management project.
* [Flyspray](http://flyspray.org) - вебсистема відстеження помилок написана на PHP.
* [MantisBT](http://www.mantisbt.org/) - система відстеження помилок на базі Web.
* [osTicket](http://osticket.com/) - Simple support ticket system.
* [OTRS](http://www.otrs.com/) - Trouble ticket system for assigning tickets to incoming queries and tracking further communications.
* [Redmine](http://www.redmine.org/) - Open source project management/ticketing web application written in Ruby.
* [Request Tracker](http://www.bestpractical.com/rt/) - Ticket-tracking system written in Perl.
* [TheBugGenie](http://www.thebuggenie.com) - Ticket system with extensive user rights system.

## Вирішення проблем

*Засоби відстеження проблем.*

* [mitmproxy](http://mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems.
* [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
* [Wireshark](http://www.wireshark.org/) - The world's foremost network protocol analyzer.

*Дистрибутиви для вирішення проблем.*

* [Trinity Rescue Kit](http://trinityhome.org) - живий CD Linux для вирішення загальних проблем.

## Керування проєктами

*Системи на основі Web для керування проєктами і відстеження помилок.*

* [ChiliProject](https://www.chiliproject.org) - гілка від Redmine.
* [GitBucket](https://github.com/takezoe/gitbucket) клон GitHub написаний на Scala; один інсталяційний jar-файл.
* [GitLab](https://www.gitlab.com/) - клон GitHub написаний на Ruby.
* [Gogs](http://gogs.io/) - домашній сервер Git написаний на Go.
* [OpenProject](https://www.openproject.org) - Project collaboration with open source.
* [Phabricator](http://phabricator.org/) написаний на PHP.
* [Redmine](http://www.redmine.org/) - написаний на ruby on rails.
* [Taiga](https://taiga.io/) - Agile, Free, Open Source Project Management Tool based on the Kanban and Scrum methods.
* [The Bug Genie](http://www.thebuggenie.com/) - написаний на PHP.
* [Trac](http://trac.edgewall.org/) - написаний на python.

## Контроль версій

*Software versioning and revision control.*

* [Fossil](http://www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.
* [Git](http://git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed.
* [GNU Bazaar](http://bazaar.canonical.com/) - Distributed revision control system sponsored by Canonical.
* [Mercurial](http://mercurial.selenic.com/) - Another distributed revision control.
* [Subversion](http://subversion.apache.org/) - Client-server revision control system.

## Віртуалізація

*ПЗ для віртуалізації.*

* [Archipel](http://archipelproject.org/) - платформа керування віртуалізацією на основі XMPP.
* [Ganeti](https://code.google.com/p/ganeti/) - Cluster virtual server management software tool built on top of KVM and Xen.
* [KVM](http://www.linux-kvm.org) - інфраструктура віртуалізації ядра Linux.
* [OpenNebula](http://opennebula.org/) - Flexible enterprise cloud made simple.
* [oVirt](http://www.ovirt.org/) - керування віртуальними машинами, сховищами та віртуальними мережами.
* [Packer](http://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
* [Proxmox VE](https://www.proxmox.com/proxmox-ve) - Complete open source virtualization management solution.
* [QEMU](http://www.qemu.org/) - QEMU is a generic and open source machine emulator and virtualizer.
* [Vagrant](https://www.vagrantup.com/) - Tool for building complete development environments.
* [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
* [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.

## VPN

*ПЗ для VPN.*

* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [Pritunl](http://pritunl.com/) - рішення на основі OpenVPN. легке в налаштуванні.
* [SoftEther](https://www.softether.org/) - багатопротокольне ПЗ для VPN з розширеними можливостями
* [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
* [strongSwan](http://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [tinc](http://www.tinc-vpn.org/) - Distributed p2p VPN.
* [wireguard](https://www.wireguard.com/) - нове, дуже швидке, мінімалістичне рішення для VPN.

## Веб

*Вебсервери.*

* [Apache](http://httpd.apache.org/) - найпопулярніший вебсервер.
* [Caddy](https://caddyserver.com/) - The HTTP/2 Web Server with Fully Managed TLS.
* [Cherokee](http://cherokee-project.com/) - Lightweight, high-performance web server/reverse proxy.
* [Lighttpd](http://www.lighttpd.net/) - Web server more optimized for speed-critical environments.
* [Nginx](http://nginx.org/) - Reverse proxy, load balancer, HTTP cache, and web server.
* [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.

*Web Performance.*

* [HAProxy](http://www.haproxy.org/) - Software based load Balancing, SSL offloading and performance optimization, compression, and general web routing.
* [Squid](http://www.squid-cache.org/) - Caching proxy for the web supporting HTTP, HTTPS, FTP, and more.
* [Traefik](https://traefik.io/) - Træfɪk is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease.
* [Varnish](https://www.varnish-cache.org/) - HTTP based web application accelerator focusing on optimizing caching and compression.

## Вебпошта

*Застосунки для вебпошти.*

* [Mailpile](https://www.mailpile.is/) - A modern, fast web-mail client with user-friendly encryption and privacy features.
* [Roundcube](http://roundcube.net/) - Browser-based IMAP client with an application-like user interface.
* [SquirrelMail](http://squirrelmail.org) - Another browser-based IMAP client.

## Вікі

*ПЗ для вікі.*

* [BookStack](https://www.bookstackapp.com/) - проста, з дружнім інтерфейсом збірка вікі на PHP, що використовує MySQL для зберігання даних.
* [DokuWiki](https://www.dokuwiki.org/dokuwiki) - Simple to use and highly versatile wiki that doesn't require a database.
* [Gollum](https://github.com/gollum/gollum) - A simple, Git-powered wiki with a sweet API and local frontend.
* [ikiwiki](http://ikiwiki.info/) - компілятор вікі.
* [MDwiki](http://dynalon.github.io/mdwiki/#!index.md) - Wiki completely built in HTML5/Javascript and runs 100% on the client.
* [MediaWiki](http://www.mediawiki.org/wiki/MediaWiki) - Used to power Wikipedia.
* [MoinMoin](http://moinmo.in/) - An advanced, easy to use and extensible WikiEngine with a large community of users.
* [Ōlelo Wiki](https://github.com/minad/olelo) - A a wiki that stores pages in a Git repository.
* [TiddlyWiki](http://tiddlywiki.com) - Complete interactive wiki in JavaScript.

# Ресурси

Різні джерела, такі як книжки, вебсайти чи статті для покращення ваших навичок і знань.

## Блоґи

* [Code as Craft](http://codeascraft.com/) - Etsy's Ops blog, lots of technical posts.
* [DevOpsGuys](http://blog.devopsguys.com/) - Devops consultants who blog about operations.
* [Rackspace Developers](http://developer.rackspace.com/blog/) - Slightly biased blog with lots of Devops Topics.

## Книжки

*Повʼязані з системним адмініструванням книжки.*

* [Learn Cisco Network Administration in a Month of Lunches] (https://www.manning.com/books/learn-cisco-network-administration-in-a-month-of-lunches) - A tutorial designed for sysadmins who need to learn how to administer Cisco switches and routers.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - How DevOps techniques can fix the problems that happen in IT organizations.
* [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) - The first and second editions describes the best practices of system and network administration, independent of specific platforms or technologies.
* [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - Is a methodology designed to jumpstart implementation of controls and process improvement.
* [UNIX and Linux System Administration Handbook](http://www.admin.com/) - Approaches system administration from a practical perspective.
* [Securing DevOps](https://manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8) - A book on Security techniques for DevOps that reviews state of the art practices used in securing web applications and their infrastructure.

## Новинні листи

* [Servers for Hackers](http://serversforhackers.com/) - Newsletter for programmers who find themselves needing to know their way around a server.
* [DevOpsLinks](http://devopslinks.com) - A community of DevOps, SysAdmin & Developers with a weekly newsletter and a team chat.

## Репозиторії

*Для дистрибутивів на основі Debian.*

* [Dotdeb](http://www.dotdeb.org/) - Repository with LAMP updated packages for Debian.

*Для дистрибутивів на основі RPM.*

* [ElRepo](http://elrepo.org/tiki/tiki-index.php) - Community Repo for Enterprise Linux (RHEL, CentOS, etc).
* [EPEL](https://fedoraproject.org/wiki/EPEL) - Repository for RHEL and compatibles (CentOS, Scientific Linux).
* [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.
* [Software Collections](https://www.softwarecollections.org) - Community Release of [Red Hat Software Collections](https://access.redhat.com/documentation/en-US/Red_Hat_Software_Collections/). Provides updated packages of Ruby, Python, etc. for CentOS/Scientific Linux 6.x.

## Вебсайти

*Повʼязані з системним адмініструванням вебсайти.*

* [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
* [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - A surprisingly vast resource for getting the basics of certain applications, tools, or even systems administration topics.

## Ліцензія

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

Дана робота розповсюджується під ліцензією [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/).
