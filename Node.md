Second 1:1 / Task 1,2
#Task 1
    Header should be full width and has a shell/container.
    Logo link.
    Logo hover is not good.
    Scale Hover that jumps is not good. Add transition.
    Hover is done on li not an element. a tag needs to be inline-block to be styled correctly.
    Don’t use parents where not needed.
    Button size not correct due to display:inline property.
    .5 px will not always render the same on different browsers.
    High line heigh for single row will aline vertically.
    display inline-flex will allow for better centering
    button min-width best option for multiple buttons of the same size. If not min width is applied it needs to be done with padding and the content of the button.
    margin: 4 auto 5
    Padding - stop using flex where it is not needed. Centered sections probably will not need flex
    min-height not needed most of the times. Use padding bot/top to get to the height that is needed.
    even if the content does not reach the end of the block it does not mean that I will not need to spread the element. Do not use gap just to get better alignment.
    Always add size to the children of the section. Flex : 0 0 20%
    word-break if you need to have text wrap better.
    when creating columns, the content needs to fit in the column that has a defined size but not to have the size determined by the content.
    underline/abstracted components should inherit/current-color from its parent if possible
    underline class can be added to the heading and remove the parent completely.
    figure tag should have a class as it can be reused in the component
    when using min/max-width, padding can be used to have the same effect.
    always add base font size/family and weight if needed as default is 400
    The one font family that is more common in the design is best to be used on the base to reduce code
    width for icons not needed as when centered it does not matter most of the times
    instead of using flex/width to match the design I can use padding
    inheritance vs direct styling - Inheritance < tag selector < class/attribute selector < id selector < important rule
    Card content can hold the head and paragraphs
    Flex is dangerous if used with different components like buttons if for example the button is missing inline-block and not consider the padding of the element.
    Don’t put height on the sections
    Main tags (Header/Footer/Section) would be used to apply background. Shell is to limit the width of the elements. Section wrapper would be used to add padding and aline content.
    Div should not have text content. Use Paragraphs.
    Icon links should be reusable in other section so classes should not be linked to the section they are created in. Create a link with the section class but the icon class should be specific to the icon.
    Fix pixel perfect
    Add Base styling for font.
    DO NOT GO BELOW 1 LINE HEIGHT
    Use where for hover+focus selectors
    Use html for starting snippet
#Task 2
    Margin inline auto will work only for components that are not full width.
    In a tags for phones and emails use href=“mail/tel:	+422 432 2342” and content should be the phone.
    Don’t use span as a way to display all of the text but only to modify parts of it. Use P.
    Buttons that seems like a part of the nav will still need to be separated
    Remove flex where not needed
    Apply shell when it seems like it should be limited by a lot more width than the rest of the content.
    Display inline-block for buttons
    Section List not the best name
    Logo/Icons should be png and images should be jpg
    Add size to the cards like 25% if I need to in a row.
    Gap is not the best use for spacing between items. Consider margin on the cards and -padding on the wrapper of the
    Consider using cols>col>card for list items. Cols has the display:flex with -10px margin and col would have sizing like 25% and padding: 0 10px
    When using an image it is important to spread it with the width and height of the parent(width 100% and height auto)
    Do not use max-width on the card content as that was if not set correctly that width would determine the size of the card. This is not the intended behavior.
    Don’t ever use flex-start to aline context to the start of the element as that is default behavior when text align is not set.
    Classes left and right is not optimal due to mobile resizing that will make them from left-right to top-bot
    Try creating one card component and use modification classes to complete the style of the card on secondary sections.
    Add links to images/headings/on captions small text like admin.
    NO CAPITAL LETTERS IN HTML
    Font-weight is 400 by default for paragraphs and 700 for headings.
    Even if you don’t see them right away columns can be equal but the content to not be aligned the same way.
    If I want to use section-head everywhere I need to create only selectors that are selected by the section first and then the
    Hover effects
————————————————————————————————————————————————————————————————————————————————
 #Task 2
    Hover effects should be different for pictures(scale is fine if overflow:hidden is used). Text scaling is not good as it can change the layout of the page.
    Class in the navigation is not good. Custom classes in the header is not easy to implement if CRM is used.
    Nav links with color change. Buttons border/color change/swap. Footer heads are only headings not links.
    Take out the button from the navigation.
    .btn.btn—orange is not a selector that should be needed
    Instead of creating a wrapper for the heading and applying just the margin on it a .hero-main h1 can be used.
    Hero-wrapper is not an article
    Card head class can be removed and style .card h4.
    Heading links should be h4>a not a>h4. This is because the correct structure is the block element to be the parent of the inline one when possible.
    Hero-content margin: 0 auto 20px too much.
    Letter spacing should be in em not px. Something close to 0.02em-0.05. Try to match it by the design and not calculate it. If it’s px it is a fixed size. em will make it dynamic.
    Figma/PS designs will have character info but it should not be taken exactly the same.
    First section wrapper should have the padding but not the wrapper. Section first has padding and then shell that will center.
    Article tag is not for sections.
    Section head could be more than just the h1-6 element.
    List section can have the .section-list-head> h2+underline+section-list-content. We can remove the section-list-content class that only gives max-width and text styling.
    Max-width on the elements of the cards means that it resizing is needed it will need a lot of changes. Use the flex-basis to set the size and padding/-margin for the gap.
    Card headings line-height is not good. Line height should be between 1-2. 0 can be used if there is unwanted spacing from inline elements.
    Images should be taking 100% width of the parent and height:auto.
    The card has a tag that is inline and img inside that is width:100%. A tag width is determined by the the content but the img width is determined by the a tag. Using display block(a takes full width of card) the 100% width works Fine.
    Card vertical/horizontal is not needed. User card for the first one and then create a modificatory class that will either make them vertical or horizontal depending on the first layout. The class can easily remove any styling that was set by the initial class.
    The image has a spacing below it that comes from the line height.
    50% image background should not have the image be 50% but rather the section-background should be 50% and the image again to be width:100% and height auto.
    Try to not use a wrapper for the content but use the section wrapper to set the width if needed and remove one more div.
    Elements that will take remaining 50% of a section could have margin-left auto but when max-width is needed it will no longer work with auto but a 50% should be set so It gets centered correctly.
    When section-content is removed and the section does not have that much content it can just have the whole wrapper be section-content.
    Don’t add small margins for the pixel perfect. Only if its spacing from the left is too much.
    Don’t do flex: 0 0 calc(50% + 12px - 2px). Do flex: 0 0 calc(50% + 10px).
    When making 2 columns it is not good to have them next to each other. There should be some spacing(padding/gap).
    Space-between changes the gap dynamically and that makes it hard to determine.
    Footer should not be cards but div.cols and div.col.
    Try removing the footer-main-wrapper and make it work.
    BEM styling does not allow to use footer selector with other components like card. Footer block should not style card component.
    Don’t style components from the section. Try to make it encapsulated in the component. Use .cards - .card
    Naprai Adekvaten grid
 #Task 3
    If header background is not part of the hero section it will not need to be positioned.
    In cases where the picture is cut off we take only the visible part.
    Width/height of the image should be the intrinsic dimensions.
    Fix socials icons
    Inline-block should not be used for nav alignments. Just flex them.
    Again Line-height is causing unwanted behavior when it’s too much on the links of the nav.
    Don’t use :first-child on the paragraph that is centered but make a modificatory class.
    Fix font faces.
    Hero should not have margin bottom. Spacing from the end of the hero section to the beginning of the next sections content should be padding-top from the second section but margin bottom from the hero.
    If the content looks connected by its meaning, it probably is one section even if it does not look like it.
    Flex + justify-content:flex-end to position block element that has full width is not correct.
    Change hero section completely. 1:03:15 if needed. Hero>hero-background + hero-main(padding-block)>shell>h1 + h2
    H1 + h5 combination can be <h1>Main head + span.small</h1>
    Just like the modification card—small, a card—center class can be used instead of :first-child.
    grid-template: 650px 450px / 500px 500px; is weird. grid-tempalte-columns: 1fr 1fr will make the same layout since the content will wrap and create the grid I want.
    Pixels for grid is not good. Use fr.
    Section-alt-images is not good. this limits the usage of the list. Making a component like ul.list-feeds and separate the component is the better approach
    Form classes should be 1:1 with the standards. form__group
    .field should be styled from the .field but not from the form class and then the field.
    Put cursor pointed on buttons.
    Hovers should not have the layout move.
    Form-group is not needed. Only add it when needed. If
    Form-row:not(:first-child) has an equivalent form-row + form-row (100% supported even on old browsers)
    Form-label styling is fine to be styled from the form.
    Spacing in the form row is coming from line height which is wrong.
    Labels can be display block and margin bottom to match the spacing from the label to the controls.
    .field should not be selected from the parent. Width 100% is fine. Field height is set by the height property and not with the top and bot padding. We only use padding inline to push the text inwards.
    Vertical align is not needed in the field.
    .field {width, height, padding-inline, font}
    :focus status that are not styled by me need to be removed.:focus-visible { Outline:none}
    Field--textarea should have height as well and not cols+rows that will determine the width and height.
    Textarea with height will need padding on top and bottom as well as it will not have any.
    Addresses should be with a tag address.
    Footer should not be separated on 3 different sections for cols but be cols>col
    Fix the icons on the footer. They can not be the way they are.
    Footer padding should be fixed