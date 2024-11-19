# Blog Comments Repository

This repository is dedicated to storing and managing comments for the blog posts hosted on [shujaurrahman.me/blogs](https://shujaurrahman.me/blogs/). It utilizes [Utterances](https://utteranc.es/), a lightweight and open-source commenting system powered by GitHub Issues.

## Features

- **Comment Storage**: Each blog post's comments are linked to an issue in this repository based on the blog post's title or unique identifier.
- **Discussion Management**: Blog-specific discussions are seamlessly handled through GitHub Issues.
- **Effortless Integration**: Uses Utterances for a clean and hassle-free comment interface.
- **Secure and Open**: Comments are stored in GitHub Issues, providing transparency and easy management.

## How It Works

1. **Linking Comments**: 
   - Each blog post on [shujaurrahman.me/blogs](https://shujaurrahman.me/blogs/) is associated with an issue in this repository.
   - The association is based on the post's title and date.
   
2. **Utterances Integration**:
   - Utterances is embedded in the blog posts for handling comments.
   - Comments submitted through Utterances are stored as comments under the corresponding GitHub Issue in this repository.
   
3. **Issue Discussions**:
   - Blog discussions are initiated or continued as issues, enabling a focused space for feedback, questions, and discussions.

## Setup

To enable comments on your blog posts using this repository:

1. Install [Utterances](https://utteranc.es/) and configure it in your blog with the following settings:
   - **Repository**: This repository (`shujaurrahman/blog-comments`).
   - **Mapping**: Choose the mapping strategy (`title`, `url`, or `pathname`) to link blog posts with GitHub Issues.
   
   I store issue-term with title of blog concatinated with date of blog.

2. Include the Utterances script in your blog's code:
   ```html
   <script src="https://utteranc.es/client.js"
           repo="shujaurrahman/blog-comments"
           issue-term="date.title"
           theme="github-light"
           crossorigin="anonymous"
           async>
   </script>
   ```

3. Deploy your blog with Utterances enabled.


