# Notes To Self

<!-- * TODO: Remember not to commit unless commiting all files -->
<!-- Reasoning, I accidently deleted some files that werent staged commited -->
<!-- FreeCodeCamp's reccommended CSS design rules -->

**Contrast Ratio**:

- 4.5:1 contrast is the bare minimum. -- AA standard
- 7:1 contrast is the top notch standard for accessibility. -- AAA standard
- 21:1 contrast is the highest possible contrast ratio, achieved by pure black and pure w.hite. -- AAA standard and higher
  You can acquire the required contrast ratio by altering hue, saturation, and the light values of the colors.

**_Visual Hierarchical_**

Using changing sizes in the headings and text can help create a distinct visual heirarchy in the page.

- Callout boxes can be used to draw attention to a specific section of the page.
- You can also use the callout boxes to add a visual button of importance other wise known as a CTA (Call to Action).
- Scaling is also important! Using scaling can help create a path for the user/reader to follow and can also help create a visual hierarchy

Visual hierarchy is important as it conveys other components like the navigation bar.

<!-- Agent's generation/ruleset of alignment -->

**Alignment**:

- Left-alignment is the most common and is generally the easiest to read.
- Center-alignment can be used for titles and headings, but should be used sparingly for body text as it can be harder to read.
- Right-alignment can be used for specific design purposes, but should also be used sparingly for body text as it can be harder to read.
- Justified text can create a clean look, but can also create uneven spacing between words, making it harder to read. It is generally not recommended for body text.
- vertical alignment can be used to create a sense of balance and harmony in the design. It can also help to create a visual hierarchy by aligning elements in a way that guides the user's eye through the page.
- When using alignment, it is important to consider the overall design and layout of the page, as well as the readability of the text. It is also important to ensure that the alignment is consistent throughout the page to create a cohesive and visually appealing design.

<!-- FreeCodeCamp's reccommended CSS design rules -->

**White Spaces**:

- White space is used to create a balance between the elements on screen.
- Macro white space is the space between larger elements like images, text blocks, and buttons.
- Active white space is the space that is intentionally created to help guide the user's eye and draw attention to certain elements on the page.
- In contrast to active white space, there is also passive white space. Passive white space is the space that is left over after all the elements on a page have been placed.
- Another type of whitespace would be micro white space. This is the space between individual characters in a line of text.

**Images**:

- Responsive Images, adapting to different screen sizes in order to support website design.
- It is important to use high quality images that are safe&optimized for the web.
- keeping an eye out for balance, harmony, and quality you should watch out for picture sizes.

  <!--Free Code Camp understanding.  -->

**Design Brief**:

- A design brief is a document that outlines the objectives, goals, and requirements of a project. It is a roadmap that guides the design process and ensures that the final product meets the needs of the client.
- The first element is the overview of the project and business. This overview should include the company's details, mission, values, unique selling points, and products or services.

- The next key element should be to document the goals and objectives for the project. This should include the purpose of the project, and the desired outcomes.

- Examples of goals include increasing traffic to a site or increasing the number of monthly page visits by X percent.

- Another key element would be the target audience. The design brief should include information about the target demographics, interests, and needs of the audience.

- You should also include information about the competition and how the project will differentiate itself from the competition.

- Another key element would be the project scope. This should include the deliverables, timeline, and budget. The deliverables should include a list of all the items that will be produced as part of the project, such as mockups, and final designs.

- Without clearly defining project scope, things can get out of hand and go over budget. So, it's best to be as detailed as possible about what is expected to be delivered and by when.

**Absolute units**:

Remember that margin is the space outside of the box. So, in this example, the box will have a margin of 10px on all sides.

Other types of absolute units include the following:

The in (inches) unit, which is equal to 96px
The cm (centimeters) unit, which is equal to 25.2/64 of an inch
The mm (millimeters) unit, which is equal to 1/10th of a centimeter
The q (quarter-millimeters) unit, which is equal to 1/40th of a centimeter
The pc (picas) unit, which is equal to 1/6th of an inch
The pt (points) unit, which is equal to 1/72th of an inch
Most of these units will be used for print and not for screens.

While the most common unit you will use is pixels, it is important to know that the other absolute units exist.

**Relative Units**:

Em is relative to its parent's text size(Usually 16px). (Use for text size and containers of text)
Good use cases for ems would be when you are working with modular components like buttons or cards. By using em units, you can ensure that all aspects of the component (such as padding, margin, and borders) scale proportionally with the font size, keeping consistent proportions.
Rem is relative to the root element's text size(16px). (Use for text size and containers of text)
So when should you use rem units? rem units are preferred over pixels for typography because they scale proportionally with the user's browser settings. This makes your content more accessible to users with visual impairments.
