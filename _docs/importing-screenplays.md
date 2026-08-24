---
layout: doc
title: Importing Screenplays
description: How to import your screenplays from various formats into VoxGuion.
order: 2
---

VoxGuion can import screenplays from multiple formats. This guide covers how to get your scripts into the app.

## Supported Import Formats

### Fountain (.fountain)

Fountain is an open-source markup syntax for screenplays. It's the recommended format for best results.

**How to import:**
1. Click **Import** or drag the `.fountain` file into the app
2. VoxGuion will parse the file automatically
3. Review the detected characters and scenes

**Tips:**
- Fountain files import most accurately
- Make sure your file follows [Fountain syntax](https://fountain.io/syntax)
- Character names should be in UPPERCASE

### Final Draft (.fdx)

Final Draft is industry-standard screenwriting software. VoxGuion can read `.fdx` files directly.

**How to import:**
1. In Final Draft, save your screenplay (no export needed)
2. Import the `.fdx` file into VoxGuion
3. All formatting and character information will be preserved

### PDF Screenplays

VoxGuion can parse properly formatted PDF screenplays.

**How to import:**
1. Import the PDF file
2. VoxGuion will use OCR if needed
3. Review the parsed results and make corrections if necessary

**Limitations:**
- PDF parsing is best-effort and may require manual corrections
- Scanned PDFs may have lower accuracy
- Standard screenplay formatting works best

### Plain Text (.txt)

For simple scripts or drafts, you can import plain text files.

**Formatting requirements:**
- Character names should be in UPPERCASE and centered or left-aligned
- Dialogue should follow the character name
- Scene headings should start with INT. or EXT.

## After Import

Once your screenplay is imported:

1. **Review Characters**: Check the Characters tab to ensure all characters were detected correctly
2. **Check Scenes**: Browse through scenes to verify the dialogue was parsed accurately
3. **Make Corrections**: Use the edit tools to fix any parsing errors

## Troubleshooting

### Characters not detected
- Ensure character names are in UPPERCASE
- Check that dialogue follows character names without blank lines

### Scenes missing
- Verify scene headings start with INT., EXT., or similar
- Scene headings should be in UPPERCASE

### Dialogue attributed incorrectly
- Check the original file formatting
- Use the edit tools to manually reassign dialogue

## Best Practices

1. **Use Fountain format** when possible for best results
2. **Keep formatting consistent** throughout your screenplay
3. **Preview before generating** to catch any parsing issues early
