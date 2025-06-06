This repository contains add-ons to Org.

You can use them by installing the `org-contrib` NonGNU ELPA package
from <https://elpa.nongnu.org/nongnu/>.


# Please help maintaining these add-ons

Files in this repository used to live in the Org repository but have
been filtered out of the Org 9.5 release.  The `contrib/` directory used
to contain a `scripts/` directory that now lives on [the Worg repository](https://code.orgmode.org/bzg/worg/src/master/code).

**Files in this repository receive little if no maintainance and there
is no guaranty that they are compatible with the Org stable version.**

For files a `Maintainer` header and a `Homepage` pointing outside of this
repository are in transition: they are maintained and will be removed
from the next minor or major release of this repository.  As a user,
please carefully track the new URL where the add-on is now maintained.

If you want to maintain some of these add-ons, please send an email to
<mailto:emacs-orgmode@gnu.org> or to <mailto:yantar92@posteo.net>
(privately) once you set up a separate repository for them.


# License

All files in this repository are licensed under the GNU General Public
License, either version 3 of the License, or (at your option) any
later version.  See [COPYING](COPYING).


# Contribute

You can send patches to `emacs-orgmode@gnu.org`.

See <https://orgmode.org/worg/org-contribute.html> for advice on how to
contribute efficiently.


# Files to remove from the next release

If a file has a "Homepage:" keyword, it will be removed from the next
minor or major release.


# Other files


## Org utils

-   **org-annotate-file.el:** Annotate a file with org syntax
-   **org-bibtex-extras.el:** Extras for working with org-bibtex entries
-   **org-checklist.el:** org functions for checklist handling
-   **org-choose.el:** Use TODO keywords to mark decision states
-   **org-collector.el:** Collect properties into tables
-   **org-contribdir.el:** Dummy file to mark the org contrib Lisp directory
-   **org-depend.el:** TODO dependencies for Org-mode
-   **org-effectiveness.el:** Measuring your personal effectiveness
-   **org-eldoc.el:** Eldoc documentation for SRC blocks
-   **org-expiry.el:** Expiry mechanism for Org entries
-   **org-git-link.el:** Provide org links to specific file version
-   **org-interactive-query.el:** Interactive modification of tags query
-   **org-invoice.el:** Help manage client invoices in OrgMode
-   **org-learn.el:** SuperMemo's incremental learning algorithm
-   **org-license.el:** Insert free licenses to your org documents
-   **org-mac-iCal.el:** Imports events from iCal.app to the Emacs diary
-   **org-mairix.el:** Hook mairix search into Org for different MUAs
-   **org-panel.el:** Simple routines for us with bad memory
-   **org-registry.el:** A registry for Org links
-   **org-screen.el:** Visit screen sessions through Org-mode links
-   **org-screenshot.el:** Take and manage screenshots in Org-mode files
-   **org-secretary.el:** Team management with org-mode
-   **org-sudoku.el:** Create and solve SUDOKU puzzles in Org tables
-   **org-toc.el:** Table of contents for Org-mode buffer
-   **org-track.el:** Keep up with Org development
-   **org-wikinodes.el:** CamelCase wiki-like links for Org


## Org exporters

-   **ox-bibtex.el:** Export bibtex fragments
-   **ox-confluence.el:** Confluence Wiki exporter
-   **ox-deck.el:** deck.js presentations exporter
-   **ox-extra.el:** Convenience functions for org export
-   **ox-freemind.el:** Freemind exporter
-   **ox-groff.el:** Groff exporter
-   **ox-s5.el:** S5 presentations exporter


## Org link

-   **ol-bookmark.el:** Links to bookmarks
-   **ol-elisp-symbol.el:** Links to Emacs-lisp symbols
-   **ol-git-link.el:** Links to specific file version
-   **ol-mew.el:** Links to Mew messages
-   **ol-vm.el:** Support for links to VM messages
-   **ol-wl.el:** Support for links to Wanderlust messages


## Org Babel languages

-   **ob-abc.el:** Org-mode Babel Functions for ABC
-   **ob-csharp.el:** Org-mode Babel Functions for csharp evaluation
-   **ob-ebnf.el:** Org-mode Babel Functions for EBNF
-   **ob-eukleides.el:** Org-mode Babel Functions for eukleides evaluation
-   **ob-fomus.el:** Org-mode Babel Functions for fomus evaluation
-   **ob-hledger.el:** Org-mode Babel Functions for hledger
-   **ob-io.el:** Org-mode Babel Functions for Io
-   **ob-J.el:** Org-mode Babel Functions for J
-   **ob-ledger.el:** Org-mode Babel Functions for Ledger
-   **ob-mathomatic.el:** Org-mode Babel Functions for mathomatic evaluation
-   **ob-mscgen.el:** Org-mode Babel Functions for Mscgen
-   **ob-oz.el:** Org-mode Babel Functions for Oz evaluation
-   **ob-picolisp.el:** Org-mode Babel Functions for Picolisp
-   **ob-shen.el:** Org-mode Babel Functions for Shen
-   **ob-stan.el:** Babel Functions for Stan
-   **ob-stata.el:** Org-mode Babel Functions for Stata evaluation
-   **ob-tcl.el:** Org-mode Babel Functions for tcl evaluation
-   **ob-vala.el:** Org-mode Babel Functions for Vala
-   **ob-vbnet.el:** Org-mode Babel Functions for VB.Net evaluation

