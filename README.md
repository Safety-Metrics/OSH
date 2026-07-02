# State OSHA Steel Erection Dashboard.

This dashboard is a single static `index.html` file that reads the published Google Sheet CSV directly in the browser.

## Publish With GitHub Pages

1. Create a GitHub repository, or use the existing dashboard repository.
2. Put `index.html` in the repository root.
3. In GitHub, open `Settings` > `Pages`.
4. Set source to `Deploy from a branch`.
5. Select the `main` branch and `/ (root)`.
6. Save.

GitHub will provide the Pages URL after the first deployment finishes.

## Update The Data

Update the Google Sheet. If the published CSV link stays the same, the dashboard will show the updated data after refresh.

CSV source:

```text
https://docs.google.com/spreadsheets/d/e/2PACX-1vR8SxjBcpMRRNWaSO74ZmuI1vgrtKoj4Ktly45QpRHK1QLKFp492sLX79rfEGxLEXnq9CfvVklyw1MH/pub?gid=0&single=true&output=csv
```
