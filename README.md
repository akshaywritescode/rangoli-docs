# 🌸 Rangoli UI – Beautifully Crafted Components for Modern Web Apps ✨
![Repo Hero Image](https://raw.githubusercontent.com/akshaywritescode/rangoli-docs/refs/heads/main/images/reset-password.png)

Rangoli UI is a sleek and customizable React component library built on **shadcn/ui** and **Tailwind CSS**. 🚀 Designed for developers who want **scalable**, **accessible**, and **aesthetic** UI components without the bloat.

## 🔥 Features

✅ Pre-styled, themeable components 🎨  
✅ Optimized for performance & accessibility ♿  
✅ Dark mode support 🌙  
✅ Easy integration with Next.js & Vite ⚡  
✅ Developer-friendly & lightweight 🚀

## 🚀 Usage

Simply copy and paste the code into your project:

```tsx
<PricingCard
  planTitle="Basic"
  planDescription="Create interactive forms that connect to your workflow"
  price={["24", "242"]}
  isMonthly={true} /*can change dynamically */
  features={[
    "100 responses/mo included",
    "1 user",
    "Unlimited forms",
    "Unlimited questions",
  ]}
  seeAllFeatureLink="/basic-features"
/>
For dependencies and setup, visit the Setup Guide.

🎨 Customization
Rangoli UI is fully customizable with Tailwind CSS. Extend styles using your tailwind.config.js:

js
Copy
Edit
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: "#ff6b6b",
      },
    },
  },
};
📖 Documentation
Find full documentation at www.rangoliui.me.

🤝 Contributing
We welcome contributions! To contribute:

Fork the repo 📌
Create a new branch ✨
Commit changes 💡
Submit a PR 🚀
💡 Want to Contribute to Live Component Examples?
If you want to contribute to live component examples, we have a separate repository for that! Check out Rangoli Live Components and submit your improvements there.

🛠 Setting Up Local Mintlify Server
Rangoli UI documentation is built with Mintlify. To set up a local development server:

sh
Copy
Edit
npx mintlify dev
For more details, visit the Mintlify Docs.

🛡️ License
Rangoli UI is licensed under the MIT License.

💖 Made with love by Akshay Yadav