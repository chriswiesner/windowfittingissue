# windowfittingissue

demo app to demonstrate issue with padding applied to childs of CoordinatorLayout when setting `fitsSystemWindows=true`

Using `AppBarLayout` produces following result:

![appbar_layout](doc/appbarlayout.png)

Please check the different implementations:
- `master`: CoordinatorLayout
- `conventional`: FrameLayout with custom WTFs
- `appbar_layout`: AppBarLayout container as suggested here: https://twitter.com/chrisbanes/status/920203521982631941
