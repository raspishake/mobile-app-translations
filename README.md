# mobile-app-translations
Language translations for the mobile app

# Guide
Each entry in the translation file contains:
1. The first line starts with "# " is the source in English that needs to be translated.
2. The second line starts with "// " is the comment for the source and is optional.
3. Put your translation on the next line right below the comment line, or below the source line if there's no comment line.
4. Then put an empty line to separate with the next entry. This is optional but a good practice.

# Placeholder
Different languages put words together in different orders. So if the source contains "%x" (x is a number), it's a placeholder for the actual data. Your translation might change the order but must keep these placeholders. For example:
```
# %1 to %2
// Event filter in Magnitude(5.2 to 9.5) or Depth(194 km to 0 km)
%1 et %2
```
