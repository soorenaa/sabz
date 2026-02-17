به نام خدا ساخته شده در زمان محدود و این مینی پروژه ui جالبی نداره اما از نظر فنی حداقل هارو داره 
اگر چه بسیار کارهای  دیگه و قابلیت های دیگه میشد ایجاد کرد اما خب در زمان کوتاه و شرایط فعلی بیش از این امکان پذیر نبود وگرنه  بسیبار با سلیقه و وسواس هستم 😶


Create By :

Next.js -  React
TypeScript - 
Chakra UI -
Tailwind CSS -
Axios - 
Headless UI -
React Icons - 
DummyJSON API - API 

Endpoints :

POST	/auth/login	
GET	/auth/me	
POST	/auth/refresh	 
GET	/products	
GET	/products/{id}	
GET	/products?limit=10&skip=10

Structure
📁 SABZ
├── 📁 .next
├── 📁 components
│   ├── 📄 AdvancedFilter.tsx
│   ├── 📄 Layout.tsx
│   ├── 📄 ProductDetail.tsx
│   ├── 📄 ProductsList.tsx
│   └── 📄 withAuth.tsx
├── 📁 lib
│   └── 📄 api.ts
├── 📁 node_modules
├── 📁 pages
│   ├── 📁 auth
│   │   └── 📄 login.tsx
│   ├── 📁 dashboard
│   │   └── 📄 index.tsx
│   ├── 📁 products
│   │   ├── 📄 [id].tsx
│   │   └── 📄 index.tsx
│   ├── 📄 _app.tsx
│   └── 📄 index.tsx
├── 📁 public
│   └── 📁 font
├── 📁 styles
│   └── 📄 globals.css
├── 📄 .gitignore
├── 📄 next.config.js
├── 📄 package.json
├── 📄 README.md
├── 📄 tailwind.config.js
└── 📄 tsconfig.json
