ALL: NFDI4Chem.png NFDI4Chem2.png NFDI4Chem-square.png NFDI4Chem.ico

# PNG
NFDI4Chem.png: NFDI4ChemHex.svg
	inkscape --without-gui --file=NFDI4ChemHex.svg --export-png=NFDI4Chem.png --export-dpi=150

NFDI4Chem2.png: NFDI4ChemHex2.svg
	inkscape --without-gui --file=NFDI4ChemHex2.svg --export-png=NFDI4Chem2.png --export-dpi=150

# Squaree PNG with white background
# suitable as avatar

NFDI4Chem-square.png: NFDI4Chem.png
	convert -background none NFDI4Chem.png -gravity center -extent 304x304 NFDI4Chem-square.png

NFDI4Chem.ico: NFDI4Chem.png
	convert -background white NFDI4Chem.png -gravity center -extent 304x304 -resize 48x48 NFDI4Chem.ico

NFDI4ChemHex4Ico.ico: NFDI4ChemHex4Ico.svg
	inkscape --without-gui --file=NFDI4ChemHex4Ico.svg --export-png=NFDI4Chem4Ico.png --export-dpi=150
	convert -background white NFDI4Chem4Ico.png -gravity center -extent 304x304 -resize 48x48 NFDI4Chem4Ico.ico
