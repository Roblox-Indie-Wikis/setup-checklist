# Wiki Checklist 
> [!IMPORTANT]
> Not Finished

## Choosing A Home

* Buying a domain (or not?) 
    * A domain is your home on the internet. If you can, it’s usually best for you to buy your own domain for identity. Most wikis use the .wiki or .org TLDs for their sites. Places like [Spaceship](https://www.spaceship.com/) and [CloudFlare](https://www.cloudflare.com/domains) are good places to start looking. If not, most wiki farms and some online services offer free domains. 
* Hosting or Wiki Farm? 
    * Where will your wiki live? Some viable wiki farm options to consider are [Miraheze](https://miraheze.org/) and [WikiOasis](https://wikioasis.org/), or if you would like to self-host, [DigitalOcean](https://www.digitalocean.com/). 
* LAMP/LEMP Stack? 
    * If you are self-hosting, what stack will you use? Apache is generally best for most use cases, though ngix can better handle large amounts of data. 
* CloudFlare caching
    * If you are self-hosting, using [CloudFlare](https://www.cloudflare.com/) to manage DNS, caching and email can be a cost effective and great way to speed up your site. 
* Works License 
    * Choose a license for your wiki Most wikis choose a [Creative Commons license](https://creativecommons.org/share-your-work/), which protects their interests but allows content to be used for others in some capacity. 

## Setting Up
* Privacy Policy Page
    * Especially if you are self-hosting, this is essential to outline what data is collected and how it is used. An example of a wiki Privacy Policy can be found [here](https://dovedale.wiki/wiki/Dovedale_Wiki:Terms_Of_Service_and_Privacy_Policy).
* Terms of Service Page
    * Especially if you are self-hosting, you can outline general guidelines and disclaimers for website use. An example of a wiki Privacy Policy can be found [here](https://dovedale.wiki/wiki/Dovedale_Wiki:Terms_Of_Service_and_Privacy_Policy).
* General Disclaimer Page 
    * A wiki disclaimer page tells people what your wiki is not. Common uses of this page disclaim liability and inform users content is not uniformly peer reviewed. An example of a general disclaimer page can be found [here](https://hybridcafe.wiki/wiki/Hybrid_Cafe_Wiki:General_disclaimer).
* Cookie Statement & Information Page
    * This page should outline what cookies your site has and what they are for. Some wiki farms provide a cookie page for you. An example of a cookie statement page can be found [here](https://dovedale.wiki/wiki/Dovedale_Wiki:Cookie_Statement).
* Rules Page 
    * Rules are important as your wiki and its discussions are open to anybody. Rules should be simple, yet descriptive. They should also be linked on the front page. An example of a rules page can be found [here](https://urbanshade.org/wiki/Project:RULES). 
* Style Guide Page
    * A style guide sets the standards for the writing, formatting, and design of your wiki. Since anyone or a large group of editors will be editing your wiki, everyone may not be on the same page as to how pages should look. A style guide helps set this down in stone. Suggested sections include Orthography, Punctuation, Wikitext formatting, Numbers, Dates and Currencies. An example of a Style Guide can be found [here](https://dovedale.wiki/wiki/Dovedale_Wiki:Style_Guide#Editorial_Style).
* About Page 
    * The about page tells users a little about the history of the wiki, why it exists, the staff team etc. Most themes also link this page in the footer. An example of an about page can be seen [here](https://starcitizen.tools/Star_Citizen_Wiki:About) and [here](https://dovedale.wiki/wiki/Dovedale_Wiki:About).
* Staff Information Page
    * A staff information page lists all staff names, user rights management procedures, and usually contains additonal details about each staff member like their rank, timezone and area of work. The staff information page can also house an explanation of the staff roles. This page should also be linked to your front page, to allow easy contact if your wiki users require it. A good example of a staff page can be seen [here](https://hybridcafe.wiki/wiki/Hybrid_Cafe_Wiki:Staff) and [here](https://dovedale.wiki/wiki/Project:Staff).
* Copyrights Page
    * A copyright page informs users of copyright procedures on the wiki. This page is usually linked in the editors as people edit, so it is important this is filled in. The copyright page should include your wiki license, an explanation to it, as well as information on media file copyright procedures, which are usually different from the pages. An example of a copyright page can be found [here](https://hybridcafe.wiki/wiki/Hybrid_Cafe_Wiki:Copyrights). 
* Image Copyrights 
    * As stated above, image copyrights usually fall under a different class. 
* Theme 
    * Your theme dictates how your site will look and feel. While you can further customise it using CSS and JS, the base of your site will rely on what theme you decide on. Popular themes for modern wikis include Timeless, Citizen and XXX. You can view a full list of themes here. 
    * Wiki Examples with different themes: 
        * Citizen: [Outlaster](https://outlaster.peakprecision.wiki/), [Tolkien Gateway](https://tolkiengateway.net/), [Untitled Tag Game](https://utg.miraheze.org/), [Apple](https://theapplewiki.com/wiki/Main_Page), [Star Citizen](https://starcitizen.tools/)
        * Timeless: [Pressure](https://urbanshade.org/), [Fisch](https://fischipedia.org/), [KeukenWiki](https://keukenwiki.nl/Hoofdpagina)
        * Vector: [Hollow Knight](https://hollowknight.wiki/), [Minecraft](https://minecraft.wiki/)
* Main Page + 
* Site Icon
* Site Logo
* Categorise Namespaces + 
* Categorise roles and permissions + 

## Configuration
* Setup Email Servers 
    * If you are self-hosting, email functionality is essential for your wiki. Things like password confirmation, resetting and more need this functionality. There are a few free services like what(?) to cover for this. 
* Register Google Search Console
    * By connecting your website with [Google Search Console](https://search.google.com/search-console) and adding a sitemap, this allows google to better index your site, and for you to see detailed statistics. To make a sitemap, check the extensions list below. 
* Register Bing Webmaster
    * You can easily link your Google and [Bing webmaster](https://www.bing.com/webmaster/tools) account in a click. Sitemap data will be shared too. This allows Bing to better index your site. 

## Core Extensions 
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

## Others
* Discord Webhook 
    * A recent changes webhook can be useful for big wikis. Miraheze and the Discord WikiBot provides this functionality. 
* IndieWikiBuddy
    * If you are forking, or there is another wiki of the same topic on a non independent wiki, this extension can help redirect people to the right place. 
