# Static Web Design

This project is a personal website for Dr. Shaileshh Bojja Venkatakrishnan, an Assistant Professor in the Department of Computer Science and Engineering at Ohio State University. The website showcases his biography, research interests, and contact information, serving as a platform for prospective students and collaborators to learn more about his work and connect.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Features

- A responsive design that adapts to various screen sizes.
- Sections for biography, research interests, and contact information.
- Dynamic content loading using Middleman's templating system.
- Clean and modern aesthetics with a focus on usability.

## Technologies Used

- **Middleman**: A static site generator that helps build and serve the website.
- **HTML/CSS**: For structuring and styling the content.
- **YAML**: For managing data
- **Markdown**: For content management in the biography and notice sections.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:

   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

2. **Install the required gems**:

Ensure you have Ruby and Bundler installed. Then run:

    bundle install
    
3. **Run the middleman server**:

Start the development server with:

    bundle exec middleman server

4. **Access the website**:

Open your web browser and navigate to http://localhost:4567

## Usage

- To add new content, edit the `.md` files in the `source/content` directory.

## Error Handling

The website implements basic error handling to enhance user experience:

- 404 Error Page: If a user navigates to a non-existent page, a custom 404 error page will be displayed. This page provides a friendly message informing users that the requested page could not be found, along with links to return to the home page or other relevant sections of the site.

## Contributions

Chris:
- Created initial file structure with main style sheets and individual pages connected through hyperlinks
- Formatted homepage with box structure and unique headings
    - Boxes: Biography, Contact Info, and Announcements
    - Styled homepage to bind announcements to bottom of the page, and let contact info to grow in height. This allows for additional information to be added to both bio and contact info without the need to resize.
    - Created markdown file for bio and announcement text
- Styled external links for cohesivity and to fit the theme


Aysha:
- Formatted footer with copyright, credits, and contact information
- Created navigation bar drop-down menu for Research 
   - Styled drop-down features like button and content
   - Created separate pages for publications, dissertations & reports, and students 

Sanju:
- Created custom 404 error page for better error handling
- Customized and enhaced navbar to include:
    - Dropdown, transitions, responsive behavior and hovering feature
    - Active link indicator
- Styled the index (home) page
    - Added drop shadows, rounded corners, left borders
    - Reformatted fonts, sizing and centering
- Added base styling and defined global styles
- Created README with instructions/usage/description

Nicholas:
