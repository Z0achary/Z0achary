equences for the `less` pager. This mapping can be further customized by the user after the plugin is
loaded. Check out sources for more.

For example: `less_termcap[md]` maps to `LESS_TERMCAP_md` which is the escape sequence that tells `less`
how to print something in bold. It's currently shown in bold red, but if you want to change it, you
can redefine `less_termcap[md]` in your zshrc file, after OMZ is sourced:
