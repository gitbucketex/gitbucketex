GitBucketEx [![build](https://github.com/gitbucketex/gitbucketex/workflows/build/badge.svg?branch=master)](https://github.com/gitbucketex/gitbucketex/actions?query=workflow%3Abuild+branch%3Amaster) (https://github.com/gitbucketex/gitbucketex/blob/master/LICENSE)
=========

GitBucketEx is a Git web platform powered by Scala offering:

- Easy installation
- Intuitive UI
- High extensibility by plugins
- API compatibility with GitHub
- Extended Version Of GitBucket

![GitBucketEx](https://git.tahaghafuri.ir/img/screenshots/screenshot-repository_viewer.png)

Features
--------
The current version of GitBucket provides many features such as:

- Public / Private Git repositories (with http/https and ssh access)
- GitLFS support
- Repository viewer including an online file editor
- Issues, Pull Requests and Wiki for repositories
- Activity timeline and email notifications
- Account and group management with LDAP integration
- a Plug-in system

Installation
--------
GitBucket requires **Java 11**. You have to install it, if it is not already installed.

1. Download the latest **gitbucket.war** from [the releases page](https://github.com/gitbucketex/gitbucketex/releases) and run it by `java -jar gitbucket.war`.
2. Go to `http://[hostname]:8080/` and log in with ID: **root** / Pass: **root**.

You can also deploy `gitbucket.war` to a servlet container which supports Servlet 3.0 (like Jetty, Tomcat, JBoss, etc). Note that GitBucket doesn't support Jakarta EE yet.

For more information about installation on Mac or Windows Server (with IIS), or configuration of Apache or Nginx and also integration with other tools or services such as Jenkins or Slack, see [Wiki](https://github.com/gitbucketex/gitbucketex/wiki).

To upgrade GitBucket, replace `gitbucket.war` with the new version, after stopping GitBucket. All GitBucket data is stored in `HOME/.gitbucket` by default. So if you want to back up GitBucket's data, copy this directory to the backup location.

Plugins
--------
GitBucketEx Uses GitBucket's Pugins::

- [gitbucket-gist-plugin](https://github.com/gitbucket/gitbucket-gist-plugin)
- [gitbucket-emoji-plugin](https://github.com/gitbucket/gitbucket-emoji-plugin)
- [gitbucket-pages-plugin](https://github.com/gitbucket/gitbucket-pages-plugin)
- [gitbucket-notifications-plugin](https://github.com/gitbucket/gitbucket-notifications-plugin)

What's New in 4.42.x
-------------
## 4.42.0 - 24 Sep 2024
- Simple UI Changes

See the [change log](CHANGELOG.md) for all of the updates.
