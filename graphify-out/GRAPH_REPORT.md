# Graph Report - GestorPro  (2026-09-26)

## Corpus Check
- 102 files · ~631,478 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 4 file(s) not represented in the graph (top: (none) 2, .css 2)

## Summary
- 445 nodes · 1039 edges · 28 communities (20 shown, 8 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `09b0f624`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- react
- useCerrarConEscape
- App.tsx
- supabase.ts
- devDependencies
- compilerOptions
- package.json
- compilerOptions
- Finanzas/index.tsx
- ModalUsuario.tsx
- What You Must Do When Invoked
- lucide-react
- TablaAnalisisProductos.tsx
- tsconfig.json
- Resumen/types.ts
- public.sesiones
- MiniReporteDiario.tsx
- graphify reference: extra exports and benchmark
- graphify reference: query, path, explain
- graphify reference: add a URL and watch a folder
- graphify reference: commit hook and native CLAUDE.md integration
- graphify reference: incremental update and cluster-only
- graphify reference: GitHub clone and cross-repo merge
- graphify reference: transcribe video and audio
- CLAUDE.md
- .claude/CLAUDE.md
- extraction-spec.md
- README.md

## God Nodes (most connected - your core abstractions)
1. `react` - 66 edges
2. `lucide-react` - 55 edges
3. `useCerrarConEscape()` - 35 edges
4. `supabase` - 31 edges
5. `usePermiso()` - 26 edges
6. `Product` - 23 edges
7. `clicConTeclado()` - 21 edges
8. `compilerOptions` - 20 edges
9. `compilerOptions` - 18 edges
10. `traerTodo()` - 17 edges

## Surprising Connections (you probably didn't know these)
- `handleNavigate()` --calls--> `puedeVerModulo()`  [EXTRACTED]
  src/App.tsx → src/utils/permisos.ts
- `TopBar()` --calls--> `usePermiso()`  [EXTRACTED]
  src/layout/TopBar.tsx → src/utils/permisos.ts
- `ModalUsuario()` --calls--> `clicConTeclado()`  [EXTRACTED]
  src/sections/Configuraciones/components/ModalUsuario.tsx → src/utils/clicConTeclado.ts
- `ModalUsuario()` --calls--> `normalizarEmail()`  [EXTRACTED]
  src/sections/Configuraciones/components/ModalUsuario.tsx → src/utils/sesion.ts
- `ModalUsuario()` --calls--> `useCerrarConEscape()`  [EXTRACTED]
  src/sections/Configuraciones/components/ModalUsuario.tsx → src/utils/useCerrarConEscape.ts

## Import Cycles
- None detected.

## Communities (28 total, 8 thin omitted)

### Community 0 - "react"
Cohesion: 0.06
Nodes (45): react, EtiquetaStock(), Props, FiltrosInventario(), Props, HeaderInventario(), Props, ModalLote() (+37 more)

### Community 1 - "useCerrarConEscape"
Cohesion: 0.11
Nodes (33): ModalAbono(), Props, ModalAnularPago(), Props, ModalClientes(), Props, ModalDetalleFiado(), Props (+25 more)

### Community 2 - "App.tsx"
Cohesion: 0.10
Nodes (30): App(), handleNavigate(), src_assets_finanzas, src_assets_inventario, src_assets_logo, src_assets_proyectos, SideBar(), SideBarProps (+22 more)

### Community 3 - "supabase.ts"
Cohesion: 0.16
Nodes (22): supabase, Finanzas(), Reportes(), DashboardResumen(), Props, TarjetaMetrica(), FiltrosUtilidades(), Props (+14 more)

### Community 4 - "devDependencies"
Cohesion: 0.12
Nodes (17): devDependencies, autoprefixer, eslint, @eslint/js, eslint-plugin-react-hooks, eslint-plugin-react-refresh, globals, postcss (+9 more)

### Community 5 - "compilerOptions"
Cohesion: 0.09
Nodes (21): compilerOptions, allowImportingTsExtensions, erasableSyntaxOnly, jsx, lib, module, moduleDetection, moduleResolution (+13 more)

### Community 6 - "package.json"
Cohesion: 0.06
Nodes (36): dependencies, lucide-react, react, react-dom, react-to-print, recharts, @supabase/supabase-js, @tailwindcss/vite (+28 more)

### Community 7 - "compilerOptions"
Cohesion: 0.10
Nodes (19): compilerOptions, allowImportingTsExtensions, erasableSyntaxOnly, lib, module, moduleDetection, moduleResolution, noEmit (+11 more)

### Community 8 - "Finanzas/index.tsx"
Cohesion: 0.12
Nodes (19): react-to-print, FiltroFechas(), Props, ModalApertura(), Props, BloqueArqueoProps, ModalCierre(), Props (+11 more)

### Community 9 - "ModalUsuario.tsx"
Cohesion: 0.24
Nodes (10): FormularioEmpresa(), ModalUsuario(), ModalUsuarioProps, PERMISOS_DEFAULT, TablaUsuarios(), Configuraciones(), DatosEmpresa, Empleado (+2 more)

### Community 10 - "What You Must Do When Invoked"
Cohesion: 0.07
Nodes (26): For /graphify add and --watch, For /graphify query, For the commit hook and native CLAUDE.md integration, For --update and --cluster-only, /graphify, Honesty Rules, Interpreter guard for subcommands, Part A - Structural extraction for code files (+18 more)

### Community 11 - "lucide-react"
Cohesion: 0.23
Nodes (9): lucide-react, FiltrosProveedores(), Props, ModalProveedor(), Props, Props, TablaProveedores(), Proveedor (+1 more)

### Community 12 - "TablaAnalisisProductos.tsx"
Cohesion: 0.24
Nodes (11): formatearFecha(), ModalDetalleProducto(), Props, Props, TablaAnalisisProductos(), AnalisisProducto, MetricaCategoria, MetricaDia (+3 more)

### Community 15 - "public.sesiones"
Cohesion: 0.67
Nodes (3): public.empleados, public.sesiones, sesiones_empleado_id_idx

### Community 16 - "MiniReporteDiario.tsx"
Cohesion: 0.33
Nodes (4): react-dom, src_index, MiniReporteDiario(), Props

### Community 17 - "graphify reference: extra exports and benchmark"
Cohesion: 0.22
Nodes (8): graphify reference: extra exports and benchmark, Step 6b - Wiki (only if --wiki flag), Step 7 - Neo4j export (only if --neo4j or --neo4j-push flag), Step 7a - FalkorDB export (only if --falkordb or --falkordb-push flag), Step 7b - SVG export (only if --svg flag), Step 7c - GraphML export (only if --graphml flag), Step 7d - MCP server (only if --mcp flag), Step 8 - Token reduction benchmark (only if total_words > 5000)

### Community 18 - "graphify reference: query, path, explain"
Cohesion: 0.33
Nodes (5): For /graphify explain, For /graphify path, graphify reference: query, path, explain, Step 0 — Constrained query expansion (REQUIRED before traversal), Step 1 — Traversal

### Community 19 - "graphify reference: add a URL and watch a folder"
Cohesion: 0.50
Nodes (3): For /graphify add, For --watch, graphify reference: add a URL and watch a folder

### Community 20 - "graphify reference: commit hook and native CLAUDE.md integration"
Cohesion: 0.50
Nodes (3): For git commit hook, For native CLAUDE.md integration, graphify reference: commit hook and native CLAUDE.md integration

### Community 21 - "graphify reference: incremental update and cluster-only"
Cohesion: 0.50
Nodes (3): For --cluster-only, For --update (incremental re-extraction), graphify reference: incremental update and cluster-only

## Knowledge Gaps
- **167 isolated node(s):** `name`, `private`, `version`, `type`, `dev` (+162 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 192 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **8 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `react` connect `react` to `useCerrarConEscape`, `App.tsx`, `supabase.ts`, `package.json`, `Finanzas/index.tsx`, `ModalUsuario.tsx`, `lucide-react`, `TablaAnalisisProductos.tsx`, `MiniReporteDiario.tsx`?**
  _High betweenness centrality (0.192) - this node is a cross-community bridge._
- **Why does `lucide-react` connect `lucide-react` to `react`, `useCerrarConEscape`, `App.tsx`, `supabase.ts`, `package.json`, `Finanzas/index.tsx`, `ModalUsuario.tsx`, `TablaAnalisisProductos.tsx`, `MiniReporteDiario.tsx`?**
  _High betweenness centrality (0.127) - this node is a cross-community bridge._
- **Why does `devDependencies` connect `devDependencies` to `package.json`?**
  _High betweenness centrality (0.051) - this node is a cross-community bridge._
- **What connects `name`, `private`, `version` to the rest of the system?**
  _167 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `react` be split into smaller, more focused modules?**
  _Cohesion score 0.061971830985915494 - nodes in this community are weakly interconnected._
- **Should `useCerrarConEscape` be split into smaller, more focused modules?**
  _Cohesion score 0.10857142857142857 - nodes in this community are weakly interconnected._
- **Should `App.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.1036036036036036 - nodes in this community are weakly interconnected._