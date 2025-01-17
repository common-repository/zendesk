=== Zendesk Support for Wordpress ===

Contributors: zendesk_official
License: Apache 2.0
Donate link: http://www.zendesk.com/
Tags: zendesk, support, customer support, help desk, helpdesk, IT, customer, admin, bug, ticket, widget, comments
Requires at least: 2.9.2
Tested up to: 6.3.1
Stable tag: 1.8.5

Bring the helpdesk into your blog

== Description ==

Zendesk Support for Wordpress allows you to bring your helpdesk, powered by Zendesk, into your blog or site. Here's an overview of all the features:

* **Single sign on with Zendesk's Remote Authentication**
Have a healthy user base already? With Single Sign On, your users won't have to login to Zendesk Support to submit tickets, check their progress or comment in community forums.

  When users try to login to Zendesk, we'll ping your Wordpress site to see if they're already logged in, and then sign them straight into Zendesk without them needing to register or set a new password. It's 100% secure, too!

* **Turn your blog comments straight into Zendesk Support tickets, with one click**
Need to take that conversation offline, or escalate someones question or problem to someone else in the company. From the comments administration screen, you can take any comment made and turn it into a Ticket. The process is completely seamless for your users, and they'll appreciate the extra mile you're going to provide amazing customer service.

* **The Zendesk Support Web Widget**
Add the Zendesk Support Web Widget to any webpage so users can search your knowledge base, chat with an agent or submit a ticket. You can have it on every page on your Wordpress blog, or choose where you want it with the use of a template tag.

* **The Zendesk Support Feedback Tab**
Add a tab to any webpage so users can search your knowledge base, chat with an agent or submit a ticket. You can completely customize the look and feel. You can have it on every page on your Wordpress blog, or choose where you want it with the use of a template tag.

Note: Zendesk Support Dropbox users - the dropbox (also known as Zendesk Support Feedback Tab) is soon to be deprecated and has been replaced with the Web Widget. You can continue to use your dropbox for now but we encourage you to try the Web Widget (available in your plug-in) which allows you to easily embed ticketing, self-service and chat on your website as well as providing a much improved experience on mobile web browsers.

* **Access your tickets from your dashboard**
Full access to your views, tickets (including custom fields) and comments. Never lose sight on your support requests, no matter where you are.

* **A simple contact form, on the dashboard**
Give your visitors the ability to quickly submit a question or issue with a two field contact form. You can place this on the dashboard, restricting it to only those with Zendesk accounts, or you can allow anyone to open a request regardless of a Zendesk account.

Like the sound of this plugin but don't have a Zendesk account yet?  Sign up in just 30 seconds for a 30 day free [help desk software](http://www.zendesk.com/?utm_source=wp&utm_medium=dl&utm_campaign=wppin "Zendesk help desk software") trial with no credit card needed.

== Screenshots ==

1. An overview of some of the features available in the settings page
2. Remote authentication, super easy to set up
3. Turn a comment into a ticket with ease
4. The comment to ticket interface
5. The Web Widget at its simplest, a Contact Form that creates a ticket in your Zendesk when filled out
6. If you have a Zendesk Help Center, the Web Widget can help deflect tickets by showing your self-service content when users search for help
7. The Zendesk dropbox in action

== Installation ==

For an automatic installation through WordPress:

1. Go to the 'Add New' plugins screen in your WordPress admin area
1. Search for 'Zendesk Support for Wordpress'
1. Click 'Install Now' and activate the plugin

For a manual installation via FTP:

1. Upload the addthis folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' screen in your WordPress admin area

To upload the plugin through WordPress, instead of FTP:

1. Upload the downloaded zip file on the 'Add New' plugins screen (see the 'Upload' tab) in your WordPress admin area and activate.

== Frequently Asked Questions ==

* **I don't have a Zendesk account, can I still use this plugin?**

  You do need a Zendesk account in order to use this plugin, otherwise it's a little useless! You can sign up in 30 seconds, which gives you a 30 day free [help desk software](http://www.zendesk.com/?utm_source=wp&utm_medium=faq&utm_campaign=wppin "zendesk help desk software") trial with no credit card needed.

* **What template tags are available at what do they do?**

  As of 1.6 there are two template tags available:

  * **the_zendesk_webwidget**

  It can be used like:

  `<?php if ( function_exists( 'the_zendesk_webwidget' ) ) the_zendesk_webwidget(); ?>`

  This will place the Zendesk Support Web Widget on to any template page you wish. **Make sure it's as close to the footer as possible.**

  Alternatively, if you want the Zendesk Web Widget placed on all pages and posts on your site, you can choose this option from this plugin's settings page, rather than using the template tag.

  * **the_zendesk_dropbox**

  It can be used like:

  `<?php if ( function_exists( 'the_zendesk_dropbox' ) ) the_zendesk_dropbox(); ?>`

  This will place the Zendesk Support Feedback Tab (formerly known as dropbox) on to any template page you wish. **Make sure it's as close to the footer as possible.**

  Alternatively, if you want the Zendesk Suuport Feedback Tab placed on all pages and posts on your site, you can choose this option from this plugin's settings page, rather than using the template tag.


* **Why doesn't the "Convert to ticket" link show up on my comments?**

  There are three possible reasons for this.

  1. The person that made the comment does not have an email address, in which case turning their comment into a ticket would be useless, as you would not be able to get back to them.
  1. That comment already has a comment against it, each comment can only have one Zendesk Support ticket associated.
  1. You are not authenticated into Zendesk via Wordpress. To do this, you'll need to login via the Zendesk for Wordpress widget. This can either be the tickets widget, or the contact form widget (where anonymous submission are turned off).

* **I don't understand how Single Sign On with Zendesk's Remote Authentication works, where can I find out more?**

  [We've made this super handy guide](https://support.zendesk.com/entries/20110872-setting-up-remote-authentication-for-wordpress "Setting up remote authentication for wordpress") on what it is and how to get started.

* **Do I have to display any dashboard widgets, the Zendesk Web Widget, the Zendesk Support Feedback Tab or the contact form?**

  Nope! It's completely up to you. If you want, you can just use the plugin for single sign on with Zendesk.

== Changelog ==

=1.8.5=
* Tested on Wordpress v6.3.1
* Security improvements

=1.8.4=
* Tested on Wordpress v5.6
* Fix adding public/private note to zendesk ticket
* Fix option to add comment to wordpress
* Updated some deprecated codes that was not supported in PHP 7.4
* NOTE: The current plugin was not yet tested in PHP v8.0. Another update will be released soon once the plugin was tested.

= 1.8.2 =
* Improve github actions

= 1.8.1 =
* Fix some deployment issues

= 1.8.0 =
* Fix the "Convert to ticket" link to show the pop up modal.
* Fix the "Change view" to show options.
* Fix the zendesk ticket details not showing after in dashboard
* Fix the submenus tend to display only for a brief moment.
* Fix the Media Library not showing uploaded media files.
* Fix show password from user profile not showing password.
* Tested on Wordpress v5.5

= 1.7.5 =
* Tested on Wordpress v5.4.2

= 1.7.4 =
* Tested on Wordpress v5.4.1

= 1.7.3 =
* Tested on Wordpress v5.1.1

= 1.7.2 =
* Remove sslverify => false option to allow the Zendesk API to perform SSL verification

= 1.7.1 =
* Create embeddable configuration if it does not yet exist
* Updated the https detection logic

= 1.7.0 =
* Make external_id optional on sso payload
* Bump jquery colorbox from 1.3.16 to 1.3.21

= 1.6.11 =
* Fix asset conflict with other plugins due to enqueue hook

= 1.6.10 =
* Fix problematic autolink regex for gravatar profile images
* Prefix JWT class and make use of autoload

= 1.6.9 =
* Fix broken link on the dashboard widget

= 1.6.8 =
* Rebranding logo and banner

= 1.6.7 =
* Rebranding strings

= 1.6.6 =
* Improve SSO login error page

= 1.6.5 =
* Security patch

= 1.6.4 =
* Add support for wordpress 4.4

= 1.6.3 =
* Security patch

= 1.6.2 =
* Updated the JWT Version we use to improve security

= 1.6.1 =
* Improved performance when retrieving Agents for the Contact Form on settings page
* Fix domain validation to accept domains starting with numbers

= 1.6 =
* Added ability to display the Embeddables Web Widget everywhere, or specifically using a template tag. More info at [zendesk.com/embeddables](http://zendesk.com/embeddables)

= 1.5 =
* Make this plugin to consume Zendesk API v2
* Several Refactoring

= 1.0 =
* Added ability to display tickets on the dashboard, for different levels of users.
* Added ability to display contact form on the dashboard, for different levels of users.
* Added ability to display the Zendesk dropbox everywhere, or specifically using a template tag.
* Added ability to convert a comment into a ticket from the administration panel.
* Added ability to use single sign on with Zendesk's remote authentication.

== Upgrade Notice ==

No upgrades at this time.

== Publishing a new version of the plugin on wordpress.org ==

If you are a developer looking to release a new version of the plugin
See: https://zendesk.atlassian.net/wiki/display/ENG/Publishing+new+versions+of+plugins+to+Wordpress.org
