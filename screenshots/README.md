# GitLens Screenshots

This directory should contain screenshots demonstrating GitLens features in action while analyzing the HTTPie codebase.

## Required Screenshots

### 1. Line-by-Line Blame
**File:** `line-blame-example.png`
**Description:** Screenshot showing GitLens line blame annotations in VS Code, displaying author information and commit details for specific lines of code in the HTTPie codebase.

### 2. File History View
**File:** `file-history-view.png`
**Description:** Screenshot of the GitLens file history panel showing the commit history for a specific file (e.g., `httpie/core.py` or `httpie/client.py`).

### 3. Commit Details Panel
**File:** `commit-details.png`
**Description:** Screenshot showing detailed commit information including author, date, commit message, and file changes.

### 4. Repository Insights Dashboard
**File:** `repository-insights.png`
**Description:** Screenshot of GitLens repository insights showing contributor patterns, commit frequency, and project statistics.

### 5. Function Analysis Example
**File:** `function-analysis.png`
**Description:** Screenshot demonstrating how GitLens shows the history of a specific function, including when it was added and who has modified it.

## How to Take These Screenshots

1. **Install GitLens Extension**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X)
   - Search for "GitLens"
   - Install the extension

2. **Clone the HTTPie Repository**
   ```bash
   git clone https://github.com/httpie/cli.git
   cd cli
   ```

3. **Open in VS Code**
   ```bash
   code .
   ```

4. **Enable GitLens Features**
   - GitLens should automatically start working
   - You may need to configure Git credentials if not already done

5. **Navigate to Key Files**
   - `httpie/__main__.py`
   - `httpie/core.py`
   - `httpie/client.py`

6. **Take Screenshots**
   - Use Windows Snipping Tool or similar
   - Capture the specific GitLens features in action
   - Save with descriptive filenames

## Screenshot Guidelines

- **Resolution:** At least 1920x1080 for clarity
- **Format:** PNG or JPG
- **Content:** Focus on the GitLens interface elements
- **Context:** Include enough surrounding code/interface to provide context
- **Annotations:** Consider adding arrows or highlights to point out key features

## Example Screenshot Descriptions

### Line Blame Example
Show the main function in `httpie/__main__.py` with GitLens blame annotations visible, highlighting:
- Author information on the right side
- Commit hash and date
- Hover tooltip with detailed commit information

### File History Example
Show the GitLens file history panel for `httpie/core.py`, displaying:
- List of commits that modified the file
- Author names and dates
- Commit messages
- File change statistics

### Commit Details Example
Show a detailed commit view, including:
- Full commit message
- Author and timestamp
- Files changed
- Line-by-line changes (diff view)

## Note
These screenshots should be taken with the actual HTTPie repository open in VS Code with GitLens enabled. The screenshots will demonstrate the real functionality of GitLens and provide visual evidence of the analysis described in `gitlens_insights.md`. 