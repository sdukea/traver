# Traver

**Watch tree traversals think.** Step through pre-, in-, post- and level-order on binary trees and linked lists, learn the outline trick that solves them in seconds, then drill until exams feel easy.

**Live:** https://sdukea.github.io/traver/

## What's inside

### Visualise
- Animate **pre-order, in-order, post-order and level-order** on a **binary tree** or a **linked list**.
- Follow the code line by line in **C** (the default), **Python**, Java or C++, with a live **call stack** (or **queue** for level-order) and the output filling in beside the tree.
- Play, pause, step, scrub and change speed. Shortcuts: `Space` play/pause, `←` `→` step, `Home` restart.
- Turn **null calls** on to see the recursion step into empty children, or turn on the **exam flag trick** to see where each node gets written down.
- Load example trees (classic letters, an expression tree, a BST, a skewed "list in disguise"), type your own in level order, or generate a random one.

### The Trick
The outline method, animated:
1. **Complete the tree:** add an empty edge wherever a child is missing, so every node has exactly two (a tree with *n* nodes always needs *n + 1*).
2. **Trace the outline:** go anticlockwise around the tree once.
3. **Read it off:** write a node as you pass its left side (pre), underside (in) or right side (post).

**Practise mode** makes you do both steps yourself: tap the nodes that need empty edges, then act as the pencil and tap the nodes in order.

### Practice
- Three question types: **Tap the order**, **Name the traversal** and **Rebuild the tree from two orders**. Or choose **Mixed**.
- **Endless** mode, or a **10-question set** with a progress bar and a results breakdown by question type.
- Filter by traversal, by structure (trees or lists), or both.
- **Hints** that teach: they draw the outline-trick dots, show where the root sits, or split the in-order list for you.
- Streak, best streak and first-try accuracy are saved in your browser.

### Cheat Sheet
The four orders at a glance, one tree worked through in every order, which traversal suits which job, code you should be able to write in C or Python (recursive and iterative), rebuilding a tree step by step, complexity, linked lists and common exam traps.

### Details
- The logo is a tree too: its six letters form a balanced binary tree. Tap it to watch it traverse itself in a different order each time.
- The ⓘ button explains how the app works and lists the shortcuts.
- Designed along Apple's Human Interface Guidelines, with light and dark mode, phone-friendly layouts and support for Reduce Motion.

## Run it

It's one static `index.html` with no build step and no dependencies. Open it in a browser, or serve the folder with any static host. GitHub Pages deploys it from `main`.

## Credits

The outline trick is adapted from the YouTube video [Preorder, Inorder and Postorder in 5 Minutes](https://www.youtube.com/watch?v=XRcC7bAtL3c).
