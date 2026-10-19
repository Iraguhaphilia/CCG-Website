C. CONSULTING GROUP WEBSITE
===========================

This folder is a complete website. Open index.html in any browser to see it.

FILES
  index.html     the whole website (text, design and gallery)
  assets/        your logo, the main photo, and a gallery folder for your own photos
  favicon.svg    the small icon in the browser tab
  robots.txt     lets Google read the site

HOST IT FOR FREE (pick one)

1. Netlify Drop (easiest)
   - Go to https://app.netlify.com/drop
   - Drag this whole folder onto the page.
   - You get a free link such as https://something.netlify.app
   - Sign up (free) to keep the site and pick a nicer name,
     for example cconsultinggroup.netlify.app

2. Cloudflare Pages (free)
   - Go to https://pages.cloudflare.com and create a free account.
   - Choose "Create a project", then "Upload assets", and upload this folder.

3. GitHub Pages (free)
   - Create a free account at https://github.com and a new public repository.
   - Upload the files of this folder, then open Settings > Pages and
     select the main branch. Your site appears at
     https://YOUR-NAME.github.io/REPOSITORY-NAME

AFTER IT IS ONLINE
  - Make a free Google Business Profile at https://business.google.com so
    customers find "C. Consulting Group, Gaculiro" on Google Maps.
  - Add the website link to your Google profile, Facebook, Instagram,
    WhatsApp Business and your flyers.
  - Optional: add the site in Google Search Console
    (https://search.google.com/search-console) so Google finds it faster.

CHANGE THE TEXT
  Open index.html in Notepad (or any text editor), use Find and Replace,
  and save.
  Phone / WhatsApp: +250 781 772 210
  Email: cconsultinggroup9@gmail.com
  Facebook and Instagram name: c.consulting_group

FACEBOOK AND INSTAGRAM LINKS
  Both names on the site are clickable.
  - Instagram opens https://www.instagram.com/c.consulting_group/
  - Facebook opens a search for "c.consulting_group", because Facebook page
    addresses cannot contain an underscore, so the exact page link is not known.
  To use your exact Facebook page link: open your page on Facebook, copy the
  address from the browser, then in index.html replace
  https://www.facebook.com/search/top?q=c.consulting_group
  with your address, and save.

REPLACE THE GALLERY PICTURES WITH YOUR REAL PHOTOS
  1. Put your photos in the folder assets/gallery
  2. In index.html find a picture block. It starts with  <span class="art"><svg
     and ends with  </svg></span>
  3. Replace everything from <svg to </svg> with:
       <img src="assets/gallery/your-photo.jpg" alt="Describe the photo">
  4. Change the title and line below it if you like, then save.
  5. Delete the sentence "Illustrations of our services..." under the gallery.
