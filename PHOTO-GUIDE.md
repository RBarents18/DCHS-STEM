# Replacing the course photos

The site uses ordinary HTML and local JPGs. There is no upload service or build step.

Replace the matching file in `images/courses/` to update both its homepage card and course project highlight:

| File | Course |
| --- | --- |
| `calculus.jpg` | AP Calculus AB |
| `computing.jpg` | AP Computer Science Principles |
| `automotive.jpg` | Automotive |
| `engineering.jpg` | Engineering 102 HS; also the homepage hero |
| `design.jpg` | Intelligent Design |

Use a clear landscape JPG, ideally 1600 pixels wide, with the important subject near the center. Card and hero crops vary by screen size. Keep file sizes around 100–400 KB when possible.

After replacement:

1. Update that image's `alt` text and intrinsic `width`/`height` in `index.html` and its course HTML file. Describe the actual scene.
2. Adjust the neighboring project title and description if the photograph shows a different activity.
3. Update the stock-photo notice: retain it for any stock photos still present, and identify custom photos accurately. The homepage hero has its own stock caption.
4. Update `photo-credits.html` and `images/courses/photo-sources.json` for any remaining stock imagery.

To add more photographs to a course, copy its `featured-project` article or add a figure to a project-summary card, give the new JPG a descriptive filename, and include descriptive alt text. Use photos cleared for school website publication.

## Content ownership

- Website: course introductions, project examples, subject tools, and reusable study/design guidance.
- Google Classroom: syllabus, current unit handouts, project instructions, rubrics, assignments, deadlines, submissions, and feedback.

All Classroom buttons currently lead to the general sign-in page. You can replace the course page's Classroom URL with its enrolled-class URL once available. Do not publish class join codes in the public HTML.

`showcase.css` styles the six refreshed pages and photo credits. The original `styles.css` remains intact for legacy pages. All existing course filenames and homepage section IDs are retained.
