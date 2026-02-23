\# 📜 Changelog



All notable changes to the Radio Player will be documented in this file.



---



\## v1.0 (2026-02-23) — First Stable Release 🌙



\*\*Production-ready foundation — clean, peaceful, reliable\*\*



\### ✅ Core Implementation

\- \*\*Beautiful UI/UX Design\*\*

&nbsp; - Sacred ۞ symbol with breathing/pulsing animations

&nbsp; - Glassmorphism panels with gold accents

&nbsp; - Dark theme optimized for nighttime listening

&nbsp; - Responsive layout for all devices

&nbsp; - Amiri font for Quranic Arabic typography



\- \*\*Stream Management\*\*

&nbsp; - Primary stream + 2 backup streams

&nbsp; - Automatic failover on stream failure

&nbsp; - 3-second timeout per connection attempt

&nbsp; - Background network monitoring for auto-reconnect



\- \*\*Error Handling (Arabic-first)\*\*

&nbsp; - Facebook/Instagram in-app browser detection → "افتح في متصفح منفصل"

&nbsp; - Ad blocker detection → "تم اكتشاف برنامج حظر إعلانات"

&nbsp; - Network offline → "لا يوجد اتصال بالإنترنت"

&nbsp; - Stream failure → "حدث خطأ فني. يرجى المحاولة لاحقًا."

&nbsp; - Configuration error → "خطأ في التكوين: لم يتم إضافة روابط البث"



\- \*\*User Experience\*\*

&nbsp; - Quranic verse: "وَإِذَا قُرِئَ الْقُرْآنُ فَاسْتَمِعُوا لَهُ وَأَنْصِتُوا لَعَلَّكُمْ تُرْحَمُونَ" (سورة الأعراف ٢٠٤)

&nbsp; - Status message: "اضغط على الرمز ۞ لبدء الاستماع المباشر"

&nbsp; - \*\*"بث" appears ONLY in tiny footer status\*\* — main UI remains clean

&nbsp; - iOS volume control: 📱 icon + "استخدم أزرار الصوت الفيزيائية"



\- \*\*Technical Excellence\*\*

&nbsp; - Single HTML file deployment

&nbsp; - Proper Promise handling per Chrome guidelines

&nbsp; - Memory leak prevention with complete audio cleanup

&nbsp; - Console-clean in production mode (`DEBUG = false`)

&nbsp; - Tested on Chrome, Firefox, Safari, Edge, Samsung Internet



\### 🌍 Browser Support

| Browser | Status |

|---------|--------|

| Chrome (Desktop/Mobile) | ✅ Full support |

| Safari (macOS/iOS) | ✅ Full support |

| Firefox | ✅ Full support |

| Edge | ✅ Full support |

| Samsung Internet | ✅ Full support |

| Facebook/Instagram In-App | ⚠️ Shows warning banner |



\### 📱 Known Limitations

\- Volume control disabled on iOS (use device physical buttons)

\- Requires modern browser (Chrome 50+, Safari 10+, Firefox 52+)

