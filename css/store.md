# 01 TYPOGRPAHY SYSTEM

html {
/_ font-size: 10px; _/
font-size: 62.5%;
}

## SPACING SYSTEM (px)

2 / 4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96 / 128

## FONT SIZE SYSTEM (px)

10 / 12 / 14 / 16 / 18 / 20 / 24 / 30 / 36 / 44 / 52 / 62 / 74 / 86 / 98

# FONT WEIGHT:

Defualt: 400
Medium: 500
Semi Bold: 600
Bold: 700

# LINE HEIGHT:

Default: 1
Small: 1.05
Medium: 1.2
Paragraph Defualt: 1.6

# Letter spacing

0.5px
0.75

# 02 Color system

- Primary:#e67e22 #cf711f #eb984e
- Tints:
  #fdf2e9
  #fae5d3
- Shades: #45260a
- Accents:
- Grey:

#888
#333

#555

#fff

# 03 Shadows

# 04 Border-radius

Default: 1
Medium: 11px

# 05 Whitespace

/**\*\***\*\***\*\***/
/_TEMPLATES_/
/**\*\***\*\***\*\***/
.grid {
display: grid;
gap: 9.6rem;
grid-template-columns: repeat(2, 1fr);
}
.grid--2-col {
grid-template-columns: (repeat(2, 1fr));
}
.grid--3-col {
grid-template-columns: (repeat(3, 1fr));
}
