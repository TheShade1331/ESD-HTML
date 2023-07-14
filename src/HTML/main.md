**ESD Day-1**

Industry Practices-1(Employability Skills)

Agenda
- Importance of Web Develeopment
  - HTML/CSS & uses
  - Tools - HTML, CSS, Javascript
- IP
   - HTML & CSS
   - JS/react
   - node/express/JSON

- Evaluation & Assessment
   - Attendance + FA + Viva + TW


Lecture
- CMD Basic Commands
- C:\Users\Administrator>cd Desktop    *Change Directory {Enter a Folder}*
- C:\Users\Administrator\Desktop>systeminfo   *System Information*
- C:\Users\Administrator\Desktop>set *To Get paths*
- C:\Users\Administrator\Desktop>color attr *To Customize Command Prompt Theme*
- C:\Users\Administrator\Desktop> title html *To Change Title*
- C:\Users\Administrator\Desktop>ipconfig *To Check IP Configuration*
- C:\Users\Administrator\Desktop>cd.. *Escape Folder*
- C:\Users\Administrator\Desktop>mkdir cmdfiles *Make Directory*
- C:\Users\Administrator\Desktop>rmdir cmdfiles *Remove Directory*
- C:\Users\Administrator\Desktop>del cmdfiles
- C:\Users\Administrator\Desktop\cmdfiles\*, Are you sure (Y/N)? Y *Similar as rmdir Just Asks Permission*
- C:\Users\Administrator\Desktop\cmdfiles>type NUL > empty.txt *Make a File*
- C:\Users\Administrator\Desktop\cmdfiles>echo HTML > empty.txt *Write HTML in File*
- C:\Users\Administrator\Desktop\cmdfiles>echo CSS > empty.txt *If Written Again it replaces Previous Data*
- C:\Users\Administrator\Desktop\cmdfiles>more empty.txt *Prints File in CMD*
- C:\Users\Administrator\Desktop\cmdfiles>move empty.txt new *Renames File & keeps it in same directory*
- C:\Users\Administrator\Desktop\cmdfiles>move empty.txt C:\Users\Administrator\Desktop\new *Renames File & Moves it to New Directory Whose Path is mentioned*
- C:\Users\Administrator\Desktop\cmdfiles>copy empty.txt C:\Users\Administrator\Desktop *Copy & Pastes the File to the Designeted Path*
- C:\Users\Administrator\Desktop>tree *Shows All Folders & Files inside Given File*
- C:\Users\Administrator\Desktop>exit *closes the CMD*


Writing First HTML Program
- <html> & </html> :- Start & End Program with this
- <head> , <body> & <style> :- Are the Building Blocks
-  These are called Tags
-  <title> is one of the Tags Used in <head>
-  <h1>, <p> & <br /> are some of the Examples of Tags Used in <body>
-  Out of Which <h1> & <p> are Used in Pairs While <br /> may or may not be used

Codes:
1. Basic
2. Heading - Style - {font-size, font-family, color, etc}
3. formatting - <b>bold = <strong>, <i>italic, <em>Empasize, <small>, <mark>highlight, <del>dash, <ins>underline, <sub>subscript, <sup>superscript
4. Anchor - <a href=""></a>including Website, "_blank" open in new tab, "_self"open in same tab
5. Image - <src>Source, <alt>if image dosen't load will show this
6. Background-Image - <background-image: url('')>background-repeat : no-repeat; background-size : cover;">
7. Table - <tr>row <th>Headings in Table, <td>Body 


**ESD Day-2**

Continuing Codes:
8. Timetable - <th colspan=2>Name</th>Spanning 2 Columns  <td rowspan="2">yagnesh</td>Spanning 2 Rows
9. List - <li>List <ul>Unorderd List <ol>Ordered List; if ul, ol Not mentioned Considers ul by default
10. Block <div>division- Makes Code blocks & Considers Whole Rows 
          <span> Also Makes Code Blocks But Only Considers Space Occupied
11. Using Nested <div>
12. Class ID .city1{} & class="city1"  
             #city2{} & id="city2"
   Classes are used to apply styles to multiple elements on a page, while ids are used to uniquely identify a single element.
13. Form :- <form> Allows to Edit the Inside Elements in the Page
            <label> & <input> :- Label gives the Title of Editable info & Input is the Input Text Box
14. Select:- <label> & <select> :-Label gives the Title of the Editable Info & Select gives a Toggelable windows for User to Click & Choose From the Given Options Made Using <option>
15.

**TO be Updated!**


**ESD Day-3**
17.   Inline-Internal CSS:
    - Inline CSS :- Style is inside tag of each element seperately
    - Internal CSS :- Style is Declared for the tag Previously & when that tag is used Same Css is copied.
    - If a tag having Internal CSS has Given a Diffrent inline CSS it prefers inline command
18.  Style CSS:
    - A Prototype CSS File. If linked to Any HTML File will Show CSS Accordingly
19.  External CSS:
    - CSS is Externally used by Linking the Above File in the Head.
20. Selector:
    - .para :- Class Para
    - #para :- id Para
    - p.comb :- <p class="comb">   //Selectors Used to Style p
    - p#comb :- <p id="comb">      //same
    - * :- All Elements            //Universal Selector
    - div>p :- <div>               //descendant selector: Selects only elements within given branch
                 <p>
21. Background:
    - Background-Image: url('') // Source of Image {Url or path}
    - Background-repeat: no-repeat; // to Stop Replicating background
    - Background size & background-position
    - Background-attachment  // Tells if Image is Fixed.
22. Color: Any Color Can be Chosen using scroll
23. Border:
    - <Width> & <border-width> & <border-style> & <border-color> & <border-radius>
24. Margin:
    - (top, bottom, left, right) Apply in this Order.
25. Text-Decoration:
    - text-decoration - Type of Text eg.{overline, line-through, underline}
    - text indent - Space Before Text
    - text-transform - Text to Capital
    - text-shadow - /* offset-x | offset-y | blur-radius | color */
26. Text-Spacing
    - letter-spacing - Spacing between Letters
    - word-spacing - Spacing Between Words
27. Font
    - font-size - size in px/%/em
    - font-family - Actual Font Glyph
    - font-style - bold/italic/underlined
    - font-variant - Variant Representations of Text eg. Small caps/normal etc
28. List
    - ul - Unordered list
       -  list-style-type - 
    - ul.nav li - Used to construct the default contents of a list item's marker
    - ol - Ordered List