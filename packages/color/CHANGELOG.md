# v0.12.0 (Thu Oct 28 2021)

:tada: This release contains work from a new contributor! :tada:

Thank you, William Pei ([@draekien](https://github.com/draekien)), for all your work!

#### 🐛 Bug Fix

- Merge remote-tracking branch 'upstream/develop' into fix/color-scheme-media-query-api-update [#981](https://github.com/system-ui/theme-ui/pull/981) ([@draekien](https://github.com/draekien))

#### Authors: 1

- William Pei ([@draekien](https://github.com/draekien))

---

# v0.11.0 (Wed Aug 25 2021)

### Release Notes

#### Add @theme-ui/css/utils with TypeScript CIF functions and fix preset types ([#1862](https://github.com/system-ui/theme-ui/pull/1862))

- Added TypeScript [Constrained identity functions](https://kentcdodds.com/blog/how-to-write-a-constrained-identity-function-in-typescript) `makeTheme`, `makeStyles` and `makeColorsScale` which can be imported from _@theme-ui/css/utils_.
- Used aformentioned functions to properly define types of presets. Exported themes are now assignable to _Theme_ but their types narrowly describe their exact values.

---

---

#### 🚀 Enhancement

- Add @theme-ui/css/utils with TypeScript CIF functions and fix preset types [#1862](https://github.com/system-ui/theme-ui/pull/1862) ([@tornewuff](https://github.com/tornewuff) [@hasparus](https://github.com/hasparus))
- feat(css): add makeTheme constrained identity function ([@hasparus](https://github.com/hasparus))

#### Authors: 2

- Piotr Monwid-Olechnowicz ([@hasparus](https://github.com/hasparus))
- Torne Wuff ([@tornewuff](https://github.com/tornewuff))

---

# v0.10.0 (Sat Jun 19 2021)

:tada: This release contains work from a new contributor! :tada:

Thank you, Vlad Shcherbin ([@vladshcherbin](https://github.com/vladshcherbin)), for all your work!

### Release Notes

#### Allow easy styling autofilled of Inputs ([#1811](https://github.com/system-ui/theme-ui/pull/1811))

Background color of autofilled inputs will now default to `theme.colors.background`. It can be changed by setting `autofillBackgroundColor` prop.

---

#### 🚀 Enhancement


#### 🐛 Bug Fix

- Allow easy styling autofilled of Inputs [#1811](https://github.com/system-ui/theme-ui/pull/1811) ([@hasparus](https://github.com/hasparus))
- fix(css): add JSDoc comment to sx.label [#1813](https://github.com/system-ui/theme-ui/pull/1813) ([@hasparus](https://github.com/hasparus))
- fix(css): add JSDoc comment to sx.label ([@hasparus](https://github.com/hasparus))
- Add missing meta repository to published packages [#1807](https://github.com/system-ui/theme-ui/pull/1807) ([@aaronadamsCA](https://github.com/aaronadamsCA))
- Add missing repository metadata to published packages [#1779](https://github.com/system-ui/theme-ui/pull/1779) ([@aaronadamsCA](https://github.com/aaronadamsCA))
- Add missing meta repository to published packages ([@aaronadamsCA](https://github.com/aaronadamsCA))

#### 🏠 Internal

- Docs: update JSX pragma guide with automatic runtime section [#1718](https://github.com/system-ui/theme-ui/pull/1718) ([@flo-sch](https://github.com/flo-sch) [@hasparus](https://github.com/hasparus))

#### Authors: 5

- [@dependabot[bot]](https://github.com/dependabot[bot])
- Aaron Adams ([@aaronadamsCA](https://github.com/aaronadamsCA))
- Florent SCHILDKNECHT ([@flo-sch](https://github.com/flo-sch))
- Piotr Monwid-Olechnowicz ([@hasparus](https://github.com/hasparus))
- Vlad Shcherbin ([@vladshcherbin](https://github.com/vladshcherbin))

---

# v0.8.3 (Wed May 05 2021)

#### ⚠️ Pushed to `stable`

- Merge branch 'stable' into develop ([@hasparus](https://github.com/hasparus))

#### Authors: 1

- Piotr Monwid-Olechnowicz ([@hasparus](https://github.com/hasparus))

---

# v0.8.0 (Wed May 05 2021)

#### 🚀 Enhancement

- v0.8 [#1688](https://github.com/system-ui/theme-ui/pull/1688) ([@lachlanjc](https://github.com/lachlanjc) [@hasparus](https://github.com/hasparus))

#### 🐛 Bug Fix

- Merge remote-tracking branch 'origin/develop' into v0.8 ([@hasparus](https://github.com/hasparus))
- fix(color-modes): default useCustomProperties to true, as in the docs ([@hasparus](https://github.com/hasparus))
- Merge branch 'config' into config-2 [#1421](https://github.com/system-ui/theme-ui/pull/1421) ([@hasparus](https://github.com/hasparus))
- Merge branch 'develop' into config ([@lachlanjc](https://github.com/lachlanjc))

#### ⚠️ Pushed to `stable`

- Merge branch 'stable' into develop ([@hasparus](https://github.com/hasparus))

#### Authors: 3

- Brent Jackson ([@jxnblk](https://github.com/jxnblk))
- Lachlan Campbell ([@lachlanjc](https://github.com/lachlanjc))
- Piotr Monwid-Olechnowicz ([@hasparus](https://github.com/hasparus))

---

# v0.7.5 (Wed Apr 28 2021)

#### ⚠️ Pushed to `stable`

- Merge branch 'develop' into stable ([@hasparus](https://github.com/hasparus))

#### Authors: 1

- Piotr Monwid-Olechnowicz ([@hasparus](https://github.com/hasparus))

---

# v0.7.0 (Thu Apr 15 2021)

#### 🚀 Enhancement

- WIP: Build packages with Preconstruct 2 [#1423](https://github.com/system-ui/theme-ui/pull/1423) ([@alexanderchan](https://github.com/alexanderchan) [@hasparus](https://github.com/hasparus))

#### 🐛 Bug Fix

- Merge branch 'develop' into preconstruct-2 ([@hasparus](https://github.com/hasparus))
- wip(workspace): update to preconstruct 2 ([@hasparus](https://github.com/hasparus))
- Merge branch 'add/preconstruct' into preconstruct-2 ([@hasparus](https://github.com/hasparus))
- Remove types reference since it comes from cjs.d.ts ([@alexanderchan](https://github.com/alexanderchan))
- Remove references to microbundle ([@alexanderchan](https://github.com/alexanderchan))
- Remove unused files ([@alexanderchan](https://github.com/alexanderchan))
- Run preconstruct fix to update main ([@alexanderchan](https://github.com/alexanderchan))

#### ⚠️ Pushed to `stable`

- Merge branch 'develop' into stable ([@hasparus](https://github.com/hasparus))

#### Authors: 2

- Alex Chan ([@alexanderchan](https://github.com/alexanderchan))
- Piotr Monwid-Olechnowicz ([@hasparus](https://github.com/hasparus))
