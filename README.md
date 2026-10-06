# Starter: a plain HTML site

The smallest thing you can deploy: a page with a bit of CSS and JavaScript. No build step, no server.

## Deploy it on ZeroTo
**Fastest (no GitHub needed):** in ZeroTo press **Deployments → New deployment → Start from a sample app**, pick this one and deploy. When it says **Live**, open the address. ZeroTo noticed it is only files and published it as a *static site*: it never sleeps and costs you no CPU or memory.

**Your own copy (so you can change it and have it redeploy on every push):**
1. Here on GitHub press **Use this template → Create a new repository**.
2. In ZeroTo open **Connectors** and connect GitHub (once).
3. **New deployment**, choose your copy, deploy. Then turn on **auto-deploy** in its settings (if your plan includes it).

> Anything that edits the code (here and below) needs **your own copy** — the one-click sample is read-only. Settings, variables, logs and releases work on both.

## Try these
- Change the heading in `index.html`, push, press **Redeploy** (or let auto-deploy do it), refresh.
- On the **Releases** tab roll back to version 1 and watch the old heading return.
- Add a second page `about.html` and link to it.

## Break it on purpose (and fix it)
- Delete `index.html` and redeploy. What does the build log say? Put it back.
- Rename `style.css` but not the `<link>` — the page loads unstyled. How would you find that in your browser's Network tab?
