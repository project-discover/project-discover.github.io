---
# An instance of the Accomplishments widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: accomplishments

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Approach
subtitle: "Discover is developed using the OCaml programming language. It includes two main parts"

# Date format
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization` and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   You can begin a multiline `description` using YAML's `|-`.

---
1. Compiler front-end: this module compiles input programs (written in C/C++, Java, Go, Solidity, etc) to intermediate code of LLVM framework (LLVM bitcode).
2. Analyzer back-end: this module will perform suitable analysis technique to detect each kind of bug and vulnerability. For example, we use separation logic to find memory bugs, abstract interpretation and data flow analysis to find integer bugs and other bugs specific to detect smart contracts.

