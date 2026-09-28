# হালিমা সাদিয়া (রা.) মহিলা মাদ্রাসা ও নূরানী কিন্ডারগার্টেন

ফ্রি-হোস্টিং-উপযোগী প্রথম কাঠামো।

## ফাইল
- `index.html` — মূল ওয়েবসাইট
- `result.html` — অনলাইন ফলাফল পেজ
- `admin.html` — অ্যাডমিন প্যানেলের প্রাথমিক কাঠামো
- `style.css` — ডিজাইন
- `assets/logo.jpg` — দেওয়া লোগো
- `supabase/schema.sql` — ফলাফল/নোটিশের ডাটাবেস কাঠামো

## পরবর্তী ধাপ
1. GitHub repository তৈরি
2. GitHub Pages চালু
3. Supabase project তৈরি
4. `schema.sql` চালানো
5. Supabase Auth দিয়ে admin login তৈরি
6. RLS policies যোগ করা
7. `result.html`-এ Supabase client সংযোগ
8. admin panel থেকে student/exam/marks CRUD
9. নোটিশ ও গ্যালারি ডেটা সংযোগ
10. চূড়ান্ত পরীক্ষা ও প্রকাশ

নিরাপত্তার জন্য Supabase service-role key কখনো frontend-এ রাখা যাবে না।
