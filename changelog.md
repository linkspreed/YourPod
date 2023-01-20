# v1.5.2 [20/01/2023]
 - ADDED plugin system, now developers can contribute with plugins for YourPod
 - FIXED 2+ minor bugs.

# v1.5.1 [13/01/2023]
 - FIXED clicking on username in message section goes to 404.
 - FIXED clicking enter on search bar refreshes the bar.
 - FIXED clicking load more on albums page cause to load albums repeatedly.
 - FIXED webp upload issue.
 - FIXED You can not scroll down in the album songs on the mobile browser.
 - FIXED {{ads}} showing in spotlight page.
 - FIXED when you click on load more in hall of fame page, you get broken profiles.
 - FIXED sometimes broken activities show on artist's page.
 - FIXED some links go to 404.
 - FIXED home page on mobile browser is not full responsive.
 - FIXED upload-song and go-pro page on mobile.
 - FIXED broken home icon showing on nonlogged in header.
 - FIXED 5+ minor bugs.

# v1.5 [23/12/2022]
 - ADDED the ability to update profile picture from settings page for phone users.
 - ADDED new theme for volcano.
 - ADDED the ability to listen to all favourites songs.
 - ADDED the ability to filter events by date.
 - ADDED the ability to customize website default color.
 - UPDATED Google plus link in footer with Instagram
 - UPDATED upload system, now ffmpeg runs in background, user can browse the website while uploading a song.
 - FIXED if the uploaded songs are not submitted, they remain forever on the server.
 - FIXED 10+ minor bugs.

# v1.4.9 [12/10/2022]
 - ADDED cronjob.php to handle all background processes (required to add).
 - ADDED the ability to disable custom pages.
 - ADDED flutterwave payment method.
 - ADDED the ability to import from https://developer.kkbox.com
 - ADDED developers page, users can login to other websites using YourPod.
 - ADDED Hindi, Urdu, Chine, Indonesian, Croatian, Hebrew, Bengali, Japanese, Portuguese, Italian, Persian, Swedish, Vietnamese, Danish, and Filipino languages.
 - ADDED emojis on messenger.
 - ADDED reserved usernames system, block certain usernames.
 - ADDED system status to detect problems on server.
 - FIXED social network links not showing on footer.
 - FIXED default currency not showing on songs and products.
 - FIXED stories views not working.
 - FIXED sitemap hanging on please wait.
 - FIXED album thumbnail upload, songs thumbnail not uploading.
 - FIXED social login for vk, linkedin, mailru and discord.
 - FIXED automatic thumbnail when uploading an album.
 - FIXED automatic description when uploading an album.
 - FIXED dropdown menu broken on mobile.
 - FIXED footer in in volcano welcome page.
 - FIXED 3 minor bugs.

# v1.4.8 [01/09/2022]
 - ADDED Wasabi storage possibility.
 - ADDED custom endpoint (domain name) for S3, Spaces, Wasabi and Backblaze.
 - ADDED Backblaze storage.
 - ADDED the ability to upload files directly to third party storages.
 - FIXED 5 minor bugs.

# v1.4.7 [06/08/2022]
 - ADDED the ability to add custom withdrawal methods.
 - ADDED feature privacy.
 - ADDED the ability to mark all messages as read.
 - ADDED time to messages.
 - ADDED the ability to resend email verfication and two auth emails.
 - ADDED hreflang tags.
 - IMPROVED SEO of whole website.
 - IMPROVED speed bt 50% more.
 - UPDATED all PHP libs to new versions.
 - FIXED earnings count was wrong.
 - FIXED verification badge now showing everywhere.
 - FIXED empty album showing when songs are private.
 - FIXED songs were downloaded as .html file if remote storage like Google cloud is enabled.
 - FIXED 5 minor bugs.

# v1.4.6 (24 Jun, 2022)
 - ADDED new left sidebar on volcano theme.
 - ADDED faqs page.
 - ADDED new discover page on default theme.
 - ADDED the ability to re-arrange playlist songs.
 - ADDED the ability to translate terms page.
 - ADDED Remember This Device option to login page.
 - ADDED Password Complexity System to registration page.
 - ADDED Auto Username to registration page.
 - ADDED the ability to translate SEO details.
 - FIXED 5 minor bugs.

# Version 1.4.5 (26 Jan, 2022)
 - ADDED ffmpeg debug system, now you can debug the output of the ffmpeg
 - FIXED uploading albums was not working.
 - FIXED email confrimation was not working.
 - FIXED price not showing on events and purchased page.
 - FIXED few minor bugs.
 - OPTIMIZED database table indexes.

# Version 1.4.4 (22 Jan, 2022)
 - ADDED Google Drive Storage, now you can upload directly to your own drive account.
 - FIXED few minor bugs.

# Version 1.4.3 (13 Jan, 2022)
 - ADDED Earn Points link to the left navbar.
 - ADDED the ability to withdrawal points as real money.
 - ADDED the ability to earn points by listening to songs.
 - MOVED Point System Settings from Website Information to General Configuration.
 - FIXED design bugs in volcano theme.
 - FIXED few minor bugs in backend.
 - ORGANIZED HTML modals.
 - ORGANIZED CDN links, now all js/css libraries are loaded from your server.

# Version 1.4.2 (02 Jan, 2022)
 - FIXED digitalocean spaces upload/test issues.
 - FIXED onesignal blank page issue.
 - FIXED wallet was not updating after purchasing an item from store.
 - FIXED delete system for categories.
 - FIXED play full album problem, it was hanging.
 - ORGINZED CSS files, removed any inline css code.

# Version 1.4.1 (10 Dec, 2021)
 - FIXED paystack payment system.
 - FIXED create announcements system.
 - FIXED social login system, VK / Mailru & Discord.
 - FIXED "You may also like" in product page was showing user avatar instead of item picture.
 - FIXED you can see only last story if you have multiple stories.
 - FIXED slow youtube video player.
 - IMPROVED speed.
 - UPDATED documentation.

# Version 1.4 (24 Nov, 2021)
 - ADDED razorpay, securionpay, payu, paystack, iyzipay, checkout, cashfree & authorize.net payment methods.
 - ADDED the ability to import songs from YouTube + Video Player.
 - ADDED the ability to upload video trailer as channel cover or musician into.
 - ADDED story system, users can upload stories with audio only, free & paid stories.
 - ADDED the ability to edit SEO tags for each page.
 - ADDED digitalocean spaces support.
 - ADDED LinkedIn, Vkontakte, Instagram, QQ, WeChat, Discord & Mailru social login.
 - ADDED 24 link validation for reset password.
 - ADDED more APIs
 - FIXED 15+ minor reported bugs..
 - IMPROVED speed.

# Version 1.3.5 (21 May, 2021)
 - FIXED PayPal on PHP 8.0
 - FIXED audio embed issue on other sites.
 - FIXED spotlight page (500 Internet Error) on PHP 8.0
 - FIXED report a song in "latest songs" page in user profile.
 - FIXED 3+ minor reported bugs.

# Version 1.3.4 (20 April, 2021)
 - ADDED ability to tip artists (enable/disable).
 - ADDED hall of fame for artists (new page) (enable/disable).
 - ADDED ability to tag other artists to show they performed together (enable/disable).
 - ADDED ability to limit the amount of characters in comments.
 - ADDED support for PHP 8.0+ and MySQL 8.0+
 - ADDED more APIs
 - FIXED 15+ minor reported bugs..
 - IMPROVED speed.

# Version 1.3.3 (04 Oct, 2020)
 - ADDED ability to restrict rights of certain user from uploading / importing a song.
 - ADDED ability to mention @ someone in the comments.
 - ADDED point system, users can earn points by doing several activities in the site.
 - ADDED ability for user to post blogs.
 - ADDED ability to reply comments.
 - ADDED more APIs
 - FIXED 25+ minor reported bugs..
 - IMPROVED speed.

# Version 1.3.2 (22 May, 2020)
 - ADDED more APIs
 - FIXED 20+ minor reported bugs..
 - IMPROVED speed.

# Version 1.3.1 (13 May, 2020)
 - ADDED the ability to add custom pages.
 - ADDED affiliate system.
 - ADDED ability to upload a folder to an album.
 - ADDED ability to set discover as landing page (enable/disable).
 - ADDED Itunes importer and Itunes affiliate system.
 - ADDED the ability to import songs from deezer.
 - ADDED audio ads, user can create ads in audio.
 - ADDED the option for artists to only upload.
 - ADDED the ability to like blog comments.
 - ADDED more APIs.
 - FIXED 30+ minor reported bugs..
 - IMPROVED speed.

# Version 1.3 (03 Dec, 2019)
 - ADDED Advertisement: Display ads on your websites.
 - ADDED Ability to import from sound cloud.
 - ADDED Ability to Login via soundcloud.
 - ADDED Ability to add preexisting single/song into an album.
 - ADDED Ability to edit/move song position in an album.
 - ADDED Ability to review song.
 - ADDED custom fields.
 - ADDED DMCA page.
 - ADDED Notification management system (Users can choose what kind of notifications they want to get).
 - ADDED Session manager (users can view / manage browser / platforms where they are logged in).
 - ADDED Two-factor authentication system using email or phone.
 - ADDED Confirmation system when user login from new location.
 - ADDED Twilio API for sending SMS messages.
 - ADDED new APIs.
 - ADDED Mass notifications.
 - ADDED Invitation Codes.
 - ADDED Radio stations.
 - FIXED 20+ minor reported bugs..
 - IMPROVED speed.

# Version 1.2.1 (08 Nov, 2019)
 - ADDED new theme (Volcano)
 - FIXED 5+ minor reported bugs..
 - IMPROVED speed.

# Version 1.2 (13 Aug, 2019)
 - ADDED statics for each song, each album, this week, this month, today's views, likes, dislikes, etc.
 - ADDED bulk upload, one click, user can select 10+ songs in albums.
 - ADDED lyrics, user can upload lyrics to song.
 - ADDED the ability to disallow or allow download and embed features.
 - FIXED 5+ minor reported bugs..

# Version 1.1 (04 Jun, 2019)
 - ADDED more payment methods, bank and stripe.
 - ADDED purchases count in song page.
 - ADDED dislike system, user can now like or dislike a song.
 - ADDED more currencies.
 - ADDED push notifications.

# Version 1.0 (8 Apr, 2019)
 - Initial release.
