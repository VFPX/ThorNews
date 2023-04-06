# How to contribute to ThorNews

## Bug report?
- Please check [issues](https://github.com/VFPX/ThorNews/issues) if the bug is reported
- If you're unable to find an open issue addressing the problem, open a new one. Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

## New version
Here are the steps to updating to a new version:

1. Create a fork at github
   - See this [guide](https://www.dataschool.io/how-to-contribute-on-github/) for setting up and using a fork
2. Make whatever changes are necessary.
---

3. Increment the new version number in _NewsItems\CurrentItemNumber.txt_.
1. Create the new item as _NewsItems\Item_NN.txt_, keeping the very top and the very bottom of the new item consistent with previous items; we suggest copying the latest item and then editing the main part of it that applies to the new item.
1. In _NewsItems\Archives.md_, add in a link to the new item at the very top, again being consistent with the layout of earlier items.
---
6. Commit
1. Push to your fork
1. Create a pull request


----
Last changed: _2023/04/02_ ![Picture](vfpxpoweredby_alternative.gif)
