# Chess Training with DITA

This project provides chess training material using DITA XML format. It includes basic rules, piece movements, and special moves.

## Folder Structure

- `topics/`: DITA topic files
- `maps/`: DITA map file linking all topics
- `images/`: Image resources
- `out/`: Generated output (HTML, PDF)

## How to Build

1. Install [DITA-OT](https://www.dita-ot.org/)
2. Run the following command:

```bash
dita -i maps/chess-rules.ditamap -f html5 -o out/html

3. Open out/html/index.html to view the result.