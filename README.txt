LIFE HUB: deploy and install
============================

FILES
  index.html            the app
  manifest.webmanifest  install info (name, icon, colours)
  sw.js                 makes it work offline
  icons/                app icons
  .nojekyll             tells GitHub Pages to serve files as-is

OPTION A: NETLIFY (about 1 minute)
  1. Go to https://app.netlify.com/drop
  2. Drag the whole life-hub folder (or the unzipped contents) onto the page.
  3. Netlify gives you a https link. Open it on your phone.

OPTION B: GITHUB PAGES
  1. Create a new GitHub repository (it can be private if your plan allows Pages, otherwise public).
  2. Upload every file and the icons folder (including .nojekyll) to the repository root.
  3. Settings > Pages > Deploy from a branch > main > / (root) > Save.
  4. After a minute your app is at https://YOUR-NAME.github.io/REPO-NAME/

INSTALL ON PHONE
  iPhone (Safari):  Share button > Add to Home Screen
  Android (Chrome): menu (3 dots) > Install app / Add to Home screen

MOVING YOUR DATA
  Data is stored in each browser on each device. Use Backup on your computer,
  then Restore inside the installed app on your phone.

UPDATING LATER
  Upload the new index.html and change VERSION in sw.js (e.g. lifehub-v2).

SYNC & SAFETY (new)
  Settings > "Sync devices" connects an encrypted private GitHub repo.
  Settings > "Safety copies" lists automatic restore points kept on this device.
  Use a SEPARATE private repository for sync data, never the repository that serves this app.

PERFORMANCE (new)
  Net Worth > Equities now starts with a Performance panel: total return per position,
  closed positions with holding period, annualised return, results by year.
  To add past buys without changing holdings, tick "log only" in the Trade Log.

BILL ESTIMATOR (new)
  Home > Utils now starts with a Monthly bill estimator for electricity and gas:
  enter usage (or meter readings) and your tariff to see the expected bill.

WORK TAB
  The Work tab (schedule, pay, pay calculator, tasks, leave and sick days, Lithuanian
  public holidays) is the 5th tab. Its data is included in Backup, Safety copies and Sync.

SWIPE & MOBILE LAYOUT
  On phones and tablets, swipe left or right to move between Life Hub, Home, Net, School and Work.
  Swipes that start on a scrolling strip, a chart, a form field or the very edge of the screen are ignored.
  Home > Utils: the utility log shows the latest two months, with a button for older months.
  Net Worth on phones: Snapshot, Report, API keys, exchange rates and Reset live under the ... menu.
