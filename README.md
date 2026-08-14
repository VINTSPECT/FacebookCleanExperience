Facebook Clean Experience is a simple guide that, as of this writing, is still effective for removing ads on Facebook without any complicated configuration. Thanks to (https://github.com/Artificial-Sweetener/facebook-clean-my-feeds) for the user script (FB - clean my feed), which removes sponsored ads from the Facebook homepage.
This is my first repository, so it will look pretty basic. Please help me out and give me feedback so I can keep improving.


Here’s the guide:

A. Initial Setup:
1. Install a userscript manager extension (Violentmonkey, ScriptCat, Firemonkey, or similar). I recommend [Violentmonkey](https://violentmonkey.github.io/) because it’s more memory-efficient.
2. Install the userscript called “[FB-clean my feeds](https://greasyfork.org/en/scripts/552339-fb-clean-my-feeds-5-05).” This is a key tool that, in my opinion, can make using Facebook enjoyable again. It does more than just remove ads.
3. Click “Install” for that userscript on your userscript manager’s extensions page.
4. Download the .json file from the “[Releases](https://github.com/VINTSPECT/FacebookCleanExperience/releases)” section of this repository. This file contains the settings I use daily on Facebook. If you’re suspicious of the file, please scan it with your best antivirus software before proceeding with the rest of this guide.


B. Setting Up the FB-Clean-My-Feeds Script
1. Open the Facebook page in your browser.
2. Look for the broom icon in the top-right corner of Facebook. Click the icon to open the script page.
3. Click “Import.” Locate the .json file you downloaded earlier and click “Open.”
4. Don't forget to click "Save". Refresh your Facebook page. Sponsored ads should no longer appear on your Facebook homepage.


C. Important notes:

1. You can further configure the settings of the FB-clean-my-feeds script yourself according to your preferences and needs. Based on my own experience, I recommend unchecking “suggestions/recommendations” in the News Feed, as this will cause your browser’s RAM usage to spike. Just check the important sections as listed in the .json file I’ve provided (sponsored, paid partnerships, sponsored—paid for by, AI in side panels, and pause animated GIFs).
2. For the Group Feed and Marketplace settings, I’ve checked the “Sponsored” and “Paid Partnership” sections to remove ads. As before, avoid checking unnecessary options so your Facebook experience isn’t disrupted by excessive memory usage. The .json file I’ve shared in this repository represents the minimal settings that I believe strike a balance between privacy and user convenience. Advanced users can customize their own settings without having to stick strictly to my preferences.
3. I’ve tested this guide on a desktop browser running Windows. I haven’t tried it on Android or iOS devices yet, but any Android or iOS browser that supports userscripts should be able to run this script. Please let me know if you encounter any issues on your mobile device.
4. This method cannot guarantee 100% success because Facebook may change its code. As of the time of writing, it’s still working for me, and I hope it continues to work.


D. Additional Notes:

If you want to enhance your Facebook experience, you can use the filter settings I use every day. Use your preferred ad-blocker extension (I use uBlock Origin). You can copy all or some of this [filters](https://github.com/VINTSPECT/FacebookCleanExperience/blob/main/Facebook%20My%20Filters.txt), depending on your needs. The filter includes removing the right sidebar and several items in the left sidebar that I don't think are necessary. In my experience, all of these settings can improve your Facebook experience in a browser and reduce unnecessary elements (think of it as “debloating” Facebook).





That’s all I have to say. I hope this is useful and helps more people. Thank you for visiting my first repository.
