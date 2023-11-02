# Filtering ecommerce

## Task Assignment

Create a new price filter for an e-commerce website. Draft a product assignment for the development team with a focus on the front-end. For example, format it as a Jira issue. Address edge cases and prioritize user experience. Note: The website receives more traffic from mobile devices than desktops.

## Output

Title: (feat) Price Filter Component

Labels: feature, frontend, backend

Assignee: @ui, @backend

Priority: Medium

Sprint: 34

Estimation: 2 sprints

Description:

As a user, I want to be able to filter products by price on the e-commerce site so that I can easily find items within my budget, with a particular focus on mobile usability.

There will be two values that user would be able to filter, but both of them can be set null, so in that case it will be ingnored. Values `from` and `to` (numbers should by type of `Float`).

- [ ] UX - Check if creating new filter won't break UI on all breakpoins (from desktop to mobile)
- [ ] UX - Find out an option how to use slider and manual input, ideally figure out how to combine two of those
- [ ] UX - The slider can have visual markers for price increments as nice to have.
- [ ] UI - As other filters, price filter should be persistant between refresh (put data in URL query), there should be option to clear that filter
- [ ] Q&A - Ensure that this feature won't break other stuff and that it works well with pagination, refreshing a page, other filters, does not compromise performance
- [ ] Backend - write filter functionality with optional arguments to filter by price via two values (from and to). Both of them are nullable. Tests should cover behaviour with other filters. Validation of arguments is required.

Acceptance Criteria:

- State should be preserved during the session even if the user navigates away from the page.
- Include a 'clear filter' option to reset the price filter easily.
- Fits between existing filter options and plays well with them.
- Ensure the price filter component is touch-friendly for mobile use.
- Prices should dynamically update in the view as the slider is adjusted with some delay so we would lower backend requests. Ensure that there is no lag in performance when the price filter is used.
- The price filter must be a slider component allowing a range selection (min-max).
