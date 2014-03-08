console-colors.c
================

Write formatted string to console with colors.

h3. Example

    printf("  url: ");
    cc_fprintf(CC_FG_DARK_GRAY, stdout, "%s\n", pkg->href);
    
Will output `  url: URL` where `URL` is in dark gray.

h3. List of colors

Foreground

	CC_FG_NONE
	CC_FG_BLACK
	CC_FG_DARK_RED
	CC_FG_DARK_GREEN
	CC_FG_DARK_YELLOW
	CC_FG_DARK_BLUE
	CC_FG_DARK_MAGENTA
	CC_FG_DARK_CYAN
	CC_FG_GRAY
	CC_FG_DARK_GRAY
	CC_FG_RED
	CC_FG_GREEN
	CC_FG_YELLOW
	CC_FG_BLUE
	CC_FG_MAGENTA
	CC_FG_CYAN
	CC_FG_WHITE

Background

	CC_BG_NONE
	CC_BG_BLACK
	CC_BG_DARK_RED
	CC_BG_DARK_GREEN
	CC_BG_DARK_YELLOW
	CC_BG_DARK_BLUE
	CC_BG_DARK_MAGENTA
	CC_BG_DARK_CYAN
	CC_BG_GRAY
	CC_BG_DARK_GRAY
	CC_BG_RED
	CC_BG_GREEN
	CC_BG_YELLOW
	CC_BG_BLUE
	CC_BG_MAGENTA
	CC_BG_CYAN
	CC_BG_WHITE
