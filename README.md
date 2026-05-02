# MindPulse (MindControl)

**AI-Powered Well-being Assessment & Biofeedback Dashboard**

MindPulse is a comprehensive, modern Next.js application designed to track, assess, and improve user well-being. It integrates interactive assessments, real-time biofeedback visualization, and AI-driven insights to provide a holistic view of mental and emotional health.

## 🌟 Features

* **Interactive Dashboard:** A comprehensive overview of user well-being, featuring a Wellbeing Index, Interaction Charts, and Active Insights.
* **Biofeedback Integration (GSR):** Real-time monitoring and visualization of Galvanic Skin Response (GSR) data to track stress and emotional arousal levels.
* **AI-Powered Assessments:** Dynamic, intelligent assessments to gauge mental state and provide personalized recommendations.
* **Personalized Pathways:** Tailored wellness journeys based on assessment results and historical data.
* **Trend Analysis:** Detailed charts and visualizations tracking well-being metrics over time.
* **Admin Capabilities:** Dedicated administrative dashboard for managing users, content, and system settings.
* **Resource Library:** A curated collection of mental health resources, articles, and exercises.
* **Responsive Design:** A seamless experience across desktop and mobile devices, utilizing a responsive sidebar and bottom navigation.

## 💻 Tech Stack

* **Framework:** [Next.js](https://nextjs.org/) (App Router)
* **Library:** [React 19](https://react.dev/)
* **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
* **Animations:** [Framer Motion](https://www.framer.com/motion/)
* **Data Visualization:** [Recharts](https://recharts.org/)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Typography:** [Inter (Google Fonts)](https://fonts.google.com/specimen/Inter)

## 🚀 Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📂 Project Structure

* `app/`: Next.js App Router pages (Dashboard, Assessment, Admin, GSR, Pathways, Profile, Resources, Trends).
* `components/`: Reusable React components organized by feature (layout, dashboard, assessment, etc.).
* `firmware/`: Hardware integration or related micro-controller code (if applicable).
* `public/`: Static assets like images and icons.

## 🛠️ Development

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
