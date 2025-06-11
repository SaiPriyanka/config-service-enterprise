Design a responsive React component using Tailwind CSS based on the following dashboard UI:

- The title at the top says "Config Service" with a subtitle "Application Properties Management".
- There are two tabs or buttons on the top-right: "Sync All" (blue button) and "Add Label".
- A search bar exists just below the title to search labels.
- There are six config cards in a 3x2 grid layout. Each card contains:
    - A title (e.g. "Production API", "Frontend Config", etc.)
    - A description (e.g. "Main production API configuration")
    - A GitHub repo link
    - A branch name (e.g., "main", "develop", "staging")
    - A properties count badge (e.g., "10 properties")
    - A sync status: Synced ✅, Pending ⏳, Error ❌, or Never.
    - A last synced time (e.g., "15m ago")
    - A large blue "Sync Now" button
    - Optional small icons: visibility 👁 and edit ✏️ in the top right

Use semantic HTML and ensure the layout is mobile responsive. Include color-coded badges and
