PhotoLink Chat — প্রস্তুত ZIP
=============================

এই ZIP-এ Cloudinary তথ্য বসানো আছে:
- Cloud Name: tdsc7x7e (আপনার স্ক্রিনশট থেকে অনুমান করা; API Keys/Cloudinary dashboard-এ যাচাই করুন)
- Upload Preset: photolink (আপনার তৈরি করা Unsigned preset)

ফিচার:
- শুধু ছবি নির্বাচন
- ব্রাউজারেই JPEG কমপ্রেশন (সর্বোচ্চ 1920px, quality 78%)
- Cloudinary-তে আপলোড
- শেয়ারযোগ্য URL, Copy link এবং Open image
- মোবাইল-ফ্রেন্ডলি UI

চালানোর ধাপ:
1. ZIP Extract করুন।
2. index.html GitHub repository-র root-এ আপলোড করুন।
3. GitHub → Settings → Pages → Deploy from a branch → main / root সেট করুন।
4. প্রকাশিত URL খুলে ছবি আপলোড পরীক্ষা করুন।

যদি আপলোড ব্যর্থ হয়:
- Cloud Name `tdsc7x7e` ঠিক আছে কি না যাচাই করুন।
- Cloudinary Settings → Upload → Upload presets-এ `photolink`-এর mode `Unsigned` আছে কি না দেখুন।
- Cloudinary-র error message দেখে preset/usage limits যাচাই করুন।

নিরাপত্তা:
- API Secret কখনো frontend HTML/JavaScript-এ দেবেন না।
- Unsigned preset public হতে পারে; Cloudinary-তে allowed formats, file size, folder এবং usage limits সেট করুন।
- লিংক যার কাছে থাকবে সে ছবি দেখতে পারে। ব্যক্তিগত ছবি আপলোডে সতর্ক থাকুন।
- এই ZIP-টি তৈরি করা হয়েছে, কিন্তু এখান থেকে আপনার Cloudinary-তে বাস্তব আপলোড টেস্ট করা সম্ভব হয়নি।
