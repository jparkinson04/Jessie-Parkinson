# Getting started

1. Unzip this folder somewhere sensible, e.g. `~/Sites/jessieparkinson-site`.
2. Open it in VS Code: File → Open Folder.
3. Open the VS Code terminal (Ctrl+` or View → Terminal) and run `claude`.
   If it's not installed yet: `npm install -g @anthropic-ai/claude-code`, then `claude`.
4. Claude Code reads `CLAUDE.md` automatically, so it knows the rules. Try a first prompt like:
   "Fill in the Echo card with this sentence and link: ... Then replace the footer links with ..."
5. To preview: right-click `index.html` → Open with Live Server (install the "Live Server" extension), or just open the file in a browser.

# Going live

- Cloudflare Pages: Workers & Pages → Create → Upload assets → drag this folder in. Then Custom domains → add jessieparkinson.com. Free.
- Or Netlify: drag the folder onto app.netlify.com/drop, then add the domain.
- Buy the domain first (Cloudflare Registrar or Namecheap). If you host on Cloudflare Pages, buying the domain there too makes the DNS step one click.
