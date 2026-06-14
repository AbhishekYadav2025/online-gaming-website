# GHB-WEB-001: GameHub – Online Gaming Community and Matchmaking Portal

**Category:** Web Design & UX  
**Sub-Category:** Gaming Community & Social Platform  
**Project Title:** GameHub – Online Gaming Community and Matchmaking Portal  
**Complexity Level:** High  

---

---

## 1. Overview

### 1.1 Project Purpose

This project requires a web designer and UX practitioner to design a complete, high-fidelity UI/UX prototype for **GameHub**, a fictional online gaming community and matchmaking portal. The design must cover all pages and user flows listed in §5, demonstrate a navigation structure in which all 6 page types are reachable within 2 clicks from the Home page, and include a component specification file that allows a front-end developer to implement the design without requesting additional information.

The deliverable must satisfy every item in the §12.1, §12.2, and §12.3 checklists. Passing those checklists is the binary test for acceptance.

### 1.2 Product Summary

GameHub is a fictional web platform designed for the online multiplayer gaming community. It is not affiliated with, derived from, or visually inspired by any existing branded gaming platform. All visual elements, icons, game titles, usernames, and content used within the designs must be entirely fictional and original.

GameHub serves as a central hub where gamers can:

- Build and customize a public profile showcasing their gaming activity and achievements
- Find and connect with other players through a skill-based matchmaking interface
- Read gaming news, tutorials, and community-authored guides
- Participate in community forums organized by game genre and topic
- Discover and register for upcoming gaming events and tournaments

The fictional client commissioning this design is **GameHub Inc.**, a startup building a community-first gaming social platform targeting competitive and casual PC and console gamers aged 16 to 35.

### 1.3 Target Audience

| Stakeholder | Role | Primary Concern |
|---|---|---|
| Casual Gamers | End User | Easy navigation, discovering events and community |
| Competitive Players | End User | Matchmaking accuracy, profile visibility, tournament info |
| Community Moderators | Platform Operator | Forum management, reporting tools, event creation |
| GameHub Inc. Founders | Client | Brand identity, user retention, platform growth |
| Front-End Developers | Handoff Recipient | Component specs with named variants, design system tokens, and spacing values in multiples of 4px |
| UX Reviewers / Evaluators | Assessment | Information architecture, usability, responsiveness |

### 1.4 Core Functions of the Platform Design

The design must demonstrate the following user-facing capabilities:

- A home page that displays at minimum 6 distinct content sections (hero, featured content, matchmaking preview, news strip, stats bar, events preview) above the footer
- A user profile system with editable sections, stats display, and social connections
- A matchmaking interface allowing players to filter opponents or teammates by skill level, game, and region
- A gaming news section with article cards, category filters, and a featured article layout
- A community forum with nested threads, category navigation, and post creation flow
- An event calendar showing upcoming tournaments, community events, and registration options
- A mobile-responsive layout for all pages
- A documented design system covering colors, typography, components, and spacing

---

## 2. Scope of Work

### 2.1 In Scope

#### Core Design Deliverables

- High-fidelity UI designs for all 6 page types listed in §5
- Mobile-responsive variants for all 6 page types
- A complete Design System Documentation file
- Prototype links (clickable flow) covering at minimum the Home → Profile → Matchmaking user journey

#### Specific UI Sections to Be Designed

- Global navigation bar with logo placeholder, nav links, search bar, and login/signup controls
- Hero section on the home page
- Featured game or event highlight section
- User profile header with avatar, username, level badge, and stats row
- Game library or activity feed on the profile page
- Matchmaking filter panel with dropdowns and a results grid
- News article card grid with category tag and featured article banner
- Forum category list and thread list layout
- Individual forum thread view with reply input
- Event calendar with list and grid view toggle
- Event detail card with registration call-to-action
- Footer with site links, social icons (placeholder), and copyright line

### 2.2 Out of Scope

- Back-end development, APIs, or database architecture
- Actual game integrations or live data connections
- Logo design or brand identity creation (a placeholder logo block is sufficient)
- Payment flow or subscription screen design
- Admin dashboard or moderation panel design
- Native mobile app design (iOS or Android)
- Animated micro-interactions beyond standard hover states in the prototype
- Copywriting beyond placeholder labels and dummy text

---

## 3. Design Standards and Tools Required

### 3.1 Design Tools

| Tool | Requirement |
|---|---|
| Figma | Primary design and prototyping tool. All frames must be in a single Figma file. |
| Figma Community Assets | Permitted only if assets are under a free commercial-use license. Source must be noted in the design system doc. |
| Adobe XD | Acceptable alternative if Figma is unavailable. Must export to a shareable link. |
| No Canva | Canva exports are not accepted. |

### 3.2 Design Standards

| Standard | Specification |
|---|---|
| Design Style | Dark-themed with accent color highlights. Gaming-focused aesthetic without copying any existing platform's visual identity. |
| Grid System | 12-column grid. Gutters: 24px desktop, 16px tablet, 12px mobile. |
| Breakpoints | Desktop: 1440px. Tablet: 768px. Mobile: 375px. |
| Spacing Scale | 4px base unit. All padding and margin values must be multiples of 4. |
| Iconography | Outline or solid icon set from a free-license library (e.g., Phosphor Icons, Heroicons, Feather Icons). Icon set name must be documented. |
| Imagery | All images must be placeholder blocks with descriptive labels (e.g., "Game Cover Art – 300x200"). No real game artwork or copyrighted images. |
| Color | Minimum 1 primary accent color, 1 secondary accent color, 1 background color, 1 surface color, 1 text color (primary), 1 text color (secondary). All defined in the design system. |
| Typography | Maximum 2 typefaces. Must be Google Fonts or other free-license fonts. Font names and weights documented in the design system. |

### 3.3 Naming and Organization Standards

| Element | Requirement |
|---|---|
| Frame Naming | Each frame named as: [PageName] / [Breakpoint] — example: Home / Desktop |
| Layer Naming | All layers named descriptively. No Layer 1, Rectangle 3, or unnamed groups. |
| Component Naming | Components named in PascalCase: NavBar, ProfileCard, MatchCard |
| Page Organization | Figma pages organized as: 01 Design System, 02 Home, 03 Profile, 04 Matchmaking, 05 News, 06 Forum, 07 Events, 08 Prototype |

---

## 4. Deliverable Package Structure

```
GameHub-Design-Package/
|
|-- 01_Design_File.fig                  (Figma source file export)
|-- 02_Design_System_Documentation.pdf  (Design system reference doc)
|-- 03_Prototype_Link.txt               (Shareable Figma prototype URL)
|-- 04_Screen_Exports/
|     |-- Home_Desktop.png
|     |-- Home_Mobile.png
|     |-- Profile_Desktop.png
|     |-- Profile_Mobile.png
|     |-- Matchmaking_Desktop.png
|     |-- Matchmaking_Mobile.png
|     |-- News_Desktop.png
|     |-- News_Mobile.png
|     |-- Forum_Desktop.png
|     |-- Forum_Mobile.png
|     |-- Events_Desktop.png
|     |-- Events_Mobile.png
|-- 00_README_Handoff.pdf               (Plain-language handoff guide)
```

### 4.1 Directory Explanation

| File | Description |
|---|---|
| 01_Design_File.fig | Full Figma source with all pages, components, and variants organized per §3.3 |
| 02_Design_System_Documentation.pdf | Exported PDF covering all tokens, components, and usage rules per §9 |
| 03_Prototype_Link.txt | A plain text file containing the shareable Figma prototype URL covering the Home → Profile → Matchmaking flow |
| 04_Screen_Exports | PNG exports at 2x resolution for every page at both Desktop (1440px) and Mobile (375px) breakpoints |
| 00_README_Handoff.pdf | 1–2 page plain-language PDF explaining file structure, font sources, icon library, and how to hand off to a developer |

---

## 5. Deliverables

| ID | Deliverable | Format | Breakpoints Required | Priority |
|---|---|---|---|---|
| D-01 | Home Page | Figma Frame + PNG Export | Desktop + Mobile | Must Have |
| D-02 | User Profile Page | Figma Frame + PNG Export | Desktop + Mobile | Must Have |
| D-03 | Matchmaking Interface | Figma Frame + PNG Export | Desktop + Mobile | Must Have |
| D-04 | Gaming News Section | Figma Frame + PNG Export | Desktop + Mobile | Must Have |
| D-05 | Community Forum Layout | Figma Frame + PNG Export | Desktop + Mobile | Must Have |
| D-06 | Event Calendar | Figma Frame + PNG Export | Desktop + Mobile | Must Have |
| D-07 | Design System Documentation | PDF | N/A | Must Have |
| D-08 | Prototype (clickable flow) | Figma Prototype Link | Desktop | Must Have |

---

## 6. File Formats and Submission Standards

### 6.1 Format Requirements

- All design frames delivered inside a single Figma source file (.fig)
- Screen exports delivered as PNG at 2x resolution
- Design system documentation delivered as a text-searchable PDF
- Handoff README delivered as PDF
- Prototype delivered as a shared Figma link (view-only access enabled)
- All files packaged in a single compressed archive named: `GameHub_Design_v1.0_[FreelancerName]`

### 6.2 File Naming Convention

```
[DocID]_[FileName]_v[VersionNumber].[extension]

Examples:
01_Design_File_v1.0.fig
02_Design_System_Documentation_v1.0.pdf
04_Home_Desktop_v1.0.png
```

### 6.3 Export Settings

- PNG exports: 2x scale, transparent background where the frame background is transparent, white background where specified
- All text in PDFs must be selectable (not flattened to image)
- Figma file must not contain any external plugin dependencies that prevent opening on another machine

### 6.4 Placeholder Convention

All variable content that a real client would fill in must use the following convention:

```
[PLATFORM NAME]
[TAGLINE TEXT]
[USERNAME]
[GAME TITLE]
[AVATAR IMAGE – 80x80]
[GAME COVER – 300x200]
[NEWS ARTICLE THUMBNAIL – 400x240]
[EVENT BANNER – 800x300]
[FORUM CATEGORY NAME]
[THREAD TITLE]
[DATE]
[REGION]
[SKILL LEVEL]
```

---

## 7. Explicit Ask: Detailed Implementation Requirements

### 7.1 What Must Be Designed

The freelancer must produce a complete, high-fidelity design package that satisfies every item in the §12.1, §12.2, and §12.3 checklists.

The design must be:

1. **Original**: No visual elements copied or traced from any existing gaming platform. All icons from a documented free-license library. All imagery is placeholder blocks only.
2. **Internally consistent**: The same component used across pages must look identical. Color tokens from the design system must be applied uniformly.
3. **Information-architecture-driven**: All 6 page types must be reachable from the global navigation bar. Content on each page must be grouped into named sections with H2 headings. No section may contain content unrelated to its heading label.
4. **Responsive**: Every page has a mobile-breakpoint frame that reflows the layout correctly without cropping or overlapping elements.
5. **Developer-ready**: Components must be built as Figma components with variants where applicable. Spacing must follow the 4px grid.

### 7.2 Page Quality Standards

#### Navigation

- Global navigation bar must appear in a consistent position on all desktop frames
- Navigation bar must include: logo placeholder block, at minimum 5 nav link labels, a search input field, and two CTA buttons (Sign In, Join Free)
- On mobile, the navigation bar must collapse into a hamburger menu icon

#### Typography

- Heading hierarchy must be clear and consistent: H1 used only for primary page heading, H2 for section titles, H3 for card titles, Body for paragraph text, Caption for metadata
- No heading level may be skipped (H1 → H2 → H3 in order)
- All text must meet WCAG AA contrast ratio against its background (4.5:1 for body text, 3:1 for large text)

#### Color

- The dark background must be used for all page backgrounds
- Surface color must be used for cards, panels, and modals
- The primary accent color must be used for primary CTAs, active states, and highlights
- No more than 3 distinct accent colors may appear in the design system

#### Imagery and Content

- Every image slot must be a filled placeholder rectangle with a label inside it
- No real game names, real platform logos, or real usernames may appear anywhere in the design
- All dummy text must be contextually appropriate gaming-related placeholder content (not Lorem Ipsum)

### 7.3 Acceptance Criteria Summary

| Criterion | Pass Condition |
|---|---|
| All 8 deliverables present | All files present in the submission archive |
| Page count | All 6 page types designed at desktop and mobile breakpoints (12 frames minimum) |
| Prototype flow | Clickable flow covers Home → Profile → Matchmaking with at least 3 interactive links |
| Design system | Color tokens, typography scale, spacing scale, and component library all documented |
| Layer naming | Zero unnamed layers (Layer 1, Rectangle 3, Group 7, etc.) in any frame |
| Component use | NavBar, ProfileCard, MatchCard, NewsCard, ForumCard, EventCard each built as a Figma component |
| Responsive layout | All 6 pages have a mobile frame with no overlapping or cropped elements |
| Placeholder compliance | All variable content uses [BRACKET] labels per §6.4 |
| Original content | Zero real game titles, platform logos, or copyrighted images present |
| Contrast compliance | All body text passes WCAG AA contrast ratio against its background |
| D-07 Design system | 02_Design_System_Documentation.pdf is present, all color token hex values are filled in with actual values, all typography scale fields (typeface, weight, size, line height) are filled in with actual values, and all 8 spacing tokens are documented with a usage example |
| D-08 Prototype link | 03_Prototype_Link.txt is present and contains a Figma URL that allows view-only access without a Figma account sign-in |
| File naming | Files named per convention in §6.2 |
| Archive packaging | All files delivered in a single compressed archive |

### 7.4 Performance Expectations

- **Delivery timeline**: 7–10 business days from project commencement
- **Revision round**: one free revision round included
- **Communication**: freelancer must flag any ambiguities within 24 hours of project start
- **Acceptance bar**: designs must satisfy every item in §12.1, §12.2, and §12.3
- **Originality**: all visual work must be original. Any frame that reproduces the layout, color scheme, or component structure of an identifiable existing platform will be rejected
- **Confidentiality**: all project details must remain confidential; deliverables must not be reused as portfolio samples for other clients without written permission

### 7.5 Platform and Compatibility Requirements

| Requirement | Specification |
|---|---|
| Figma version | Figma (browser or desktop app), latest stable version |
| File size | Figma source file must not exceed 200MB |
| Font availability | All fonts must be available on Google Fonts or bundled as .ttf/.otf inside the archive |
| PNG resolution | All exports at 2x (double the frame pixel dimensions) |
| Prototype sharing | Figma prototype link must allow view-only access without a Figma account |

---

## 8. Page-by-Page Design Requirements

Each page listed below must be designed at the Desktop (1440px) breakpoint and the Mobile (375px) breakpoint. Each page must contain all the sections listed. Each section must contain the UI elements described.

---

### 8.1 Home Page (D-01)

#### Section 1: Global Navigation Bar
- Logo placeholder block (left-aligned)
- Nav links: Home, Games, Matchmaking, News, Community, Events
- Search input field with a search icon
- Sign In button (secondary style)
- Join Free button (primary accent style)
- On mobile: hamburger icon replaces nav links; Sign In and Join Free collapse into the mobile menu

#### Section 2: Hero Section
- Full-width background (dark, with a subtle geometric or abstract pattern — no copyrighted imagery)
- H1 headline: fictional tagline placeholder
- Subheading: one line of descriptive placeholder text
- Two CTAs: primary button and secondary button
- A visual element placeholder (e.g., a labeled rectangle: "Hero Illustration – 600x400")

#### Section 3: Featured Game or Event Highlight
- Section title (H2)
- Horizontal card row or a 2-column layout with one large featured card and two smaller cards
- Each card contains: image placeholder, title label, category tag, and a CTA link

#### Section 4: Live Matchmaking Preview
- Section title (H2)
- A condensed version of the matchmaking panel showing: game filter dropdown, skill filter dropdown, and a 3-card row of player result cards
- A "Find Full Match" CTA button

#### Section 5: Gaming News Strip
- Section title (H2)
- A horizontal scroll row or 3-column card grid
- Each news card contains: thumbnail placeholder, article title, category tag, and publish date

#### Section 6: Community Stats Bar
- A full-width dark band showing 4 platform stats: [NUMBER] Members, [NUMBER] Games Listed, [NUMBER] Matches Made, [NUMBER] Events This Month
- Each stat has a label below the number

#### Section 7: Upcoming Events Preview
- Section title (H2)
- A 3-card row of event cards
- Each card contains: event banner placeholder, event name, date, game name, and a Register button

#### Section 8: Footer
- Logo placeholder block
- Four link columns: Platform, Community, Support, Legal
- Each column has a column heading and at least 3 link labels
- A bottom bar with copyright text and social icon placeholders (5 icons minimum)

---

### 8.2 User Profile Page (D-02)

#### Section 1: Global Navigation Bar
- Identical to Home Page navigation bar
- On mobile: same hamburger behavior

#### Section 2: Profile Header
- Cover image placeholder (full-width, 1440x240 on desktop)
- Avatar image placeholder (circular, 120x120, overlapping the cover bottom edge)
- Username (H2)
- User tagline or bio (one line, Body text)
- Level badge (styled tag showing: "Level [NUMBER]")
- Three stat pills in a row: Matches Played, Win Rate, Friends
- Edit Profile button (visible only in own-profile state; show as a placeholder label)

#### Section 3: Game Library
- Section title (H3)
- A grid of game cards (minimum 6 cards in the desktop view)
- Each card: game cover placeholder, game title, hours played label, last played date

#### Section 4: Recent Activity Feed
- Section title (H3)
- A vertical list of activity items (minimum 5 items)
- Each item: avatar placeholder (small), activity description text, timestamp, and a game tag

#### Section 5: Achievements Panel
- Section title (H3)
- A horizontal row of achievement badge placeholders (minimum 6 badges)
- Each badge: icon placeholder (48x48), achievement name below

#### Section 6: Friends List Preview
- Section title (H3)
- A 2-column grid of friend cards (minimum 4 cards)
- Each card: avatar placeholder (small circular), username, online status indicator (colored dot), and a View Profile link

---

### 8.3 Matchmaking Interface (D-03)

#### Section 1: Global Navigation Bar
- Identical to Home Page navigation bar

#### Section 2: Page Header
- H1 heading: "Find Your Match" (placeholder label)
- Subheading: one line of placeholder descriptor text

#### Section 3: Filter Panel
- Left-aligned sidebar (desktop) or collapsible panel (mobile)
- Filter fields:
  - Game selector dropdown (labeled "[GAME TITLE]")
  - Game mode selector dropdown (labeled "[GAME MODE]")
  - Skill level selector: Beginner, Intermediate, Advanced, Expert (radio buttons or segmented control)
  - Region selector dropdown (labeled "[REGION]")
  - Play style selector: Casual, Ranked, Competitive (toggle or radio)
  - Availability: a time-of-day selector or simple text input placeholder
- Apply Filters button (primary accent)
- Reset Filters link

#### Section 4: Results Grid
- Section title or results count label (e.g., "[NUMBER] Players Found")
- A 3-column card grid on desktop, 1-column list on mobile
- Each player card contains:
  - Avatar placeholder (circular, 64x64)
  - Username
  - Level badge
  - Skill level tag
  - Preferred game label
  - Region label
  - Win rate stat
  - Invite to Match button (primary accent)
  - View Profile link

#### Section 5: Active Match Lobby Preview
- A collapsible or side-panel element showing a lobby with 4 player slots
- Each slot: avatar placeholder or empty slot indicator
- Lobby name label, game title label, Start Match button (disabled until slots filled — show as a grayed-out state)

---

### 8.4 Gaming News Section (D-04)

#### Section 1: Global Navigation Bar
- Identical to Home Page navigation bar

#### Section 2: Page Header
- H1 heading placeholder
- Category filter tab row: All, Esports, Game Releases, Tutorials, Community, Patch Notes

#### Section 3: Featured Article Banner
- Full-width card (desktop: 1200px wide, mobile: full width)
- Large image placeholder (800x300)
- Category tag
- Article title (H2)
- Author name and publish date
- Read More button

#### Section 4: Article Card Grid
- A 3-column card grid on desktop, 1-column on mobile
- Minimum 6 article cards visible
- Each card contains: thumbnail placeholder (400x240), category tag, article title (H3), author name, publish date, and a Read More link

#### Section 5: Sidebar (desktop only)
- Trending Topics list: a vertical list of 5 topic labels with a post count
- Community Picks: 3 small article cards (thumbnail + title only)

#### Section 6: Pagination
- Previous and Next buttons
- Page number indicators (show at least 5 page numbers as a row)

---

### 8.5 Community Forum Layout (D-05)

#### Section 1: Global Navigation Bar
- Identical to Home Page navigation bar

#### Section 2: Forum Category List
- Page H1 heading placeholder
- A vertical list of forum categories (minimum 6 categories)
- Each category row contains: category icon placeholder (32x32), category name (H3), category description (one line), thread count, post count, and a last-active timestamp

#### Section 3: Thread List View
- Section title (H2): the selected category name
- A New Thread button (primary accent, top right)
- A vertical list of thread items (minimum 8 threads)
- Each thread item contains: author avatar placeholder (small circular), thread title, author username, reply count, view count, category tag, and last reply timestamp
- Pinned thread indicator (e.g., a pin icon) for the first item

#### Section 4: Individual Thread View
- Thread title (H1)
- Original post block: author avatar, username, level badge, post body text (placeholder), post timestamp, and reaction icons (like, quote, report — labeled placeholders)
- Reply block: minimum 3 reply items in the same layout as the original post block
- Reply input area: avatar placeholder (small), a multi-line text input placeholder, and a Post Reply button

#### Section 5: Forum Sidebar (desktop only)
- Forum Rules block: a small panel with 3–5 placeholder rule lines
- Active Users Now: a small panel showing 4 avatar placeholders in a row and a count label
- Report a Post link

---

### 8.6 Event Calendar (D-06)

#### Section 1: Global Navigation Bar
- Identical to Home Page navigation bar

#### Section 2: Page Header
- H1 heading placeholder
- View toggle: Grid View icon button and List View icon button (show both states — one active, one inactive)

#### Section 3: Calendar Grid View
- A full-width monthly calendar grid
- Days of the week as column headers
- Cells for each date, with at least 4 date cells containing event indicator dots or event name chips
- Clicking a date cell (show as an active/selected state) reveals an event summary panel beside or below the grid

#### Section 4: Event List View
- A vertical list of upcoming events (minimum 6 events)
- Each event item contains:
  - Event banner placeholder (horizontal, 400x120)
  - Event name (H3)
  - Date and time label
  - Game or category tag
  - Prize pool label (placeholder: "[PRIZE POOL]")
  - Slots available label (placeholder: "[X] / [Y] Slots Filled")
  - Register Now button (primary accent)
  - View Details link

#### Section 5: Event Detail Card (expanded state)
- A modal or side-panel showing the full event details
- Event banner placeholder (full width within panel)
- Event name (H2)
- Organizer name
- Date, time, and duration
- Game title
- Format description (placeholder text)
- Prize breakdown (placeholder table: 1st, 2nd, 3rd place amounts)
- Rules summary (3 placeholder rule lines)
- Register button (primary accent)
- Close or Back link

---

## 9. Design System Requirements

The Design System Documentation (D-07) must be a fully drafted reference document, not a placeholder or title page. It must contain all of the following sections.

### 9.1 Color Tokens

A complete color token table containing:

| Token Name | Hex Value | Usage |
|---|---|---|
| color-background | [HEX] | Page background |
| color-surface | [HEX] | Cards, panels, modals |
| color-surface-raised | [HEX] | Elevated cards, dropdowns |
| color-accent-primary | [HEX] | Primary CTAs, active states, highlights |
| color-accent-secondary | [HEX] | Secondary accents, tags, badges |
| color-text-primary | [HEX] | Headings and primary body text |
| color-text-secondary | [HEX] | Metadata, captions, secondary labels |
| color-border | [HEX] | Card borders, dividers, input outlines |
| color-success | [HEX] | Online status, success states |
| color-warning | [HEX] | Warning states |
| color-error | [HEX] | Error states, destructive actions |

All hex values must be filled in with the actual values used in the design.

### 9.2 Typography Scale

| Token | Typeface | Weight | Size | Line Height | Usage |
|---|---|---|---|---|---|
| text-h1 | [Font Name] | Bold | [px] | [px] | Page headings |
| text-h2 | [Font Name] | SemiBold | [px] | [px] | Section titles |
| text-h3 | [Font Name] | Medium | [px] | [px] | Card titles |
| text-body | [Font Name] | Regular | [px] | [px] | Body text |
| text-caption | [Font Name] | Regular | [px] | [px] | Metadata, timestamps |
| text-button | [Font Name] | SemiBold | [px] | [px] | Button labels |

All fields must be filled in with the actual values used in the design.

### 9.3 Spacing Scale

A table listing the 4px base-unit spacing scale:
- space-1: 4px
- space-2: 8px
- space-3: 12px
- space-4: 16px
- space-5: 24px
- space-6: 32px
- space-7: 48px
- space-8: 64px

Each spacing token must be documented with its usage example (e.g., "space-4: inner padding of all cards").

### 9.4 Component Library

The following components must each be documented with a screenshot (Figma frame export) and a usage note:

| Component | Required Variants |
|---|---|
| NavBar | Desktop, Mobile (collapsed), Mobile (expanded) |
| Button | Primary, Secondary, Disabled, Icon-only |
| Input Field | Default, Focused, Error, Disabled |
| Dropdown | Closed, Open |
| ProfileCard | Default, Compact |
| MatchCard | Default, Invited state |
| NewsCard | Default, Featured |
| ForumCard | Default, Pinned |
| EventCard | Default, Registered |
| Badge | Level badge, Category tag, Skill tag, Status dot |
| Avatar | Large (120px), Medium (64px), Small (32px) |
| Pagination | Default state, Active page state |

### 9.5 Iconography

- State the icon library name and version
- State the license type
- Show a sample grid of 12 icons used in the design with their names

### 9.6 Grid and Layout

- Document the 12-column grid with gutter and margin values for each breakpoint
- Show a visual diagram of the grid (Figma frame export)

---

## 10. Responsive Design Requirements

### 10.1 Breakpoints

| Breakpoint | Width | Layout Behavior |
|---|---|---|
| Desktop | 1440px | 12-column grid. Multi-column layouts. Sidebar visible. |
| Tablet | 768px | 8-column grid. Two-column layouts. Sidebar collapses. |
| Mobile | 375px | 4-column grid. Single-column layouts. Nav becomes hamburger. |

Only Desktop and Mobile frames are required as final deliverables. Tablet is optional.

### 10.2 Mobile-Specific Behavior Requirements

| Element | Mobile Behavior |
|---|---|
| Global Navigation | Hamburger icon. Tapping reveals a full-screen nav overlay with all links. |
| Hero Section | Stack headline above the CTA buttons. Image placeholder below. |
| Card Grids | Single column. Full width cards. |
| Filter Panel (Matchmaking) | Collapses to a "Filters" button that reveals a bottom sheet or overlay. |
| Forum Thread List | Full-width list items. Sidebar hidden. |
| Event Calendar Grid | Shrinks to show one week at a time with left/right navigation arrows. |
| Footer | Single-column stacked layout. Link columns stacked vertically. |

### 10.3 No Overflow Rule

No element in any mobile frame may extend beyond the 375px frame width. No horizontal scroll may be implied by the layout.

---

## 11. Drafting Standards and Style Guide

### 11.1 Visual Design Principles

- **Dark-first aesthetic**: the dark background is the design foundation. Light text on dark panels is the standard reading state.
- **Accent-driven hierarchy**: the primary accent color draws the eye to the most important interactive element on the page. No more than one primary CTA per visual zone.
- **Card-based content structure**: all repeating content items (news articles, player results, events, forum threads) must be placed inside card containers with a defined background color token, border or shadow, and corner radius value from the design system. No repeating content item may be placed directly on the page background without a card container.
- **Consistent corner radius**: all cards and buttons must use the same corner radius value, defined in the design system.
- **Spacing consistency**: all internal card padding, section gaps, and grid gutters must match the spacing scale in §9.3.

### 11.2 What to Avoid

| Avoid | Reason |
|---|---|
| Real game titles, logos, or cover art | Copyright violation — will trigger immediate rejection |
| Reproducing the layout or color scheme of an existing named platform | Originality requirement — will trigger rejection |
| Lorem Ipsum text | Does not demonstrate content hierarchy understanding — use contextual gaming placeholder text |
| Unlabeled image placeholders | Evaluators cannot determine intent — all placeholders must have a descriptive label |
| Inconsistent component use | The same component must look identical every time it appears |
| Unnamed Figma layers | Developer-handoff requirement — all layers must be named |
| Fonts not from Google Fonts or a documented free-license source | Licensing risk |
| More than 3 accent colors | Creates visual noise and inconsistency |

---

## 12. Acceptance Criteria and Quality Checklist

### 12.1 Completeness Checklist

- [ ] All 8 deliverables (D-01 through D-08) present in the submission archive
- [ ] All files named per the naming convention in §6.2
- [ ] All 6 page types (Home, Profile, Matchmaking, News, Forum, Events) designed at Desktop breakpoint
- [ ] All 6 page types designed at Mobile (375px) breakpoint
- [ ] Figma prototype covers the Home → Profile → Matchmaking flow with at least 3 interactive links
- [ ] All PNG exports are at 2x resolution
- [ ] Design System Documentation PDF is present and fully filled in (not a placeholder document)
- [ ] Handoff README PDF is present

### 12.2 Design Quality Checklist

- [ ] Zero real game titles, platform logos, or copyrighted images present in any frame
- [ ] All image slots are labeled placeholder rectangles
- [ ] All body text passes WCAG AA contrast ratio (4.5:1) against its background
- [ ] All large text (18px+ or 14px+ bold) passes WCAG AA contrast ratio (3:1) against its background
- [ ] NavBar component is consistent across all 6 page desktop frames
- [ ] The following 12 components are built as Figma components: NavBar, Button, Input Field, Dropdown, ProfileCard, MatchCard, NewsCard, ForumCard, EventCard, Badge, Avatar, Pagination
- [ ] All components have the required variants listed in §9.4
- [ ] Color tokens from §9.1 are applied consistently across all frames
- [ ] Typography scale from §9.2 is applied consistently across all frames
- [ ] All spacing values are multiples of 4px
- [ ] No mobile frame has any element extending beyond 375px width

### 12.3 File and Submission Checklist

- [ ] Zero unnamed layers in any Figma frame (Layer 1, Rectangle 3, Group 7, etc.)
- [ ] All layers and frames named per conventions in §3.3
- [ ] Figma file opens without missing fonts
- [ ] Prototype link allows view-only access without a Figma account sign-in requirement
- [ ] All PDFs are text-searchable (not flattened images)
- [ ] Archive is a single compressed file named per §6.1
- [ ] No Canva exports present in the archive
- [ ] Figma source file does not exceed 200MB

---

## 13. Timeline and Revision Policy

### 13.1 Delivery Timeline

| Milestone | Timeline |
|---|---|
| Freelancer acknowledges project and flags questions | Within 24 hours of project award |
| First draft of all deliverables submitted | Within 7–10 business days of project award |
| Client review period | 3 business days |
| Freelancer revision turnaround (Round 1) | Within 3 business days of receiving feedback |
| Final delivery | Within 16 business days of project award |

### 13.2 Revision Policy

- One free revision round is included in the project scope
- Revisions must be responsive to the client's specific written feedback
- Revisions that constitute new scope (e.g., adding a new page type not in §5) are not included
- If a delivered design fails 3 or more items in the §12 checklists, the freelancer must revise at no extra cost regardless of revision round count

---

## 14. Important Disclaimers

> **For Internal Use Only:** This Instruction Document is prepared for the purpose of briefing a freelance designer on Fiverr. It does not constitute endorsement of any specific tool, platform, or design style.

> **No Real Platform Affiliation:** GameHub is a fictional platform created for evaluation purposes. Any resemblance to existing gaming platforms, brands, or products is coincidental and must be avoided in the deliverable.

> **Copyright Responsibility:** The freelancer is solely responsible for ensuring that all assets, fonts, icons, and visual elements used in the design are either original work or licensed for commercial use. Copyrighted game artwork, logos, screenshots, or branded assets of any kind are strictly prohibited.

> **Placeholders:** All bracketed placeholders [LIKE THIS] are variable content to be replaced by the real client before any design is used in production.

> **Confidentiality:** The freelancer must treat all project information as strictly confidential. Deliverables may not be reused as portfolio samples or shared publicly without the client's prior written consent.

---

*End of Instruction Document*

---

**Document Metadata**

| Field | Value |
|---|---|
| Document Title | Instruction Document: GameHub – Online Gaming Community and Matchmaking Portal |
| Project | GameHub – Online Gaming Community and Matchmaking Portal |
| Category | Web Design and UX / Gaming Community and Social Platform |
| Status | Ready for Freelancer Review |
| Prepared By | GameHub Inc. (Fictional Client) |
| Date | [DATE] |
