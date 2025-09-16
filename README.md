# SupportGroups.online Marketing Site

This repository contains the static marketing site for **SupportGroups.online**, an initiative of **Mr. Metaphysical Health & Wellness (MMHW)**. The site introduces visitors to the platform, outlines how it works, showcases available group categories, provides simple pricing tiers, and encourages users to join or refer friends.

## Structure

* `index.html` – The main page built using plain HTML and [Tailwind CSS](https://tailwindcss.com) via CDN. It includes:
  * A header with branding and navigation links.
  * A hero section describing the platform and a search bar (non‑functional in this static version).
  * A list of upcoming groups with sample data.
  * A **Browse by category** section highlighting different support group topics.
  * A **How it works** section with three simple steps.
  * A **Pricing** section with three tiers (Community, Member, Facilitator).
  * A call‑to‑action banner and footer with additional links.

## Customization

* Update the content directly in `index.html` to reflect real group data, pricing or copy changes.
* Tailwind classes are used extensively for styling; you can modify styles by adjusting classes or adding your own custom CSS in the `<style>` block at the top of the file.
* The search bar and buttons are placeholders; hook them up to back‑end logic or external services as you build out the application.

## Running Locally

Open `index.html` in your browser to view the site. No build step is required.

## Deployment

For simple static hosting, drag and drop the `supportgroups-site` folder to Netlify Drop or upload via GitHub Pages. Ensure that the `index.html` file is located at the root of the deployed directory so it serves as the default document.