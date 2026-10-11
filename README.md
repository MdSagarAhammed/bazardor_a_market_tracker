# 🛒 বাজার দর (BazarDor)

**প্রয়োজনীয় পণ্যের দাম এক নজরে।** BazarDor is a responsive Bangla-first market-price dashboard for checking everyday grocery prices in Bangladesh, comparing estimated prices across markets, and following daily price movement.

## Features

- **Live product catalogue:** Fetches products and categories exclusively from the provided BazarDor API; no local sample product catalogue is used.
- **Price movement overview:** Separate sections for the top six price risers and fallers.
- **Product details and market comparison:** Login-protected product pages with min/max/average price summaries and market-level comparisons.
- **Category browsing and sorting:** Category routes with numeric ascending/descending price sorting that correctly handles Bengali digits.
- **Authentication:** Better Auth email/password registration and sign-in, optional Google/GitHub OAuth, protected product details, profile and sign-out.
- **Responsive Bangla UI:** Mobile-friendly navigation, scrolling price ticker, loading skeletons, toast notifications and a custom 404 page.

## Tech stack

- Next.js App Router
- JavaScript
- React 19
- Tailwind CSS v4 + custom responsive CSS
- Better Auth
- MongoDB Atlas
- `react-hot-toast`
- `lucide-react`