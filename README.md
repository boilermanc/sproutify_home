# Sproutify Home (Mobile)

Expo + React Native rewrite of the Sproutify mobile app using **TypeScript** and **Supabase**.  
Goal: preserve existing functionality and backend (auth, DB, storage, RLS, realtime), while modernizing the UI and developer experience.

## Tech Stack
- **Runtime:** Expo (React Native, TS)
- **Navigation:** React Navigation (stack/tabs)
- **Data:** TanStack Query (fetch/cache/mutations)
- **State:** Zustand (auth + light global state)
- **Validation:** Zod
- **Backend:** `@supabase/supabase-js` (auth, PostgREST, storage, realtime)

## Repo Status
This is a fresh repo for the rewrite. Initial scaffolding will include:
