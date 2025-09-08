# Team Workflow Cheat Sheet

## 1. One Page at a Time
- Work in **vertical slices** (UI + API + style).
- A page is **done** when it works end-to-end with mock API.

## 2. Contract-First
- Write API contract in `docs/api/feature.md` **before coding**.
- Frontend uses mocks until backend is ready.

## 3. Mock First
- Use MSW/mock services.  
- Toggle with `VITE_API_MODE=mock|real`.

## 4. Dev Panel
- Add `DevMenu` in dev mode to jump between pages & overlays.

## 5. Roles per Slice
- A: UI + flow  
- B: API + mocks  
- C: Styling + tests  

## 6. Issues & PRs
- Max 2 issues per dev.  
- Small PRs (<300 LOC).  
- Merge via PR review → `dev`.

## 7. Work Order
1. API contract  
2. Mock handler  
3. UI skeleton  
4. Connect backend  
5. Polish (style, a11y, copy)

## 8. Don’ts
- Don’t build backend first.  
- Don’t spread over many pages.  
- Don’t push huge PRs.  
- Don’t block navigation → use DevMenu.