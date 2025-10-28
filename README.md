# Khan Academy Onboarding Prototype

An interactive onboarding experience prototype for Khan Academy that introduces users to the platform through avatar creation and personalization.

## 🎯 Project Overview

This prototype reimagines the Khan Academy onboarding experience by:
- Creating a personalized avatar companion that guides learners
- Collecting user preferences through an interactive island-based journey
- Maintaining the avatar throughout the learning experience
- Allowing customization through a point-based shop system

## 📁 Files Overview

- **`index.html`** - Landing page / navigation hub
- **`comprehensive-onboarding.html`** - Main onboarding journey with 6 islands
- **`khan-courses-page.html`** - Mock courses page with avatar companion
- **`avatar-shop.html`** - Shop for purchasing avatar items using points

## 🚀 Getting Started

### Option 1: Online (Recommended for Testing)
Visit: **https://shirzartenwer.github.io/KA_onboard/**

### Option 2: Local Testing
1. Download all HTML files to the same folder
2. Open `index.html` in a web browser
3. Navigate through the experience

## 🧪 Testing Instructions

### For Moderated Prototype Testing

#### Setup (5 minutes)
1. Open the prototype URL on the testing device (desktop, tablet, or mobile)
2. Ensure the device has a stable internet connection
3. Have the prototype open on `index.html` (the home page)
4. Clear browser data if testing with multiple participants on the same device

#### Test Flow (15-20 minutes)

**Phase 1: First Impressions (2 min)**
- Show the home page
- Ask: "What do you think this is? What would you do first?"
- Observe natural navigation choices

**Phase 2: Onboarding Journey (10 min)**
- Let the participant go through the onboarding
- Observe:
  - Do they understand the island navigation?
  - Do they notice optional vs. mandatory islands?
  - Do they try to skip islands?
  - How do they react to avatar creation?
- Ask questions during the flow:
  - "What do you think will happen next?"
  - "Why did you choose that animal/option?"
  - "Is any information unclear?"

**Phase 3: Post-Onboarding (5 min)**
- After completing onboarding, observe:
  - Do they notice their avatar on the courses page?
  - Do they explore the avatar shop?
  - Do they understand the points system?
- Ask:
  - "How do you feel about the onboarding experience?"
  - "Would you want to customize your avatar?"
  - "What would you change?"

**Phase 4: Navigation & Features (3 min)**
- Ask them to:
  - Return to the home page
  - Visit the avatar shop
  - Try to reset their profile
- Observe ease of navigation

### Key Testing Questions

**Usability:**
- Was the navigation intuitive?
- Were the instructions clear?
- Were there any confusing moments?
- Did anything feel broken or incomplete?

**Engagement:**
- Which parts were most interesting?
- Which parts felt boring or too long?
- Would you complete this onboarding?
- Would you customize your avatar?

**Emotional Response:**
- How did the avatar make you feel?
- Did you feel connected to your avatar?
- Did the onboarding feel welcoming?
- Did you feel excited to start learning?

**Mobile/Device Specific:**
- Was text readable?
- Were buttons easy to tap?
- Did anything look broken on your screen?
- Did scrolling feel natural?

## 🎮 User Journey Map

```
1. Landing Page (index.html)
   ├── Start Onboarding → comprehensive-onboarding.html
   ├── Skip to Courses → khan-courses-page.html (if completed before)
   └── Visit Shop → avatar-shop.html

2. Onboarding Journey (comprehensive-onboarding.html)
   ├── Island 0: Basic Info (mandatory)
   ├── Island 1: Learning Style (mandatory)
   ├── Island 2: Goals (mandatory)
   ├── Island 3: Future Dreams (optional)
   ├── Island 4: Avatar Selection (optional)
   └── Island 5: Curiosity Lab (optional)
   → Completion → khan-courses-page.html

3. Courses Page (khan-courses-page.html)
   ├── Avatar companion in sidebar
   ├── Link to Home
   └── (Would link to Shop in full version)

4. Avatar Shop (avatar-shop.html)
   ├── Purchase items with points
   ├── Customize avatar
   └── Return to Home
```

## 🔄 Reset Instructions

To reset the prototype between testing sessions:
1. Click the "🔄 Reset Everything" button on the home page
2. Or manually clear browser localStorage:
   - Chrome: F12 → Application → Local Storage → Clear
   - Safari: Develop → Show Web Inspector → Storage → Clear
   - Firefox: F12 → Storage → Local Storage → Clear

## 📱 Device Compatibility

This prototype is optimized for:
- ✅ Desktop/Laptop browsers (Chrome, Safari, Firefox, Edge)
- ✅ Tablets (iPad, Android tablets)
- ✅ Mobile phones (iOS Safari, Android Chrome)

**Recommended browsers:**
- Chrome 90+
- Safari 14+
- Firefox 88+
- Edge 90+

## 🎨 Design Features

- **Responsive Design**: Works on all screen sizes
- **Avatar System**: Persistent avatar across pages
- **Island Navigation**: Non-linear onboarding journey
- **Points & Rewards**: Gamification through shop system
- **Local Storage**: Saves progress in browser

## ⚠️ Known Limitations

This is a **prototype** with the following limitations:
- No actual course content (mock courses only)
- Points are simulated (not earned through learning)
- No backend/database (uses browser localStorage)
- No user accounts or authentication
- Limited avatar customization options
- No analytics or data collection

## 🐛 Troubleshooting

**Issue: Progress not saving**
- Solution: Ensure browser allows localStorage
- Check browser privacy settings
- Try a different browser

**Issue: Navigation not working**
- Solution: Ensure all HTML files are in the same folder
- Check that file names match exactly
- Try opening index.html directly

**Issue: Display looks broken**
- Solution: Try a different browser
- Clear browser cache
- Check screen size (works best on screens 320px+ wide)

## 📊 Data Collection Notes

For testing purposes, consider collecting:
- Time spent on each island
- Which islands were skipped
- Avatar choices
- User feedback quotes
- Observed pain points
- Moments of delight
- Navigation issues

## 🎯 Testing Goals

Primary research questions:
1. Does the island-based onboarding feel intuitive?
2. Do users connect with their avatar companion?
3. Is the optional vs. mandatory distinction clear?
4. Does the flow feel too long or just right?
5. Would users return to customize their avatar?
6. Does the avatar enhance the learning experience?

## 📝 Feedback Template

Use this template when collecting feedback:

```
Participant ID: _____
Device Type: Desktop / Tablet / Mobile
Age Range: _____
Date: _____

Onboarding Completion: Full / Partial / Skipped
Time Spent: _____ minutes

Issues Encountered:
-
-

Positive Moments:
-
-

Suggestions:
-
-

Overall Experience (1-5): _____
Likelihood to Complete (1-5): _____
Avatar Connection (1-5): _____

Additional Notes:
```

## 🤝 Contributing

This is a prototype for testing purposes. Feedback welcome!

## 📄 License

Educational prototype - Not for commercial use

---

**Need Help?** Contact the project team with any questions or issues during testing.

**Last Updated:** 2025-10-27
