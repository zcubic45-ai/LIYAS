# LIYASCLOTHING LIMITED

एक responsive clothing brand website: Home, Collection, Our story, Design details, Contact और Privacy. Collection filters, device-local wishlist और enquiry text-file download शामिल हैं.

## अपने कंप्यूटर पर खोलें
ZIP extract करें और index.html को browser में खोलें. किसी installation या build की ज़रूरत नहीं. सभी artwork और files पैकेज में हैं; बाहरी fonts/images की आवश्यकता नहीं.

## GitHub Pages पर live करें
1. https://github.com पर sign in करें और New repository चुनें.
2. नाम `liyasclothing` रखें. Public चुनें और repository बनाएँ.
3. Add file → Upload files चुनें.
4. इस folder के अंदर की index.html, style.css, app.js, assets folder और README.md upload करें. index.html repository के root में हो; पूरा parent folder upload न करें. assets folder की structure बनाए रखें.
5. Commit changes करें.
6. Settings → Pages खोलें.
7. Build and deployment → Source में Deploy from a branch चुनें.
8. Branch में main, folder में /(root) चुनें और Save करें.
9. Deployment के बाद Pages में Visit site मिलेगा. सामान्य URL: https://YOUR-USERNAME.github.io/liyasclothing/
10. बाद में files edit/upload करके commit करने पर website update होगी.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## अपनी जानकारी लगाएँ
- index.html: brand copy, business contact details, privacy information.
- app.js: sample product names, colours, categories.
- assets/: original SVG concept illustrations. अपनी product photos लगाएँ तो app.js में image paths और alt descriptions बदलें.
- style.css: colours, spacing, responsive layout.

## Launch notes
यह presentation/catalogue website है. Products, illustrations और copy concept samples हैं; real inventory, prices, reviews या company history के दावे नहीं हैं. Contact form enquiry file download करता है, message नहीं भेजता. Wishlist इसी device पर localStorage में रहती है. Payment, backend, live inventory और order processing शामिल नहीं हैं. वास्तविक बिक्री शुरू करने के लिए commerce service/payment backend अलग से जोड़ें. Public launch से पहले असली product photos, prices, email/phone और अपनी business policies जोड़ें.

## Verification
JavaScript syntax check और local file-reference checks पूरे किए गए. Automated browser testing चलाने का प्रयास हुआ, लेकिन environment में Chromium executable उपलब्ध नहीं था; visual/mobile rendering का browser verification पूरा नहीं हुआ.
