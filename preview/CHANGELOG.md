# @tabler/preview

## 1.5.0

### Minor Changes

- 5e119d4: Added Pay page with dedicated layout, navigation link, and card/PayPal payment form.
- 100a37b: Added background pattern utilities and documentation, including updated preview demos.
- ec94693: Added new `card-gradients.html` page showcasing various gradient card styles and components.
- b0fa655: Added Change Password modal with current password, new password with strength indicator, confirm password validation, and show/hide password toggles.
- ad22d04: Added color palette to signing component.
- b0fa655: Added Confirm Delete modal with warning icon, confirmation checkbox, and JavaScript validation to enable delete button only when confirmed.
- 4ce08ca: Added new Crypto Dashboard page with cryptocurrency portfolio overview, market data, and order history.
- b0fa655: Added Edit Profile modal with avatar upload, personal information fields, social links, and date of birth.
- 8d8727f: Added language selector dropdown to navbar with flag indicators for multilingual support.
- 4ce08ca: Refactored page-menu structure for dashboards and updated navigation menu organization.
- 48dbd1e: Migrated build system from Rollup to Vite across all packages. Replaced `rollup.config.mjs` with `vite.config.mjs` and updated build scripts to use `vite build` instead of `rollup`. Build outputs remain identical (UMD and ESM formats) with no breaking changes for end users.
- 4ce08ca: Refactored navbar-side component by consolidating separate include files (apps, language, notifications, theme, user) into a single `navbar-side.html` file for better maintainability.
- b0fa655: Added New Task modal with fields for task name, description, assigned user, priority, due date, and category tags.
- 9c5d729: Added new onboarding page with progress indicator and navigation layout.
- 9c5d729: Added Progress Background component with text labels and value display.
- 9c5d729: Added Progress Steps component for step-by-step navigation indicators.
- 99b9ea4: Added new Task List page with tables showing tasks organized by status (Upcoming, In Progress, Completed) and modal dialog for adding new tasks.
- e3d86c5: Upgraded `apexcharts` from `3.54.1` to `5.3.6` and added CSS variables (`--chart-{id}-color-{index}`) for dynamic chart colors to fix compatibility with the new version.

### Patch Changes

- 4ce08ca: Added crypto markets and orders data files (`crypto-markets.json`, `crypto-orders.json`) for cryptocurrency dashboard functionality.
- cf04a00: Update Tabler Icons to v3.35.0
- ac87b76: Updated preview templates to replace deprecated `font-weight-*` classes with Bootstrap-compatible `fw-*` utility classes.
- 5e119d4: Added `bg-blur` utility and increased `container-tight` width for layout flexibility.
- 399a5c5: Updated icons to v3.34.1 with 75 new icons.
- 8947d7c: Updated activity messages.
- 1489b13: Added `.prose` alias for markdown content and updated preview/docs references and redirects.
- 83ec6f8: Added Driver.js library integration and Tour demo page for interactive product tours and onboarding guides.
- 9c5d729: Updated trending component to use `arrow-up`/`arrow-down` instead of `trending-up`/`trending-down`.
- bd35fd3: Fixed responsive layouts on the Form Elements page.
- 41fd82b: Updated `@tabler/icons` to v3.36.1.
- c707018: Added comprehensive All Elements page with all UI components and Bootstrap elements
- Updated dependencies [5e119d4]
- Updated dependencies [100a37b]
- Updated dependencies [059bae1]
- Updated dependencies [5018aa9]
- Updated dependencies [9c5d729]
- Updated dependencies [ec94693]
- Updated dependencies [c860288]
- Updated dependencies [2dc7eda]
- Updated dependencies [c8b8b24]
- Updated dependencies [6e656ad]
- Updated dependencies [8bc6fa7]
- Updated dependencies [e206d7a]
- Updated dependencies [4ce08ca]
- Updated dependencies [b8b63d7]
- Updated dependencies [0106d6b]
- Updated dependencies [a198b0c]
- Updated dependencies [9432835]
- Updated dependencies [9c5d729]
- Updated dependencies [8d8727f]
- Updated dependencies [5e119d4]
- Updated dependencies [3aba62e]
- Updated dependencies [0c79963]
- Updated dependencies [301e778]
- Updated dependencies [48dbd1e]
- Updated dependencies [4ce08ca]
- Updated dependencies [9a3361f]
- Updated dependencies [9c5d729]
- Updated dependencies [9c5d729]
- Updated dependencies [9c5d729]
- Updated dependencies [9c5d729]
- Updated dependencies [1489b13]
- Updated dependencies [41ed22a]
- Updated dependencies [83ec6f8]
- Updated dependencies [9c5d729]
- Updated dependencies [736e604]
- Updated dependencies [f8dee0a]
- Updated dependencies [9c5d729]
- Updated dependencies [666ccd6]
- Updated dependencies [e3d86c5]
  - @tabler/core@1.5.0

## 1.4.0

### Patch Changes

- 6c38a48: Update Bootstrap to v5.3.7
- Updated dependencies [6c4dd36]
- Updated dependencies [6fec73a]
- Updated dependencies [9951fe9]
- Updated dependencies [db6200a]
- Updated dependencies [e96f055]
- Updated dependencies [a200d30]
- Updated dependencies [6c38a48]
- Updated dependencies [2a12f72]
- Updated dependencies [49ab9ea]
- Updated dependencies [666a296]
- Updated dependencies [cfd4cb6]
  - @tabler/core@1.4.0

## 1.3.2

### Patch Changes

- Updated dependencies [446c34e]
  - @tabler/core@1.3.2

## 1.3.1

### Patch Changes

- Updated dependencies [a7f73d7]
  - @tabler/core@1.3.1

## 1.3.0

### Patch Changes

- 8850f61: Enhance pagination component with new styles
