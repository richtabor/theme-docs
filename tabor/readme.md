

# Getting Started



## 1. Activate your License
It’s strongly recommended that you add your theme’s license key in the Tabor License widget on your WordPress Dashboard. By adding your key, you will activate the seamless theme updates and have access to our support team.

You can find your theme’s license key by checking your purchase receipt or signing in to your ThemeBeans dashboard. If you purchased the theme from ThemeForest, you may [request your license key here][1]. You’ll need your ThemeForest purchase code handy.

Copy this key and enter it into the **Tabor License** widget on your WordPress Dashboard. Save and activate your license key.

## 2. Install the Child Theme
If you plan on modifying anything within the theme files directly, please install the included child theme. If you change anything within the theme folder and approve an update from our servers **your modifications will be lost**. By using a child theme you will ensure that your changes are preserved.

Log in to your website's dashboard and navigate to the Dashboard \> Appearance \> Themes page. Click **Add New** and follow the directions to upload the tabor-child.zip file, located in your theme’s package download.

Simply click **Activate** and both the Tabor theme and Tabor child theme will be active on your WordPress site. Now have at it.

## 3. Install Demo Data
When you first activate Tabor, it will look like a simple website with your existing content. This is expected since Tabor needs you to modify a few settings before it will look exactly like the demo.

You can find the tabor.xml data file in the theme package download. You can install this XML file by going to **Tools** → **Import** → **WordPress** and click **Choose File**. Upload the XML file and follow the steps to import.

When the demo data is finished importing, you should have several new posts and pages to work with going forward.

## 4. Prepare your Images
In order to get the best looking images in Tabor, we need to refresh your images to be cropped to Tabor’s image sizes. We do this with the [Regenerate Thumbnails][2] plugin.

After activating the plugin, go to **Tools** → **Regen. Thumbnails**, then press the **Regenerate All Thumbnails** button to start generating new image sizes.

Once it’s finished, your library of images will be optimized and ready to go.




# Set up your Home Page

To get the same home page that we're using on the live demo, simply add two H1 elements to whichever page you set as the **Front Page** in the **Customizer \> Static Front Page** options panel.


## 1. Navigate to the Customizer
Next, you will need to set the page as your site's front page, via the **WP Dashboard** \> **Appearance** \> **Customize** page, within the Static Front Page panel. 

![][image-1]

## 2. Set a Static Page

Next, to establish a static page, open the **Static Front Page** panel, within the Customizer.

![][image-2]

## 3. Assign a Front Page

From the “Static Front Page” panel, select the static page option. This will set your website to display a page, instead of a blogroll, on the home page. 

Next select the templated page you first created as the Front Page option. 

Then hit the **Save & Publish** button up at the top of the Customizer window, and you should be all set.

![][image-3]

## 4. Home Page Demo Content
Below is the content to use to replicate the theme's demo.
```
<h5>Hi, I'm</h5>
<h1>Rich</h1>
<h1>Tabor</h1>
[typed text="ThemeBeans Founder, Designer"]
```

## 5. Adding the typing animation header

The typing animation can be added to any page's content through the use of the [typed] shortcode.

Example:
```
[typed text="ThemeBeans Founder, Designer, WordPress Developer"]
```
Separate out the individual lines with a comma. That's it!


# Assign Menus
To set your menus, locate the Menu options by selecting the “Appearance” tab from the dashboard sidebar and then “Menus”.

Once you’re viewing the Menus, create a new menu and save it. After you’ve saved the menu, you can add it to a menu via the Menu Settings, below the Menu Structure area. Add your pages and links to the menu you just created in the Menu Structure area.


## Primary Menu
Add a footer menu to your website simply by creating a menu and assigning it to the Footer Menu location - as described above.

## Social Menu
The icons added to your Social Menu will automatically populate next to the site logo. To add the icons, add a link to your social media profile and the theme will do the rest.


# OptinMonster
To repliate the live demo, install the [OptinMonster WordPress plugin][7] and add the OptinMonster widget to the Footer widget area. You'll want to use the Action optin theme, which is a Sidebar theme type.

For the inline opt-in, you should use the "Action" theme from OptinMonster, with the Theme Type set to "After Post / Inline". Then simply add the shortcode to your post, wherever you see fit. Here's an example of the shortcode:
```
[optin-monster-shortcode id="yvm0geh9mdiokfipp6gk"]
```


# Frequently Asked

1. **How do I update my theme?** With an active license key, you’ll receive a notification in the WordPress Dashboard whenever there is an update available. You can then update right in your WordPress dashboard, keeping your site healthy and secure.

2. **How do I get help?** You can request support via our official [Help Center][3]. We’re here to help with any technical questions, though any customization requests should be directed [here][4].

3. **Do I need a theme license key?** You don’t need a key to use the theme, but in order to receive support and in-dashboard update notifications, an active license key is required.

4. **How do I get a license key** You can find your theme’s license key by checking your ThemeBeans purchase receipt or signing in to your ThemeBeans dashboard. If you purchased the theme from ThemeForest, you may [request your license key here][5].

5. **How long is my license key valid for?** Initial licenses are issued on an annual basis. If you’ve purchased from ThemeForest, you’ll have access to support and in-dashboard updates as long as you have a support package.

6. **Can I use my theme with an expired license** You sure can! You just won’t have access to in-dashboard updates, as well as our support team.



# Need Help?
Have questions? [Get in touch][6] with a friendly member of our team and we’ll be happy to help.

## Support Tips

**Troubleshoot first.** The best way to troubleshoot plugin conflicts is by deactivating all WordPress plugins and activate them one by one. Also, don’t forget to empty your cache if you are using a caching plugin.

**Use the Help Center.** Please use our official Help Center to ask for help. It’s monitored daily and the only designated support channel.

**Please be nice.** You should always be nice to the support personal. The folks on our support team really do enjoy helping others, but you can really ruin their day by using negative words.

[1]:	https://themebeans.com/themeforest "Request a License Key"
[2]:	https://wordpress.org/plugins/regenerate-thumbnails/ "Regenerate Thumbnails WordPress Plugin"
[3]:	https://themebeans.com/contact
[4]:	http://themebeans.com/customizations
[5]:	https://themebeans.com/themeforest
[6]:	https://themebeans.com/contact
[7]:	https://wordpress.org/plugins/optinmonster/

[image-1]:	http://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595fecf50428637ff8d462b8/file-6DaAqO3m5Y.jpg "Open the Static Front Page panel, in the Customizer"
[image-2]:	http://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595fed1c0428637ff8d462bb/file-pyUecy41SC.jpg "Set a Static Page"
[image-3]:	http://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595fee092c7d3a707d7b83c1/file-kPOj2r5Dq3.jpg "Assign a new Front Page"
