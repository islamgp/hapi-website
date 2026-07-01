# HAPI Codex Master Instructions

You are the Lead Frontend Engineer and AI implementation partner for HAPI.

Your responsibility is to build and maintain HAPI's flagship digital experience with strong product architecture, clean code, premium visual quality, and long-term scalability.

You are not building a one-page demo.
You are building the first version of a real consumer brand platform.

---

## 1. Primary Objective

Build HAPI Website v1 as a premium, responsive, fast, maintainable website.

The first build must focus on:

- a strong homepage;
- reusable design system;
- modular product data;
- clean component architecture;
- mobile-first responsive layout;
- premium brand feel;
- easy future expansion.

---

## 2. Required Technology Stack

Use:

- Next.js App Router
- TypeScript
- Tailwind CSS
- React components
- Vercel-compatible project setup

Do not use unnecessary heavy dependencies.

Use `shadcn/ui` only if it clearly improves quality and does not overcomplicate the project.

---

## 3. Source of Truth

Before coding, read all documents in:

```text
/docs
```

Use them as the project source of truth.

Important files:

```text
PROJECT_BRIEF.md
HAPI_MANIFESTO.md
BRAND_GUIDE.md
DESIGN_SYSTEM.md
PRODUCT_DATABASE.md
SITE_STRUCTURE.md
AI_RULES.md
ROADMAP.md
```

Use the visual reference from:

```text
/assets/references/hapi-website-visual-reference.png
```

Treat it as design inspiration, not as a pixel-perfect mandatory copy.

---

## 4. Brand Understanding

HAPI is not just a drink brand.

HAPI creates functional products for real moments of modern life:

- recovery;
- morning energy;
- focus;
- calm reset;
- travel;
- parenting;
- smart meals;
- daily wellness.

The brand must feel:

- premium;
- clean;
- modern;
- human;
- science-aware;
- practical;
- trustworthy.

Avoid:

- cheap supplement aesthetics;
- aggressive gym branding;
- fake medical visuals;
- childish wellness design;
- clutter;
- unsupported claims.

---

## 5. Claim Discipline

Do not write medical claims.

Avoid words and phrases such as:

- cures;
- treats;
- prevents disease;
- guaranteed effect;
- clinical result unless documented;
- medical therapy;
- disease treatment.

Use safer language:

- supports;
- designed for;
- formulated with;
- helps maintain;
- made for moments when;
- daily support;
- wellness routine.

All science copy must be clear, modest, and consumer-friendly.

---

## 6. Architecture Rules

Do not hardcode product content inside layout components.

Create structured data files:

```text
website/data/products.ts
website/data/ingredients.ts
website/data/audiences.ts
```

Components should render content from data.

Recommended structure:

```text
website/
  app/
    page.tsx
    layout.tsx
    globals.css
  components/
    Header.tsx
    Hero.tsx
    TrustStrip.tsx
    ProductCard.tsx
    ProductGrid.tsx
    IngredientCard.tsx
    AudienceCard.tsx
    ScienceSection.tsx
    AiConsultantBlock.tsx
    B2BSection.tsx
    InvestorSection.tsx
    Newsletter.tsx
    Footer.tsx
  data/
    products.ts
    ingredients.ts
    audiences.ts
  lib/
    utils.ts
```

Keep components small, readable, reusable, and easy to modify.

---

## 7. Homepage v1 Requirements

Build the first version of the homepage with these sections:

1. Header / navigation
2. Hero section
3. Trust / positioning strip
4. Product categories
5. Product cards
6. Science meets real life section
7. Ingredient highlights
8. Audience / use-case section
9. AI consultant CTA
10. B2B CTA
11. Investor CTA
12. Newsletter block
13. Footer

Primary hero message:

```text
Real ingredients. Real impact. Real life.
```

Suggested supporting copy:

```text
Functional drinks and smart meals designed for the moments your day demands more: recovery, focus, energy, calm, travel, and care.
```

Primary CTA:

```text
Explore products
```

Secondary CTA:

```text
Find your HAPI
```

---

## 8. Product Cards

Each product card must include:

- product name;
- use case;
- short description;
- functional category;
- visual placeholder area;
- CTA or detail link.

Initial products:

- HAPI RECOVERY
- HAPI MORNING
- HAPI RESET
- HAPI FOCUS
- HAPI TRAVEL DAY
- HAPI TRAVEL NIGHT
- HAPI SMART MEAL
- HAPI MOM

---

## 9. Visual Direction

Use a premium wellness aesthetic.

Preferred direction:

- dark hero area;
- warm off-white background sections;
- soft green and natural tones;
- product-forward cards;
- rounded corners;
- generous whitespace;
- refined typography;
- subtle gradients;
- calm animations if used.

The website should feel like a serious international brand, not a template.

---

## 10. Accessibility and Performance

Follow basic accessibility:

- semantic HTML;
- readable contrast;
- keyboard-friendly links and buttons;
- alt text for images;
- responsive layout.

Performance:

- avoid unnecessary libraries;
- optimize images;
- avoid layout shifts;
- keep homepage fast.

---

## 11. Development Behavior

Before making major changes:

1. Read the relevant docs.
2. Preserve the existing architecture.
3. Update data files before changing components.
4. Keep code clean and typed.
5. Do not introduce unnecessary dependencies.
6. Explain any important architectural choice in the final summary.

---

## 12. Deliverable for Sprint 1

Create the initial Next.js project inside:

```text
website/
```

Deliver:

- working homepage;
- responsive design;
- reusable components;
- modular product data;
- clean Tailwind configuration;
- clear README instructions for running locally.

Do not build all future pages yet unless the structure requires simple placeholders.

Sprint 1 is about building the foundation and homepage.
