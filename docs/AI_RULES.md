# AI Rules for Codex

Codex must follow these rules when working on HAPI.

## 1. Product architecture

Do not hardcode product content randomly inside components.

Create structured data files:

```text
website/data/products.ts
website/data/ingredients.ts
website/data/audiences.ts
```

Components should render from data.

## 2. Design reference

The visual reference is located in:

```text
assets/references/
```

Codex should use it as design inspiration, not as a pixel-perfect copy.

## 3. Claims

Do not write medical claims.

Avoid:
- cures;
- treats;
- prevents disease;
- guaranteed effect;
- clinical claims without source.

Use:
- supports;
- designed for;
- formulated with;
- helps maintain;
- made for moments when.

## 4. Brand tone

The tone must be:

- premium;
- clear;
- calm;
- practical;
- science-aware;
- human.

Avoid hype.

## 5. Website stack

Use:

- Next.js
- TypeScript
- Tailwind CSS
- Vercel-compatible setup.

## 6. First build task

Create HAPI Website v1 with:

- homepage;
- products section;
- science section;
- audience section;
- AI consultant CTA block;
- B2B CTA;
- investor CTA;
- responsive layout.

## 7. Maintainability

Every future change should be easy.

When adding a new product, update product data first, not the layout manually.
