# lrslib (fork)

This is a fork of lrslib 7.3 (2024.5.30) by David Avis, the reverse-search
vertex enumeration library: http://cgm.cs.mcgill.ca/~avis/C/lrs.html

Modifications (2026, confined to `lrslib.c` and `lrslib.h`): a
`commondenom` input option that makes lrs print each enumerated vertex as
a `*vertexcommon` line, a common denominator followed by the integer
numerators of the coordinates. The certificate generator `lrs-postprocess`
parses this output to build its certificates. Everything else is unchanged
from upstream.

Build with `make lrsgmp` (needs GMP). lrslib is distributed under the GNU
General Public License version 2, see COPYING.
