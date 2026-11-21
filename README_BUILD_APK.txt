====================================================
বাকি খাতা ও ব্যবসায় হিসাব — Android Studio প্রজেক্ট গাইড
====================================================

প্যাকেজ নাম: com.bestu.hishabkhata
Firebase Project ID: hishab-khata-b3043
Realtime Database URL: https://hishab-khata-b3043-default-rtdb.firebaseio.com

APK তৈরি করার ধাপসমূহ:
১. এই ZIP ফাইলটি আনজিপ (Extract) করুন।
২. Android Studio ওপেন করুন এবং "Open" অপশনে ক্লিক করে 'hishab-khata-android' ফোল্ডারটি সিলেক্ট করুন।
৩. Gradle Sync সম্পন্ন হওয়া পর্যন্ত অপেক্ষা করুন (app/google-services.json ইতিমধ্যেই সঠিক জায়গায় বসানো আছে)।
৪. উপরের মেনু থেকে Build > Build Bundle(s) / APK(s) > Build APK(s) ক্লিক করুন।
৫. বিল্ড শেষ হলে 'app/build/outputs/apk/debug/app-debug.apk' ফাইলটি আপনার অ্যান্ড্রয়েড ফোনে ইনস্টল করুন।

Firebase Realtime Database সেটআপ (গুরুত্বপূর্ণ):
- Firebase Console (https://console.firebase.google.com) থেকে আপনার 'hishab-khata-b3043' প্রজেক্টে যান।
- বাম পাশের মেনু থেকে Build > Realtime Database চালু করুন।
- Rules ট্যাবে নিচের মতো অনুমতি দিন যাতে অ্যাপ থেকে ডাটা পড়া ও লেখা যায়:
  {
    "rules": {
      ".read": true,
      ".write": true
    }
  }
