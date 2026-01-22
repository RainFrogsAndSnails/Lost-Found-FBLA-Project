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

Absolute Units
px (Pixels): This absolute unit is a fixed-size unit of measurement in CSS. It is the most common absolute unit and provides precise control over dimensions. 1px is always equal to 1/96th of an inch.
in (Inch): This absolute unit is equal to 96px.
cm (Centimeters): This absolute unit is equal to 25.2/64 of an inch.
mm (Millimeters): This absolute unit is equal to 1/10th of a centimeter.
q (Quarter-Millimeters): This absolute unit is equal to 1/40th of a centimeter.
pc (Picas): This absolute unit is equal to 1/6th of an inch.
pt (Points): This absolute unit is equal to 1/72th of an inch.
Relative Units
Percentages: These relative units allow you to define sizes, dimensions, and other properties as a proportion of their parent element. For example, if you set width: 50%; on an element, it will occupy half the width of its parent container.
em Unit: These units are relative to the font size of the element. If you are using ems for the font-size property, the size of the text will be relative to the font size of the parent element.
rem Unit: These units are relative to the font size of the root element, which is the html element.
vh Unit: vh stands for "viewport height" and 1vh is equal to 1% of the viewport's height.
vw Unit: vw stands for "viewport width" and 1vw is equal to 1% of the viewport's width.
calc Function
calc() Function: With the calc() function, you can perform calculations directly within your stylesheets to determine property values dynamically. This means that you can create flexible and responsive user interfaces by calculating dimensions based on the viewport size or other elements.
