# client_project_f26

## Responsive layout

The mobile layout stacks the page content and shows the main navigation in a two-by-two grid. At `min-width: 48rem`, the navigation fits on one row, photos sit beside the related text, and topic cards form two columns.

At `min-width: 64rem`, the site identity and navigation share a header row. The “On This Page” links move into a sticky sidebar, so section links stay within reach as readers scroll. The home page uses three columns for its stage and program cards.

CSS Grid is used at every width because the navigation, cards, and sidebar need aligned rows and columns. Flexbox centers the text inside the navigation links.
