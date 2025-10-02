# Bug Fixes  

## HTML  

1. <!-- <html> --> - original tag missing "lang" declaration; line 2  
<html lang="en"> - fix  

2. <!-- <meta> --> - original tag missing "charset" tag; line 6  
<meta charset="UTF-8"> - fix  

3. <!-- <img src="easter-bunny-150-profile.png"> --> - original missing "images" folder and alt text; line 14  
<img src="images/easter-bunny-150-profile.png" alt="Easter Bunny"> - fix  

4. <!-- <h4>The Easter Bunny</h4> --> - original skips h3 in hierarchy; line 46  
<h3> The Easter Bunny </h3> - fix  

5. <!-- <h5>Rabbits and Hares</h5> --> - original skips h3 and h4 in hierarchy; line 50  
<h3> Rabbits and Hares </h3> - fix  

6. <!-- <br><br><br><br><br> --> - original unnecessary break tags; line 57  
fix comment out tags  

7. <!-- <h3>Enough Content --> - original missing closing h3 tag; line 62  
<h3>Enough Content</h3> - fix  

8. <!-- <link rel="stylesheet" href="layout.css"> --> - original missing "css" folder declaration line 11  
<link rel="stylesheet" href="css/layout.css"> - fix  

## CSS  

1. <!-- color: #B2; --> - original unfinished hexadecimal value; line 33  
color: #B2D732; - fix  

2. <!-- color: #FE27122; --> - orignial incorrect hexadecimal value; line 86  
color: #FE2712; - fix  

3. <!-- line-height: 1.35me; --> - original typo of em; line 67  
line-height: 1.35em; - fix  

4. <!-- font-size: 5 vw; --> - original unrecognized font size value; line 44  
font-size: 5vw; - fix  