# Md. Faysal Talukder — Portfolio Website

## GitHub-এ আপলোড ও লাইভ করার নিয়ম (GitHub Pages)

1. GitHub-এ একটা নতুন repository তৈরি করো — নাম দাও, উদাহরণ: `portfolio`
2. এই ৩টা জিনিস (index.html, style.css, assets ফোল্ডার) repository-তে আপলোড করো (Add file → Upload files)
3. Repository-র **Settings → Pages**-এ যাও
4. **Branch: main**, folder: **/ (root)** সিলেক্ট করে Save করো
5. কিছুক্ষণ পর তোমার সাইট লাইভ হবে এই লিংকে:
   `https://<তোমার-github-ইউজারনেম>.github.io/portfolio/`

## ফাইল স্ট্রাকচার
```
portfolio/
├── index.html
├── style.css
└── assets/
    ├── profile.jpg
    └── project-halalfood.jpg
```

## পরে যা বদলাতে পারবে
- **নতুন প্রজেক্ট যোগ**: `index.html`-এ `<section id="work">` অংশে `.work-card` ব্লকটা কপি করে নতুন প্রজেক্টের ছবি ও লেখা বসাও (ছবি `assets/` ফোল্ডারে রাখতে হবে)
- **রঙ পরিবর্তন**: `style.css`-এর একদম উপরে `:root` অংশে `--green-900`, `--gold` ভ্যারিয়েবলগুলো বদলালেই পুরো সাইটের রঙ বদলে যাবে
- **টেক্সট এডিট**: `index.html`-এ সরাসরি লেখা বদলাও
