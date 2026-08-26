# VYORA Social source bundle
# Supabase credentials are intentionally not included. Configure VITE_SUPABASE_URL and VITE_SUPABASE_ANON_KEY in your environment.


===== artifacts/vyora-social/index.html =====

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1" />
    <title>VYORA Social</title>
    <meta name="description" content="VYORA Social — built on Replit. Update this description to reflect the app." />
    <meta name="robots" content="index, follow" />
    <meta property="og:title" content="VYORA Social" />
    <meta property="og:description" content="VYORA Social — built on Replit. Update this description to reflect the app." />
    <meta property="og:type" content="website" />
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:title" content="VYORA Social" />
    <meta name="twitter:description" content="VYORA Social — built on Replit. Update this description to reflect the app." />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>


===== artifacts/vyora-social/package.json =====

{
  "name": "@workspace/vyora-social",
  "version": "0.0.0",
  "private": true,
  "type": "module",
  "scripts": {
    "dev": "vite --config vite.config.ts --host 0.0.0.0",
    "build": "vite build --config vite.config.ts",
    "serve": "vite preview --config vite.config.ts --host 0.0.0.0",
    "typecheck": "tsc -p tsconfig.json --noEmit"
  },
  "devDependencies": {
    "@hookform/resolvers": "^3.10.0",
    "@radix-ui/react-accordion": "^1.2.4",
    "@radix-ui/react-alert-dialog": "^1.1.7",
    "@radix-ui/react-aspect-ratio": "^1.1.3",
    "@radix-ui/react-avatar": "^1.1.4",
    "@radix-ui/react-checkbox": "^1.1.5",
    "@radix-ui/react-collapsible": "^1.1.4",
    "@radix-ui/react-context-menu": "^2.2.7",
    "@radix-ui/react-dialog": "^1.1.7",
    "@radix-ui/react-dropdown-menu": "^2.1.7",
    "@radix-ui/react-hover-card": "^1.1.7",
    "@radix-ui/react-label": "^2.1.3",
    "@radix-ui/react-menubar": "^1.1.7",
    "@radix-ui/react-navigation-menu": "^1.2.6",
    "@radix-ui/react-popover": "^1.1.7",
    "@radix-ui/react-progress": "^1.1.3",
    "@radix-ui/react-radio-group": "^1.2.4",
    "@radix-ui/react-scroll-area": "^1.2.4",
    "@radix-ui/react-select": "^2.1.7",
    "@radix-ui/react-separator": "^1.1.3",
    "@radix-ui/react-slider": "^1.2.4",
    "@radix-ui/react-slot": "^1.2.0",
    "@radix-ui/react-switch": "^1.1.4",
    "@radix-ui/react-tabs": "^1.1.4",
    "@radix-ui/react-toast": "^1.2.7",
    "@radix-ui/react-toggle": "^1.1.3",
    "@radix-ui/react-toggle-group": "^1.1.3",
    "@radix-ui/react-tooltip": "^1.2.0",
    "@replit/vite-plugin-cartographer": "catalog:",
    "@replit/vite-plugin-dev-banner": "catalog:",
    "@replit/vite-plugin-runtime-error-modal": "catalog:",
    "@tailwindcss/typography": "^0.5.15",
    "@tailwindcss/vite": "catalog:",
    "@tanstack/react-query": "catalog:",
    "@types/node": "catalog:",
    "@types/react": "catalog:",
    "@types/react-dom": "catalog:",
    "@vitejs/plugin-react": "catalog:",
    "@workspace/api-client-react": "workspace:*",
    "class-variance-authority": "catalog:",
    "clsx": "catalog:",
    "cmdk": "^1.1.1",
    "date-fns": "^3.6.0",
    "embla-carousel-react": "^8.6.0",
    "framer-motion": "catalog:",
    "input-otp": "^1.4.2",
    "lucide-react": "catalog:",
    "next-themes": "^0.4.6",
    "react": "catalog:",
    "react-day-picker": "^9.11.1",
    "react-dom": "catalog:",
    "react-hook-form": "^7.55.0",
    "react-icons": "^5.4.0",
    "react-resizable-panels": "^2.1.7",
    "recharts": "^2.15.2",
    "sonner": "^2.0.7",
    "tailwind-merge": "catalog:",
    "tailwindcss": "catalog:",
    "tw-animate-css": "^1.4.0",
    "vaul": "^1.1.2",
    "vite": "catalog:",
    "wouter": "^3.3.5",
    "zod": "catalog:"
  },
  "dependencies": {
    "@supabase/supabase-js": "^2.112.3"
  }
}


===== artifacts/vyora-social/src/App.tsx =====

import { type ReactNode, useEffect, useState } from 'react';
import { QueryClient, QueryClientProvider } from '@tanstack/react-query';
import { ErrorBoundary } from '@/components/error-boundary';
import { Toaster } from '@/components/ui/toaster';
import { TooltipProvider } from '@/components/ui/tooltip';
import {
  ArrowLeft,
  ArrowUpRight,
  Bookmark,
  Check,
  Compass,
  Heart,
  Image,
  LogOut,
  Mail,
  MessageCircle,
  MessageSquare,
  MoreHorizontal,
  Moon,
  Search,
  Send,
  Settings as SettingsIcon,
  Share2,
  Shield,
  Sparkles,
  Sun,
  UserRound,
  UsersRound,
  X,
} from 'lucide-react';
import {
  Link,
  Route,
  Switch,
  useLocation,
  Router as WouterRouter,
} from 'wouter';
import NotFound from '@/pages/not-found';
import Messages from '@/pages/messages';

const queryClient = new QueryClient();

type Theme = 'light' | 'dark';
type AvatarTone = 'lime' | 'coral' | 'aqua' | 'ink';

const people = [
  { name: 'Mina Okafor', handle: '@mina.makes', tone: 'coral' as AvatarTone, initials: 'MO', detail: 'slow mornings' },
  { name: 'Ravi Chen', handle: '@ravi.afterhours', tone: 'aqua' as AvatarTone, initials: 'RC', detail: 'street corners' },
  { name: 'Noor Velez', handle: '@noor.notes', tone: 'lime' as AvatarTone, initials: 'NV', detail: 'tiny rituals' },
];

const posts = [
  {
    id: 'p1',
    name: 'Mina Okafor',
    handle: '@mina.makes',
    time: '18 min',
    tone: 'coral' as AvatarTone,
    initials: 'MO',
    copy: <>Found a blue chair in the morning light and decided it was the whole plan for today. <strong>#smallwins</strong></>,
    art: 'sunset',
    likes: 84,
    comments: 9,
  },
  {
    id: 'p2',
    name: 'Ravi Chen',
    handle: '@ravi.afterhours',
    time: '1 hr',
    tone: 'aqua' as AvatarTone,
    initials: 'RC',
    copy: <>A reminder that a good playlist can make an ordinary walk feel like a scene from a very quiet film.</>,
    art: 'studio',
    likes: 47,
    comments: 4,
  },
  {
    id: 'p3',
    name: 'Noor Velez',
    handle: '@noor.notes',
    time: '3 hr',
    tone: 'lime' as AvatarTone,
    initials: 'NV',
    copy: <>What are you making room for this week? Mine is less rushing, more noticing.</>,
    likes: 112,
    comments: 16,
  },
];

function Brand() {
  return (
    <Link href="/" className="brand-mark" data-testid="link-brand">
      <span className="brand-orbit">v</span>
      <span className="brand-word">VYORA</span>
    </Link>
  );
}

function Avatar({ initials, tone = 'lime', size = '' }: { initials: string; tone?: AvatarTone; size?: string }) {
  return <span className={`avatar ${tone} ${size}`} data-testid={`img-avatar-${initials.toLowerCase()}`}>{initials}</span>;
}

function ThemeToggle({ theme, onToggle }: { theme: Theme; onToggle: () => void }) {
  return (
    <button className="icon-btn" onClick={onToggle} aria-label={`Switch to ${theme === 'light' ? 'dark' : 'light'} mode`} data-testid="button-theme-toggle">
      {theme === 'light' ? <Moon size={17} /> : <Sun size={17} />}
    </button>
  );
}

function Shell({ children, theme, onToggleTheme }: { children: ReactNode; theme: Theme; onToggleTheme: () => void }) {
  const [location] = useLocation();
  const [profileOpen, setProfileOpen] = useState(false);
  const isFeed = location === '/';
  return (
    <div className="vyora-app app-frame">
      <aside className="side-rail">
        <Brand />
        <div className="rail-kicker">Your corner of the internet</div>
        <nav className="rail-nav" aria-label="Main navigation">
          <Link href="/" className={`rail-link ${isFeed ? 'active' : ''}`} data-testid="link-feed"><Compass size={17} /> <span>Vibe feed</span></Link>
          <button className="rail-link" onClick={() => window.alert('Search is taking shape. Try a vibe from the feed for now.')} data-testid="button-search"><Search size={17} /> <span>Discover</span></button>
          <button className="rail-link" onClick={() => window.alert('Your circles will appear here as you follow people.')} data-testid="button-circles"><UsersRound size={17} /> <span>Circles</span></button>
          <Link href="/messages" className={`rail-link ${location === '/messages' ? 'active' : ''}`} data-testid="link-messages"><MessageSquare size={17} /> <span>Messages</span></Link>
        </nav>
        <div className="rail-kicker">Make it yours</div>
        <nav className="rail-nav">
          <Link href="/settings" className={`rail-link ${location === '/settings' ? 'active' : ''}`} data-testid="link-settings"><SettingsIcon size={17} /> <span>Settings</span></Link>
          <Link href="/guidelines" className={`rail-link ${location === '/guidelines' ? 'active' : ''}`} data-testid="link-guidelines"><Shield size={17} /> <span>Community care</span></Link>
        </nav>
        <div className="rail-bottom">
          <button className="rail-link" onClick={onToggleTheme} data-testid="button-rail-theme">{theme === 'light' ? <Moon size={17} /> : <Sun size={17} />} <span>{theme === 'light' ? 'Night mode' : 'Day mode'}</span></button>
          <div className="rail-profile">
            <Avatar initials="IA" />
            <div><div className="rail-profile-name">Ivy Anders</div><div className="rail-profile-handle">@ivy.inbetween</div></div>
          </div>
        </div>
      </aside>
      <main className="main-stage">
        <header className="topbar">
          <div className="topbar-title">{isFeed ? 'Tuesday, a little softer' : location.slice(1).replace('-', ' ')}</div>
          <div className="topbar-actions">
            <ThemeToggle theme={theme} onToggle={onToggleTheme} />
            <butt
