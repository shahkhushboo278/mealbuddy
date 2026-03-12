# 🥗 MealBuddy — Vegetarian Nutrition Tracker

**A WhatsApp-style chat app to track what you eat, count calories, and get personalized health tips — built for vegetarians.**

🔗 **Live App:** [shahkhushboo278.github.io/mealbuddy](https://shahkhushboo278.github.io/mealbuddy/)

---

## 📱 What is MealBuddy?

MealBuddy is a conversational nutrition tracker that feels just like chatting on WhatsApp. Instead of filling out forms or tapping through menus, you simply type what you ate — and MealBuddy tracks everything automatically.

> *"I had dal roti for lunch and a banana smoothie"* → logged, calories counted, macros updated.

No sign-up. No install. Works on any phone or browser. 100% free.

---

## ✨ Features

### 💬 Chat-Based Logging
- Type meals naturally — `"2 idli with sambhar"`, `"large bowl of oatmeal"`, `"masala chai"`
- Supports quantity words — `"two"`, `"half"`, `"large"`, `"small"`
- Understands measurement descriptions — `"250ml milk"` won't inflate your calories
- Instant response with calorie count after each entry

### 📊 Live Dashboard (5 tabs)
| Tab | What it shows |
|-----|--------------|
| **Overview** | Total calories, health score ring, healthy vs unhealthy count |
| **Meals** | Full food log with timestamps and health labels |
| **Macros** | Protein, carbs, fats, fiber bars vs daily targets |
| **Tips** | Personalized recommendations based on what you ate |
| **Recipes** | Save your own recipes and log them in one tap |

### 🌱 200+ Vegetarian Foods
Foods are organized across 7 cuisines and categories:

- 🇮🇳 **Indian** — dal, rajma, idli, dosa, roti, biryani, samosa, khichdi, and 40+ more
- 🧆 **Middle Eastern** — hummus, falafel, pita, tabbouleh, baba ganoush, and more
- 🥢 **Chinese / Asian** — tofu, fried rice, edamame, miso soup, pad thai, and more
- 🍔 **Fast Food (Veg)** — veg burger, pizza, nachos, wraps, mac & cheese
- 💪 **Gym & Protein** — protein shake, quinoa, chia seeds, greek yogurt, and more
- 🍓 **Fruits** — 25+ fruits including mango, guava, pomegranate, lychee, jackfruit
- 🥦 **Vegetables** — 25+ veggies including Indian staples like okra, bitter gourd, drumstick

### 📖 Custom Recipes
- Add your own home recipes with full nutrition info
- Save once, log forever — just type the recipe name in chat
- Edit or delete recipes anytime
- Recipes persist across sessions (saved in browser)

### 📱 Mobile-Friendly
- Responsive design — works on all screen sizes
- On mobile: chat and dashboard are separate screens with easy switching
- Add to home screen on iPhone/Android — works like a native app

### 💾 Data Persistence
- Today's food log is automatically saved
- Reopening the app restores your log for the day
- Custom recipes are saved permanently until you delete them

---

## 🚀 How to Use

### Option 1 — Use the live app
Go to **[shahkhushboo278.github.io/mealbuddy](https://shahkhushboo278.github.io/mealbuddy/)** — no installation needed.

### Option 2 — Add to your phone's home screen
1. Open the link in your phone's browser
2. **iPhone:** Tap Share → "Add to Home Screen"
3. **Android:** Tap menu (⋮) → "Add to Home Screen"

### Option 3 — Download and run locally
1. Download `index.html` from this repository
2. Open it in any browser — Chrome, Safari, Firefox, Edge
3. No server needed — it runs entirely in your browser

---

## 💬 Chat Examples

```
You:        2 eggs and toast
MealBuddy:  Healthy pick! Your body will thank you 💪  [236 kcal]

You:        large bowl of oatmeal with banana
MealBuddy:  Great choice! That's a nutritious option 💚  [327 kcal]

You:        masala chai 250ml
MealBuddy:  Logged! Not bad — fairly balanced.  [60 kcal]

You:        veg pizza slice
MealBuddy:  Logged! High in calories — try to add some fiber next meal 🌿  [260 kcal]
```

---

## 🔧 Adding Your Own Foods

Open `index.html` in any text editor (Notepad / TextEdit). Find the `FOOD_DB` section and add a line:

```js
"aloo paratha": { cal:300, protein:6, carbs:42, fat:12, fiber:3, healthy:false, category:"indian", emoji:"🫓" },
```

**Fields:**
| Field | Description |
|-------|-------------|
| `cal` | Calories per serving |
| `protein` | Grams of protein |
| `carbs` | Grams of carbohydrates |
| `fat` | Grams of fat |
| `fiber` | Grams of fiber |
| `healthy` | `true` = healthy, `false` = indulgent |
| `category` | Any label: `"indian"`, `"fruit"`, `"snack"`, etc. |
| `emoji` | Any emoji that fits the food |

Save the file, reload the browser, and your food is now recognized in chat.

---

## 🗂️ Project Structure

```
mealbuddy/
└── index.html        # The entire app — HTML, CSS, and JavaScript in one file
```

MealBuddy is intentionally a single-file app. No frameworks, no dependencies, no build steps. Just one HTML file you can open anywhere.

---

## 🛠️ Built With

- **Vanilla HTML / CSS / JavaScript** — zero dependencies
- **Google Fonts** — DM Sans + Syne
- **Browser localStorage** — for saving meals and recipes
- **GitHub Pages** — for free hosting

---

## 📈 Roadmap / Future Ideas

- [ ] Weekly nutrition history and charts
- [ ] Weight and water intake tracking
- [ ] Meal planning (breakfast / lunch / dinner categories)
- [ ] Export daily report as PDF
- [ ] Share meal log with friends
- [ ] Calorie goal customization (currently fixed at 2000 kcal)
- [ ] More cuisine databases — Mexican, Italian, Korean

---

## 🙋 About

Built by **Khushboo Shah** as a personal nutrition tool for vegetarians who want a simple, chat-style way to track what they eat — without complicated apps or subscriptions.

If you find it useful, feel free to ⭐ star the repo or share the link with friends!

---

## 📄 License

This project is open for personal use. If you'd like to use it commercially or build on top of it, please reach out first.

---

*Made with 🌱 for vegetarians everywhere*
