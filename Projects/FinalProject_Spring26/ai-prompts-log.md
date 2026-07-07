# AI Prompts Log

## Initial Project Prompt (April 23, 2026)
**Prompt:** "For my final Project I will be creating and hosting a Website only through AI Prompting. Some                         basic for the project are: 1. Every prompt given, and its task performed, will be saved on a                         page title AI Prompt. 2. This web page will be created for further future uses. 3. Have version                         control using Git/Github. 4. Hosted within github pages. 5. For the first page I would like a                         simple binary conversion calculator (Base 2 to Decimal, Decimal to Base 2)"

**Task Performed:** Initialized a Git repository locally in `FinalProject_0.1`. Created the foundational site                         structure including `index.html` (the binary calculator), this `ai-prompts.html` (the log page),                         `style.css` (minimalistic design system), and `script.js` (calculator logic). Prepared                         instructions for hosting the site via GitHub Pages.

---

## Refinement Prompt (April 23, 2026)
**Prompt:** "Based upon the plan provided: 1. You can create the project within a subdirectory of                         CSIT212Final titled FinalProject_0.1 2. I have not created the github repository itself or used                         github pages, directions for such should be provided. 3. For the Design I would like it be                         minimalisitc 4. The format for AI Prompts can be a smple log for now but I may want to use                         timeline in the future Proceed with the implementation plan with these factors in mind"

**Task Performed:** Created the directory `FinalProject_0.1` and configured Git. Wrote all the frontend files                         applying a clean, minimalistic aesthetic, ensuring the logs are simply formatted for now, and                         drafted the final markdown guide on GitHub Pages creation.

---

## GitHub Deployment & Log Update Prompt (April 23, 2026)
**Prompt:** "Can you create the repository from command line and push it for me? ... I have authenticated the                         login ... lets name the final Project repo CSIT212 Final Project ... seems like AI Prompts was                         not updated"

**Task Performed:** Authenticated via the GitHub CLI, created the repository remotely under the name                         CSIT212-Final-Project, pushed all local files to GitHub, and subsequently updated                         this AI Prompts log to capture these latest instructions.

---

## Ongoing Documentation Rule Prompt (April 23, 2026)
**Prompt:** "All future prompts please update the page accordingly"

**Task Performed:** Acknowledged the rule and updated the AI Prompts log to reflect this instruction. All future                         tasks will automatically include an update to this page followed by a commit and push to the                         remote repository.

---

## Title Change Prompt (April 23, 2026)
**Prompt:** "Can you change the title of the website to CSIT 212 Final Project"

**Task Performed:** Updated the &lt;title&gt; tags and navigation brand text across both                         index.html and ai-prompts.html to "CSIT 212 Final Project", added this                         log entry, and pushed the changes to GitHub.

---

## Reference Table Prompt (April 23, 2026)
**Prompt:** "on the right side of the calculator, can you add a table of decimal 0-15 and its binary                         representation"

**Task Performed:** Modified index.html to include a side-by-side flex layout and added an HTML table                         containing decimal numbers 0-15 mapped to their binary equivalents. Updated                         style.css to handle the new flex wrapper, card styling, and clean minimalistic                         table design. Added this log and pushed to GitHub.

---

## Conversion Steps Prompt (April 23, 2026)
**Prompt:** "Under the calculator, provide steps for converting decimal to binary and binary to decimal"

**Task Performed:** Appended a new section below the calculator on index.html with detailed, numbered                         steps for binary-to-decimal and decimal-to-binary conversions. Updated style.css                         with a grid layout and matching styling for the instructions, then added this log entry and                         pushed everything to GitHub.

---

## Boolean Logic Page Prompt (April 23, 2026)
**Prompt:** "Change title of Calculator to Binary Calculator, I also want to add another page that explains                         boolean logic such as AND OR XOR NAND"

**Task Performed:** Updated the title and navigation links across all pages to "Binary Calculator". Created a new                         boolean-logic.html page featuring explanatory cards and truth tables for AND, OR,                         XOR, and NAND gates, integrated it into the navigation, and pushed the updates to GitHub.

---

## GitHub Pages Hosting Query (April 23, 2026)
**Prompt:** "How do I host this website using github pages"

**Task Performed:** Updated the AI Prompts log to record the user's question, committed the update to the repository,                         and replied directly in the chat with the step-by-step instructions for enabling GitHub Pages                         from their repository settings.

---

## Interactive Boolean Logic Prompt (April 23, 2026)
**Prompt:** "Lets make the boolean logic page interactive, Allow the user to control the input bits, change                         the boolean logic gate, and display the output as a light on or off"

**Task Performed:** Designed and built an interactive Logic Gate Simulator on the boolean-logic.html                         page. Users can click to toggle input bits (0 or 1), select an AND, OR, XOR, or NAND gate via a                         dropdown, and instantly see the result represented by a light bulb indicator. Refactored                         script.js to handle logic safely across both pages, added matching premium CSS                         styling, documented this update, and pushed to GitHub.

---

## Algorithm Visualizer Prompt (April 26, 2026)
**Prompt:** "Based on Lecture_2022_20-_20Final_20Review.pdf create an interactive page that allows the user                         to visualize how each Algorithm works along with current step of the algorithm in java code"

**Task Performed:** Designed and implemented a sophisticated Algorithm Visualizer on a new page                         (algorithm-visualizer.html). Created an interactive playback system (play, pause,                         step) using a state machine generator to perfectly sync visual array sorting representations                         with live Java code highlighting. Initially added support for Merge Sort and Quick Sort,                         seamlessly integrated the new page into the website's navigation, updated CSS with smooth                         animations, documented the changes, and pushed to GitHub.

---

## Visualizer Expansion Prompt (April 26, 2026)
**Prompt:** "The user shouldnt have to scroll to visualize all the code, Also please include a short                         description of the algorithm, what it is, how it works, and real world use cases towards the                         bottom of the page. Now that quick and merge sort are working lets add the others also"

**Task Performed:** Updated CSS to remove scroll restrictions on the code panel so all Java code is fully visible.                         Added a dynamic "Algorithm Details" section below the visualizer that injects a description,                         time complexity, and real-world use cases. Implemented the 3 remaining sorting algorithms                         (Insertion Sort, Heap Sort, Counting Sort) into the interactive state machine, documented the                         changes, and pushed to GitHub.

---

## Mobile Responsiveness Prompt (April 26, 2026)
**Prompt:** "Make this website accessible on mobile"

**Task Performed:** Added comprehensive media queries to both style.css and visualizer.css.                         Ensured that navigation links, flexbox layouts, grid items, and the new algorithm visualizer                         stack vertically and resize appropriately on smaller screens (below 768px and 900px breakpoints)                         to provide a seamless mobile experience. Pushed the changes to GitHub.

---

## Layout Re-arrangement Prompt (April 26, 2026)
**Prompt:** "Move the description and instructiosn for each page toward the top"

**Task Performed:** Re-structured the DOM for all three core pages (index.html,                         boolean-logic.html, and algorithm-visualizer.html) so that their                         respective description blocks, instruction grids, and algorithm details sections are now                         prominently displayed at the top, directly beneath the main header, instead of at the bottom.                         Adjusted spacing and margins to ensure a polished look, and pushed the changes to GitHub.

---

## Circuit Builder Prompt (April 26, 2026)
**Prompt:** "Can you create a page where users can develop logic circuits"

**Task Performed:** Designed and built a complex, fully interactive Logic Circuit Builder from scratch using Vanilla                         JavaScript (circuit.js) and SVG. Created a new circuit-builder.html                         page and styled it with a grid workspace (circuit.css). Users can drag-and-drop                         Nodes (Inputs, Outputs, AND, OR, XOR, NAND, NOT), seamlessly connect them by drawing dynamic                         wire connections, and the engine automatically evaluates the topological signal flow to update                         output lights in real-time. Added a bulk update script to automatically link the new page in the                         navigation bar of all existing files, and pushed to GitHub.

---

## Navbar Polish Prompt (April 26, 2026)
**Prompt:** "The navigation bar can be spaced out better, also allow the user to press CSIT 212 Final to                         bring them back to the main page"

**Task Performed:** Updated the CSS to remove the restrictive maximum width on the navigation bar so it fills the                         screen more naturally, and increased the gap between the navigation links for better spacing.                         Ran a Python script to quickly convert the "CSIT 212 Final Project" text branding into a                         clickable hyperlink pointing back to index.html across all 5 HTML pages. Pushed the                         final adjustments to GitHub.

---

## Mobile Circuit Touch Prompt (April 26, 2026)
**Prompt:** "for the circuit builder, on a mobile phone, I am unable to move the nodes with my finger"

**Task Performed:** Updated circuit.js to fully support mobile touch events. Bound                         touchstart, touchmove, and touchend alongside the                         existing mouse event listeners. Ensured that touching a node prevents the default screen                         scrolling behavior while dragging, and implemented document.elementFromPoint to                         accurately detect when an SVG connection wire is correctly dropped onto an input port using a                         finger. Pushed the bug fix to GitHub.

---

## Local Log Instruction (April 26, 2026)
**Prompt:** "From now on, we will continually update ai-prompts-log.md after every prompt. I do not want it to be pushed to this branch though."

**Task Performed:** Acknowledged the new instruction. Confirmed that `ai-prompts-log.md` is successfully ignored by Git (via `.gitignore`) so it will never be committed or pushed to any branch, but will be continually updated locally after each task.

---

## Language Summaries & Dropdown Prompt (April 26, 2026)
**Prompt:** "Great, I feel like I reached a stage where I am unsure of what has been performed within html,css,js and python. I would like you to create a page for each language and allow the user to select a drop down menu within the navigation bar and chose the page."

### Prompting Comments
**On `implementation_plan.md` -> Section: Proposed Changes -> Automated Scripts**
* "Lets make sure this is saved to the scripts folder"

**On `implementation_plan.md` -> Section: User Review Required**
* "I want to educate the user on each concept that was performed as if the user has no knowledge and is learning. Be detailed and explain variables, classes, conditionals, etc"

**General Request**
* "also add comments performed to the ai prompts log, since it is using markdown, is it possible to create a header for this section of it (Prompting Comments, something like such. )"

**Task Performed:** Wrote an implementation plan and created four highly educational summary pages (`html-summary.html`, `css-summary.html`, `js-summary.html`, and `python-summary.html`). Each page acts as a beginner-friendly tutorial explaining core programming concepts (like semantic HTML, CSS Grid, JS Variables, Conditionals, Python File I/O) specifically in the context of how they were used to build this exact website. Wrote a Python script (`scripts/update_nav.py`) and successfully executed it to inject a hoverable "Languages" dropdown menu into the navigation bar across all 8 project files simultaneously. Added CSS dropdown styling and pushed the updates to the `Iteration-0.2` branch.

---

## Modular Automation Scripts (April 26, 2026)
**Prompt:** "why choose to create scripts? can we make them modular for future use such as allowing the user to enter input for what to do"

### Prompting Comments
* "why choose to create scripts?"
* "can we make them modular for future use such as allowing the user to enter input for what to do"

**Task Performed:** Explained that scripts are utilized to automate highly repetitive manual labor (like editing identical navigation bars across 8 different files). This guarantees zero typos and saves massive amounts of time. Wrote a new, highly modular Python script (`scripts/bulk_html_editor.py`) using the `argparse` library. This allows any user to securely run the script from their terminal, passing in custom arguments for `--target`, `--insert`, and `--mode` (before/after/replace) to bulk-edit the entire website codebase instantly on demand.

---



---# Basic HTML Wireframe (April 26, 2026)
**Prompt:** "Create a separe folder for a different website, i want you to make it the most basic html code it can be with keeping all features, I do not care about css and js for now."

### Prompting Comments
**On `implementation_plan.md` -> Section: Proposed Changes -> New Directory**
* "/HTML_Fmntl"

**On `implementation_plan.md` -> Section: Proposed Changes -> Scripting**
* "remember to create the script to allow someone like me to run a python file in terminal, I want the terminal to display instrunctions and what the user will need to do, and what the user can do "

**On `implementation_plan.md` -> Section: User Review Required (Features Question)**
* "I want it to be how like how someone would be planning the website "

**On `implementation_plan.md` -> Section: User Review Required (Git Question)**
* "No git control yet"

**Task Performed:** Created an interactive, highly readable Python script (`scripts/html_stripper.py`) that acts as a command-line wizard. It prints a clear UI in the terminal explaining its function to the user, and guides them step-by-step through generating the wireframe. Successfully executed the script to clone the 8 project files into a new `HTML_Fmntl` folder (kept outside of Git version control). The script successfully scrubbed all `<link>`, `<script>`, `<style>` blocks, and `class="..."` properties from the code, resulting in a completely raw structural skeleton ideal for website planning and semantic accessibility testing.

---

## Native HTML Dropdowns & Future-Proofing (April 26, 2026)
**Prompt:** "Create the html learning content for this question an answer, provide the concept it is, I think building a drop down list? but is this also futue proof for css and java?"

**Task Performed:** Appended a brand new educational section to `html-summary.html`. The new article directly answers the question by explaining the two primary methods for building native dropdowns (`<select>` for forms, and `<details>`/`<summary>` for expandable menus). Furthermore, the text heavily emphasizes that native HTML elements are the single most "future-proof" foundation a developer can build upon, as they guarantee out-of-the-box accessibility and cross-device compatibility before any CSS or JavaScript is even applied.

---
