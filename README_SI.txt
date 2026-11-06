MOBILE LANKA - STARTER APP

මෙය install කළ හැකි PWA online shop starter එකකි.

පරීක්ෂා කිරීම:
1. index.html විවෘත කළාම සාමාන්‍ය preview එක පෙනේ. Install පහසුකම සහ service worker සඳහා HTTPS hosting අවශ්‍යයි.
2. Internet එකට දැමීමට Netlify Drop (https://app.netlify.com/drop) වෙත මෙම ZIP එක unzip කර ඇති folder එක drag-and-drop කරන්න.
3. ලැබෙන public URL එකෙන් shop එක විවෘත කළ හැක.
4. Android Chrome හි URL එක විවෘත කර menu > Add to Home screen තෝරන්න.

වැදගත් සීමා:
- දැනට Admin Panel එකේ products මේ browser/device එකේම localStorage තුළ සුරැකේ. වෙනත් phone එකකින් වෙනස්කම් පෙනෙන්නේ නැහැ.
- සැබෑ online admin panel එකක් (සියලු devices වලට sync වන) සඳහා database/backend එකක් සහ ඔබේම account එකක් සම්බන්ධ කළ යුතුයි. එය ඊළඟ අදියරයි.
- WhatsApp order number එක app.js තුළ WHATSAPP_NUMBER variable එකේ байна (94753600878 ලෙස සකසා ඇත).
- Google Play Store native APK/AAB එකක් නොවේ; මෙය Android හි install කළ හැකි web app/PWA එකකි.
