# DIYbio Widgets

An open source web-based visualization and editing toolkit for do-it-yourself biology (DIYbio).

Access to tools. GPL'd.

## What Widgets?

+ Plasmid & Sequence Editor
    + For both circular and linear sequences
    + Spec:
        + Radial visualization of sequences as *features* (sub-sequences)
        + Visualization interactions, hover, highlight, select
        + Effective, visible labels
        + Full *annotation* for each *feature* , displayed conveniently on hover
        + Side-by-side display of radial plasmid visualization and plain text sequences.
        + Sequence and *feature* highlighting
        + Insert and delete operations
        + Visualization zoom
        + Toggles for display components for diagram creation
+ Sequence checker
    + Diff tool to check, verify, and visualize sequences
    + Spec:
        + Handles AB1 or ABI files.
        + Use Smith-Waterman Algorithm
        + Needs both analog line graph output and sequence diffing in plain text
        + Use vertical diff (rather than long, side-scrolling horizontal)
+ Standard Protocol Format
    + Complete set of operations and a grammar to specify and simulate DIYbio practices
    + Spec:
        + Requires a standard set of operations
        + Provides simulation
        + Share and re-use protocols
        + Possibly generate protocols based on desired results
+ Folding prediction
    + Tool to identify problematic folds in DNA, RNA, etc
+ Codon Switcher
    + Switches order of codons to optimize modifications to have lower risk of failure.


