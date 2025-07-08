# Astro DB Snippets

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-astrodb-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-astrodb-snippets)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-astrodb-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-astrodb-snippets)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-astrodb-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-astrodb-snippets)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-astrodb-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-astrodb-snippets&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-astrodb-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-astrodb-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-astrodb-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-astrodb-snippets/blob/main/LICENSE)

> A professional Visual Studio Code extension offering a comprehensive set of database-related code snippets for Astro DB development.

## Overview

Astro DB Snippets accelerates and standardizes database schema and query construction within VS Code by providing ready‑to‑use, well‑documented code patterns. It is designed to streamline the development of database models, queries, and migrations in projects using Astro DB.

## Getting Started

1. Install [Visual Studio Code](https://code.visualstudio.com/).
2. Open the **Extensions** view (`Ctrl+Shift+X` on Windows/Linux or `⌘+Shift+X` on macOS).
3. Search for **Astro DB Snippets** or install directly from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-astrodb-snippets).
4. Reload VS Code to enable the extension.

## Key Features

- **Schema Snippets**: Quickly generate column definitions for primary keys, text, number, boolean, date, JSON, and foreign key references.
- **Query Snippets**: Insert common query patterns such as `select`, `limit`, `orderBy`, `groupBy`, joins, filters, and pagination clauses.
- **Mutation Snippets**: Build `insert`, `update`, and `delete` operations, including conflict resolution (`onConflictDoNothing`, `onDuplicateKeyUpdate`).
- **Logical Operators**: Apply boolean conditions (`and`, `or`, `not`, `inArray`, `between`, `like`, etc.) with a single keystroke.
- **Join and Subquery Support**: Generate `leftJoin`, `innerJoin`, `fullJoin`, `$with`, and nested query constructs effortlessly.

## Provided Snippets

Type the prefix of any snippet below, then press **Tab** or **Enter** to expand.

| Snippet                      | Description                             |
| ---------------------------- | --------------------------------------- |
| `db_primary_key`             | Define a primary key column             |
| `db_text`                    | Define a text column                    |
| `db_number`                  | Define a numeric column                 |
| `db_boolean`                 | Define a boolean column                 |
| `db_date`                    | Define a date column                    |
| `db_json`                    | Define a JSON column                    |
| `db_references`              | Define an integer foreign key reference |
| `db_select`                  | `select(...)` query                     |
| `db_select_distinct`         | `selectDistinct(...)`                   |
| `db_select_distinct_on`      | `selectDistinctOn(...)`                 |
| `db_limit`                   | `limit(...)`                            |
| `db_order_by`                | `orderBy(...)`                          |
| `db_group_by`                | `groupBy(...)`                          |
| `db__with`                   | `$with(...)` subquery                   |
| `db_with`                    | `with(...)` subquery                    |
| `db_update`                  | `update(...)` mutation                  |
| `db_insert`                  | `insert(...)` mutation                  |
| `db_on_conflict_do_nothing`  | `onConflictDoNothing()`                 |
| `db_on_conflict_do_update`   | `onConflictDoUpdate(...)`               |
| `db_on_duplicate_key_update` | `onDuplicateKeyUpdate(...)`             |
| `db_delete`                  | `delete()` mutation                     |
| `db_left_join`               | `leftJoin(...)`                         |
| `db_right_join`              | `rightJoin(...)`                        |
| `db_inner_join`              | `innerJoin(...)`                        |
| `db_full_join`               | `fullJoin(...)`                         |
| `db_eq`                      | `eq(...)` condition                     |
| `db_ne`                      | `ne(...)` condition                     |
| `db_gt`                      | `gt(...)` condition                     |
| `db_gte`                     | `gte(...)` condition                    |
| `db_lt`                      | `lt(...)` condition                     |
| `db_lte`                     | `lte(...)` condition                    |
| `db_is_null`                 | `isNull()` check                        |
| `db_is_not_null`             | `isNotNull()` check                     |
| `db_in_array`                | `inArray(...)`                          |
| `db_not_in_array`            | `notInArray(...)`                       |
| `db_exists`                  | `exists()` check                        |
| `db_not_exists`              | `notExists()` check                     |
| `db_between`                 | `between(...)`                          |
| `db_not_between`             | `notBetween(...)`                       |
| `db_like`                    | `like(...)`                             |
| `db_ilike`                   | `ilike(...)`                            |
| `db_not_ilike`               | `notIlike(...)`                         |
| `db_not`                     | `not(...)`                              |
| `db_and`                     | `and(...)`                              |
| `db_or`                      | `or(...)`                               |
| `db_array_contains`          | `arrayContains(...)`                    |
| `db_array_contained`         | `arrayContained(...)`                   |
| `db_array_overlaps`          | `arrayOverlaps(...)`                    |

## Contributing

Contributions to the Angular Starter Extension Pack are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-astrodb-snippets).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-astrodb-snippets/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-astrodb-snippets/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-astrodb-snippets/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-astrodb-snippets/blob/main/LICENSE) file for full details.
