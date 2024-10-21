# Academic Website Redesign

A redesign for the a personal website of Dr. Shaileshh Bojja Venkatakrishnan, an Assistant Professor in the Department of Computer Science and Engineering at Ohio State University. The website redesign showcases his biography, research interests, and contact information, serving as a platform for prospective students and collaborators to learn more about his work and connect.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Individual Contributions](#individual-contributions)

## Features

- A responsive design that adapts to various screen sizes.
- Sections for biography, research interests, and contact information.
- Dynamic content loading using Middleman's templating system.
- Clean and modern aesthetics with a focus on usability.

## Technologies Used

- **Middleman**: A static site generator that builds and serves the website locally.
- **HTML/SCSS**: Used for structuring and styling the website content.
- **YAML**: Used to dynamically render entries of reusable data.
- **Markdown**: Stores large text content blocks; leveraged for the biography and notice sections.

## Installation

To set up the project locally, follow these steps:

1. **Clone Repository:**

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git cd your-repo-name
    ```

2. **Install Ruby:**  
Install ruby v3.3.3. You can check your version with:

    ```bash
    ruby -v
    ```

3. **Install Dependencies:**  
Install all required gems by running the following command:

    ```bash
    bundler install
    ```

4. **Run Middleman Server:**  
Locally host the website on port 4567 by running the following command:

    ```bash
    bundle exec middleman server
    ```

5. **Access Site Locally:**  
Open your web browser and navigate to http://localhost:4567

## Usage

- Add a new publication, dissertation or student:
        - Create an entry in the respective subsection of `research.yml` file of `data` directory.
- Add a new article or tpc role:
        - Create an entry in the respective subsection of `news.yml` file of `data` directory.
- Add a new course:
        - Create an entry in the `teaching.yml` file of `data` directory.

## Contributing

**Code Style:**

- Strictly use HTML/CSS for simplicty.
        - Integrate HTML w/ ruby code via ERB files, and SCSS w/ CSS via CSS files for more advanced functionality.
- Ensure all HTML/CSS is validated via [w3c validation service](https://validator.w3.org/)
- Refactor all reused HTML into layout files w/ dynamic frontmatter integrations.
- Break-up CSS into partials and pages files respectively.
- Use markdown files for large text blocks.
- Use YAML files for reusable data, as to easily add new data and render it dynamically.

**Git Style**:

- Create a branch for features that will not be completed within a single push.
- Prefix branch names with descriptors of work being done and use dashes as separators.
  - ‘feature/deck-card-classes’, ‘bugfix/’
- Rebase branches instead of merging them.
- Commit messages must have subject line (50 char max) and optional body copy (wrapped at 72 columns) separated by a blank line.
- Subject lines should be capitalized, not end in a period, and be written in an imperative mood.
  - 'Add', 'Implement', 'Fix'
- Body copy must only contain what and why explanations, never how. The how should be in documentation.

## Individual Contributions

**Aysha:**

- Formatted footer with copyright, credits, and contact information
- Created navigation bar drop-down menu for Research
        - Styled drop-down features like button and content
        - Created separate pages for publications, dissertations & reports, and students

**Christopher:**

- Created initial file structure with main style sheets and individual pages connected through hyperlinks
- Formatted homepage with box structure and unique headings
        - Boxes: Biography, Contact Info, and Announcements
        - Styled homepage to bind announcements to bottom of the page, and let contact info to grow in height. This allows for additional information to be added to both bio and contact info without the need to resize.
        - Created markdown file for bio and announcement text
- Styled external links for cohesivity and to fit the theme

**Nicholas:**

- Designed project file structure and site color palette.
- Created site layout page.
        - Designed header and navbar w/ linkage to separate pages and a hover effect.
- Made YAML files for all course, student, article, publication, and dissertation data.
- Created Research, Teaching, and News pages w/ all of their CSS styling.

**Sanju:**

- Created custom 404 error page for better error handling
- Customized and enhaced navbar to include:
- Dropdown, transitions, responsive behavior and hovering feature
- Active link indicator
- Styled the index (home) page
- Added drop shadows, rounded corners, left borders
- Reformatted fonts, sizing and centering
- Added base styling and defined global styles
- Created README with instructions/usage/description
