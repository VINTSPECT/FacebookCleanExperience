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
4. Refresh your Facebook page. Sponsored ads should no longer appear on your Facebook homepage.


C. Important notes:
1. You can further configure the settings of the FB-clean-my-feeds script yourself according to your preferences and needs. Based on my own experience, I recommend unchecking “suggestions/recommendations” in the News Feed, as this will cause your browser’s RAM usage to spike. Just check the important sections as listed in the .json file I’ve provided (sponsored, paid partnerships, sponsored—paid for by, AI in side panels, and pause animated GIFs).
2. For the Group Feed and Marketplace settings, I’ve checked the “Sponsored” and “Paid Partnership” sections to remove ads. As before, avoid checking unnecessary options so your Facebook experience isn’t disrupted by excessive memory usage. The .json file I’ve shared in this repository represents the minimal settings that I believe strike a balance between privacy and user convenience. Advanced users can customize their own settings without having to stick strictly to my preferences.
3. Panduan ini saya gunakan di browser desktop dengan OS windows. Saya belum mencoba di perangkat android/ios dan seharusnya browser android/ios yang mendukung userscript dapat menjalankan script ini. Informasikan saya apabila anda menemui kendala di perangkat hp.
4. Cara ini tidak dapat menjamin keberhasilan 100% karena Facebook dapat mengubah kode di facebook. Untuk saat ini saat tulisan ini ditulis masih berfungsi di saya dan semoga dapat terus berfungsi.


D. Additional Notes:
1. If you want to enhance your Facebook experience, you can use the filter settings I use every day. Use your preferred ad-blocker extension (I use uBlock Origin). You can copy all or some of the filters below, depending on your needs:

   
! ----- FACEBOOK FILTERS -----

! Removes friend and followed stories from home
www.facebook.com##.x193iq5w.xgmub6v.x1ceravr.x1v0nzow
! Removes Reels, Groups, Events Navigation Buttons
www.facebook.com##ul.xuk3077.x78zum5.x1iyjqo2.xl56j7k.xe11lzi.x1vy8oqc.x88anuq>li:nth-child(2)
www.facebook.com##ul.xuk3077.x78zum5.x1iyjqo2.xl56j7k.xe11lzi.x1vy8oqc.x88anuq>li:nth-child(4)
www.facebook.com##ul.xuk3077.x78zum5.x1iyjqo2.xl56j7k.xe11lzi.x1vy8oqc.x88anuq>li:nth-child(5)
! Removes Reels button from left sidebar
www.facebook.com##.x1us19tq.x1iyjqo2.xdt5ytf.x78zum5 > .x1iyjqo2 li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:has(span:has-text(/^Reels$/))
! Removes Reels button from Facebook Menu
www.facebook.com###_r_7q_ > div.x193iq5w.x2lah0s.xdt5ytf.x78zum5.x9f619.x1ja2u2z.x1n2onr6:has(span:has-text(/^Reels$/))

! My Preferences
www.facebook.com##.x1v0nzow.x1ceravr.x17zi3g0.xvue9z.x193iq5w > .xod5an3
www.facebook.com##.xf7dkkf.x1l90r2v.xv54qhq.xyamay9.x2lah0s
www.facebook.com##.x1us19tq.x1iyjqo2.xdt5ytf.x78zum5 > .x1iyjqo2 .xwib8y2
www.facebook.com##div:nth-of-type(2) > ul
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(11) > .x193iq5w.x2lah0s.xdt5ytf.x78zum5.x9f619.x1ja2u2z.x1n2onr6 > .x2lwn1j.x1iyjqo2.xdt5ytf.x78zum5.x1ja2u2z.x1n2onr6.x9f619 > .xf159sx.xmzvs34.x193iq5w.x2lah0s.xdt5ytf.x78zum5.x1ja2u2z.x1n2onr6.x9f619 > .x1lliihq.x1a2a7pz.x1lku1pv.x87ps6o.x1q0g3np.xo1y3bh.x140muxe.xu25z0z.x1fmog5m.x1t137rt.x1ja2u2z.xggy1nq.x1hl2dhg.x16tdsg8.x1n2onr6.x1c1uobl.x18d9i69.xyri2b.xexx8yu.xeuugli.x2lwn1j.x1lziwak.xat24cr.x14z9mp.xdj266r.x3ct3a4.x2lah0s.xdl72j9.x1ypdohk.x9f619.x14e42zd.x1qhh985.x10w94by.x972fbf.x1t7ytsu.x1q0q8m5.x18b5jzi.x13fuv20.x1phubyo.xqeqjp1.xc5r6h4.xjqpnuy.xjbqb8w.x1qjc9v5.x1i10hfl
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(20)
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(8)
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(13) > .x193iq5w.x2lah0s.xdt5ytf.x78zum5.x9f619.x1ja2u2z.x1n2onr6
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(14)
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(17)
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(16) > .x193iq5w.x2lah0s.xdt5ytf.x78zum5.x9f619.x1ja2u2z.x1n2onr6
www.facebook.com##li.x1c1uobl.x18d9i69.xyri2b.xexx8yu.x1lziwak.xat24cr.x14z9mp.xdj266r.html-li:nth-of-type(19)
www.facebook.com###right_rail_container > .x1t2pt76.xedcshv.xdt5ytf.x78zum5.x1ja2u2z.x1n2onr6.x9f619 > .xq1qtft.x1n2onr6.x1odjw0f.x1oyok0e.xwo3gff.xx8ngbg.x2lwn1j.xs83m0k.x1iyjqo2.x1l7klhg.xjx87ck.x1yqm8si.xfk6m8.x1rohswg.x1pq812k.x1ja2u2z.x6ikm8r.xdt5ytf.x78zum5.x5lxg6s.x1q594ok.xb57i2i
! ----- END OF FACEBOOK FILTERS -----



That’s all I have to say. I hope this is useful and helps more people. Thank you for visiting my first repository.
