# TailwindCSS Cheatsheet

> Last updated on November 9th, 2020 for TailwindCSS v1.9.6

This README contains a complete list of the TailwindCSS class names for a quick reference. Go ahead, try a `cmd+f` search. 

It also contains a more condensed, printable one-page version:

![Printable TailwindCSS Cheatsheet](https://github.com/gojutin/tailwindcss-cheatsheet/blob/main/printable-tailwindcss-cheatsheet.jpg?raw=true)

## Default Config

[View the TailwindCSS default configuration](https://github.com/tailwindlabs/tailwindcss/blob/v1/stubs/defaultConfig.stub.js)

Breakpoints: sm:640px | md:768px | lg:1024px | xl:1280px

Colors: transparent, current, black, white, grays, reds, oranges, yellows, greens, teals, blues, indigos, purples, pinks

Spacing: 0|1|2|3|4|5|6|8|10|12|16|20|24|32|40|48|56|64|px

Supported Variants: responsive|group-hover|focus-within|first|last|odd|even|hover|focus|active|visited|disabled|motion-safe|motion-reduce


## Utility Classes

### LAYOUT 

**Container**
- .container

**Box Sizing**
- .box-[border|content]

**Display**
- .block
- .inline-block
- .inline
- .flex
- .inline-flex
- .table
- .table-caption
- .table-cell
- .table-column
- .table-column-group
- .table-footer-group
- .table-header-group
- .table-row-group
- .table-row
- .flow-root
- .grid
- .inline-grid
- .contents
- .hidden

**Floats**
- .float-[right|left|none]
- .clearfix
  
**Clear**
- .clear-[left|right|both|none]

**Object Fit**
- .object-[contain|cover|fill|none|scale-down]

**Object Position**
- .object-bottom
- .object-center
- .object-left
- .object-left-bottom
- .object-left-top
- .object-right
- .object-right-bottom
- .object-right-top
- .object-top

**Overflow**
- .overflow-[auto|hidden|visible|scroll]
- .overflow-x-[auto|hidden|visible|scroll]
- .overflow-y-[auto|hidden|visible|scroll]
- .scrolling-[touch|auto]

**Overscroll Behavior**
- .overscroll-[auto|contain|none]
- .overscroll-y-[auto|contain|none]
- .overscroll-x-[auto|contain|none]

**Position**
- .static
- .fixed
- .absolute
- .relative
- .sticky

**Top / Right / Bottom / Left**
- .inset-[0|auto]
- .inset-y-[0|auto]
- .inset-x-[0|auto]
- .top-[0|auto]
- .right-[0|auto]
- .bottom-[0|auto]
- .left-[0|auto]

**Visibility**
- .visible
- .invisible

**Z-index**
- .z-[0|10|20|30|40|50|auto]

### FLEXBOX
> Make sure to use the `.flex` class with the classes below!

**Flex Direction**
- .flex-row
- .flex-row-reverse
- .flex-col
- .flex-col-reverse

**Flex Wrap**
- .flex-wrap
- .flex-wrap-reverse
- .flex-no-wrap
  
**Flex**
- .flex-1
- .flex-auto
- .flex-initial
- .flex-none

**Flex Grow**
- .flex-grow-0
- .flex-grow
  
**Flex Shrink**
- .flex-shrink-0
- .flex-shrink

**Order**
- .order-[1|2|3|4|5|6|7|8|9|10|11|12]
- .order-[first|last|none]

### GRID

**Grid Template Columns**
- .grid-cols-[1|2|3|4|5|6|7|8|9|10|11|12|none]

**Grid Column Start / End**
- .col-auto
- .col-span-[1|2|3|4|5|6|7|8|9|10|11|12|full]
- .col-start-[1|2|3|4|5|6|7|8|9|10|11|12|13|auto]
- .col-end-[1|2|3|4|5|6|7|8|9|10|11|12|13|auto]

**Grid Template Rows**
- .grid-rows-[1|2|3|4|5|6|none]

**Grid Row Start / End**
- .row-auto
- .row-span-[1|2|3|4|5|6|full]
- .row-start-[1|2|3|4|5|6|7|auto]
- .row-end-[1|2|3|4|5|6|7|auto]

**Grid Auto Flow**
- .grid-flow-row
- .grid-flow-col
- .grid-flow-row-dense
- .grid-flow-col-dense

**Grid Auto Columns**
- .auto-cols-auto
- .auto-cols-min
- .auto-cols-max
- .auto-cols-fr
  
**Grid Auto Rows**
- .auto-rows-auto
- .auto-rows-min
- .auto-rows-max
- .auto-rows-fr
  
**Gap**
- .gap-[0|1|2|3|4|5|6|8|10|12|16|20|24|32|40|48|56|64|px]
- .gap-x-[0|1|2|3|4|5|6|8|10|12|16|20|24|32|40|48|56|64|px]
- .gap-y-[0|1|2|3|4|5|6|8|10|12|16|20|24|32|40|48|56|64|px]
  
### BOX ALIGNMENT

**Justify Content**
- .justify-[start|end|center|between|around|evenly]

**Justify Items**
- .justify-items-[auto|start|end|center|stretch]

**Justify Self**
- .justify-self-[auto|start|end|center|stretch]
  
**Align Content**
- .content-[center|start|end|between|around|evenly]
  
**Align Items**
- .items-[start|end|center|baseline|stretch]
  
**Align Self**
- .self-[auto|start|end|center|stretch]
  
**Place Content**
- .place-content-[center|start|end|between|around|evenly|stretch]

**Place Items**
- .place-items-[auto|start|end|center|stretch]
  
**Place Self**
- .place-self-[auto|start|end|center|stretch]
  
### SPACING

**Padding**
- .[p|py|px|pt|pr|pb|pl]-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|px]

**Margin**
- .[m|my|mx|mt|mr|mb|ml]-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|auto|px]
- .-[m|my|mx|mt|mr|mb|ml]-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|px]
  
**Space Between**
- .space-[x|y]-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|px|reverse]
- .-space-[x|y]-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|px]

### SIZING

**Width**
- .w-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|auto|px]
- .w-[1/2|1/3|2/3|1/4|2/4|3/4]
- .w-[1/5|2/5|3/5|4/5]
- .w-[1/6|2/6|3/6|4/6|5/6]
- .w-[1/12|2/12|3/12|4/12|5/12|6/12|7/12|8/12|9/12|10/12|11/12]
- .w-[full|screen]
  
**Min-Width**
- .min-w-[0|full]

**Max-Width**
- .max-w-[none|xs|sm|md|lg|xl|2xl|3xl|4xl|5xl|6xl|full]
- .max-w-screen-[sm|md|lg|xl]
  
**Height**
- .h-[0|1|2|3|4|5|6|10|12|16|20|24|32|40|48|56|64|auto|px|full|screen]
  
**Min-Height**
- .min-h-[0,full,screen]
  
**Max-Height**
- .max-h-[full,screen]
  
### TYPOGRAPHY

**Font Family**
- .font[sans|serif|mono]
  
**Font Size**
- .text-[xs|sm|base|lg|xl|2xl|3xl|4xl|5xl|6xl]
  
**Font Smoothing**
- .antialiased
- .subpixel-antialiased

**Font Style**
- .italic
- .not-italic

**Font Weight**
- .font-[hairline|thin|light|normal|medium|semibold|bold|extrabold|black]
  
**Font Variant Numeric**
- .normal-nums
- .ordinal
- .slashed-zero
- .lining-nums
- .oldstyle-nums
- .proportional-nums
- .tabular-nums
- .diagonal-fractions
- .stacked-fractions
  
**Letter Spacing**
- .tracking-[tighter|tight|normal|wide|wider|widest]
  
**Line Height**
- .leading-[3|4|5|6|7|8|9|10|none|tight|snug|normal|relaxed|loose]
  
**List Style Type**
- .list-[none|disc|decimal]
  
**List Style Position**
- .list-[inside|outside]
  
**Placeholder Color**
- .placeholder-[transparent|current|black|white]
- .placeholder-gray-[100|200|300|400|500|600|700|800|900]
- .placeholder-red-[100|200|300|400|500|600|700|800|900]
- .placeholder-orange-[100|200|300|400|500|600|700|800|900]
- .placeholder-yellow-[100|200|300|400|500|600|700|800|900]
- .placeholder-green-[100|200|300|400|500|600|700|800|900]
- .placeholder-teal-[100|200|300|400|500|600|700|800|900]
- .placeholder-blue-[100|200|300|400|500|600|700|800|900]
- .placeholder-indigo-[100|200|300|400|500|600|700|800|900]
- .placeholder-purple-[100|200|300|400|500|600|700|800|900]
- .placeholder-pink-[100|200|300|400|500|600|700|800|900]
  
**Placeholder Opacity**
- .placeholder-opacity-[0|25|50|75|100]
  
**Text Align**
- .text-[left|center|right|justify]
  
**Text Color**
- .text-[transparent|current|black|white]
- .text-gray-[100|200|300|400|500|600|700|800|900]
- .text-red-[100|200|300|400|500|600|700|800|900]
- .text-orange-[100|200|300|400|500|600|700|800|900]
- .text-yellow-[100|200|300|400|500|600|700|800|900]
- .text-green-[100|200|300|400|500|600|700|800|900]
- .text-teal-[100|200|300|400|500|600|700|800|900]
- .text-blue-[100|200|300|400|500|600|700|800|900]
- .text-indigo-[100|200|300|400|500|600|700|800|900]
- .text-purple-[100|200|300|400|500|600|700|800|900]
- .text-pink-[100|200|300|400|500|600|700|800|900]

**Text Opacity**
- .text-opacity-[0|25|50|75|100]
  
**Text Decoration**
- .underline
- .line-through
- .no-underline

**Text Transform**
- .uppercase
- .lowercase
- .capitalize
- .normal-case
  
**Vertical Align**
- .align-[baseline|top|middle|bottom|text-top|text-bottom]

**Whitespace**
- .whitespace-[normal|no-wrap|pre|pre-line|pre-wrap]
  
**Word Break**
- .break-[normal|words|all]
- .truncate
  
### BACKGROUNDS

**Background Attachment**
- .bg-[fixed|local|scroll]
  
**Background Clip**
- .bg-clip-[border|padding|content|text]
  
**Background Color**
- .bg-[transparent|current|black|white]
- .bg-gray-[100|200|300|400|500|600|700|800|900]
- .bg-red-[100|200|300|400|500|600|700|800|900]
- .bg-orange-[100|200|300|400|500|600|700|800|900]
- .bg-yellow-[100|200|300|400|500|600|700|800|900]
- .bg-green-[100|200|300|400|500|600|700|800|900]
- .bg-teal-[100|200|300|400|500|600|700|800|900]
- .bg-blue-[100|200|300|400|500|600|700|800|900]
- .bg-indigo-[100|200|300|400|500|600|700|800|900]
- .bg-purple-[100|200|300|400|500|600|700|800|900]
- .bg-pink-[100|200|300|400|500|600|700|800|900]

**Background Opacity**
- .bg-opacity-[0|25|50|75|100]
  
**Background Position**
- .bg-bottom
- .bg-center
- .bg-left
- .bg-left-bottom
- .bg-left-top
- .bg-right
- .bg-right-bottom
- .bg-right-top
- .bg-top

**Background Repeat**
- .bg-repeat
- .bg-no-repeat
- .bg-repeat-x
- .bg-repeat-y
- .bg-repeat-round
- .bg-repeat-space

**Background Size**
- .bg-[auto|cover|contain]
  
**Background Image**
- .bg-none
- .bg-gradient-to-[t|tr|r|br|b|bl|l|tl]
  
**Gradient Color Stops**
- .from-[transparent|current|black|white]
- .from-gray-[100|200|300|400|500|600|700|800|900]
- .from-red-[100|200|300|400|500|600|700|800|900]
- .from-orange-[100|200|300|400|500|600|700|800|900]
- .from-yellow-[100|200|300|400|500|600|700|800|900]
- .from-green-[100|200|300|400|500|600|700|800|900]
- .from-teal-[100|200|300|400|500|600|700|800|900]
- .from-blue-[100|200|300|400|500|600|700|800|900]
- .from-indigo-[100|200|300|400|500|600|700|800|900]
- .from-purple-[100|200|300|400|500|600|700|800|900]
- .from-pink-[100|200|300|400|500|600|700|800|900]
- .via-[transparent|current|black|white]
- .via-gray-[100|200|300|400|500|600|700|800|900]
- .via-red-[100|200|300|400|500|600|700|800|900]
- .via-orange-[100|200|300|400|500|600|700|800|900]
- .via-yellow-[100|200|300|400|500|600|700|800|900]
- .via-green-[100|200|300|400|500|600|700|800|900]
- .via-teal-[100|200|300|400|500|600|700|800|900]
- .via-blue-[100|200|300|400|500|600|700|800|900]
- .via-indigo-[100|200|300|400|500|600|700|800|900]
- .via-purple-[100|200|300|400|500|600|700|800|900]
- .via-pink-[100|200|300|400|500|600|700|800|900]
- .to-[transparent|current|black|white]
- .to-gray-[100|200|300|400|500|600|700|800|900]
- .to-red-[100|200|300|400|500|600|700|800|900]
- .to-orange-[100|200|300|400|500|600|700|800|900]
- .to-yellow-[100|200|300|400|500|600|700|800|900]
- .to-green-[100|200|300|400|500|600|700|800|900]
- .to-teal-[100|200|300|400|500|600|700|800|900]
- .to-blue-[100|200|300|400|500|600|700|800|900]
- .to-indigo-[100|200|300|400|500|600|700|800|900]
- .to-purple-[100|200|300|400|500|600|700|800|900]
- .to-pink-[100|200|300|400|500|600|700|800|900]

### BORDERS

**Border Radius**
- .rounded
- .rounded-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-t-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-r-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-b-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-l-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-tl-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-tr-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-bl-[none|sm|md|lg|xl|2xl|3xl|full]
- .rounded-br-[none|sm|md|lg|xl|2xl|3xl|full]


**Border Width**
- .border
- .border-[0|2|4|8]
- .border-[t|r|b|l]
- .border-t-[0|2|4|8]
- .border-r-[0|2|4|8]
- .border-b-[0|2|4|8]
- .border-l-[0|2|4|8]
  
**Border Color**
- .border-[transparent|current|black|white]
- .border-gray-[100|200|300|400|500|600|700|800|900]
- .border-red-[100|200|300|400|500|600|700|800|900]
- .border-orange-[100|200|300|400|500|600|700|800|900]
- .border-yellow-[100|200|300|400|500|600|700|800|900]
- .border-green-[100|200|300|400|500|600|700|800|900]
- .border-teal-[100|200|300|400|500|600|700|800|900]
- .border-blue-[100|200|300|400|500|600|700|800|900]
- .border-indigo-[100|200|300|400|500|600|700|800|900]
- .border-purple-[100|200|300|400|500|600|700|800|900]
- .border-pink-[100|200|300|400|500|600|700|800|900]

**Border Opacity**
- .border-opacity-[0|25|50|75|100]
  
**Border Style**
- .border-[solid|dashed|dotted|double|none]
  
**Divide Width**
- .divide-[x|y]
- .divide-x-[0|2|4|8|reverse]
- .divide-y-[0|2|4|8|reverse]
  
**Divide Color**
- .divide-[transparent|current|black|white]
- .divide-gray-[100|200|300|400|500|600|700|800|900]
- .divide-red-[100|200|300|400|500|600|700|800|900]
- .divide-orange-[100|200|300|400|500|600|700|800|900]
- .divide-yellow-[100|200|300|400|500|600|700|800|900]
- .divide-green-[100|200|300|400|500|600|700|800|900]
- .divide-teal-[100|200|300|400|500|600|700|800|900]
- .divide-blue-[100|200|300|400|500|600|700|800|900]
- .divide-indigo-[100|200|300|400|500|600|700|800|900]
- .divide-purple-[100|200|300|400|500|600|700|800|900]
- .divide-pink-[100|200|300|400|500|600|700|800|900]
  
**Divide Opacity**
- .divide-opacity-[0|25|50|75|100]
  
**Divide Style**
- .divide-[solid|dashed|dotted|double|none]
  
### TABLES

**Border Collapse**
- .border-[collapse|seperate]

**Table Layout**
- .table-[auto|fixed]
  
### EFFECTS

**Box Shadow**
- .shadow
- .shadow-[xs|sm|md|lg|xl|2xl|inner|outline|none]
  
**Opacity**
- .opacity-[0|25|50|75|100]

### TRANSITIONS AND ANIMATION

**Transition Property**
- .transition
- .transition-[none|all|colors|opacity|shadow|transform]
  
**Transition Duration**
- .duration-[75|100|150|200|300|500|700|1000]
  
**Transition Timing Function**
- .ease-[linear|in|out|in-out]
  
**Transition Delay**
- .delay-[75|100|150|200|300|500|700|1000]
  
**Animation**
- .animate-[none|spin|ping|pulse|bounce]
  
### TRANSFORMS

**Scale**
- .scale-[0|50|75|90|95|100|105|110|125|150]
- .scale-x-[0|50|75|90|95|100|105|110|125|150]
- .scale-y-[0|50|75|90|95|100|105|110|125|150]
  
**Rotate**
- .rotate-[0|1|2|3|6|12|45|90|180]
- .-rotate-[1|2|3|6|12|45|90|180]
  
**Translate**
- .translate-x-[0|1|2|3|4|5|6|7|8|10|12|16|20|24|32|40|48|56|64|px|full|1/2]
- .-translate-x-[1|2|3|4|5|6|7|8|10|12|16|20|24|32|40|48|56|64|px|full|1/2]
- .translate-y-[0|1|2|3|4|5|6|7|8|10|12|16|20|24|32|40|48|56|64|px|full|1/2]
- .-translate-y-[1|2|3|4|5|6|7|8|10|12|16|20|24|32|40|48|56|64|px|full|1/2]
  
**Skew**
- .skew-x-[0|1|2|3|6|12]
- .-skew-x-[1|2|3|6|12]
- .skew-y-[0|1|2|3|6|12]
- .-skew-x-[1|2|3|6|12]

**Transform Origin**
- .origin-center
- .origin-top
- .origin-top-right
- .origin-right
- .origin-bottom-right
- .origin-bottom
- .origin-bottom-left
- .origin-left
- .origin-top-left

### INTERACTIVITY

**Appearance**
- .appearance-none
  
**Cursor**
- .cursor-[auto|default|pointer|wait|text|move|not-allowed]
  
**Outline**
- .outline-[none|white|black]
  
**Pointer Events**
- .pointer-events-[none|auto]
  
**Resize**
- .resize
- .resize-[none|y|x]
  
**User Select**
- .select-[none|text|all|auto]

### SVG

**Fill**
- .fill-current
  
**Stroke**
- .stroke-current
  
**Stroke Width**
- .stroke-[0|1|2]

### ACCESSIBILITY

**Screen Readers**
- .sr-only
- .not-sr-only
