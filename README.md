# FASTA Motif Viewer

A lightweight, browser-based tool for detecting regulatory motifs 
in upstream FASTA sequences with mismatch tolerance and 
publication-quality output.

## Live Tool
👉 [Open FASTA Motif Viewer](https://subaas10.github.io/FASTA-motif-viewer/fasta_motif_viewer.html)

No installation required — runs entirely in your browser.

## Features
- Upload any upstream FASTA sequences (multiple files supported)
- Search for any regulatory motif (e.g. promoter elements, 
  transcription factor binding sites)
- Mismatch tolerance — detect degenerate or variant motifs
- Colour-coded nucleotide display (WebLogo style: A/T/G/C)
- Compressed gap notation [Xnt] for clean sequence display
- Auto-calculated distance to ATG start codon
- Toggle ATG start codon marker on/off
- Filter strains with hits, without hits, or exact matches only
- Export results as TSV for downstream analysis
- Print/PDF export for publication-quality figures
- Case-sensitive search option for soft-masked sequences

## Usage
1. Click the live link above
2. Upload your FASTA file(s) containing upstream sequences
3. Type your motif of interest in the Motif Identifier panel
4. Adjust mismatch tolerance as needed
5. Export as TSV or Print/PDF for publication

## Input Format
Plain FASTA format. Any standard FASTA header is accepted:

## Development Note
The concept and design of this tool were developed by 
Subaas Sritharan. The implementation was developed with 
the assistance of Claude (Anthropic) and ChatGPT (OpenAI) 
based on the author's specifications.

## Author
Sritharan Subaas
University of Colombo, Sri Lanka

## License
MIT License — see LICENSE file for details.
