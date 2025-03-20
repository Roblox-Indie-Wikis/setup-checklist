## Wiki Checklist 
description 


## Choosing A Home

* Buying a domain (or not?) 
    * A domain is your home on the internet. If you can, it’s usually best for you to buy your own domain for identity. Most wikis use the .wiki or .org TLDs for their sites. Places like Spaceship and CloudFlare are good places to start looking. If not, most wiki farms and some online services offer free domains. 
* Hosting or Wiki Farm? 
    * Where will your wiki live? Some viable wiki farm options to consider are Miraheze and WikiOasis, or if you would like to self-host, DigitalOcean. 
* LAMP/LEMP Stack? 
    * If you are self-hosting, what stack will you use? Apache is generally best for most use cases, though ngix can better handle large amounts of data. 
* CloudFlare caching
    * If you are self-hosting, using CloudFlare to manage DNS, caching and email can be a cost effective and great way to speed up your site. 
* Works License 
    * Choose a license for your wiki Most wikis choose a Creative Commons license, which protects their interests but allows content to be used for others in some capacity. 

Setting Up
* Privacy Policy Page
    * Especially if you are self-hosting, this is essential to outline what data is collected and how it is used. 
* Terms of Service Page
    * Especially if you are self-hosting, you can outline general guidelines
* General Disclaimer Page 
    * A wiki disclaimer page tells people what your wiki is not. Common uses of this page disclaim liability and inform users content is not uniformly peer reviewed. 
* Cookie Information Page
    * This page should outline what cookies your site has and what they are for. Some wiki farms provide a cookie page for you. 
* Rules Page 
    * 
* Style Guide Page + 
* About Page + 
* Staff Information Page + 
* Copyrights Page + 
* Image Copyrights + 
* Theme + 
* Main Page + 
* Site Icon
* Site Logo
* Categorise Namespaces + 
* Categorise roles and permissions + 

Configuration
* Setup Email Servers 
    * If you are self-hosting, email functionality is essential for your wiki. Things like password confirmation, resetting and more need this functionality. There are a few free services like what(?) to cover for this. 
* Register Google Webmaster
    * By connecting your website with Google Webmaster and adding a sitemap, this allows google to better index your site, and for you to see detailed statistics. To make a sitemap, check the extensions list below. 
* Register Bing Webmaster
    * You can easily link your Google and Bing webmaster account in a click. Sitemap data will be shared too. This allows Bing to better index your site. 

Core Extensions 
These extensions are almost always essential to running a successful wiki. Some  may come pre installed, but need to be activated in LocalSettings.php. 
* WikiSEO 
* RobloxAPI 
* TemplateStyles
* TemplateStyles Extender
* TabberNeue
* SyntaxHighlight
* Portable Infobox
* Parser Functions
* Math
* EmbedVideo fork
* Svg handler
* Pdf handler
* ConfirmEdit/Turnstile
* PageImages
* ShortDescription
* AutoSitemap
* CookieWarning 
* Previews
* Multimedia Viewer
* Related Articles
* Site notice

Others
* Discord Webhook 
    * A recent changes webhook can be useful for big wikis. Miraheze and the Discord WikiBot provides this functionality. 
* IndieWikiBuddy
    * If you are forking, or there is another wiki of the same topic on a non independent wiki, this extension can help redirect people to the right place. 
