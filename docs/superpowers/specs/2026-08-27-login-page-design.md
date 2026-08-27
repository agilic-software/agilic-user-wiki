# Design: User Wiki — Login Page

**Date:** 2026-08-27
**Status:** Approved

## Purpose

The `agilic-user-wiki` repo is a Docsify-based documentation site (currently just a bare
`index.html` + `README.md`, no content yet). This spec adds the first real content page,
documenting the Login screen for end users, and establishes the basic docs structure the
rest of the wiki will build on.

Source of truth for the page content: `agilic-ui/agilic-app/src/app/components/auth/login/login.component.html`.

## Scope

- Stand up a `docs/` folder as the Docsify content root, with a sidebar for navigation.
- Add one new page: a full walkthrough of the Login screen (not just core sign-in — every
  user-facing element on that screen: email/password sign-in, Google sign-in, Register,
  Reset password, Terms & Privacy links, org-invite branding banner, "Read me" link, and
  the "Do Not Share Personal Information" link).
- Text-only content for now — no screenshot embedded (none available); a placeholder note
  marks where one can be added later.

Out of scope: any other wiki pages, build/deploy tooling, visual redesign of `index.html`.

## Structure

```
docs/
  README.md              — Docsify homepage for the site
  _sidebar.md             — nav: Home, Getting Started > Signing In
  getting-started/
    login.md              — the new login page
```

`index.html` (repo root) is updated so Docsify loads content from `docs/` and renders the
sidebar (`loadSidebar: true`, `basePath: 'docs/'`... or homepage/coverpage config equivalent
— exact Docsify config keys resolved during implementation).

The repo-root `README.md` is left as-is (GitHub's repo description shown on the repo page);
it is not part of the Docsify site content — `docs/README.md` is the site's actual homepage.

## Page content outline (`docs/getting-started/login.md`)

1. **Title & intro** — "Signing In" — one-paragraph purpose of the login screen.
2. **Arriving via an invite** — note about the org-branding banner (inviter's logo/company
   name) shown when the user follows an invite link.
3. **Signing in with email and password**
   - Enter email
   - Enter password (mentions the show/hide toggle)
   - Agree to Terms & Conditions / Privacy Policy (both are links)
   - Click "Sign In"
4. **Field validation** — the two error states: email required / email not valid; password
   required.
5. **Signing in with Google** — the "Or Continue with" alternative sign-in path.
6. **New user?** — link to Register.
7. **Forgot your password?** — link to Reset password.
8. **First-time user? "Read me"** — link to onboarding info.
9. **Privacy** — "Do Not Share Personal Information" link.
10. **Screenshot placeholder** — a short HTML comment or note marking where a real
    screenshot can be dropped in later.

Footer details on the live screen (copyright line, version number) are not documented —
they aren't user-facing help content.

## Testing / Validation

No automated tests (static Docsify content). Validation is manual: open `index.html` (e.g.
via a local static server) and confirm the sidebar renders and the login page displays
correctly with working internal links.
