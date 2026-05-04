# 🎯 Goal Buddy - Accountability Partner Matching App

Find your perfect accountability partner and achieve your goals together!

## 🚀 What is Goal Buddy?

Goal Buddy is a web app that matches people with accountability partners based on:
- **Shared goals** (video editing, content writing, running, fitness, etc.)
- **Compatible schedules** (Daily, 3-4x/week, weekends)
- **Working style compatibility** (Chill & flexible vs. Structured & disciplined)
- **Preferred collaboration method** (Chat only, voice/video, or regular check-ins)

Instead of failing alone due to procrastination, users get paired with someone equally committed to achieving the same goal. They can chat, make plans, push each other, and stay motivated.

## ✨ Features

✅ **User Authentication** - Simple email/password signup and login  
✅ **8-Question Onboarding** - Smart profile matching questions  
✅ **Tinder-style Swiping** - Swipe through compatible matches  
✅ **Instant Matching** - When both users like each other, they match  
✅ **Real-time Chat** - Message matched partners and make plans  
✅ **Persistent Data** - All data saved in browser localStorage  
✅ **Mobile-friendly** - Works on phones, tablets, and desktop  
✅ **Pre-loaded Demo Users** - Test immediately without setup  

## 🎮 Quick Start (No Installation Needed)

### **Option 1: Open in Browser (Fastest)**
1. Go to: https://github.com/Sushruth18/mru-du_sync2005
2. Click on `index.html`
3. Click **"Raw"** button
4. Press `Ctrl+S` (or `Cmd+S` on Mac) to save locally
5. Open the saved file in any web browser

### **Option 2: Clone & Run Locally**
```bash
git clone https://github.com/Sushruth18/mru-du_sync2005.git
cd mru-du_sync2005
# Simply open index.html in your browser
```

### **Option 3: GitHub Pages (Live URL)**
1. Go to repository → **Settings** → **Pages**
2. Select `main` branch as source
3. Wait 1-2 minutes for deployment
4. Visit: `https://Sushruth18.github.io/mru-du_sync2005/`

## 👥 Test with Demo Accounts

The app comes with 7 pre-loaded demo users. Use any of these to login:

| Email | Goal | Password |
|-------|------|----------|
| alex@test.com | Learn video editing | password |
| jordan@test.com | Improve content writing | password |
| sam@test.com | Run 5km daily | password |
| casey@test.com | Learn video editing | password |
| morgan@test.com | Run 5km daily | password |
| taylor@test.com | Improve storytelling | password |
| riley@test.com | Learn video editing | password |

**Or create a new account** with any email and password.

## 🎯 How to Use

### **Step 1: Sign Up or Log In**
- Create an account or use a demo account
- Password: `password`

### **Step 2: Answer 8 Onboarding Questions**
1. 🎯 **What goal are you working on?** (e.g., "Learn video editing")
2. 📊 **What's your current level?** (Beginner/Intermediate/Advanced)
3. 🔄 **What are you looking for?** (Same level/More experienced/Learn together)
4. ⏱️ **How often will you work on this?** (Daily/3-4x/week/Weekends)
5. 🕒 **Preferred time?** (Morning/Afternoon/Night)
6. ⚡ **Your working style?** (Chill & flexible/Structured/Competitive)
7. 🎯 **Goal deadline?** (No deadline/1 month/3 months/Custom)
8. 💬 **How to collaborate?** (Chat only/Voice-video/Regular check-ins)

### **Step 3: Swipe Through Matches**
- See compatible users who share your goal and schedule
- Click ❌ to skip or ❤️ to like
- When both users like each other → **Instant Match!** 🎉

### **Step 4: Chat & Collaborate**
- Open your Matches list
- Click on a match to open chat
- Message them and make plans together
- Stay accountable and achieve your goal!

## ⚙️ Matching Algorithm

Users see each other if:
- ✅ **Same goal** (keyword match)
- ✅ **Same frequency** (Daily ↔ Daily, 3-4x ↔ 3-4x, Weekends ↔ Weekends)
- ✅ **Overlapping times** (Morning/Afternoon/Night overlap by 4+ hours)

**Mutual Match:**
- When both users swipe right (like) each other → Automatic match
- They can immediately start chatting

## 💾 Data Storage

- **No backend server needed** - All data stored in browser localStorage
- **Persistent** - Data survives page refresh
- **Private** - Only you can access your data
- **Clear localStorage**: Open DevTools (F12) → Application → LocalStorage → Clear

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (vanilla)
- **Storage**: Browser localStorage
- **Deployment**: GitHub Pages
- **Responsive**: Mobile-first design

## 📱 Browser Compatibility

Works on:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Android Chrome)

## 🎯 Perfect For

- 📚 **Learning together** - Video editing, writing, coding
- 🏃 **Fitness goals** - Running, exercising, yoga
- 📝 **Creative pursuits** - Storytelling, content creation
- 💼 **Skill development** - Any hobby or professional skill
- 🤝 **Staying motivated** - Shared accountability and support

## 🔥 Why Goal Buddy Works

1. **Matching by Execution, Not Just Interest**
   - Most apps match by interest. We match by commitment level, schedule, and working style.

2. **Accountability is Real**
   - With a real person waiting for you, you're less likely to procrastinate.

3. **Immediate Connection**
   - Swipe → Like → Match → Chat. Zero friction.

4. **Flexible for Any Goal**
   - Academic, fitness, creative, professional - any goal works.

## 📊 Features in This MVP

**✅ Implemented:**
- Login/Signup
- 8-question onboarding
- Swipe interface
- Smart matching algorithm
- Instant mutual matching
- Real-time chat
- Match persistence
- Mobile-responsive design

**🚀 Future Enhancements:**
- User profiles with photos
- Goal progress tracking
- Scheduled check-in reminders
- Voice/video call integration
- Gamification (badges, streaks)
- Goal milestones and plans
- Community features
- AI-powered better matching

## 🐛 Known Limitations (MVP)

- localStorage only (data clears if browser cache cleared)
- Demo users are hardcoded (no real backend)
- No image uploads
- No video calling (yet)
- Single-device only (data doesn't sync across devices)

## 💡 Pro Tips

1. **Test matching:** Log in as different demo users on different browser windows/tabs
2. **Create matches:** When logged in as User A, like User B. Then switch to User B and like User A back.
3. **Clear data:** If you want a fresh start, open DevTools → Application → LocalStorage → Clear all
4. **Responsive design:** Try resizing your browser or opening on mobile

## 📝 License

Open source - feel free to use and modify!

## 🎤 Pitch Summary

*"Goal Buddy is an accountability partner matching platform. Users answer 8 questions about their goals, schedule, and commitment level. The app then swipes them through compatible matches like Tinder. When both users like each other, they instantly match and can chat to plan and stay accountable together. Zero backend complexity—everything runs in the browser."*

## 🚀 Ready to Build?

- Clone this repo
- Customize demo users
- Add your own features
- Deploy to GitHub Pages
- Share with friends
- Start achieving goals together!

---

**Made with ❤️ for accountability partners everywhere. 🎯**
