```TypeScript
interface IUser {
  name: string;
  role: string;
  technologies: {
    programmingLanguages: string[];
    frontend: string[];
    backend: string[];
    blockchain?: string[];
    devOps: string[];
    developmentTools: {
      buildTools: string[];
      testing: string[];
      linting: string[];
      versionControl: string[];
      packageManagers: string[];
    };
    methodologies: string[];
    designTools: string[];
    other: string[];
  };
  languages: { name: string; level: string }[];
  location: { current: string; description: string };
  years: number;
}

const Raymont: IUser = {
  name: "Raymont",
  role: "JavaScript / TypeScript Engineer",
  technologies: {
    programmingLanguages: ["JavaScript", "TypeScript"],
    frontend: [
      "HTML",
      "CSS",
      "SCSS",
      "React",
      "Redux Toolkit",
      "Axios",
      "React Hook Form",
      "Zod",
      "Yup",
      "TanStack Query",
      "Next.js",
      "Remix",
      "Vue2/3",
      "Nuxt",
      "Strapi CMS",
      "Shadcn/UI",
      "Material UI",
      "Tailwind CSS",
      "SCSS Modules",
      "Electron",
      "Chart.js",
      "React Native",
      "Telegram Web MiniApps",
      "i18n",
      "Aria/Semantic/SEO"
    ],
    backend: [
      "Node.js",
      "Express",
      "JWT",
      "Socket.IO",
      "MongoDB",
      "MySQL",
      "SQLite",
      "Firebase",
      "node-telegram-bot-api"
    ],
    blockchain: [
      "Web3 basics",
      "WebRTC",
      "WebSockets",
      "SSE",
      "viem",
      "wagmi",
      "Liquidity pools",
      "Wallet integration"
    ],
    devOps: ["Nginx", "Docker", "Ngrok", "CI/CD (GitHub Actions, GitLab CI/CD)", "SSL/TLS setup"],
    developmentTools: {
      buildTools: ["Webpack", "Vite", "Gulp"],
      testing: ["Jest", "React Testing Library", "Loki", "Storybook"],
      linting: ["ESLint", "Prettier", "Stylelint"],
      versionControl: ["Git", "GitLab", "GitHub", "Husky"],
      packageManagers: ["npm", "yarn"]
    },
    methodologies: ["BEM", "DRY", "KISS", "Feature-Sliced Design (FSD)"],
    designTools: [
      "Figma",
      "Adobe Photoshop",
      "Adobe Illustrator",
      "Photopea",
      "MagicaVoxel",
      "DragonBones"
    ],
    other: ["Notion", "Jira", "Trello", "Evernote", "Toggl", "ChatGPT"]
  },
  languages: [
    { name: "Russian", level: "Native" },
    { name: "English", level: "B1" },
    { name: "Japanese", level: "Wakarimasen" },
    { name: "French", level: "Bonjour" }
  ],
  location: {
    current: "Kazakhstan, open for remote",
    description: "Remote / Relocation open"
  },
  years: 19
};

```

[![CodeWars user raymont](https://www.codewars.com/users/Raymont/badges/large)](https://www.codewars.com/users/Raymont)
[![LeetCode user raymont](https://img.shields.io/badge/dynamic/json?style=for-the-badge&labelColor=black&color=%23ffa116&label=Solved%20tasks&query=solved&url=https%3A%2F%2Fleetcode-badge.vercel.app%2Fapi%2Fusers%2Fraymont&logo=leetcode&logoColor=yellow)](https://leetcode.com/raymont/)
