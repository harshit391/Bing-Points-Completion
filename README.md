# Bing-Points-Completion

A simple browser-based tool that automates Bing searches to help complete Microsoft Rewards daily search points.

## How to Use

1. Open `index.html` in your browser.
2. Keep the browser open and wait approximately 4 minutes.
3. The tool will automatically open Bing search tabs at 7-second intervals.
4. Once all searches are complete, you will be redirected to a confirmation page.

## How It Works

- Opens 34 Bing search tabs with unique numeric queries (69 through 102).
- Each search is spaced 7 seconds apart to simulate normal browsing.
- A random session ID (CVID) is generated per run for unique search sessions.
- After all searches complete, the page redirects to `done.html`.

## Requirements

- A modern web browser (Chrome, Edge, Firefox, etc.).
- Pop-ups must be allowed for this site. If your browser blocks pop-ups, add an exception for `index.html` or allow pop-ups when prompted.
- You must be signed into your Microsoft account on Bing for points to be credited.

## Notes

- The total runtime is approximately 4 minutes (34 searches x 7 seconds).
- Make sure not to close the original `index.html` tab while the tool is running.
- This tool runs entirely client-side with no external dependencies.
