VCP-Stammes Page Tempalte
=========================

A mediator inspired Jekyll page theme. The theme is optimized to provide [VCP](http://vcp.de) groups an easy to use webpage template. It provides all functionalities to setup an simple scouting webpage.

Screenshots
--------
![screenshot](/assets/images/screenshot1.jpg)
![screenshot](/assets/images/screenshot2.jpg)
![screenshot](/assets/images/screenshot3.jpg)

Features
-------
* Fully Responsive layout
* Integrated templates for staff and groups
* Minimal design
* FontAwesome implemented for easy use of icons fonts
* Free & Open Source Font usage

Getting Started
---
- [Fork this repository](https://github.com/dirkfabisch/mediator)
- Clone it: `git clone https://github.com/YOUR-USER/mediator`
- Install the [GitHub Pages gem](https://github.com/github/pages-gem) (includes Jekyll): `bundle install`
- Install the [Bourbon gem](https://github.com/thoughtbot/bourbon) `gem install bourbon`
- Run the jekyll server: `jekyll serve`

You should have a server up and running locally at <http://localhost:4000>.

Configuration
-----

The main settings happen in side of the _config.yml file:

### Site

Main settings for the site

* **title**: name of your site
* **description**: description of your site
* **logo**: small logo for the site (300x * 300x)
* **cover**: large background image on the index page

* **name**: name webmaster
* **email**: mail address of the webmaster
* **group_name**: name of the scout group
* **group_address**: address of group
* **group_phone**: phone number of the group or webmaster
* **group_email**: emailadress of the group

* **url**: url of the website

### Social

The template allows to add all major social plattforms to your site.
Fill the the form for each plattform. If you leave the share_* entries empty, the sharing buttons below a post are not shown.  If you leave the **url** and **desc** empty the icons are not shown on the index page, but the share icons on the article pages remains untouched (Thanks to [Phil](https://github.com/philsturgeon))

* **icon**:	name of social plattform (must match a name of [font-awsome](http://fortawesome.github.io/Font-Awesome/) icon set )
* **url**:	url of your account
* **desc**: slogan of the plattform
* **share_url**: share url
* **share_title**: first part of url for the title
* **share_link**: second part of the share url for the link to the post

The Liquid template engine will magical combine the different parts to a share url.

```
http://twitter.com/share?text=post_title&amp;url=post_url
````

See [_config.yml](https://github.com/dirkfabisch/mediator/blob/master/_config.yml) for more examples.

Group
-----
You can define preformated group descriptions. They show up at the front page and are linked to a more detailed sub page. To get all the details in place, you have to provide some metadata.

* **layout**: should be `group`
* **title**: name of the group
* **image**: image of the group
* **leaders**: description of the group leads
  * **name**: full name of the group lead
  * **bio**: short sentence about the carier
  * **contanct**: contact information like phone number
  * **image**: portrait image
* **meeting**: information about when the group meetings are happen
  * **point**: meeting point / address
  * **day**: meeting day
  * **from**: start time
  * **to**: end time
  * **level**: level of the group e.g. cup scouts
  * **age**: agre range

Licensing
---------

[MIT](https://github.com/dirkfabisch/madiator/blob/master/LICENSE) with no added caveats, so feel free to use this on your site without linking back to me or using a disclaimer or anything silly like that.

Contact
-------
I'd love to hear from you at [@quablab](https://twitter.com/quablab). Feel free to open issues if you run into trouble or have suggestions. Pull Requests always welcome.
