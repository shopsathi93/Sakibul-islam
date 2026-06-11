# Sakibul Islam - Personal Portfolio

A completely static portfolio website ensuring high SEO visibility and performance.
Built entirely using purely HTML5, CSS3, and JavaScript without build frameworks, ensuring seamless direct hosting on GitHub Pages out-of-the-box.

## Features

- **No Build Steps**: Directly host-ready for GitHub Pages.
- **AI Chatbot**: Uses direct client-side fetch calls via REST to the Gemini Api without any node.js backend requirement.
- **Tailwind CSS Play CDN**: Implemented via `@tailwindcss/browser` without npm or build processes.
- **SEO Optimized**: Proper meta titles, descriptions, and sitemaps are included.

## Configuration

When deploying on GitHub Pages:
The \`config/gemini-config.js\` will contain \`GEMINI_API_KEY\`. As this runs purely in-browser, you should configure your Google API Key with Domain Restrictions strictly limiting it to \`https://sakibulislam.pro.bd/\` so your quotas are not abused.
