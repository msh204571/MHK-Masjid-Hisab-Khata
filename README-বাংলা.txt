MHK — Masjid Hisab Khata

ফাইল:
- index.html: GitHub repository-এর root-এ পুরোনো index.html-এর জায়গায় আপলোড করুন।
- firestore.rules: Firebase Console > Firestore Database > Rules-এ পুরো লেখা বসিয়ে Publish করুন।

এই সংস্করণে:
- Firebase compat SDK ব্যবহার করা হয়েছে; ES module import বাদ, যাতে মোবাইল ব্রাউজারে module-loading সমস্যা কমে।
- Firebase Auth LOCAL persistence: একই ব্রাউজারে refresh করলে লগইন থাকার কথা।
- পরিবারভিত্তিক সব জমা এক সারিতে যোগ হয়; পরিবার তালিকা ও চাঁদার সারাংশে মোট জমা, পরিশোধিত মাস ও ১২ মাসের বাকি মাস দেখা যায়।
- Firestore-এ পরিবার, জমা, অন্যান্য আয়, ব্যয় ও খাবারের তালিকা সংরক্ষিত হয়।
- সাধারণ ব্যবহারকারী শুধু দেখতে পারবে; অ্যাডমিন UID-ই লিখতে পারবে।

গুরুত্বপূর্ণ:
- অবশ্যই HTTPS GitHub Pages URL থেকে খুলবেন; content:// বা ডাউনলোড করা local HTML ফাইল থেকে নয়।
- Firebase Authentication > Settings > Authorized domains-এ msh204571.github.io না থাকলে যোগ করুন। auth/unauthorized-domain দেখালে এটি আবশ্যক।
- ফাইলের syntax/static structure যাচাই করা হয়েছে; আপনার Firebase project-এ লাইভ লগইন/ডেটা write এখানে চালিয়ে পরীক্ষা করা সম্ভব হয়নি। বাস্তব হিসাব দেওয়ার আগে ছোট পরীক্ষামূলক এন্ট্রি দিয়ে refresh করে যাচাই করুন।
