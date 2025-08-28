🏋️‍♂️ Dobby Fitness Agent

Personalized fitness & diet plans powered by Fireworks AI.
Bring your own Fireworks API key, enter your profile details (age, weight, height, activity, diet preference, goal), and instantly generate a custom workout + nutrition plan.

Live Demo: https://dobby-fitness-agent.vercel.app/

✨ Features

Custom fitness & diet plan — generated from your profile inputs.

BYO Fireworks API Key — secure, no account sharing.

Simple & clean UI — just fill in your details and hit Generate Plan.

On-the-go use — designed for mobile and gym floor use.

Balanced approach — includes diet guidelines, progressive workout plan, and reminders on essentials (hydration, protein, sleep, form, consistency).

🧰 Tech Stack

Frontend: Next.js + React

Styling: TailwindCSS / Shadcn UI

Deployment: Vercel

AI Backend: Fireworks API

🚀 Quick Start
1) Clone the repo
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

2) Install dependencies
# Using npm
npm install

# Or yarn
yarn

# Or pnpm
pnpm install

3) Setup environment variables

Create a .env.local file in the root folder:

FIREWORKS_API_KEY=your_api_key_here
FIREWORKS_MODEL=accounts/fireworks/models/<model-id>
FIREWORKS_BASE_URL=https://api.fireworks.ai/inference/v1


⚠️ Note: The API key can also be entered directly into the app by the user. Never commit your API key to GitHub.

4) Run the development server
npm run dev


Open http://localhost:3000
 in your browser.

🧑‍💻 Usage

Open the app (demo
 or local).

Enter your Fireworks API key.

Fill in profile details:

Age

Sex

Height (cm)

Weight (kg)

Activity level (Sedentary → Very Active)

Dietary preference (Veg / Non-veg / Vegan / etc.)

Fitness goal (Lose Weight / Build Muscle / Stay Fit)

Click Generate Plan.

Get your Diet Plan + Fitness Plan instantly.

🔐 Security

API keys are only used client-side to make requests to Fireworks.

No data is stored on servers unless you add a backend.

Keep .env.local out of version control.

📸 Screenshot

⚙️ Roadmap

Save generated plans locally

Export to PDF / Notes

Multi-day workout splits

Tracking progress (RPE, reps, weights)

Voice input for mobile

🤝 Contributing

Fork the project

Create a branch: git checkout -b feat/awesome-feature

Commit changes: git commit -m "Add awesome feature"

Push: git push origin feat/awesome-feature

Open a Pull Request
