# Med Orbit LLC medical billing site

## Page structure

The homepage follows a lead-generation flow inspired by the BellMedEx homepage: grouped navigation, a two-column hero with an inquiry form, a service overview, detailed workflow content, a reporting example, specialties, onboarding, FAQs, and repeated contact prompts. The brand, copy, services, and sample dashboard come from the Med Orbit LLC concept; BellMedEx content and claims were not copied.

## Edit the site manually

Open `index.html` in a code editor such as Notepad or VS Code. The site is kept in one file so it is straightforward to change:

- Press **Ctrl+F** and search for the exact sentence, heading, or button label you want to change.
- Replace the text between the HTML tags, keeping the tags themselves in place. For example, change the words inside `<h2>…</h2>`.
- Service cards are grouped in the section with `id="services"`; specialties use `id="specialties"`; FAQs use `id="faq"`; contact content uses `id="contact"`.
- The styles are in `<style>` blocks near the top. Colors are set in the `:root` variables: `--blue`, `--blue-dark`, `--blue-pale`, `--blue-tint`, `--blue-surface`, and `--paper`.
- The sample dashboard figures are explicitly marked as illustrative. Replace them with verified figures or remove that snapshot section before publishing.
- The contact form is a front-end preview. It does not transmit or save submissions; connect a backend or form service before using it with real visitors.

## Edit visible text in the browser

Open `index.html`, click **Edit this website** at the bottom right, then **Start editing**. Click outlined text to change it. Your changes save in that browser. Export a JSON backup to keep or move edits, import it to restore them, or choose **Reset text** to return to the starter copy.

## Reference and publishing

The layout pattern was informed by [BellMedEx](https://bellmedex.com/). This is an original Med Orbit LLC concept, not a copy of BellMedEx’s text, claims, or branding. Verify your organization’s actual contact information, credentials, data, links, and legal notices before publishing.
