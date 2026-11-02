DEUTSCH PARTNER AI — প্রথম সংস্করণ

এই ফোল্ডারটি একটি PWA starter app। Android Chrome-এ ইনস্টল করা যাবে, তবে প্রথমে HTTPS hosting দরকার।

চালানোর সহজ উপায়:
1) ZIP extract করুন।
2) GitHub-এ নতুন repository তৈরি করে সব ফাইল upload করুন।
3) Settings > Pages > Deploy from branch > main / root নির্বাচন করুন।
4) GitHub Pages URL Chrome-এ খুলুন।
5) Chrome menu (⋮) > Install app / Add to Home screen চাপুন।

Gemini API:
1) Google AI Studio থেকে API key তৈরি করুন।
2) অ্যাপে Optional Gemini API key ঘরে key paste করুন।
3) এটি এই ডিভাইসের browser localStorage-এ থাকবে। এই ব্যক্তিগত prototype অন্য কারও সঙ্গে share করবেন না।
4) API free tier-এ usage limits ও data-use terms থাকতে পারে। সংবেদনশীল তথ্য পাঠাবেন না।

ডায়লগ ফরম্যাট:
Person A: Guten Tag!
Person B: Guten Tag! Wie kann ich Ihnen helfen?
প্রতি লাইনে একজন speaker; Person A এবং Person B পালাক্রমে থাকবে।

সীমাবদ্ধতা:
- এই prototype-এ fixed script sequencing, speech synthesis, speech recognition এবং optional AI correction আছে।
- Voice recognition browser/device অনুযায়ী বদলাতে পারে।
- Gemini key browser-এ রাখা production-secure নয়। ব্যক্তিগত prototype-এর বাইরে ব্যবহারের আগে backend/proxy দরকার।
- Saved dialogues এই browser/device-এর localStorage-এ থাকে; browser data মুছলে হারাতে পারে।
