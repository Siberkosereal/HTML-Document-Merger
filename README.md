# HTML-Document-Merger
This script provides a simple way to consolidate multiple HTML files into one unified HTML document. It ensures all content is aggregated into a single file for easier management, searching, or archiving.
Features

    Automated Aggregation: Scans and collects every HTML file in the directory.

    Structural Dividers: Adds horizontal rules and source filenames between merged documents for clear separation.

    Encoding Safety: Uses UTF-8 encoding and includes necessary meta tags to prevent text corruption.

    Error Handling: Designed to skip unreadable files without interrupting the merging process.

Usage

    Move the script to the folder containing your HTML files.

    Run the command: python html_merger.py

    Find the consolidated result in merged_output.html.

Technical Details

    Language: Python 3.x

    Dependencies: None (Uses standard library).
