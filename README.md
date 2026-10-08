# Secondary structure editor

Open a DSSP-annotated CIF or mmCIF file and select **Run viewer**. Change colors, title, letter size, spacing, wrapping, and numbering. Select residues or a range to override how structures are drawn. Undo or restore file assignments, then download the SVG.

All processing happens in your browser. No protein data is included in this repository, and selected files are not uploaded to a server. Edits are session-only; export your picture before leaving.

Reads DSSP summary annotations, or a polymer sequence scheme with supported label-numbered structure ranges. Does not calculate secondary structure from atomic coordinates. The original whitespace-separated residue table format is also supported. Maximum file size: 25 MB.

This is a static GitHub Pages site with no build dependencies. Serve index.html from the repository root.
