# Tree View:
```
src
├── assets
│   ├── icons
│   │   ├── Calendar.svg
│   │   ├── ExternalLink.svg
│   │   ├── Facebook.svg
│   │   ├── Github.svg
│   │   ├── GoogleScholar.svg
│   │   ├── Institution.svg
│   │   ├── LinkedIn.svg
│   │   ├── Mail.svg
│   │   ├── Moon.svg
│   │   ├── ORCID.svg
│   │   ├── RSS.svg
│   │   ├── Settings.svg
│   │   ├── Sun.svg
│   │   ├── Twitter.svg
│   │   └── User.svg
│   └── icons.ts
├── components
│   ├── content
│   │   ├── ContentHeader.astro
│   │   └── ContentLinks.astro
│   ├── layout
│   │   ├── Footer.astro
│   │   ├── LeftSidebar.astro
│   │   ├── Navbar.astro
│   │   └── RightMain.astro
│   └── ui
│       ├── BackLink.astro
│       ├── BaseItemCard.astro
│       ├── Icon.astro
│       ├── ShareButtons.astro
│       ├── Tag.astro
│       └── Timeline.astro
├── config
│   ├── index.ts
│   ├── navigation.ts
│   ├── pages.ts
│   ├── site.ts
│   ├── social.ts
│   └── themes.ts
├── content
│   ├── posts
│   │   ├── morphology.md
│   │   └── welcome.md
│   └── projects
│       ├── arabic-sentiment-transformers.md
│       ├── fake-news-detection.md
│       └── research-infrastructure.md
├── content.config.ts
├── layouts
│   ├── BaseDetail.astro
│   ├── BaseLayout.astro
│   ├── BaseListing.astro
│   └── DevToolsLayout.astro
├── pages
│   ├── projects
│   │   ├── [id].astro
│   │   └── index.astro
│   └── rss.xml.ts
├── styles
│   └── global.css
├── types
│   ├── config.ts
│   ├── content.ts
│   ├── display.ts
│   ├── index.ts
│   └── themes.ts
└── utils
    ├── adapters.ts
    ├── readingTime.ts
    └── tags.ts

```

# Content:

## assets/icons/Calendar.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-calendar-event"><path stroke="none" d="M0 0h24v24H0z" fill="none" /><path d="M4 7a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2l0 -12" /><path d="M16 3l0 4" /><path d="M8 3l0 4" /><path d="M4 11l16 0" /><path d="M8 15h2v2h-2l0 -2" /></svg>

```


## assets/icons/ExternalLink.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-external-link">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M12 6h-6a2 2 0 0 0 -2 2v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-6" />
	<path d="M11 13l9 -9" />
	<path d="M15 4h5v5" />
</svg>
```


## assets/icons/Facebook.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-brand-facebook">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3" />
</svg>
```


## assets/icons/Github.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-brand-github">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5" />
</svg>
```


## assets/icons/GoogleScholar.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-school">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M22 9l-10 -4l-10 4l10 4l10 -4v6" />
	<path d="M6 10.6v5.4a6 3 0 0 0 12 0v-5.4" />
</svg>
```


## assets/icons/Institution.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-building-bank">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M3 21l18 0" />
	<path d="M3 10l18 0" />
	<path d="M5 6l7 -3l7 3" />
	<path d="M4 10l0 11" />
	<path d="M20 10l0 11" />
	<path d="M8 14l0 3" />
	<path d="M12 14l0 3" />
	<path d="M16 14l0 3" />
</svg>
```


## assets/icons/LinkedIn.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-brand-linkedin">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M8 11v5" />
	<path d="M8 8v.01" />
	<path d="M12 16v-5" />
	<path d="M16 16v-3a2 2 0 1 0 -4 0" />
	<path d="M3 7a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4v10a4 4 0 0 1 -4 4h-10a4 4 0 0 1 -4 -4l0 -10" />
</svg>
```


## assets/icons/Mail.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-mail">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2v-10" />
	<path d="M3 7l9 6l9 -6" />
</svg>
```


## assets/icons/Moon.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-moon">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M12 3c.132 0 .263 0 .393 0a7.5 7.5 0 0 0 7.92 12.446a9 9 0 1 1 -8.313 -12.454l0 .008" />
</svg>
```


## assets/icons/ORCID.svg

```svg
<svg 
  xmlns="http://www.w3.org/2000/svg" 
  width="24" 
  height="24" 
  viewBox="0 0 24 24" 
  fill="none" 
  stroke="currentColor" 
  stroke-width="1.5" 
  stroke-linecap="round" 
  stroke-linejoin="round" 
  class="icon icon-tabler icon-tabler-orcid"
>
  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
  <!-- Círculo exterior -->
  <path d="M12 12m-9 0a9 9 0 1 0 18 0a9 9 0 1 0 -18 0" />
  <!-- La "i" con su punto -->
  <path d="M9 11v5" />
  <path d="M9 8v.01" /> 
  <!-- La "D" estilizada -->
  <path d="M12 8v8" />
  <path d="M12 8h1.5a2.5 2.5 0 0 1 2.5 2.5v3a2.5 2.5 0 0 1 -2.5 2.5h-1.5" />
</svg>

```


## assets/icons/RSS.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-rss">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M4 19a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" />
	<path d="M4 4a16 16 0 0 1 16 16" />
	<path d="M4 11a9 9 0 0 1 9 9" />
</svg>

```


## assets/icons/Settings.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-settings">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M10.325 4.317c.426 -1.756 2.924 -1.756 3.35 0a1.724 1.724 0 0 0 2.573 1.066c1.543 -.94 3.31 .826 2.37 2.37a1.724 1.724 0 0 0 1.065 2.572c1.756 .426 1.756 2.924 0 3.35a1.724 1.724 0 0 0 -1.066 2.573c.94 1.543 -.826 3.31 -2.37 2.37a1.724 1.724 0 0 0 -2.572 1.065c-.426 1.756 -2.924 1.756 -3.35 0a1.724 1.724 0 0 0 -2.573 -1.066c-1.543 .94 -3.31 -.826 -2.37 -2.37a1.724 1.724 0 0 0 -1.065 -2.572c-1.756 -.426 -1.756 -2.924 0 -3.35a1.724 1.724 0 0 0 1.066 -2.573c-.94 -1.543 .826 -3.31 2.37 -2.37c1 .608 2.296 .07 2.572 -1.065" />
	<path d="M9 12a3 3 0 1 0 6 0a3 3 0 0 0 -6 0" />
</svg>
```


## assets/icons/Sun.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-sun">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M8 12a4 4 0 1 0 8 0a4 4 0 1 0 -8 0" />
	<path d="M3 12h1m8 -9v1m8 8h1m-9 8v1m-6.4 -15.4l.7 .7m12.1 -.7l-.7 .7m0 11.4l.7 .7m-12.1 -.7l-.7 .7" />
</svg>
```


## assets/icons/Twitter.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-brand-x">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M4 4l11.733 16h4.267l-11.733 -16l-4.267 0" />
	<path d="M4 20l6.768 -6.768m2.46 -2.46l6.772 -6.772" />
</svg>
```


## assets/icons/User.svg

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-user">
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<path d="M8 7a4 4 0 1 0 8 0a4 4 0 0 0 -8 0" />
	<path d="M6 21v-2a4 4 0 0 1 4 -4h4a4 4 0 0 1 4 4v2" />
</svg>
```


## assets/icons.ts

```ts
const rawIcons = import.meta.glob('./icons/*.svg', {
    query: '?raw',
    import: 'default',
    eager: true,
}) as Record<string, string>;


export const ICONS: Record<string, string> = Object.keys(rawIcons).reduce((acc, filePath) => {
    const fileName = filePath
        .replace('./icons/', '')
        .replace('.svg', '');

    acc[fileName] = rawIcons[filePath];
    return acc;
}, {} as Record<string, string>);

export type IconName = keyof typeof ICONS;

```


## components/content/ContentHeader.astro

```astro
---
import type { DisplayMeta } from "../../types";

interface Props {
    title: string;
    meta?: DisplayMeta[];
}

const { title, meta = [] } = Astro.props;
---

<header class="page-header container-narrow">
    {title && <h1 class="page-title">{title}</h1>}
    {
        meta.length > 0 && (
            <div class="item-meta mt-6">
                {meta.map((item, index) => (
                    <span class="flex items-center">
                        {index > 0 && (
                            <span class="opacity-40 mx-2 text-xs">•</span>
                        )}
                        {item.datetime ? (
                            <time datetime={item.datetime}>{item.value}</time>
                        ) : (
                            <span>
                                {item.label && (
                                    <span class="opacity-60 font-medium">
                                        {item.label}:{" "}
                                    </span>
                                )}
                                <span class="font-bold">{item.value}</span>
                            </span>
                        )}
                    </span>
                ))}
            </div>
        )
    }
</header>

```


## components/content/ContentLinks.astro

```astro
---
import type { DisplayLink } from "../../types";

interface Props {
    links: DisplayLink[];
    className?: string;
}

const { links, className = "" } = Astro.props;
---

{
    links.length > 0 && (
        <div class={`item-links horizontal container-narrow ${className}`}>
            {links.map((link) => (
                <a
                    href={link.href}
                    target={link.external !== false ? "_blank" : undefined}
                    rel={
                        link.external !== false
                            ? "noopener noreferrer"
                            : undefined
                    }
                >
                    {link.label} &rarr;
                </a>
            ))}
        </div>
    )
}

```


## components/layout/Footer.astro

```astro
---
import { SITE, THEME_CONFIG, SETTINGS } from "../../config";
import Icon from "../ui/Icon.astro";

const currentYear = new Date().getFullYear();
const showToggle = THEME_CONFIG.lightAndDark;
const showDevTools = import.meta.env.DEV || SETTINGS.addDevToolsInProduction;
---

<footer class="footer">
    <div class="flex items-center gap-4">
        <span class="body-xs">&copy; {currentYear} {SITE.author}.</span>
    </div>
    <div class="flex items-center gap-4">
       
        <a
            href="/rss.xml"
            aria-label="RSS Feed"
            title="RSS Feed"
            target="_blank"
            rel="noreferrer"
            class="btn-icon"
        >
            <Icon name="RSS" size={16} />
        </a>
        {
            showToggle && (
                <button
                    id="theme-toggle"
                    aria-label="Toggle Dark Mode"
                    class="btn-icon"
                >
                    <Icon name="Sun" size={16} class="hidden dark:block" />
                    <Icon name="Moon" size={16} class="block dark:hidden" />
                </button>
            )
        }
        {
            showDevTools && (
                <a
                    href="/dev-tools"
                    aria-label="Developer Tools"
                    title="Developer Tools"
                    class="btn-icon"
                >
                    <Icon name="Settings" size={16} />
                </a>
            )
        }
    </div>
</footer>

```


## components/layout/LeftSidebar.astro

```astro
---
import { SITE, SOCIALS, SOCIAL_ICONS } from "../../config";
import { getCollection } from "astro:content";
import Icon from "../ui/Icon.astro";
import { Image } from 'astro:assets';

const activeSocials = SOCIALS.filter((s) => s.isActive);
const bioCollection = await getCollection("bio");
const bio = bioCollection[0]?.data;
---

<aside class="sidebar max-lg:flex-row max-lg:flex-wrap max-lg:gap-3 max-md:gap-2">
    <div class="flex flex-col items-center text-center max-lg:flex-row max-lg:text-left max-lg:gap-3 max-lg:items-center max-md:gap-2">
        {bio?.avatar && (
            <Image
                src={`/${bio.avatar}`}
                alt={`Avatar of ${bio.name}`}
                width={160} /* Maximum width in global.css for sidebar-avatar class */
                height={160}
                densities={[1.5, 2]} 
                format="webp"
                class="sidebar-avatar"
                loading="eager"
            />
        )}
        <div class="flex flex-col items-center max-lg:items-start">
            {bio?.name && <h1 class="sidebar-name">{bio.name}</h1>}
            {bio?.institution && (
                <p class="sidebar-info">
                    <Icon name="Institution" size={24} />
                    {bio.institution}
                </p>
            )}
            {bio?.shortBio && (
                <p class="sidebar-bio mt-2 max-md:hidden">{bio.shortBio}</p>
            )}
            <div class="flex gap-1 flex-wrap items-center justify-center max-lg:justify-start mt-3">
                {activeSocials.map((social) => (
                    <a
                        href={social.href}
                        aria-label={social.linkTitle}
                        title={social.linkTitle}
                        target="_blank"
                        rel="noreferrer"
                        class="social-link"
                    >
                        <Icon name={SOCIAL_ICONS[social.name] || social.name} size={24} />
                    </a>
                ))}
            </div>
        </div>
    </div>
</aside>

```


## components/layout/Navbar.astro

```astro
---
import { NAV_LINKS, PAGES } from "../../config";

const currentPath = Astro.url.pathname;
---

<nav class="navbar">
    <ul class="nav-links">
        {
            NAV_LINKS.filter((link) => {
                const isHome = link.href === "/";
                const pageKey = isHome
                    ? "home"
                    : link.href.split("/").filter(Boolean)[0];
                const pageConfig = (PAGES as any)[pageKey];
                return link.isActive !== false && pageConfig?.active !== false;
            }).map((link) => (
                <li>
                    <a
                        href={link.href}
                        class={`nav-link ${
                            currentPath === link.href ||
                            (link.href !== "/" &&
                                currentPath.startsWith(link.href))
                                ? "active"
                                : "inactive"
                        }`}
                    >
                        {link.label}
                        <span class="nav-link-line" />
                    </a>
                </li>
            ))
        }
    </ul>
</nav>

```


## components/layout/RightMain.astro

```astro
---
import Navbar from "./Navbar.astro";
import Footer from "./Footer.astro";
---

<div class="main-content">
    <Navbar />
    <div class="main-body animate-in">
        <slot />
    </div>
    <Footer />
</div>
```


## components/ui/BackLink.astro

```astro
---
interface Props {
    href: string;
    label: string;
}

const { href, label } = Astro.props;
---

<a href={href} class="back-link">
    Go back to {label}
</a>
```


## components/ui/BaseItemCard.astro

```astro
---
import Tag from "./Tag.astro";
import Icon from "./Icon.astro";

interface Props {
    title: string;
    href: string;
    description?: string;
    date?: string;
    authors?: string;
    extraInput?: string;
    tags?: string[];
    externalUrl?: string;
}

const { title, href, description, date, authors, extraInput, tags, externalUrl } = Astro.props;
---

<article class="card">
    <div class="card-content">
        <a href={href} class="card-title">{title}</a>

        <div class="card-meta">
            {date && (
                <span class="flex items-center gap-1">
                    <Icon name="Calendar" size={24} />
                    <span>{date}</span>
                </span>
            )}
            {authors && (
                <span class="flex items-center gap-1">
                    <Icon name="User" size={24} />
                    <span>{authors}</span>
                </span>
            )}
            {extraInput && (
                <span class="flex items-center gap-1">
                    <Icon name="Institution" size={24} />
                    <span>{extraInput}</span>
                </span>
            )}
        </div>

        {
            tags && tags.length > 0 && (
                <div class="flex gap-2 flex-wrap mb-3">
                    {tags.map((tag) => (
                        <Tag name={tag} size="sm" />
                    ))}
                </div>
            )
        }

        {description && <p class="card-desc">{description}</p>}
    </div>

    {
        externalUrl && (
            <div class="flex-shrink-0">
                <a href={externalUrl} target="_blank" rel="noopener noreferrer" class="card-link">
                    View
                </a>
            </div>
        )
    }
</article>
```


## components/ui/Icon.astro

```astro
---
import { ICONS, type IconName } from "../../assets/icons";

interface Props {
    name: IconName | string;
    size?: number | string;
    class?: string;
    strokeWidth?: number;
    id?: string;
}

const { name, size = 24, class: className, strokeWidth = 1.5, id } = Astro.props;
const iconContent = ICONS[name as IconName];
if (!iconContent) {
    throw new Error(
        `[Unknown Icon]: ${name}`
    )
}
---

{
    iconContent ? (
        <svg
            id={id}
            xmlns="http://www.w3.org/2000/svg"
            width={size}
            height={size}
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width={strokeWidth}
            stroke-linecap="round"
            stroke-linejoin="round"
            class={className}
            set:html={iconContent}
        />
    ) : (
        <span class="text-red-500 text-xs">[Icon Not Found: {name}]</span>
    )
}

```


## components/ui/ShareButtons.astro

```astro
---
import Icon from "./Icon.astro";

interface Props {
    title: string;
    url: string;
    description?: string;
}

const { title, url, description } = Astro.props;

const shareUrls = {
    twitter: `https://twitter.com/intent/tweet?text=${encodeURIComponent(title)}&url=${encodeURIComponent(url)}`,
    facebook: `https://www.facebook.com/sharer/sharer.php?u=${encodeURIComponent(url)}`,
    linkedin: `https://www.linkedin.com/sharing/share-offsite/?url=${encodeURIComponent(url)}`,
    email: `mailto:?subject=${encodeURIComponent(title)}&body=${encodeURIComponent(url)}`,
};
---

<div class="flex items-center gap-4 mt-8">
    <span class="body-sm font-semibold" style="opacity: 0.75;">Share:</span>
    <div class="flex gap-2">
        <a href={shareUrls.twitter} target="_blank" rel="noopener noreferrer" aria-label="Share on Twitter" class="icon-btn">
            <Icon name="Twitter" size={24} />
        </a>
        <a href={shareUrls.facebook} target="_blank" rel="noopener noreferrer" aria-label="Share on Facebook" class="icon-btn">
            <Icon name="Facebook" size={24} />
        </a>
        <a href={shareUrls.linkedin} target="_blank" rel="noopener noreferrer" aria-label="Share on LinkedIn" class="icon-btn">
            <Icon name="LinkedIn" size={24} />
        </a>
        <a href={shareUrls.email} aria-label="Share via Email" class="icon-btn">
            <Icon name="Mail" size={24} />
        </a>
    </div>
</div>
```


## components/ui/Tag.astro

```astro
---
interface Props {
    name: string;
    count?: number;
    size?: "sm" | "md" | "lg";
}

const { name, count, size = "md" } = Astro.props;

const sizeClasses = {
    sm: "text-xs",
    md: "text-sm",
    lg: "text-base",
};
---

<a href={`/tags/${name.toLowerCase()}`} class={`tag ${sizeClasses[size]}`}>
    #{name}
    {count !== undefined && <span class="opacity-60 ml-1">({count})</span>}
</a>
```


## components/ui/Timeline.astro

```astro
---
export interface TimelineItemData {
    title: string;
    period: string;
    subtitle: string;
    description?: string;
    thesis?: string;
}

interface Props {
    items: TimelineItemData[];
}

const { items } = Astro.props;
---

<div class="timeline flex flex-col">
    {
        items.map((item) => (
            <div class="timeline-item flex gap-8">
                <div class="timeline-marker flex flex-col items-center shrink-0">
                    <div class="dot w-3 h-3 rounded-full bg-accent mt-2 z-10" />
                    <div class="timeline-line flex-1 w-[2px] bg-border my-2" />
                </div>
                <div class="timeline-content pb-8 flex-1">
                    <div class="entry-header flex justify-between items-baseline gap-4 mb-1">
                        <h3 class="title-md transition-colors duration-200">
                            {item.title}
                        </h3>
                        <span class="body-sm font-semibold opacity-75 whitespace-nowrap">
                            {item.period}
                        </span>
                    </div>
                    <div class="body font-semibold opacity-90">
                        {item.subtitle}
                    </div>
                    {item.description && (
                        <div class="body mt-2">
                            {item.description}
                        </div>
                    )}
                    {item.thesis && (
                        <div class="body italic mt-2 opacity-80">
                            Thesis: {item.thesis}
                        </div>
                    )}
                </div>
            </div>
        ))
    }
</div>

```


## config/index.ts

```ts
export { SITE, THEME_CONFIG, SETTINGS, ANALYTICS } from "./site";
export { NAV_LINKS } from "./navigation";
export { SOCIALS, SOCIAL_ICONS } from "./social";
export { PAGES } from "./pages";
export { THEMES, type Theme, type ThemeName } from "./themes";
```


## config/navigation.ts

```ts
import type { NavLink } from "../types";

export const NAV_LINKS: NavLink[] = [
    { href: "/", label: "About", isActive: true },
    { href: "/publications", label: "Publications", isActive: true },
    { href: "/projects", label: "Projects", isActive: true },
    { href: "/cv", label: "CV", isActive: true },
];

```


## config/pages.ts

```ts
import type { PagesConfig } from "../types";

export const PAGES: PagesConfig = {
    home: {
        title: "About Me",
        subtitle: "Research Engineer in NLP & AI",
        isActive: true,
    },
    blog: {
        title: "Blog",
        subtitle: "Insights into AI, NLP, and Engineering.",
        isActive: true,
    },
    publications: {
        title: "Publications",
        subtitle: "Scientific articles in NLP and Text Processing.",
        isActive: true,
    },
    talks: {
        title: "Talks & Presentations",
        subtitle: "",
        isActive: false,
    },
    projects: {
        title: "Projects",
        subtitle: "Engineering and Research implementations.",
        isActive: true,
    },
    teaching: {
        title: "Teaching",
        subtitle: "",
        isActive: false,
    },
    tags: {
        title: "Tags",
        subtitle: "",
        isActive: false,
    },
    cv: {
        title: "Curriculum Vitae",
        subtitle: "Professional and Academic Journey",
        isActive: true,
    },
};

```


## config/site.ts

```ts
import type { SiteConfig, ThemeConfig, SettingsConfig, UmamiAnalyticsConfig, AnalyticsConfig } from "../types";

export const SITE: SiteConfig = {
    website: "https://aa-aliane.github.io/",
    author: "Aliane Amine",
    desc: "Personal portfolio of Aliane Amine, Research Engineer in Natural Language Processing.",
    title: "Aliane Amine",
    ogImage: "main_page.jpg",
    postPerPage: 5,
    favicon: "/favicon.svg",
    lang: "en",
};

export const THEME_CONFIG: ThemeConfig = {
    lightAndDark: true,
    themeLight: "light_default",
    themeDark: "dark_notepad",
};

export const SETTINGS: SettingsConfig = {
    showTagsInNavbar: true,
    showRSSInFooter: true,
    addDevToolsInProduction: true,
};

const umami: UmamiAnalyticsConfig = {
    websiteId: "", // e.g., 'xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx'
    src: "https://cloud.umami.is/script.js", // Default Umami cloud script URL
}

export const ANALYTICS: AnalyticsConfig = {
    // Google Analytics 4 Measurement ID (e.g., 'G-XXXXXXXXXX')
    ga4Id: "",
    // Umami Analytics configuration
    umami: umami
};

```


## config/social.ts

```ts
import type { SocialLink } from "../types";

export const SOCIALS: SocialLink[] = [
    {
        name: "Github",
        href: "https://github.com/aa-Aliane",
        linkTitle: `Follow Aliane Amine on Github`,
        isActive: true,
    },
    {
        name: "Mail",
        href: "mailto:aliane781@gmail.com",
        linkTitle: `Send an email to Aliane`,
        isActive: true,
    },
    {
        name: "Google Scholar",
        href: "https://scholar.google.com/",
        linkTitle: `Aliane Amine on Google Scholar`,
        isActive: false,
    },
    {
        name: "ORCID",
        href: "https://orcid.org/",
        linkTitle: `Aliane Amine on ORCID`,
        isActive: false,
    },
    {
        name: "LinkedIn",
        href: "https://www.linkedin.com/in/aliane-amine-032b77147/",
        linkTitle: `Aliane Amine on LinkedIn`,
        isActive: true,
    },
];

export const SOCIAL_ICONS: Record<string, string> = {
    Github: "Github",
    Mail: "Mail",
    Linkedin: "LinkedIn",
    "Google Scholar": "GoogleScholar",
    ORCID: "ORCID",
    RSS: "RSS",
};
```


## config/themes.ts

```ts
import type { Theme, ThemeColors, ThemeName } from "../types/themes";

export { type Theme, type ThemeName, type ThemeColors };

export const THEMES: Record<string, Theme> = {
  light_default: {
    background: "#f9fafb",
    foreground: "#111827",
    accent: "#3b82f6",
    muted: "#6b7280",
    border: "#e5e7eb",
    surface: "#f9fafb",
    isDark: false,
  },
  dark_default: {
    background: "#212737",
    foreground: "#eaedf3",
    accent: "#60a5fa",
    muted: "#343f60",
    border: "#ab4b08",
    surface: "#212737",
    isDark: true,
  },
  light_notepad: {
    isDark: false,
    background: "#fdf8e9",
    surface: "#fdf8e9",
    foreground: "#29231c",
    muted: "#736658",
    border: "#eaddc6",
    accent: "#b84c30",
  },
  dark_notepad: {
    isDark: true,
    background: "#241f1c",
    surface: "#241f1c",
    foreground: "#e6dfd3",
    muted: "#8a7d71",
    border: "#3d342d",
    accent: "#d97757",
  },
};

```


## content/posts/morphology.md

````md
---
title: "Morphology in NLP: From Language Families to Subword Algorithms"
date: "2026-05-23"
description: "A deep dive into how the morphological structure of human languages shapes the design of NLP systems — from classical rule-based methods to BPE and the frontiers of morphology-aware LLMs."
tags:
  - "NLP"
  - "Morphology"
  - "Tokenization"
  - "Low-Resource Languages"
  - "Transformers"
---

<!--
  ⚠️  LaTeX rendering note
  This post uses $...$ (inline) and $$...$$ (display) math notation.
  To enable rendering, install two packages:

    npm install remark-math rehype-katex

  Then in your astro.config.mjs:

    import remarkMath from 'remark-math';
    import rehypeKatex from 'rehype-katex';

    markdown: {
      remarkPlugins: [remarkMath],
      rehypePlugins: [rehypeKatex],
    }

  And add the KaTeX stylesheet to your base layout:
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.css" />

  Without these, the raw LaTeX source will be visible but the post is still readable.
-->

Morphology is the branch of linguistics that studies the internal structure of words: how they're formed, how they change, and what those changes mean. For NLP, it's not an academic curiosity. It shapes every step of the pipeline — from tokenization to generation — and understanding it deeply is one of the cleaner ways to separate systems that generalize from those that merely memorize.

This post starts with the typological map of world languages (why not all languages are equally "hard"), moves through classical and statistical morphological analysis, then lands on the algorithms powering modern tokenizers — BPE, WordPiece, Unigram — and closes on where the field is actively bleeding.[^survey]

---

## 1. The Morphological Spectrum of Human Languages

Linguists have long organized languages along a spectrum defined by how they encode grammatical information. The extremes are clean; most languages live somewhere in between.

### 1.1 Analytic (Isolating) Languages

In analytic languages, words tend to be invariant. Grammatical relationships are expressed through word order and separate function words, not through word-internal changes.

**Examples:** Mandarin Chinese, Vietnamese, Modern English (partially).

In Mandarin, the same word serves as noun, verb, or adjective depending on context; there are no verb conjugations and no plural suffixes. A sentence like _wǒ chī fàn_ ("I eat rice") uses three completely invariant units.

For NLP, analytic languages are in many ways the easiest case: a word is a word. Vocabulary coverage is high, and simple whitespace tokenization gets you surprisingly far.

### 1.2 Agglutinative Languages

Agglutinative languages build words by stacking morphemes together, where each morpheme carries a single, discrete meaning. The morpheme boundaries are relatively transparent — you can read a word like a compound molecule.

**Examples:** Turkish, Finnish, Swahili, Hungarian, Basque.

The canonical demonstration is Turkish:

| Form                      | Gloss                            |
| ------------------------- | -------------------------------- |
| `ev`                      | house                            |
| `ev-ler`                  | houses (plural)                  |
| `ev-ler-im`               | my houses                        |
| `ev-ler-im-de`            | in my houses                     |
| `ev-ler-im-de-ki`         | that which is in my houses       |
| `ev-ler-im-de-ki-ler-den` | from those that are in my houses |

The word `evlerindekilerden` is a single orthographic token but encodes what English would express with an entire prepositional phrase. A naïve word-level vocabulary over a Turkish corpus is an explosion — the same root generates thousands of surface forms.

### 1.3 Fusional (Inflectional) Languages

Fusional languages also modify words to express grammar, but unlike agglutinative languages, a single morpheme can carry _multiple_ grammatical features simultaneously — they are fused together and not cleanly separable.

**Examples:** Arabic, Russian, Latin, Greek, German, Spanish, French.

Consider the Latin ending _-ō_ in _amō_ ("I love"). That single suffix simultaneously encodes: first person, singular number, present tense, indicative mood, active voice. There is no way to decompose it into five independent morphemes.

Arabic is a particularly rich case. It uses a **root-and-pattern** (templatic) morphology: a consonantal root (usually three consonants) is intercalated with vowel patterns to produce a family of semantically related words:

| Root          | Pattern   | Form                  | Meaning  |
| ------------- | --------- | --------------------- | -------- |
| ك-ت-ب (k-t-b) | `CāCaC`   | كَتَبَ (_kataba_)     | he wrote |
| ك-ت-ب         | `CāCiC`   | كَاتِب (_kātib_)      | writer   |
| ك-ت-ب         | `maCCaCa` | مَكْتَبَة (_maktaba_) | library  |
| ك-ت-ب         | `CiCāC`   | كِتَاب (_kitāb_)      | book     |
| ك-ت-ب         | `CuCuC`   | كُتُب (_kutub_)       | books    |

This non-concatenative structure breaks the assumption of every standard subword tokenizer, which models morphology as linear concatenation.

### 1.4 Polysynthetic Languages

At the extreme end, polysynthetic languages can pack what amounts to a full sentence's worth of information into a single word.

**Examples:** Inuktitut, Mohawk, West Greenlandic.

The Inuktitut word _tusaatsiarunnanngittualuujunga_ translates roughly as "I can't hear very well." It is one word. This extreme degree of morphological complexity makes even the definition of "word" slippery, and vocabulary-based NLP approaches essentially don't work without morphological decomposition.

---

## 2. Why Morphology Matters for NLP Systems

The practical impact of morphological richness is felt everywhere:

**Vocabulary explosion.** For a fixed-size corpus, morphologically rich languages produce far more unique surface forms. A word-level model for Finnish or Arabic will suffer from severe data sparsity even on large corpora.

**Lemmatization difficulty.** Mapping _wrote_, _written_, _writes_, _writing_ to _write_ is trivial in English; doing the same for Arabic or Russian requires genuine morphological analysis.

**Out-of-vocabulary (OOV) generalization.** If a model has never seen _antiestablishmentarianism_ but knows _anti-_, _establish_, _-ment_, _-arian_, _-ism_ separately, it should be able to handle it. Pure word-level models cannot.

**Transfer learning.** When fine-tuning a pretrained language model on a morphologically rich low-resource language, the tokenizer's segmentation quality directly bounds model performance. A bad tokenizer cuts off morpheme boundaries mid-unit, producing meaningless subwords.

---

## 3. Classical Morphological Analysis

Before neural methods, morphological analyzers were carefully engineered, linguistically grounded systems.

### 3.1 Finite-State Transducers (FSTs)

The workhorse of classical computational morphology is the **Finite-State Transducer** — a finite automaton that maps one string to another. A morphological analyzer implemented as an FST maps a surface form (what you see in text) to a lemma+feature string (what the word means morphologically).

Formally, an FST is a 7-tuple:

$$\mathcal{T} = (Q, \Sigma, \Delta, \delta, q_0, F)$$

where $Q$ is a finite set of states, $\Sigma$ the input alphabet, $\Delta$ the output alphabet, $\delta: Q \times (\Sigma \cup \{\epsilon\}) \to 2^{Q \times (\Delta \cup \{\epsilon\})}$ the transition function, $q_0$ the initial state, and $F \subseteq Q$ the set of accepting states.

The elegance of FSTs is that they are **invertible**: the same transducer compiled in reverse generates all valid surface forms from a lemma+features specification. This gives you both analysis and generation for free.

Systems like the **Buckwalter Arabic Morphological Analyzer** (BAMA) and the IRSTLM-based tools for Turkish were FST-based and remained competitive for years. Their weakness: they require deep linguistic expertise to build and are brittle in the face of neologisms, foreign borrowings, and informal text (social media, dialects).

### 3.2 Rule-Based Stemming

Simpler than FSTs, stemmers apply heuristic suffix-stripping rules without attempting to produce linguistically accurate analyses. The Porter Stemmer for English is the classic example — it reduces _running_ → _run_, _happily_ → _happi_ (not a real word, but consistent). Fast and language-agnostic in spirit, but linguistically crude.

---

## 4. Statistical Morphological Segmentation

The middle ground between full linguistic FSTs and neural black boxes is unsupervised statistical segmentation: learning morpheme boundaries from raw text, without linguistic annotation.

### 4.1 Morfessor

**Morfessor** [^morfessor] is the canonical system in this space. It models the lexicon as a generative model over morpheme sequences and learns to segment words by optimizing the Minimum Description Length (MDL) criterion:

$$\mathcal{L}(\theta, D) = \mathcal{L}(\theta) + \mathcal{L}(D \mid \theta)$$

The first term penalizes a large morpheme lexicon; the second penalizes poor compression of the corpus. The system finds segmentations that are compact without being trivial (i.e., treating every character as a morpheme or every word as an atom).

Morfessor works reasonably well on agglutinative languages and was for years the recommended baseline for morpheme segmentation in the CoNLL shared tasks.

---

## 5. Subword Tokenization: The Neural Era

Modern NLP systems don't perform explicit morphological analysis — they use **subword tokenization** algorithms that learn a vocabulary of frequent character sequences from data, implicitly capturing morphological structure as a byproduct.

The three algorithms that matter are BPE, WordPiece, and Unigram Language Model.

### 5.1 Byte-Pair Encoding (BPE)

BPE[^bpe] was originally a data compression algorithm, adapted for NLP by Sennrich et al. in 2016 for Neural Machine Translation. It is now the backbone of GPT-2, GPT-4, LLaMA, and many others.

**The algorithm:**

1. Start with a vocabulary of individual characters (and a special end-of-word token `</w>`).
2. Count all adjacent symbol pair frequencies in the training corpus.
3. Merge the most frequent pair into a new symbol.
4. Repeat until the vocabulary reaches a target size $V$.

```python
from collections import Counter, defaultdict

def get_vocab(corpus: list[str]) -> dict[str, int]:
    """Convert corpus to character-level vocabulary with word counts."""
    vocab = Counter()
    for word in corpus:
        # Represent each word as space-separated characters with end marker
        vocab[' '.join(list(word)) + ' </w>'] += 1
    return vocab

def get_pairs(vocab: dict[str, int]) -> dict[tuple, int]:
    """Count all adjacent character-pair frequencies."""
    pairs = defaultdict(int)
    for word, freq in vocab.items():
        symbols = word.split()
        for i in range(len(symbols) - 1):
            pairs[(symbols[i], symbols[i + 1])] += freq
    return pairs

def merge_vocab(pair: tuple, vocab: dict[str, int]) -> dict[str, int]:
    """Merge the best pair across the entire vocabulary."""
    new_vocab = {}
    bigram = ' '.join(pair)
    replacement = ''.join(pair)
    for word in vocab:
        new_word = word.replace(bigram, replacement)
        new_vocab[new_word] = vocab[word]
    return new_vocab

def learn_bpe(corpus: list[str], num_merges: int) -> list[tuple]:
    vocab = get_vocab(corpus)
    merges = []
    for _ in range(num_merges):
        pairs = get_pairs(vocab)
        if not pairs:
            break
        best_pair = max(pairs, key=pairs.get)
        vocab = merge_vocab(best_pair, vocab)
        merges.append(best_pair)
    return merges

# Example
corpus = ["low", "lower", "lowest", "new", "newer", "newest", "wider", "wide"]
merges = learn_bpe(corpus, num_merges=10)
for merge in merges:
    print(f"Merged: {merge[0]} + {merge[1]} → {''.join(merge)}")
```

After training, a lookup table of merges is applied greedily at inference time. The vocabulary size $V$ is a hyperparameter controlling the granularity/coverage trade-off: small $V$ → more characters, more OOV robustness; large $V$ → more whole words, faster inference.

A key property: BPE naturally tends to keep common words intact (they appear as full tokens) while splitting rare words into recognizable pieces. The word `unhappiness` might become `un`, `happiness` or `un`, `happy`, `ness` depending on the training corpus.

**Complexity.** Each merge step is $O(|V|)$ pair counting; with $k$ merges and corpus size $N$, the full training run is $O(kN)$. In practice, efficient implementations (Hugging Face tokenizers) run in seconds on large corpora.

### 5.2 WordPiece

**WordPiece** is used by BERT, DistilBERT, and most of the Google family. The key difference from BPE: instead of merging the most _frequent_ pair, WordPiece merges the pair that maximally increases the likelihood of the training data under a language model:

$$\text{score}(A, B) = \frac{\text{freq}(AB)}{\text{freq}(A) \times \text{freq}(B)}$$

This is essentially a pointwise mutual information criterion. Pairs that are frequent but only because both parts are individually frequent (like `th` in English) score lower than pairs that co-occur specifically together. The result is a vocabulary that captures more linguistically meaningful units.

WordPiece also introduces the `##` prefix convention: subwords that appear word-internally are prefixed with `##` to signal they are continuations, not word-initial tokens. So `embedding` → `em`, `##bed`, `##ding`.

### 5.3 Unigram Language Model

**Unigram LM tokenization**[^unigram], used in SentencePiece (which powers T5, XLNet, mBART, and NLLB), takes a fundamentally different approach: instead of a _greedy merge_ procedure, it starts with a large candidate vocabulary and _prunes_ it.

The objective is to find the vocabulary $\mathcal{V}$ and segmentation probabilities $p(x)$ for each subword $x$ that maximize the likelihood of the corpus. For a word $W$ with candidate segmentations $\mathcal{S}(W)$:

$$P(W) = \sum_{s \in \mathcal{S}(W)} \prod_{x \in s} p(x)$$

The EM algorithm alternates between:

- **E-step:** Find the best segmentation for each word given current $p(x)$ using the Viterbi algorithm.
- **M-step:** Update $p(x)$ from the expected counts.

Pruning then removes the subwords whose removal causes the smallest drop in total corpus log-likelihood, iterating until the target vocabulary size is reached.

The advantage: Unigram LM supports **probabilistic segmentation** — at inference, you can sample from the distribution over segmentations rather than always taking the argmax. This acts as a data augmentation technique during training and improves robustness.

### 5.4 Comparison Summary

| Property         | BPE                | WordPiece             | Unigram LM          |
| ---------------- | ------------------ | --------------------- | ------------------- |
| Direction        | Bottom-up merges   | Bottom-up merges      | Top-down pruning    |
| Merge criterion  | Frequency          | PMI / likelihood gain | Log-likelihood loss |
| Segmentation     | Deterministic      | Deterministic         | Probabilistic       |
| OOV handling     | Character fallback | Character fallback    | Character fallback  |
| Used by          | GPT family, LLaMA  | BERT family           | T5, mBART, NLLB     |
| Speed (training) | Fast               | Fast                  | Slower (EM)         |

---

## 6. The Problem These Algorithms Don't Fully Solve

Subword tokenization is a pragmatic engineering solution, not a linguistic one. It works well for English and other analytic/mildly inflected languages. But it has known failure modes that become acute on morphologically rich languages.

**The Arabic problem.** Arabic words are often represented by a single orthographic token that encodes a conjunction, a preposition, a definite article, a stem, a subject agreement marker, and an object agreement marker. BPE will split this token, but the split is determined by corpus statistics, not morpheme boundaries. The resulting subwords may cross morpheme lines, fragmenting the semantic units the model needs to learn.

**The cliticization problem.** In many languages, clitics (words that attach phonologically to a host) are written without spaces. French _je l'ai vu_ (I saw him/it) already works fine because of the apostrophe — but Arabic and Hebrew clitic writing is spaced differently, and BPE has no way to know that the first character of a token is a clitic that should arguably be treated as a separate word.

**Vocabulary allocation.** A multilingual model trained on 100 languages with a 250K vocabulary (like NLLB-200) must partition that vocabulary across all languages. Morphologically rich low-resource languages end up with a tiny allocation, causing severe over-segmentation and consequently longer, more expensive sequences.

Empirically, the relationship between tokenization granularity and downstream task performance has been studied extensively. For low-resource MT, morpheme-aware tokenization consistently outperforms pure BPE when training data is below approximately 100K sentence pairs.

---

## 7. Current Research Directions

### 7.1 Morphology-Aware Tokenization

Several recent works attempt to inject linguistic knowledge back into subword tokenization:

- **MorphPiece** constrains BPE merges to respect morpheme boundaries detected by a morphological analyzer, producing subwords that align with morphemes rather than merely frequent n-grams.
- **Linguistically Motivated Vocabulary Reduction (LMVR)** uses morphological analysis to seed the initial vocabulary before running BPE, improving segmentation quality for Turkish and Arabic.

### 7.2 Character and Byte-Level Models

An alternative to subword tokenization is to operate directly at the character or byte level, eliminating the tokenization step entirely:

- **ByT5**[^byt5] (Byte-level T5) processes raw UTF-8 bytes. It is naturally robust to noise, spelling variation, and all morphological complexity. The cost: sequences are 3–5x longer, and attention over long sequences is expensive.
- **Charformer** introduces a Gradient-Based Subword Tokenization (GBST) module that learns soft subword boundaries end-to-end as part of training, rather than as a preprocessing step.

### 7.3 Morphological Probing of LLMs

A growing body of work probes pretrained LLMs for morphological knowledge using **probing classifiers** — lightweight linear models trained on top of frozen representations to predict morphological features (case, number, tense, etc.).

Results are nuanced: large models encode substantial morphological information in their representations even when trained on raw subword sequences. But the encoding is inconsistent across layers and languages, and it correlates with tokenization quality — models that receive better-segmented tokens learn better morphological representations.

### 7.4 Low-Resource Morphological Analysis with Neural Models

For languages where FSTs exist (Arabic, Turkish, Finnish), hybrid systems combining neural encoders with FST constraints are now state of the art. The neural component handles ambiguity resolution and dialectal variation; the FST constrains the output to the space of linguistically valid analyses.

For languages without FSTs — the vast majority of the world's 7,000+ languages — **cross-lingual transfer** is the primary strategy: training on related, higher-resource languages and fine-tuning on small annotated sets. The Universal Dependencies (UD) project has enabled this by providing morphologically annotated treebanks in a consistent schema across 100+ languages.

---

## 8. A Practical Takeaway

When you're building an NLP system for a new language, the first question to ask is not "which model architecture?" but "what is the morphological profile of this language?"

If it's analytic, standard tokenization with a modest vocabulary is probably fine. If it's agglutinative or fusional, you need to take morphology seriously — and that means thinking carefully about: vocabulary size, segmentation algorithm choice, whether a morphological analyzer exists and is worth integrating, and whether your evaluation data appropriately reflects morphological diversity (i.e., includes rare inflectional forms, not just frequent lemmas).

Morphology is where the gap between "works on the benchmark" and "works in the wild" is largest. Building systems that respect it isn't academic purism — it's good engineering.

---

## References

[^survey]: Nikolaev, D. et al. (2023). _A Survey of Morphological Analysis for Low-Resource Languages_. ACL Anthology.

[^bpe]: Sennrich, R., Haddow, B., & Birch, A. (2016). _Neural Machine Translation of Rare Words with Subword Units_. ACL 2016. [arXiv:1508.07909](https://arxiv.org/abs/1508.07909)

[^morfessor]: Creutz, M., & Lagus, K. (2002). _Unsupervised Discovery of Morphemes_. Morphological and Phonological Learning Workshop, ACL 2002.

[^unigram]: Kudo, T. (2018). _Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates_. ACL 2018. [arXiv:1804.10959](https://arxiv.org/abs/1804.10959)

[^byt5]: Xue, L. et al. (2022). _ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models_. TACL 2022. [arXiv:2105.13626](https://arxiv.org/abs/2105.13626)

````


## content/posts/welcome.md

```md
---
title: "Welcome to my Academic Portfolio"
date: "2026-05-22"
description: "A brief introduction to my new personal website and what I'll be sharing here."
tags:
  - "Personal"
  - "Portfolio"
---

Welcome to my new personal portfolio! 

As a **Scientific Research Engineer** specializing in **Natural Language Processing**, I wanted a space to showcase my research, publications, and engineering projects. 

In this blog, I plan to share insights about:
- Recent advancements in NLP and Large Language Models.
- Challenges and solutions in low-resource language processing (specifically Arabic).
- Bridge building between research and production-ready software.
- Infrastructure and DevOps for AI research.

Stay tuned for more updates!

```


## content/projects/arabic-sentiment-transformers.md

```md
---
title: "Arabic Sentiment Analysis with Transformers"
description: "Transformer-based sentiment classification for Arabic text (MSA and dialectal), built at CERIST using BERT and AraBERT."
tags:
  - "NLP"
  - "Transformers"
  - "Hugging Face"
  - "Sentiment Analysis"
  - "Python"
image: "/images/placeholder.svg"
---

## Project Overview

Built high-accuracy sentiment classification models for Arabic text at CERIST, using transformer architectures (BERT, AraBERT, mBERT) via Hugging Face. The project targeted both Modern Standard Arabic and dialectal Arabic, which behave very differently under standard tokenization and required separate evaluation.

## Technical Details

- **Architectures**: BERT, AraBERT, mBERT, compared against classical ML baselines (SVM, logistic regression on TF-IDF features).
- **Frameworks**: PyTorch, Hugging Face Transformers.
- **Data**: [Add dataset name/size, e.g. "labeled dataset of X tweets/reviews across positive/negative/neutral classes"].
- **Evaluation**: Accuracy and F1 compared across architectures and against traditional baselines, with error analysis on dialectal variation.

## Challenges

Arabic's morphological richness and the frequent code-switching in dialectal text (Arabic mixed with French/English) made standard tokenization approaches underperform. AraBERT's Arabic-specific pretraining gave a measurable advantage over general multilingual BERT for this reason.

## Outcome

Improved classification accuracy compared to traditional machine learning baselines. [Replace with your actual number, e.g. "X% F1, a Y point improvement over the SVM baseline."]

## My Role

Designed the experimental setup, fine-tuned the transformer models, and ran the comparative evaluation against classical baselines.

```


## content/projects/fake-news-detection.md

```md
---
title: "Fake News Detection System"
description: "A system combining semantic representation and deep classification models to identify misinformation."
tags:
  - "NLP"
  - "Deep Learning"
  - "Security"
  - "Python"
image: "/images/placeholder.svg"
---

## Project Overview

Development of systems to detect fake news by combining advanced semantic representations with deep learning classification models.

## Key Features

- **Semantic Embedding**: Using word and sentence embeddings for rich text representation.
- **Classification**: Implementing deep neural networks to distinguish between credible and fake information.
- **Evaluation**: Rigorous testing on curated datasets of news articles.

```


## content/projects/research-infrastructure.md

```md
---
title: "Research Infrastructure & APIs"
description: "Implementation of REST APIs and web interfaces to expose and visualize research results."
tags:
  - "Full Stack"
  - "FastAPI"
  - "React"
  - "Docker"
image: "/images/placeholder.svg"
---

## Overview

Building the bridge between research models and end-users through robust APIs and interactive web interfaces.

## Engineering Stack

- **Backend**: FastAPI, Django REST Framework.
- **Frontend**: React, TypeScript.
- **Infrastructure**: Docker for production deployment, PostgreSQL and MongoDB for data management.
- **DevOps**: Administration of GPU workstations for deep learning training.

```


## content.config.ts

```ts
import { defineCollection } from 'astro:content';
import { glob } from 'astro/loaders';
import { z } from 'zod';

const publications = defineCollection({
    loader: glob({ pattern: "**/*.md", base: "./src/content/publications" }),
    schema: z.object({
        title: z.string(),
        author: z.string().optional(),
        date: z.string().optional(),
        journal: z.string().optional(),
        external_url: z.string().optional(),
        image: z.string().optional(),
        description: z.string().optional(),
        tags: z.array(z.string()).optional(),
    }),
});

const talks = defineCollection({
    loader: glob({ pattern: "**/*.md", base: "./src/content/talks" }),
    schema: z.object({
        title: z.string(),
        date: z.string().optional(),
        event: z.string().optional(),
        external_url: z.string().optional(),
        description: z.string().optional(),
        tags: z.array(z.string()).optional(),
        image: z.string().optional(),
    }),
});

const posts = defineCollection({
    loader: glob({ pattern: "**/*.md", base: "./src/content/posts" }),
    schema: z.object({
        title: z.string(),
        date: z.string().optional(),
        description: z.string().optional(),
        author: z.string().optional(),
        tags: z.array(z.string()).optional(),
        external_url: z.string().optional(),
        image: z.string().optional(),
    }),
});

const teaching = defineCollection({
    loader: glob({ pattern: "**/*.md", base: "./src/content/teaching" }),
    schema: z.object({
        title: z.string(),
        institution: z.string().optional(),
        description: z.string().optional(),
        tags: z.array(z.string()).optional(),
        external_url: z.string().url().optional(),
    }),
});

const bio = defineCollection({
    loader: glob({ pattern: "bio.md", base: "./src/content" }),
    schema: z.object({
        name: z.string(),
        avatar: z.string(),
        shortBio: z.string().optional(),
        institution: z.string().optional(),
    }),
});

const projects = defineCollection({
    loader: glob({ pattern: "**/*.md", base: "./src/content/projects" }),
    schema: z.object({
        title: z.string(),
        description: z.string().optional(),
        tags: z.array(z.string()).optional(),
        external_url: z.string().optional(),
        image: z.string().optional(),
    }),
});

const cv = defineCollection({
    loader: glob({ pattern: "cv.md", base: "./src/content" }),
    schema: z.object({
        name: z.string(),
        title: z.string(),
        experience: z.array(z.object({
            role: z.string(),
            institution: z.string(),
            period: z.string(),
            description: z.string(),
        })).optional(),
        education: z.array(z.object({
            degree: z.string(),
            institution: z.string(),
            period: z.string(),
            thesis: z.string().optional(),
            description: z.string().optional(),
        })).optional(),
    }),
});

export const collections = {
    'publications': publications,
    'talks': talks,
    'posts': posts,
    'bio': bio,
    'projects': projects,
    'cv': cv,
    'teaching': teaching,
};

```


## layouts/BaseDetail.astro

```astro
---
import { getEntry, render } from "astro:content";
import BaseLayout from "./BaseLayout.astro";
import BackLink from "../components/ui/BackLink.astro";
import Tag from "../components/ui/Tag.astro";
import Icon from "../components/ui/Icon.astro";
import { getDetailItem } from "../utils/adapters";
import { SITE } from "../config";

interface Props {
    collection: "publications" | "talks" | "projects" | "posts" | "teaching";
    id: string;
}

const { collection, id } = Astro.props;
const entry = (await getEntry(collection, id)) as any;

if (!entry) return Astro.redirect("/404");

const { Content } = await render(entry);
const detail = getDetailItem(entry, collection);

const meta = [];
if (detail.date) meta.push({ label: "Date", value: detail.date, icon: "Calendar" });
if (detail.authors) meta.push({ label: "Author", value: detail.authors, icon: "User" });
if (detail.extraInput) {
    const icon = "Institution";
    const label = collection === "publications" ? "Journal" : collection === "talks" ? "Event" : collection === "teaching" ? "Institution" : "Info";
    meta.push({ label, value: detail.extraInput, icon });
}

const description = entry.data.description || detail.description || SITE.desc;
const ogImage = entry.data.image || SITE.ogImage;
---

<BaseLayout title={detail.title} description={description} ogImage={ogImage} ogType="article">
    <div class="flex justify-between items-center mb-4">
        <BackLink href={detail.backHref} label={collection} />
        {detail.externalUrl && (
            <a href={detail.externalUrl} target="_blank" rel="noopener noreferrer" class="link">
                View external
            </a>
        )}
    </div>

    <article>
        <h1 class="page-title mb-4">{detail.title}</h1>

        {meta.length > 0 && (
            <div class="card-meta mb-4">
                {meta.map((m: any) => (
                    <span class="flex items-center gap-1">
                        <Icon name={m.icon} size={14} />
                        <span>{m.value}</span>
                    </span>
                ))}
            </div>
        )}

        {detail.tags && detail.tags.length > 0 && (
            <div class="flex gap-2 flex-wrap mb-4">
                {detail.tags.map((tag: string) => (
                    <Tag name={tag} size="sm" />
                ))}
            </div>
        )}

        <div class="prose">
            <Content />
        </div>

        <slot name="share" />
        <slot name="footer" />
    </article>
</BaseLayout>
```


## layouts/BaseLayout.astro

```astro
---
import { SITE, THEME_CONFIG, ANALYTICS, THEMES } from "../config";
import { ClientRouter } from "astro:transitions";
import LeftSidebar from "../components/layout/LeftSidebar.astro";
import RightMain from "../components/layout/RightMain.astro";
import "@fontsource/inter/400.css";
import "@fontsource/inter/500.css";
import "@fontsource/inter/600.css";
import "@fontsource/inter/700.css";
import "@fontsource/inter/800.css";
import "@fontsource/jetbrains-mono/400.css";
import "@fontsource/jetbrains-mono/500.css";
import "katex/dist/katex.min.css";
import "../styles/global.css";

const themeLightKey = (THEME_CONFIG.themeLight.startsWith('light_') ? THEME_CONFIG.themeLight : `light_${THEME_CONFIG.themeLight}`) as keyof typeof THEMES;
const themeDarkKey = (THEME_CONFIG.themeDark.startsWith('dark_') ? THEME_CONFIG.themeDark : `dark_${THEME_CONFIG.themeDark}`) as keyof typeof THEMES;

const themeLight = THEMES[themeLightKey] || THEMES.light_default;
const themeDark = THEMES[themeDarkKey] || THEMES.dark_default;

interface Props {
    title: string;
    description?: string;
    ogImage?: string;
    ogType?: "website" | "article";
    robots?: "index, follow" | "noindex, nofollow";
}

const {
    title,
    description = SITE.desc,
    ogImage = SITE.ogImage,
    ogType = "website",
    robots = "index, follow"
} = Astro.props;

const canonicalURL = new URL(Astro.url.pathname, Astro.site || SITE.website);

const jsonLd = {
    "@context": "https://schema.org",
    "@type": "Person",
    name: SITE.author,
    url: SITE.website,
    jobTitle: "Professor",
    description: SITE.desc,
};
---

<!doctype html>
<html lang={SITE.lang}>
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width" />
        <link rel="icon" type="image/svg+xml" href={SITE.favicon} />
        <link rel="icon" href="/favicon.ico" sizes="any" />
        <meta name="generator" content={Astro.generator} />

        <!-- Robots / Indexing -->
        <meta name="robots" content={robots} />

        <style
            is:global
            define:vars={{
                lightBg: themeLight.background,
                lightFg: themeLight.foreground,
                lightAccent: themeLight.accent,
                lightMuted: themeLight.muted,
                lightBorder: themeLight.border,
                lightSurface: themeLight.surface,

                darkBg: themeDark.background,
                darkFg: themeDark.foreground,
                darkAccent: themeDark.accent,
                darkMuted: themeDark.muted,
                darkBorder: themeDark.border,
                darkSurface: themeDark.surface,
            }}
        >
            :root {
                --background: var(--lightBg);
                --foreground: var(--lightFg);
                --accent: var(--lightAccent);
                --text-muted: var(--lightMuted);
                --border: var(--lightBorder);
                --surface: var(--lightSurface);
                scrollbar-gutter: stable;
            }

            [data-theme="dark"] {
                --background: var(--darkBg);
                --foreground: var(--darkFg);
                --accent: var(--darkAccent);
                --text-muted: var(--darkMuted);
                --border: var(--darkBorder);
                --surface: var(--darkSurface);
            }
        </style>

        <!-- Canonical URL -->
        <link rel="canonical" href={canonicalURL} />

        <!-- General Meta Tags -->
        <title>{title} | {SITE.title}</title>
        <meta name="title" content={`${title} | ${SITE.title}`} />
        <meta name="description" content={description} />
        <meta name="author" content={SITE.author} />

        <!-- Open Graph / Facebook -->
        <meta property="og:type" content={ogType} />
        <meta property="og:url" content={Astro.url} />
        <meta property="og:title" content={title} />
        <meta property="og:description" content={description} />
        <meta property="og:image" content={new URL(ogImage, Astro.url)} />

        <!-- Twitter -->
        <meta property="twitter:card" content="summary_large_image" />
        <meta property="twitter:url" content={Astro.url} />
        <meta property="twitter:title" content={title} />
        <meta property="twitter:description" content={description} />
        <meta property="twitter:image" content={new URL(ogImage, Astro.url)} />

        <!-- Structured Data (JSON-LD) -->
        <script type="application/ld+json" set:html={JSON.stringify(jsonLd)} />

        <ClientRouter />

        {
            (ANALYTICS.umami.websiteId || ANALYTICS.ga4Id) && (
                <script is:inline define:vars={{
                    umamiId: ANALYTICS.umami.websiteId,
                    umamiSrc: ANALYTICS.umami.src,
                    ga4Id: ANALYTICS.ga4Id
                }}>
                    let analyticsLoaded = false;
                    const loadAnalytics = () => {
                        if (analyticsLoaded) return;
                        analyticsLoaded = true;

                        if (umamiId && umamiSrc) {
                            const script = document.createElement('script');
                            script.src = umamiSrc;
                            script.defer = true;
                            script.setAttribute('data-website-id', umamiId);
                            document.head.appendChild(script);
                        }

                        if (ga4Id) {
                            const script1 = document.createElement('script');
                            script1.src = 'https://www.googletagmanager.com/gtag/js?id=' + ga4Id;
                            script1.async = true;
                            document.head.appendChild(script1);

                            window.dataLayer = window.dataLayer || [];
                            window.gtag = function(){window.dataLayer.push(arguments);}
                            window.gtag('js', new Date());
                            window.gtag('config', ga4Id);

                            document.addEventListener('astro:page-load', () => {
                                window.gtag('config', ga4Id, {
                                    page_path: window.location.pathname,
                                });
                            });
                        }
                    };

                    ['scroll', 'click', 'mousemove', 'touchstart', 'keydown'].forEach(event => {
                        window.addEventListener(event, loadAnalytics, { once: true, passive: true });
                    });
                    setTimeout(loadAnalytics, 5000); // Fallback
                </script>
            )
        }
        <script is:inline>
            function setTheme() {
                const theme = (() => {
                    if (
                        typeof localStorage !== "undefined" &&
                        localStorage.getItem("theme")
                    ) {
                        return localStorage.getItem("theme");
                    }
                    if (
                        window.matchMedia("(prefers-color-scheme: dark)")
                            .matches
                    ) {
                        return "dark";
                    }
                    return "light";
                })();

                document.documentElement.setAttribute("data-theme", theme);
                localStorage.setItem("theme", theme);
            }

            setTheme();
            document.addEventListener("astro:after-swap", setTheme);

            function initToggle() {
                const toggle = document.getElementById("theme-toggle");
                if (toggle) {
                    toggle.addEventListener("click", () => {
                        const current =
                            document.documentElement.getAttribute("data-theme");
                        const next = current === "dark" ? "light" : "dark";
                        document.documentElement.setAttribute(
                            "data-theme",
                            next,
                        );
                        localStorage.setItem("theme", next);
                    });
                }
            }

            document.addEventListener("astro:page-load", initToggle);
        </script>
    </head>
    <body
        class="bg-background text-foreground transition-colors duration-300 min-h-screen"
    >
        <div class="flex max-lg:flex-col mx-auto max-w-6xl w-full min-h-screen">
            <LeftSidebar />
            <RightMain>
                <slot />
            </RightMain>
        </div>
    </body>
</html>

```


## layouts/BaseListing.astro

```astro
---
import { getCollection } from "astro:content";
import BaseLayout from "../layouts/BaseLayout.astro";
import BaseItemCard from "../components/ui/BaseItemCard.astro";
import { getListingItem } from "../utils/adapters";

interface Props {
    collection: "publications" | "talks" | "projects" | "posts" | "teaching" | "all";
    title: string;
    subtitle?: string;
    entries?: any[];
    page?: any;
}

const { collection, title, subtitle, entries: manualEntries, page } = Astro.props;

let entries = manualEntries || (collection !== "all" ? await getCollection(collection as any) : []);
if (page) entries = page.data;

const sortedEntries = entries.sort((a: any, b: any) => {
    const dateA = a.data.date ? new Date(a.data.date).getTime() : 0;
    const dateB = b.data.date ? new Date(b.data.date).getTime() : 0;
    return dateB - dateA;
});
---

<BaseLayout title={title}>
    {(title || subtitle) && (
        <header class="page-header">
            {title && <h1 class="page-title">{title}</h1>}
            {subtitle && <p class="page-subtitle">{subtitle}</p>}
        </header>
    )}

    <section class="item-list">
        {sortedEntries.map((entry: any) => {
            const item = getListingItem(entry);
            return <BaseItemCard {...item} href={`/${collection}/${entry.id}`} />;
        })}
    </section>

    {page && page.lastPage > 1 && (
        <nav class="pagination">
            {page.url.prev ? (
                <a href={page.url.prev} class="pagination-link">Newer</a>
            ) : (
                <span class="pagination-inactive">Newer</span>
            )}
            <span class="pagination-info">Page {page.currentPage} of {page.lastPage}</span>
            {page.url.next ? (
                <a href={page.url.next} class="pagination-link">Older</a>
            ) : (
                <span class="pagination-inactive">Older</span>
            )}
        </nav>
    )}
</BaseLayout>

```


## layouts/DevToolsLayout.astro

```astro
---
import { SITE, THEME_CONFIG, THEMES } from "../config";
import { ClientRouter } from "astro:transitions";
import "@fontsource/inter/400.css";
import "@fontsource/inter/500.css";
import "@fontsource/inter/600.css";
import "@fontsource/inter/700.css";
import "@fontsource/inter/800.css";
import "@fontsource/jetbrains-mono/400.css";
import "@fontsource/jetbrains-mono/500.css";
import "../styles/global.css";

interface Props {
    title: string;
    description?: string;
}

const { title, description } = Astro.props;

const themeLightKey = (THEME_CONFIG.themeLight.startsWith('light_') ? THEME_CONFIG.themeLight : `light_${THEME_CONFIG.themeLight}`) as keyof typeof THEMES;
const themeDarkKey = (THEME_CONFIG.themeDark.startsWith('dark_') ? THEME_CONFIG.themeDark : `dark_${THEME_CONFIG.themeDark}`) as keyof typeof THEMES;

const themeLight = THEMES[themeLightKey] || THEMES.light_default;
const themeDark = THEMES[themeDarkKey] || THEMES.dark_default;
---

<!doctype html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width" />
        <link rel="icon" type="image/svg+xml" href={SITE.favicon} />
        <link rel="icon" href="/favicon.ico" sizes="any" />
        <title>{title} | Dev Tools</title>
        <meta name="description" content={description || "Development internal tools."} />
        <meta name="robots" content="noindex, nofollow" />

        <style
            is:global
            define:vars={{
                lightBg: themeLight.background,
                lightFg: themeLight.foreground,
                lightAccent: themeLight.accent,
                lightMuted: themeLight.muted,
                lightBorder: themeLight.border,
                lightSurface: themeLight.surface,

                darkBg: themeDark.background,
                darkFg: themeDark.foreground,
                darkAccent: themeDark.accent,
                darkMuted: themeDark.muted,
                darkBorder: themeDark.border,
                darkSurface: themeDark.surface,
            }}
        >
            :root {
                --background: var(--lightBg);
                --foreground: var(--lightFg);
                --accent: var(--lightAccent);
                --text-muted: var(--lightMuted);
                --border: var(--lightBorder);
                --surface: var(--lightSurface);
                scrollbar-gutter: stable;
            }

            [data-theme="dark"] {
                --background: var(--darkBg);
                --foreground: var(--darkFg);
                --accent: var(--darkAccent);
                --text-muted: var(--darkMuted);
                --border: var(--darkBorder);
                --surface: var(--darkSurface);
            }
        </style>

        <ClientRouter />

        <script is:inline define:vars={{ allowDark: THEME_CONFIG.lightAndDark }}>
            function setTheme() {
                const theme = (() => {
                    if (!allowDark) return "light";
                    if (
                        typeof localStorage !== "undefined" &&
                        localStorage.getItem("theme")
                    ) {
                        return localStorage.getItem("theme");
                    }
                    if (
                        window.matchMedia("(prefers-color-scheme: dark)")
                            .matches
                    ) {
                        return "dark";
                    }
                    return "light";
                })();

                document.documentElement.setAttribute("data-theme", theme);
                if (allowDark) {
                    localStorage.setItem("theme", theme);
                }
            }

            setTheme();
            document.addEventListener("astro:after-swap", setTheme);
        </script>
    </head>
    <body class="bg-background text-foreground transition-colors duration-300 min-h-screen p-10">
        <div class="max-w-[1600px] mx-auto">
            <header class="mb-12 flex justify-between items-end border-b border-border pb-8">
                <div>
                    <h1 class="text-4xl font-extrabold tracking-tight">
                        {title}
                    </h1>
                    {description && <p class="text-lg opacity-60 mt-2">{description}</p>}
                </div>
                <div class="flex gap-4 items-center">
                    <a href="/dev-tools" class="font-semibold text-sm transition-colors duration-200 hover:text-accent">Dev Tools Menu</a>
                    <span class="opacity-30">|</span>
                    <a href="/" class="font-semibold text-sm transition-colors duration-200 hover:text-accent">Live Site &rarr;</a>
                </div>
            </header>

            <slot />
        </div>
    </body>
</html>

```


## pages/projects/[id].astro

```astro
---
import { getCollection } from "astro:content";
import BaseDetail from "../../layouts/BaseDetail.astro";
import { PAGES } from "../../config";

if (PAGES.projects.isActive === false) {
    return Astro.redirect("/404");
}

export async function getStaticPaths() {
    if (PAGES.projects.isActive === false) return [];
    const projects = await getCollection("projects");
    return projects.map((project: any) => ({
        params: { id: project.id },
        props: { project },
    }));
}

const { id } = Astro.params;
---

<BaseDetail collection="projects" id={id} />

```


## pages/projects/index.astro

```astro
---
import BaseListing from "../../layouts/BaseListing.astro";
import { PAGES } from "../../config";

if (PAGES.projects.isActive === false) {
    return Astro.redirect("/404");
}
---

<BaseListing
    title={PAGES.projects.title}
    subtitle={PAGES.projects.subtitle}
    collection="projects"
/>

```


## pages/rss.xml.ts

```ts
import rss from "@astrojs/rss";
import { getCollection } from "astro:content";
import { SITE, PAGES } from "../config";

export async function GET(context: any) {
    const posts = PAGES.blog.isActive !== false ? await getCollection("posts") : [];
    const publications = PAGES.publications.isActive !== false ? await getCollection("publications") : [];

    const items = [
        ...posts.map((post: any) => ({
            title: post.data.title,
            pubDate: post.data.date,
            description: post.data.description,
            link: `/posts/${post.id}/`,
        })),
        ...publications.map((pub: any) => ({
            title: `[Publication] ${pub.data.title}`,
            pubDate: pub.data.date,
            description: pub.data.description || `Published in ${pub.data.journal || 'Journal'}`,
            link: `/publications/${pub.id}/`,
        })),
    ].sort((a, b) => new Date(b.pubDate).getTime() - new Date(a.pubDate).getTime());

    return rss({
        title: SITE.title,
        description: SITE.desc,
        site: context.site || SITE.website,
        items,
    });
}

```


## styles/global.css

```css
@import "tailwindcss";

@custom-variant dark (&:where([data-theme=dark], [data-theme=dark] *));

/* ===========================================
   UNIFIED VISUAL IDENTITY SYSTEM
   Based on DESIGN-GUIDE.md principles
   =========================================== */

@theme {
    --color-background: var(--background);
    --color-foreground: var(--foreground);
    --color-accent: var(--accent);
    --color-sidebar-bg: var(--sidebar-bg);
    --color-border: var(--border);
    --color-text-muted: var(--text-muted);
    --color-surface: var(--surface);
}

/* --- Theme Variables --- */
:root,
html[data-theme="light"] {
    --sidebar-bg: var(--background);
}

html[data-theme="dark"],
html.dark {
    --sidebar-bg: var(--background);
}

html {
    font-family: "Inter", system-ui, sans-serif;
    scroll-behavior: smooth;
}

body {
    margin: 0;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

/* ===========================================
   TYPOGRAPHY SYSTEM
   =========================================== */

/* Headings */
h1,
.title-xl {
    font-size: 1.5rem;
    font-weight: 800;
    letter-spacing: -0.02em;
    line-height: 1.2;
    color: var(--foreground);
}

h2,
.title-lg {
    font-size: 1.25rem;
    font-weight: 700;
    letter-spacing: -0.01em;
    line-height: 1.3;
    color: var(--foreground);
}

h3,
.title-md {
    font-size: 1.1rem;
    font-weight: 700;
    line-height: 1.4;
    color: var(--foreground);
}

/* Body Text */
p,
.body {
    font-size: 0.95rem;
    line-height: 1.65;
    color: var(--foreground);
    opacity: 0.92;
}

.body-sm {
    font-size: 0.85rem;
    line-height: 1.5;
    color: var(--foreground);
    opacity: 0.85;
}

.body-xs {
    font-size: 0.75rem;
    line-height: 1.4;
    color: var(--foreground);
    opacity: 0.75;
}

/* Mono (code, tags) */
code,
.mono {
    font-family: "JetBrains Mono", monospace;
    font-size: 0.85rem;
    font-weight: 500;
    line-height: 1.5;
}

/* Links */
a,
.link {
    color: inherit;
    text-decoration: underline;
    text-underline-offset: 4px;
    font-weight: 600;
    transition:
        color 0.2s ease,
        opacity 0.2s ease;
}

/* Global Lists */
ul {
    list-style-type: disc;
    margin-bottom: 1rem;
    padding-left: 1.5rem;
}

ol {
    list-style-type: decimal;
    margin-bottom: 1rem;
    padding-left: 1.5rem;
}

li {
    margin-bottom: 0.5rem;
}

ul li::marker {
    color: var(--accent);
}

a:hover,
.link:hover {
    color: var(--accent);
    opacity: 1;
}

/* ===========================================
   LAYOUT & SPACING
   =========================================== */

.container-narrow {
    max-width: 800px;
    margin: 0;
}

.container-full {
    max-width: none;
}

/* Spacing scale */
.space-y-1 {
    margin-bottom: 0.5rem;
}

.space-y-2 {
    margin-bottom: 1rem;
}

.space-y-3 {
    margin-bottom: 1.5rem;
}

.space-y-4 {
    margin-bottom: 2rem;
}

.mt-4 {
    margin-top: 1rem;
}

.mt-8 {
    margin-top: 2rem;
}

.mb-2 {
    margin-bottom: 0.5rem;
}

.mb-4 {
    margin-bottom: 1rem;
}

.mb-8 {
    margin-bottom: 2rem;
}

.pt-4 {
    padding-top: 1rem;
}

.pt-8 {
    padding-top: 2rem;
}

.pb-4 {
    padding-bottom: 1rem;
}

.pb-8 {
    padding-bottom: 2rem;
}

.gap-1 {
    gap: 0.5rem;
}

.gap-2 {
    gap: 1rem;
}

.gap-3 {
    gap: 1.5rem;
}

.gap-4 {
    gap: 2rem;
}

/* ===========================================
   COMPONENT CLASSES
   =========================================== */

/* Card (list items) */
.card {
    padding: 1rem 0;
}

.card-title {
    font-size: 1.25rem;
    font-weight: 700;
    line-height: 1.3;
    letter-spacing: -0.01em;
    text-decoration: none;
    color: var(--foreground);
    display: block;
    margin-bottom: 0.5rem;
    transition: color 0.2s ease;
}

.card-title:hover {
    color: var(--accent);
    text-decoration: underline;
}

.card-meta {
    font-size: 0.85rem;
    font-weight: 500;
    color: var(--foreground);
    opacity: 0.75;
    display: flex;
    gap: 0.75rem;
    align-items: center;
    flex-wrap: wrap;
    margin-bottom: 0.75rem;
}

.card-desc {
    font-size: 0.9rem;
    color: var(--foreground);
    opacity: 0.8;
    line-height: 1.5;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;
}

.card-link {
    font-size: 0.85rem;
    font-weight: 700;
    color: var(--foreground);
    white-space: nowrap;
    transition: color 0.2s ease;
}

.card-link:hover {
    color: var(--accent);
    text-decoration: underline;
}

/* Tags/Badges */
.tag {
    display: inline-flex;
    align-items: center;
    color: var(--accent);
    font-size: 0.8rem;
    font-weight: 700;
    line-height: 1;
    text-decoration: none;
    transition: opacity 0.2s ease;
}

.tag:hover {
    opacity: 1;
    text-decoration: underline;
}

/* Buttons */
.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.5rem 1rem;
    font-weight: 600;
    font-size: 0.9rem;
    border: 1px solid var(--border);
    border-radius: 0.25rem;
    background: transparent;
    color: var(--foreground);
    transition: all 0.2s ease;
    text-decoration: none;
}

.btn:hover {
    border-color: var(--accent);
    color: var(--accent);
}

.btn-sm {
    padding: 0.25rem 0.75rem;
    font-size: 0.8rem;
}

.btn-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 32px;
    height: 32px;
    border-radius: 50%;
    border: 1px solid var(--border);
    background: var(--surface);
    color: var(--foreground);
    transition: all 0.2s ease;
}

.btn-icon:hover {
    background: var(--accent);
    border-color: var(--accent);
    color: var(--background);
    transform: translateY(-2px);
}

/* Icon Button (for share buttons, social links) */
.icon-btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 42px;
    height: 42px;
    border-radius: 50%;
    border: 1px solid var(--border);
    background: var(--surface);
    color: var(--foreground);
    transition: all 0.2s ease;
}

.icon-btn:hover {
    background: var(--accent);
    border-color: var(--accent);
    color: var(--background);
    transform: translateY(-2px);
}

.icon-btn svg {
    width: 24px;
    height: 24px;
    stroke-width: 1.5px;
}

/* Social Links */
.social-link {
    display: inline-flex;
    padding: 0.25rem;
    opacity: 0.75;
    transition: all 0.3s ease;
}

.social-link:hover {
    opacity: 1;
    color: var(--accent);
    transform: rotate(6deg);
}

.social-link svg {
    width: 28px;
    height: 28px;
    stroke-width: 1.5px;
    transition: transform 0.2s ease;
}

.social-link:hover svg {
    stroke: var(--accent);
}

/* ===========================================
   LAYOUT SECTIONS
   =========================================== */

/* Sidebar */
.sidebar {
    width: 280px;
    height: 100vh;
    position: sticky;
    top: 0;
    padding: 4rem 1.5rem 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    flex-shrink: 0;
    background: var(--background);
    transition: background 0.3s ease;
}

.sidebar-avatar {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid var(--border);
    transition: border-color 0.3s ease;
}

.sidebar-avatar:hover {
    border-color: var(--accent);
}

.sidebar-name {
    font-size: 1.5rem;
    font-weight: 800;
    letter-spacing: -0.02em;
    line-height: 1.2;
    color: var(--foreground);
}

.sidebar-info {
    font-size: 0.85rem;
    color: var(--foreground);
    opacity: 0.7;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    margin-top: 0.25rem;
}

.sidebar-bio {
    font-size: 0.9rem;
    color: var(--foreground);
    opacity: 0.8;
    line-height: 1.5;
    padding: 0 0.5rem;
}

/* Navbar */
.navbar {
    padding: 1rem 1.5rem;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    background: var(--background);
    transition: background 0.3s ease;
}

@media (min-width: 1024px) {
    .navbar {
        position: sticky;
        top: 0;
        z-index: 10;
    }
}

.nav-links {
    display: flex;
    gap: 1.5rem;
    list-style: none;
    padding: 0;
    margin: 0;
    flex-wrap: wrap;
}

.nav-link {
    font-size: 0.9rem;
    font-weight: 600;
    text-decoration: none;
    color: var(--foreground);
    position: relative;
    transition: color 0.2s ease;
}

.nav-link.active {
    color: var(--accent);
}

.nav-link.inactive {
    opacity: 0.75;
}

.nav-link-line {
    position: absolute;
    bottom: -0.5rem;
    left: 0;
    width: 0;
    height: 4px;
    background-color: var(--accent);
    transition: width 0.3s ease;
}

.nav-link:hover .nav-link-line,
.nav-link.active .nav-link-line {
    width: 100%;
}

/* Main Content Area */
.main-content {
    flex: 1;
    min-width: 0;
    display: flex;
    flex-direction: column;
    background: var(--background);
    transition: background 0.3s ease;
}

.main-body {
    padding: 1.5rem 2rem 2rem;
    flex: 1;
}

.main-body-sm {
    padding: 1rem 1.5rem 1.5rem;
}

/* Footer */
.footer {
    padding: 1.5rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 0.85rem;
    color: var(--foreground);
}

/* ===========================================
   PAGE SECTIONS
   =========================================== */

.page-header {
    margin-bottom: 2rem;
}

.page-title {
    font-size: 1.5rem;
    font-weight: 800;
    letter-spacing: -0.02em;
    line-height: 1.2;
    color: var(--foreground);
    margin: 0;
}

.page-subtitle {
    font-size: 1rem;
    color: var(--foreground);
    opacity: 0.75;
    margin-top: 0.5rem;
    margin-bottom: 0;
}

.section {
    margin-bottom: 2rem;
}

.section-title {
    font-size: 1.2rem;
    font-weight: 700;
    letter-spacing: -0.01em;
    color: var(--foreground);
    margin-bottom: 1rem;
}

/* ===========================================
   PROSE (Content Typography)
   =========================================== */

.prose {
    font-size: 1rem;
    line-height: 1.7;
    color: var(--foreground);
}

.prose h1 {
    font-size: 1.5rem;
    font-weight: 800;
    letter-spacing: -0.02em;
    line-height: 1.2;
    margin: 2rem 0 1rem;
}

.prose h2 {
    font-size: 1.2rem;
    font-weight: 700;
    letter-spacing: -0.01em;
    margin: 1.5rem 0 0.75rem;
}

.prose h3 {
    font-size: 1.1rem;
    font-weight: 700;
    margin: 1.25rem 0 0.5rem;
}

.prose p {
    margin-bottom: 1rem;
}

.prose ul,
.prose ol {
    margin-bottom: 1rem;
    padding-left: 1.5rem;
}

.prose li {
    margin-bottom: 0.5rem;
}

.prose ul li::marker {
    color: var(--accent);
    font-weight: 800;
}

.prose ol li::marker {
    color: var(--accent);
    font-weight: 800;
}

.prose a {
    color: inherit;
    text-decoration: underline;
    text-underline-offset: 4px;
    font-weight: 600;
    transition: color 0.2s ease;
}

.prose a:hover {
    color: var(--accent);
}

.prose code {
    font-family: "JetBrains Mono", monospace;
    font-size: 0.85em;
    font-weight: 500;
    background: var(--surface);
    color: var(--accent);
    padding: 0.15rem 0.3rem;
    border-radius: 0.2rem;
}

.prose pre {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 0.25rem;
    padding: 1rem;
    overflow-x: auto;
    margin-bottom: 1rem;
}

.prose pre code {
    background: transparent;
    color: var(--foreground);
    padding: 0;
}

.prose img {
    max-width: 100%;
    height: auto;
    border-radius: 0.25rem;
    margin: 1rem 0;
}

.prose blockquote {
    border-left: 4px solid var(--accent);
    padding-left: 1rem;
    margin: 1rem 0;
    opacity: 0.85;
    font-style: italic;
}

.prose hr {
    border: none;
    border-top: 1px solid var(--border);
    margin: 2rem 0;
}

/* ===========================================
   SHARED COMPONENTS
   =========================================== */

/* Back Link */
.back-link {
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--foreground);
    opacity: 0.7;
    text-decoration: none;
    transition: opacity 0.2s ease;
}

.back-link:hover {
    opacity: 1;
}

/* Item List */
.item-list {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

/* Pagination */
.pagination {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1.5rem;
    margin-top: 2rem;
    padding-top: 1.5rem;
}

.pagination-link {
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--foreground);
    text-decoration: none;
    transition: color 0.2s ease;
}

.pagination-link:hover {
    color: var(--accent);
}

.pagination-inactive {
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--foreground);
    opacity: 0.4;
}

.pagination-info {
    font-size: 0.85rem;
    color: var(--foreground);
    opacity: 0.6;
}

/* Divider */
.divider {
    border: none;
    border-top: 1px dashed var(--border);
}

.divider-solid {
    border: none;
    border-top: 1px solid var(--border);
}

/* ===========================================
   ICONS (SVG defaults)
   =========================================== */

.icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
}

.icon-sm {
    width: 14px;
    height: 14px;
}

.icon-md {
    width: 18px;
    height: 18px;
}

.icon-lg {
    width: 24px;
    height: 24px;
}

.icon-muted {
    opacity: 0.7;
}

/* ===========================================
   ACCESSIBILITY & ANIMATION
   =========================================== */

*:focus-visible {
    outline: 2px dashed var(--accent);
    outline-offset: 2px;
}

@media (prefers-reduced-motion: reduce) {
    *,
    *::before,
    *::after {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
    }
}

.animate-in {
    animation: fadeIn 0.5s ease-out forwards;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(10px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* ===========================================
   DEV TOOLS SPECIFIC
   =========================================== */

.viewport-frame {
    border: 1px solid var(--border);
    border-radius: 0.5rem;
    background: var(--surface);
    overflow: hidden;
    display: flex;
    flex-direction: column;
}

.viewport-header {
    padding: 0.75rem 1rem;
    border-bottom: 1px solid var(--border);
    background: var(--background);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.iframe-container {
    position: relative;
    width: 100%;
    padding-top: 56.25%;
    /* 16:9 */
    overflow: hidden;
    border-radius: 0.5rem;
    border: 1px solid var(--border);
    background: var(--background);
}

.iframe-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 200%;
    height: 200%;
    transform: scale(0.5);
    transform-origin: 0 0;
    border: none;
}

/* ===========================================
   RESPONSIVE
   =========================================== */

@media (max-width: 1024px) {
    .sidebar {
        width: 100%;
        height: auto;
        position: relative;
        border-right: none;
        padding: 1rem;
        flex-direction: row;
        flex-wrap: wrap;
        gap: 0.75rem;
    }

    .sidebar-avatar {
        width: 112px;
        height: 112px;
    }

    .main-body {
        padding: 1rem 1.5rem;
    }

    .main-content {
        width: 100%;
        flex: none;
    }
}

@media (max-width: 768px) {
    .sidebar {
        padding: 0.75rem 1rem;
        gap: 0.5rem;
    }

    .sidebar-avatar {
        width: 80px;
        height: 80px;
    }

    .sidebar-name {
        font-size: 1.25rem;
    }

    .sidebar-bio {
        display: none;
    }

    .main-body {
        padding: 0.75rem 1rem;
    }

    .nav-links {
        gap: 1rem;
    }

    .nav-link {
        font-size: 0.85rem;
    }
}

```


## types/config.ts

```ts
export interface SiteConfig {
    website: string;
    author: string;
    desc: string;
    title: string;
    ogImage: string;
    postPerPage: number;
    favicon: string;
    lang: string;
}

export interface ThemeConfig {
    lightAndDark: boolean;
    themeLight: string;
    themeDark: string;
}

export interface SettingsConfig {
    showTagsInNavbar: boolean;
    showRSSInFooter: boolean;
    addDevToolsInProduction: boolean;
}

export interface UmamiAnalyticsConfig {
    websiteId: string;
    src: string;
}

export interface AnalyticsConfig {
    ga4Id?: string;
    umami?: UmamiAnalyticsConfig;
}

export interface NavLink {
    href: string;
    label: string;
    isActive: boolean;
}

export interface SocialLink {
    name: string;
    href: string;
    linkTitle: string;
    isActive: boolean;
}

export interface PageConfig {
    title: string;
    subtitle: string;
    isActive: boolean;
}

export type PagesConfig = Record<string, PageConfig>;
```


## types/content.ts

```ts
export interface Bio {
    name: string;
    avatar: string;
    shortBio?: string;
    institution?: string;
}

export interface CVItem {
  institution: string;
  period: string;
  description: string;
}

export interface EducationItem extends CVItem {
  degree: string;
  thesis?: string;
}

export interface ExperienceItem extends CVItem {
  role: string;
}

export interface CV {
  name: string;
  title: string;
  experience: ExperienceItem[];
  education: EducationItem[];
}

export interface BasePage {
  title: string;
  description?: string;
  tags: string[];
}

export interface Blog extends BasePage {
  date: string;
  author?: string;
}

export interface Project extends BasePage {
  date: string;
  external_url?: string;
}

export interface Publication extends BasePage {
  date: string;
  author?: string;
  journal?: string;
  external_url?: string;
}

export interface Talk extends BasePage {
  date: string;
  event?: string;
  external_url?: string;
}

export interface Teaching extends BasePage {
  institution?: string;
  external_url?: string;
}
```


## types/display.ts

```ts
export interface DisplayMeta {
    label?: string;
    value: string;
    datetime?: string;
}

export interface DisplayLink {
    href: string;
    label: string;
}

export interface ListingItem {
    title: string;
    description?: string;
    date?: string;
    authors?: string;
    extraInput?: string;
    tags: string[];
    externalUrl?: string;
    image?: string;
}

export interface DetailItem extends ListingItem {
    backHref: string;
}
```


## types/index.ts

```ts
export type {
    Bio,
    CVItem,
    EducationItem,
    ExperienceItem,
    CV,
    BasePage,
    Blog,
    Project,
    Publication,
    Talk,
    Teaching,
} from "./content";

export type { DisplayLink, DisplayMeta, ListingItem, DetailItem } from "./display";

export type {
    SiteConfig,
    ThemeConfig,
    SettingsConfig,
    UmamiAnalyticsConfig,
    AnalyticsConfig,
    PagesConfig,
    NavLink,
    SocialLink,
} from "./config";
```


## types/themes.ts

```ts
export interface ThemeColors {
    background: string;
    foreground: string;
    accent: string;
    muted: string;
    border: string;
    surface: string;
}

export interface Theme extends ThemeColors {
    isDark: boolean;
}

export type ThemeName = string;
```


## utils/adapters.ts

```ts
import type { ListingItem, DetailItem } from "../types";

function formatDate(dateValue: string | Date | undefined): string | undefined {
    if (!dateValue) return undefined;
    const date = typeof dateValue === 'string' ? new Date(dateValue) : dateValue;
    if (isNaN(date.getTime())) return undefined;
    return date.toLocaleDateString('en-US', { year: 'numeric', month: 'long' });
}

export function getListingItem(entry: any, collection?: string): ListingItem {
    const d = entry.data;
    
    return {
        title: d.title,
        description: d.description,
        date: formatDate(d.date),
        authors: d.author,
        extraInput: d.journal || d.event || d.institution,
        tags: d.tags || [],
        externalUrl: d.external_url,
        image: d.image,
    };
}

export function getDetailItem(entry: any, collection: string): DetailItem {
    const listing = getListingItem(entry, collection);
    
    return {
        ...listing,
        backHref: collection === 'posts' ? '/posts' : `/${collection}`,
    };
}
```


## utils/readingTime.ts

```ts
export function getReadingTime(text: string): number {
    const wordsPerMinute = 200;
    const noOfWords = text.split(/\s+/g).length;
    const minutes = noOfWords / wordsPerMinute;
    return Math.ceil(minutes);
}

```


## utils/tags.ts

```ts
import { getCollection } from 'astro:content';

export async function getAllTags() {
    const publications = await getCollection('publications');
    const talks = await getCollection('talks');
    const projects = await getCollection('projects');
    const posts = await getCollection('posts');
    const teaching = await getCollection('teaching');

    const allEntries = [...publications, ...talks, ...projects, ...posts, ...teaching];
    const tags: Record<string, number> = {};

    allEntries.forEach(entry => {
        const entryTags = (entry.data as any).tags || [];
        entryTags.forEach((tag: string) => {
            const normalizedTag = tag.trim().toLowerCase();
            if (normalizedTag) {
                tags[normalizedTag] = (tags[normalizedTag] || 0) + 1;
            }
        });
    });

    return Object.entries(tags)
        .map(([name, count]) => ({ name, count }))
        .sort((a, b) => b.count - a.count || a.name.localeCompare(b.name));
}

export async function getContentByTag(tag: string) {
    const normalizedSearchTag = tag.toLowerCase();

    const publications = await getCollection('publications');
    const talks = await getCollection('talks');
    const projects = await getCollection('projects');
    const posts = await getCollection('posts');
    const teaching = await getCollection('teaching');

    const filterFn = (entry: any) => {
        const entryTags = (entry.data as any).tags || [];
        return entryTags.some((t: string) => t.toLowerCase() === normalizedSearchTag);
    };

    return [
        ...publications.filter(filterFn).map(e => ({ ...e, collection: 'publications' })),
        ...talks.filter(filterFn).map(e => ({ ...e, collection: 'talks' })),
        ...projects.filter(filterFn).map(e => ({ ...e, collection: 'projects' })),
        ...posts.filter(filterFn).map(e => ({ ...e, collection: 'posts' })),
        ...teaching.filter(filterFn).map(e => ({ ...e, collection: 'teaching' })),
    ].sort((a, b) => {
        const dateA = new Date((a.data as any).date || 0);
        const dateB = new Date((b.data as any).date || 0);
        return dateB.getTime() - dateA.getTime();
    });
}

```

