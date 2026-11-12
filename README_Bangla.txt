STUDYFLOW OFFLINE PWA — বাংলা নির্দেশিকা

এই ZIP-এর ভিতরে:
- index.html: StudyFlow অ্যাপ
- manifest.webmanifest: Installable app information
- service-worker.js: Offline cache
- icons/: App icons

গুরুত্বপূর্ণ:
১) PWA install এবং service worker চালাতে HTTPS ওয়েব হোস্টিং দরকার।
২) ZIP-এর ফাইলগুলো একই ফোল্ডার কাঠামোয় রাখতে হবে।
৩) প্রথমবার অনলাইনে অ্যাপের URL খুলে লোড সম্পূর্ণ হতে দাও।
৪) এরপর Chrome মেনু (⋮) থেকে Install app / Add to Home screen নির্বাচন করো।
৫) একবার অনলাইনে সফলভাবে লোড হওয়ার পর StudyFlow-এর মূল পেজ অফলাইনে খোলা যাবে।
৬) YouTube ভিডিও/সার্চ লিংক অফলাইনে চলবে না; ইন্টারনেট লাগবে।
৭) পুরোনো StudyFlow-এর Export Backup JSON ফাইল থাকলে নতুন ভার্সনে Import Backup দিয়ে ফিরিয়ে আনতে পারবে।

পরবর্তী ধাপ:
এই ফাইলগুলো HTTPS-এ হোস্ট করতে হবে। এরপর Android Chrome থেকে ইনস্টল করব।
