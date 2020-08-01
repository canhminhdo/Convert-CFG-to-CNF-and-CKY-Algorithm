# Convert CFG grammar to CNF grammar and applying CKY for parsing a sentence

This project is about how to convert CFG to CNF and use the CKY algorithm to parse a sentence
based on converted CNF grammar.

**Input:**

- cfg_rule.txt file.

- sentence.txt file.

**Output:**

- cnf_rule.txt file.

- 1 image for CKY table for the sentence.

- 1 image for CKY table filled values by the CKY algorithm for the sentence.

## 1. Prerequisites

- Install dependencies for the project, such as `numpy` and `matplotlib`.

- Input files are located in the `input` folder.

- Output files are located in the `output` folder, so you should create the folder beforehand.

## 2. Some notices when converting a CFG grammar to a CNF grammar

- By default, the start symbol will appear in the left-hand side in the first line of given CFG grammar.

- `S*` should not appear into your CFG grammar, because we use it as default for the new start symbol
when the original start symbol appears on the right-hand side.

- If you want to try with `λ production`, please use `λ` symbol in your rules.
