==================================================
  TestShop — Mini E-Commerce for Meta Pixel Testing
==================================================

FILES
------
  index.html   ← الملف الوحيد، افتحه في أي browser

==================================================
  META PIXEL SETUP
==================================================

1. افتح index.html في text editor
2. دور على: var META_PIXEL_ID = 'YOUR_PIXEL_ID_HERE';
3. غير YOUR_PIXEL_ID_HERE بـ Pixel ID بتاعك
4. نفس الكلام في الـ <noscript> tag جوا

EVENTS THAT FIRE AUTOMATICALLY:
  ✅ PageView        — لما الصفحة تتفتح
  ✅ AddToCart       — لما تضغط "Add to Cart" على أي منتج
  ✅ InitiateCheckout — لما تضغط Checkout
  ✅ Purchase        — بعد ثانية من الـ Checkout (simulated)

TEST WITH: Meta Pixel Helper Chrome Extension
  https://chrome.google.com/webstore/detail/meta-pixel-helper

==================================================
  SPOTIFY INTEGRATION
==================================================

الموقع فيه Spotify embed جاهز.
لو عايز تغير الـ playlist:

1. روح لأي playlist على Spotify
2. اضغط (...) → Share → Embed Playlist
3. انسخ الـ src URL
4. في index.html دور على:
   src="https://open.spotify.com/embed/playlist/..."
5. استبدل الـ URL بالـ playlist بتاعتك

==================================================
  HOW TO USE
==================================================

Option A — فتح محلي:
  فقط افتح index.html في Chrome/Firefox

Option B — رفع على server:
  ارفع index.html على أي hosting (Netlify, Vercel, etc.)
  المهم إن الـ Pixel يشتغل صح على domain

==================================================
