# 📚 Single YAML Configuration Guide

## ✅ **সেটআপ সম্পূর্ণ!**

এখন আপনার bookmark system শুধুমাত্র একটি ফাইল দিয়ে পরিচালিত হবে:

```
public/bookmarks.yml  ← এই একটি ফাইলই যথেষ্ট!
```

## 🎯 **কিভাবে ব্যবহার করবেন:**

### 1. **Bookmark যোগ/সম্পাদনা করুন:**

- শুধুমাত্র `public/bookmarks.yml` ফাইল এডিট করুন
- অন্য কোন কোড ফাইল পরিবর্তন করার দরকার নেই

### 2. **পরিবর্তন দেখুন:**

তিনটি উপায়ে refresh করতে পারেন:

**🔄 Refresh Button:** Search box এর পাশে 🔄 বাটনে ক্লিক করুন

**⌨️ Keyboard Shortcut:** `Ctrl+R` বা `F5` চাপুন

**🌐 Browser Refresh:** পুরো পেজ refresh করুন

### 3. **Live Feedback:**

- Refresh করলে সফল হলে: "📚 Bookmarks refreshed!" দেখাবে
- সমস্যা হলে: "❌ Failed to refresh bookmarks" দেখাবে

## 📁 **File Structure:**

```
OpenBookmarks/
├── public/
│   └── bookmarks.yml          ← 🎯 একমাত্র এডিট করার ফাইল
├── src/
│   ├── css/                   ← CSS files
│   ├── *.ts                   ← TypeScript files (এগুলো touch করবেন না)
└── other files...
```

## ⚡ **Key Features:**

- ✅ **Single Source:** শুধু `public/bookmarks.yml` এডিট করুন
- ✅ **Auto-reload:** Refresh বাটন বা keyboard shortcut
- ✅ **Cache Busting:** সর্বদা fresh data load হয়
- ✅ **Live Notifications:** Success/error feedback
- ✅ **No Code Changes:** কোড পরিবর্তনের দরকার নেই

## 🚀 **Example Usage:**

1. `public/bookmarks.yml` ফাইল খুলুন
2. নতুন bookmark যোগ করুন:

```yaml
- title: "New Site"
  url: "https://example.com"
  category: "tools"
  icon: "🔧"
  description: "My new bookmark"
```

3. Save করুন
4. Browser এ `Ctrl+R` চাপুন বা 🔄 বাটনে ক্লিক করুন
5. নতুন bookmark দেখুন!

## 🎵 **Music Category যোগ করা হয়েছে:**

আপনার YAML file এ music category এবং 8টি জনপ্রিয় music platform যোগ করা হয়েছে:

- Spotify, Apple Music, YouTube Music
- SoundCloud, Bandcamp, Deezer, Tidal, Last.fm

**এখন সব setup complete! আপনি শুধু `public/bookmarks.yml` এডিট করে bookmarks manage করতে পারবেন! 🎉**
