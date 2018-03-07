# ats2-mode for Emacs/Spacemacs

**NOTE:** Changes are only being tested on Spacemacs with the assumption that
the effect inside vanilla Emacs will be identical. If something doesn't work
as advertised in Emacs, then please open an issue.

### Key changes (from mrd/ats2-mode)

- Nested brackets highlight correctly.
- Use font-lock's faces for function definitions/keywords/constants/strings etc.
  This makes the appearance consistent with other major modes that you might be
  using for other languages.
- This awesome `Readme`.

### Installing

1. Clone this repo/download the `.el` file.
2. If you're using `Spacemacs` add the following line to the end of `dotspacemacs/user-config` in `.spacemacs`

   ```
   (add-to-list 'load-path "~/path/to/ats2-mode/")
   (require 'ats2-mode)
   ```
   If you're using vanilla Emacs, you probably need to add it somewhere inside
   `.emacs`.
