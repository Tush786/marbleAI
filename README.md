Prerequisites:
1. Create React App: Run the following command to create a React app named "Admin Panel UI":
npx create-react-app "marble"

2. Dependencies: Install the necessary dependencies including Tailwind CSS, React-icons, and apexcharts.js:
npm install tailwindcss, react-icons, apexcharts

3. Database: For dummy data, you can create an array within your React application to simulate data for the line graph on the UI.

Built With:
React.js
Tailwind CSS
HTML
ApexCharts.js

How To Start App:
npm run start

Project Structure (Suggested):
marble/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Dashboard.jsx
│   │   |── DashboardCard.jsx
│   │   |── Graph.jsx
│   │   |── Home.jsx
│   │   |── Tab1.jsx
│   │   |── Tab2.jsx
│   │   |── Tab3.jsx 
│   │   |── Tab4.jsx 
│   │   
│   ├── ContextAPI/
│   │   └── Contextprovider.jsx
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   └── index.js
├── package.json
└── README.md
└── tailwind.config.js
