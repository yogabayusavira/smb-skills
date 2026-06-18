# smb-design.md

## Purpose

Create local business websites that feel trustworthy, professional, and easy to use.

This file exists because AI-generated websites often default to SaaS and software-product design patterns.

Local business websites serve different visitors with different goals.

Design decisions should prioritize trust, clarity, accessibility, and conversion over trend-driven design choices.

When there is a conflict between user preference and established local business best practices, explain the tradeoff, recommend the stronger option, and allow the user to decide.

---

## Core Design Principle

Professional before impressive.

Trustworthy before modern.

Clear before clever.

Local business websites are designed to help visitors solve a problem and contact a business.

Avoid defaulting to SaaS-style patterns, startup aesthetics, or software-product design conventions.

---

## Why Local Business Websites Differ From SaaS

AI-generated websites often drift toward SaaS design patterns because SaaS websites are heavily represented in web development examples and training data.

SaaS visitors often want to:

* evaluate
* compare
* research
* understand a product

Local business visitors often want to:

* solve a problem
* contact a business
* verify trust
* confirm service availability
* get a quote
* schedule service

Design decisions should reflect those differences.

---

## Visitor Intent

Most local business visitors are already problem-aware.

They usually know what service they need.

The website should reduce friction between visitor intent and business contact.

Visitors are typically asking:

* Can this business help me?
* Can I trust them?
* Do they serve my area?
* Are they available?
* How do I contact them?

---

## Mobile-First Design

Mobile is the primary experience.

Design decisions should be evaluated on mobile first and desktop second.

Desktop layouts should adapt from the mobile experience rather than the reverse.

Prioritize:

* readability
* button accessibility
* CTA visibility
* navigation simplicity
* form usability

---

## Homepage First

The homepage establishes the design system for the entire website.

Complete and refine the homepage before expanding additional pages.

Other pages should inherit their design language from the homepage.

Use placeholders where future functionality or integrations may be added.

Examples:

* contact form processing
* booking systems
* review integrations
* maps
* CRM integrations

Do not assume specific providers or services.

---

## Navigation

The primary contact method should always be easy to find.

Visitors should never have to search for a way to contact the business.

### Top Bar

Use the top bar for useful operational information.

Prioritize:

* current business status
* business hours
* emergency service availability
* service areas
* phone number
* email address

Examples:

* Open Now
* Closed • Opens Tomorrow at 8:00 AM
* 24/7 Emergency Service
* Serving Dallas, Plano & Frisco

Avoid using the top bar primarily for promotional messaging.

### Main Navigation

A common structure:

* Home
* Services ▼
* About
* Reviews
* Contact
* Phone Number

Display the actual phone number whenever available.

Prefer:

(555) 123-4567

instead of:

Call Now

The phone number should be clickable.

### Services Dropdown

When multiple service pages exist, use a services dropdown.

Allow visitors to reach important service pages in a single click.

### Mobile Navigation

Keep mobile navigation simple.

Prioritize:

* phone access
* contact access
* menu access

Contact actions should remain highly visible.

---

## Homepage Layout

Homepage Structure:

Top Bar

Navigation

Hero

Trust Signals

Services

About

Service Areas

Reviews

FAQ

Contact Section

Footer

### Hero

Purpose:

Immediately explain what the business does and who it serves.

Desktop:

Left Side:

* Headline
* Supporting text
* Primary CTA

Right Side:

* Business image

Mobile:

* Content first
* Image below content

The hero should focus on clarity and trust.

Avoid turning the hero into a SaaS-style product explanation.

### Trust Signals

Purpose:

Provide immediate credibility.

Desktop:

4–6 trust items in a row.

Mobile:

2-column grid.

Examples:

* Google Rating
* Review Count
* Years in Business
* Licensed & Insured
* Emergency Service Available
* Satisfaction Guarantee
* Industry Certifications
* Association Memberships
* Accreditation Logos
* Partner Logos

Display logos when available.

Display text-based trust signals when logos are unavailable.

Keep this section compact and highly scannable.

### Services

Purpose:

Present primary services and direct visitors to dedicated service pages.

Desktop:

3-column card grid.

Tablet:

2-column grid.

Mobile:

Single-column stack.

Each service card contains:

* Service number
* Service title
* Short description
* Learn More button

Prefer numbered service cards.

Images may be used when real service or project photography is available.

Icons should be used sparingly and only when they improve clarity.

Each card should link to its dedicated service page.

Display the most important services first.

If additional services exist, continue the same card pattern.

Keep descriptions concise.

### About

Purpose:

Briefly introduce the business.

Desktop:

Two-column layout.

Left Side:

* Business story
* Experience
* Mission

Right Side:

* Team image
* Owner image
* Business image

Mobile:

Single-column layout.

Keep this section concise.

The goal is to humanize the business and build trust.

### Service Areas

Purpose:

Show where the business operates.

Display:

* Cities
* Neighborhoods
* Counties
* Regions

Keep descriptions short.

Visitors should quickly determine whether service is available in their area.

### Reviews

Purpose:

Display real customer feedback.

Desktop:

3 review cards per row.

Tablet:

2 review cards per row.

Mobile:

1 review card per row.

Use Google Reviews when available.

Display:

* Reviewer name
* Star rating
* Review text
* Review source
* Review date when available

Preserve clear Google attribution.

Use a grid layout.

Do not use a carousel.

### FAQ

Purpose:

Answer common customer questions.

Use an accordion layout.

Questions may include:

* Pricing expectations
* Service process
* Availability
* Emergency service
* Service areas

Keep answers concise.

Focus on practical information.

### Contact Section

Purpose:

Provide a final contact opportunity before the footer.

Desktop:

Left Side:

* Google Map

Right Side:

* Contact Form

Mobile:

* Contact Form
* Google Map

Form Fields:

* Name
* Phone
* Email
* Message

Use a placeholder implementation.

Do not assume a specific provider or backend.

---

## Services Page Layout

Page Structure:

Hero

Services List

Service Details

FAQ

Contact Section

Footer

### Services List

Desktop:

3-column grid.

Tablet:

2-column grid.

Mobile:

Single-column stack.

Each service card should include:

* Service number or title
* Short description
* Learn More button

### Service Details

For each service include:

* What the service is
* Who it is for
* Common problems it solves
* Why the business offers it

Keep content concise.

Use the same design language established on the homepage.

---

## About Page Layout

Page Structure:

Hero

Business Story

Why Choose Us

Team or Owner Section

Reviews

Contact Section

Footer

### Business Story

Include:

* How the business started
* What the business does
* Business experience
* Business values

### Why Choose Us

Examples:

* Experience
* Certifications
* Licensed and insured
* Customer service
* Local expertise
* Reliability

### Team or Owner Section

Include:

* Owner photo
* Team photo
* Short bio
* Business values

Use the same design language established on the homepage.

---

## Contact Page Layout

Page Structure:

Hero

Contact Information

Google Map

Contact Form

Footer

### Contact Information

Include:

* Phone number
* Email address
* Business hours
* Service area
* Physical address when available

Keep information easy to scan.

---

## Calls to Action

Use action-oriented CTAs.

Examples:

* Get a Quote
* Request Service
* Schedule Service
* Book Appointment
* Contact Us

CTAs should support the visitor's intent rather than educate them about the business.

---

## Forms

Every website should include a footer contact form.

This form becomes available throughout the website.

Forms should remain implementation-agnostic.

Create form placeholders and structure first.

Integrations can be connected later.

Keep forms short and practical.

---

## Icons and Visual Elements

Use icons intentionally.

AI-generated websites often overuse icons because SaaS templates frequently place icons everywhere.

Good uses:

* phone numbers
* email addresses
* locations
* business hours
* operational information

Avoid placing icons on every heading, card, list item, and section by default.

Visual restraint often appears more professional than visual excess.

---

## Layout

Keep layouts simple and readable.

Use:

* clear spacing
* strong section separation
* predictable patterns
* easy scanning
* clean alignment
* generous whitespace

Whitespace is a design tool.

Do not fill empty space simply because it exists.

A professional website often feels calmer and more trustworthy than a crowded one.

---

## Images

Use real business photos when available.

If real business photos are unavailable, use relevant Unsplash images as placeholders.

Prefer:

* real business photos
* team photos
* completed projects
* service photos
* location photos

Avoid generic stock imagery whenever possible.

Authenticity improves trust.

---

## Typography

Typography should prioritize readability.

Use clear hierarchy:

* large headlines
* clear section headings
* readable body text

Avoid decorative typography that reduces clarity.

---

## Color and Visual Style

Use a light theme.

Force the website to remain in light mode regardless of device settings.

Do not automatically switch themes based on operating system preferences.

Light mode is the standard design direction for this design system.

Use strong, professional brand colors.

Prefer:

* strong contrast
* solid colors
* clear visual hierarchy

Avoid:

* futuristic aesthetics
* excessive glow effects
* neon styling
* software-product aesthetics

Visual clarity is more important than visual novelty.

---

## Animations

Use motion carefully.

Animations should support clarity and hierarchy.

Good animation behavior:

* subtle
* short
* smooth
* functional

Avoid animation that distracts from contact and conversion.

---

## Accessibility

Make the website easy to use.

Prioritize:

* readable text
* clear buttons
* strong contrast
* usable forms
* simple navigation

Accessibility supports both usability and conversion.

---

## Best-Practice Guidance

Recommend best practices.

Do not blindly reproduce requests when stronger alternatives exist.

Explain tradeoffs.

Recommend the stronger option.

Allow the user to decide.

---

## Addons

Scan:

smb-skills/addons/

Present all available addon files as selectable options.

Allow the user to choose which addons should be included.

For each selected addon:

1. Read Requirements.
2. Check whether required integrations are already implemented.
3. Search smb-skills/integrations/ for missing integrations.
4. Append any missing integrations to todo.md.

Before appending:

* Check whether the task already exists in todo.md.
* Do not create duplicate tasks.

Todo.md is the source of truth for unfinished work.

After addon selection and todo.md updates are complete, continue to:

smb-skills/branding.md


---
## Todo Management

A todo.md file must always exist.

Whenever a new requirement, dependency, integration, missing asset, missing content, missing API key, or unfinished feature is discovered:

Append it to todo.md.

Never overwrite existing tasks.

Only append new tasks.

Before adding a task:

1. Check whether the task already exists.
2. If it already exists, do not duplicate it.

Examples:

- Missing OpenRouter integration
- Missing Resend integration
- Missing Google Maps integration
- Missing logo
- Missing business photos
- Missing Google Review URL
- Missing API keys

Todo.md acts as the single source of truth for unfinished work.

---
## Completion Standard

Before considering the design complete, confirm that it is:

* mobile-first
* local-business focused
* trust-driven
* easy to contact
* easy to scan
* professional
* conversion-oriented

Do not allow the design to drift into SaaS or software-product territory unless the business itself is a software product.

---

## Completion

Confirm the setup is complete.

After confirmation, continue to `smb-skills/branding.md`.