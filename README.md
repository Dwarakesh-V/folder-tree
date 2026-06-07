Directory tree printer with gitignore-style filtering.

Usage:
    tree.py <folder> [--ignore PATTERN ...] [--ignore-file FILE]

Examples:
    tree.py .
    tree.py . --ignore "*.pyc" "__pycache__" ".git"
    tree.py . --ignore-file .gitignore
    tree.py . --ignore "*.log" --ignore-file .gitignore
