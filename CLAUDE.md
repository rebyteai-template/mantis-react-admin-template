# AI Agent Instructions for Mantis React Admin Template

This file provides guidance for AI coding agents customizing this Vite + React admin dashboard template.

## Quick Start

1. **Dashboard**: Edit pages in `src/pages/`
2. **Components**: Customize components in `src/components/`
3. **Theme**: Modify theme settings for branding

---

## Files to MODIFY (Customize These)

### Pages
| Location | Purpose |
|----------|---------|
| `src/pages/` | Dashboard pages |
| `src/pages/dashboard/` | Main dashboard |

### Components
| Location | Purpose |
|----------|---------|
| `src/components/` | Reusable UI components |
| `src/layout/` | Layout components |

### Theme & Branding
| Location | Purpose |
|----------|---------|
| `src/themes/` | Theme configuration |
| `src/assets/` | Images, logos |

---

## Files to KEEP (Don't Modify Unless Necessary)

```
src/utils/          # Utility functions
src/hooks/          # Custom React hooks
src/store/          # State management
src/api/            # API integrations
```

---

## Build and Test

```bash
# Install dependencies
npm install

# Start dev server
npm run start

# Build for production
npm run build
```

---

## Deployment Notes

**Build output**: `dist/` or `build/` folder

For static hosting, deploy the build output folder.
