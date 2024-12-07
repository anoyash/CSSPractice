# CSS Topics

<ol>
  <li>Understanding CSS and how to link it with HTML</li>
  <ul>
    <li>Inline Styling -> ID styling -> (Class Styling/Attribute/Pseudo-classes) -> eleemtns/Pseudo elements -> Universal (*) -> Browser default styling 😏</li>
    <li>CSS boilerplate code</li>
  </ul>
  <li>CSS Box Model </li>
  <ol>
    <li>Extrinsic sizing</li>
    <li>Intrinsic sizing</li>
    <li>CSS property min-content vs max-content</li>
    <li>Content Box -> Padding Box -> Border Box -> Margin </li>
    <li><p>While "max-content" represents the ideal size an element would take if given unlimited space,
   Allowing it to expand to fit its full content without wrapping or shrinking;
   Essentially, "min-content" makes an element as small as possible,
   While "max-content" lets it expand to its natural size based on its content</p></li>
  </ol>
  <li>CSS Selectors</li>
  <ol>
    <li>Universal selector (*)</li>
    <li>Type selector (give element name)</li>
    <li>Class selector (.)</li>
    <li>Id selector (#) </li>
    <li>Attribute selector [data-type] , where data-type will be attribute to the HTML element </li>
    <li>Grouping selectors : same styling can be applied to multiple HTML elemeents and selectors</li>
    <li>Complex selector => div p { }</li>
    <li>Compound selector => {<aa CLASS="my-class"> </aa>} aa.my-class { color : red } </li>
    <li><strong>Pseudo Class , we use : </strong></li>
    <li><strong>Pseudo Elements , we use :: </strong></li>
  </ol>
  <li>CSS position property</li>
  <ol>
    <li>Non-positioned elements : static ( normal flow )</li>
    <li>Positioned elements : relative , absolute , fixed , sticky </li>
    <li>z-index : It will be auto , if no value is provided explicitly for the postioned elements</li>
    <li>Sticky needs to be understand separately ( undone )</li>
  </ol>
  <li>RGB Vs RGBA CSS colors</li>
  <ul>
    <li>
      Red Green and Blue , each have value range from 0 to 255.
    </li>
    <li>
      RGBA contains one extra parameter : Alpha channel which controls transparency. Its values 
      ranges from 0 to 1. 1 -> no transparent at all and 0 -> (fully transparent)
    </li>
  </ul>
  <li>Responsive ness</li>
  <ol>
    <li> px , % , vh and vw , vmax and vmin , em and rem</li>
    <li>Flex display</li>
    <li>Media queries</li>
  <ol>
</ol>
