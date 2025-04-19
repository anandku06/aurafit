# 🌿 AuraFit – Your AI Fitness Trainer

AuraFit is an intelligent AI-powered fitness trainer built to help you reach your health goals with personalized guidance, real-time coaching, and smart lifestyle insights. It combines the power of voice interaction, machine learning, and seamless authentication to create a truly immersive fitness experience.

---

## 🚀 Tech Stack

| Tech         | Description                                                             |
|--------------|-------------------------------------------------------------------------|
| Next.js      | Full-stack React framework for building fast, scalable web apps         |
| Clerk        | User authentication and session management                              |
| Vapi         | Voice assistant API for real-time AI conversations                      |
| Convex       | Serverless backend for storing and syncing fitness data                 |
| Gemini API   | AI brain behind the personalized coaching and workout recommendations   |

---

## 🔥 Features

- 🤖 AI-generated workout routines, wellness tips, and motivation
- 🔐 Secure user authentication with Clerk
- 🎙️ Real-time voice coaching using Vapi
- 📊 Track fitness goals, progress, and habits
- 🧘 Personalized fitness and wellness plans powered by Gemini AI
- ☁️ Scalable, real-time backend powered by Convex

---

## 📦 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/anandku06/aurafit.git
cd aurafit
```

2. **Install Dependencies**

```bash
npm install
# or
yarn install
```

3. **Set Up Environment Variables**

Create a `.env.local` file in the root directory and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

VAPI_API_KEY=your_vapi_api_key

NEXT_PUBLIC_CONVEX_URL=your_convex_url

GEMINI_API_KEY=your_gemini_api_key
```

4. **Run the Development Server**

```bash
npm run dev
# or
yarn dev
```

Visit [http://localhost:3000](http://localhost:3000) to see your app in action.

---

## 🛠️ Project Structure

```
/app               → Next.js App Router
/components        → Reusable UI components
/lib               → API clients and helpers (Gemini, Vapi, etc.)
/convex            → Convex backend logic
/middleware.ts     → Clerk middleware for authentication
.env.local         → Environment variables
```

---

## 🧠 AI Integration

- **Gemini API** generates personalized advice, workouts, and health tips based on user data.
- **Vapi** enables users to have a conversation with their AI trainer through voice.

---

## 🔐 Authentication

Clerk provides modern and secure auth features:
- Magic links & OAuth (Google, GitHub, etc.)
- User profile & session management

---

## 🧪 Future Enhancements

- 🏋️ Progress analytics dashboard
- 🥗 AI meal planner with calorie tracking
- 📅 Schedule syncing with Google Calendar
- 📱 Mobile app (Next.js PWA or React Native)
- 🧍 Pose detection and real-time form correction

---

## 🙌 Contributing

Contributions are welcome!  
If you'd like to suggest improvements or new features, feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Inspiration

**AuraFit** is built with the belief that fitness should be intuitive, personalized, and inspiring. With AI as your companion, your wellness journey becomes smarter, not harder.

---

## 📬 Contact

Crafted with ❤️ by [Anand Kumar](https://github.com/anandku06)  
Get in touch: **anandkr1704@gmail.com**