---
layout: doc
title: Supported File Formats
description: Complete list of screenplay and audio formats supported by VoxGuion.
order: 6
---

This page lists all file formats supported by VoxGuion for import and export.

## Import Formats (Screenplays)

### Fountain (.fountain)
- **Description**: Open-source plain text screenplay format
- **Support level**: Full support (recommended)
- **Details**: All Fountain syntax elements are recognized
- **Learn more**: [fountain.io](https://fountain.io)

### Final Draft (.fdx)
- **Description**: Industry-standard screenwriting software format
- **Support level**: Full support
- **Details**: Reads all character, dialogue, and scene information
- **Versions**: Final Draft 8 and later

### PDF (.pdf)
- **Description**: Portable Document Format
- **Support level**: Good support with some limitations
- **Details**: Uses intelligent parsing and OCR when needed
- **Best results**: Properly formatted screenplay PDFs

### Plain Text (.txt)
- **Description**: Simple text files
- **Support level**: Basic support
- **Requirements**: Standard screenplay formatting conventions
- **Best for**: Quick imports of draft scripts

### Rich Text Format (.rtf)
- **Description**: Formatted text documents
- **Support level**: Basic support
- **Details**: Formatting is stripped, text is parsed

## Export Formats (Audio)

### MP3 (.mp3)
- **Description**: Most common audio format
- **Quality options**: 128, 256, 320 kbps
- **Best for**: Sharing, podcasts, general playback

### WAV (.wav)
- **Description**: Uncompressed audio format
- **Quality options**: 16-bit, 24-bit
- **Best for**: Professional editing, highest quality needs

### M4A (.m4a)
- **Description**: Apple's AAC audio format
- **Quality options**: 128, 256 kbps
- **Best for**: Apple devices, good quality with compression

## Character Encoding

All text import formats support:
- UTF-8 (recommended)
- UTF-16
- ASCII
- Latin-1 (ISO-8859-1)

**Tip**: Save your screenplay files as UTF-8 for best compatibility with special characters and international scripts.

## Screenplay Formatting Requirements

For best import results, ensure your screenplays follow these conventions:

### Scene Headings
```
INT. LOCATION - TIME
EXT. LOCATION - TIME
```

### Character Names
```
CHARACTER NAME
(in uppercase, before dialogue)
```

### Dialogue
```
CHARACTER NAME
The dialogue text goes here, following
the character name.
```

### Parentheticals
```
CHARACTER NAME
(whispering)
The dialogue with direction.
```

### Action Lines
```
Regular prose describing action, not in uppercase.
```

## Limitations

### PDF Import
- Scanned documents may have OCR errors
- Non-standard formatting may cause parsing issues
- Very complex layouts may not parse correctly

### Plain Text Import
- Requires consistent formatting
- May need manual corrections after import
- No metadata is preserved

## Recommended Workflow

For the best experience:

1. **Write in Fountain or Final Draft** for native support
2. **Export to Fountain** from other screenwriting apps if possible
3. **Use PDF as last resort** for scripts you can't get in other formats
4. **Review after import** to catch any parsing issues
