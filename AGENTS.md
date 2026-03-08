# Repository Guide

This repository is a Markdown recipe collection organized by meal/category folders.

## What is in this repo

- Top-level folders are cuisine/use-case categories: `baking`, `booze`, `breakfast`, `dessert`, `drinks`, `fermented`, `mains`, `preserves`, `salads`, `sauces`, `sides`.
- Most recipe files are standalone Markdown documents (`.md`) with a title, ingredients, and method.
- `mains` is further split into `meat`, `vegetable`, and `pasta`.
- `dessert` includes nested subcategories (for example `cheesecake/baked` and `cheesecake/no-bake`).
- A small number of entries are placeholders (source link only) or partially structured.

## Existing content conventions

Observed common pattern:

1. `# Recipe Title`
2. Optional source/note line(s)
3. `## Ingredients`
4. `## Method`
5. Optional sections like `## Notes`, `## Tips`, `## Variations`

Formatting style in current files:

- Ingredients usually use unordered bullets (`- item`).
- Method usually uses ordered steps (`1. ...`).
- Optional ingredient groups are represented as plain labels (for example `Sauce:`) or subheadings.
- Source references are often included as plain URLs or HTML comments near the top.

## Rules for adding new recipes

- Put each new recipe in the most specific category folder.
- Use lowercase kebab-case filenames with a `.md` extension.
- Keep one recipe per file.
- Start with a single H1 title that matches the recipe name.
- Include `## Ingredients` and `## Method` for complete recipes.
- If a recipe is only a captured reference, keep it explicit as a placeholder and include the source link.

Recommended template:

```md
# Recipe Name

<!-- Optional source URL -->

Optional short context note.

## Ingredients

- quantity ingredient
- quantity ingredient

## Method

1. Step one.
2. Step two.

## Notes

- Optional serving, storage, or variation notes.
```

## Rules for editing existing recipes

- Preserve the original voice and intent unless asked to rewrite.
- Prefer minimal edits: fix what is necessary without reformatting unrelated sections.
- Keep existing source attribution (plain link or HTML comment).
- Do not rename or move files unless explicitly requested.
- When touching a file, fix obvious local issues (typos, broken numbering, missing punctuation) only if they are in edited lines.

## Style guidance

- Use clear, concise, imperative steps.
- Keep ingredient lines easy to scan: quantity first, then ingredient.
- Prefer metric units, but keep original units when part of the source recipe.
- Keep Markdown simple; avoid heavy formatting.
- Use images only when they add value (finished dish, key technique, or reference capture).

## Abbreviations used in recipes

Common abbreviations already used in this repository include:

- `t` = teaspoon
- `T` = tablespoon
- `g` = grams
- `kg` = kilograms
- `ml` = millilitres
- `l` = litres
- `oz` = ounces

Guideline:

- Keep the abbreviation style used in a given recipe file.
- For new recipes, prefer one style and stay consistent within the file (for example, use either `t`/`T` or `tsp`/`tbsp`, not both).

## Units

Always prefer metric units.

## Quality check before finishing

- File is in the correct folder and has a `.md` extension.
- H1 title is present and accurate.
- `## Ingredients` and `## Method` exist for complete recipes.
- Steps are readable and in a logical cooking order.
- Temperatures, times, and quantities are internally consistent.
- Links and image URLs are valid-looking and not malformed.

## Known repository quirks

- There is one recipe file without a `.md` extension: `mains/vegetable/lemon-spinach-risotto`.
- Some files are intentionally short placeholders that only preserve a source link.

Treat these as legacy content unless a task explicitly asks to normalize them.
