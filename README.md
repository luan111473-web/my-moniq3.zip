/** @type {import('next').NextConfig} */
const nextConfig = {}

module.exports = nextConfig
{
  "name": "my-moniq3",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "14.1.0",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "tailwindcss": "^3.4.0",
    "@headlessui/react": "^1.7.14",
    "framer-motion": "^10.16.4",
    "lucide-react": "^0.268.0"
  },
  "devDependencies": {
    "autoprefixer": "^10.4.15",
    "postcss": "^8.4.29"
  }
}
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};
# Moniq3 Clone

Dự án web Next.js mô phỏng Moniq3 với Tailwind, xác thực, upload âm thanh, editor WebGL, và thanh toán.

## 🚀 Cách chạy
1. Cài Node.js >= 18
2. Clone dự án và cài gói:
   ```bash
   npm install
   ```
3. Chạy server dev:
   ```bash
   npm run dev
   ```
4. Truy cập `http://localhost:3000`

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
