# HTML & CSS 2 Kompetenzcheck Teil 2
**Erweitere deine Website aus dem letzten Kompetenzcheck (Travel, usw.) um folgende Features:**

1. Bildfiltereffekt: 
   - Experimentiere mit der Hinzufügung eines einfachen Bildfiltereffekts mit CSS. 
   - Verwende die Eigenschaft `filter`, um Effekte wie Unschärfe, Graustufen oder Helligkeit auf die Bilder im Raster anzuwenden. 
   - Teste verschiedene Filterwerte, um ansprechende visuelle Effekte zu erzeugen. 
2. Mobile Navigation: 
   - Implementiere ein mobiles Navigationsmenü, auch bekannt als Burger-Menü. 
   - Du kannst das bereitgestellte vertikale Navigationsleisten-Beispiel von W3Schools verwenden (Quelle: https://www.w3schools.com/howto/howto_js_mobile_navbar.asp). 
   - Kopiere und füge den CSS- und HTML-Code aus der Quelle ein. 
   - Passe die Navigationspunkte und Links an die Reiseziele an. 
3. Keyframe-Animation: 
   - Füge eine einfache Keyframe-Animation zu einem Element der Website hinzu. 
   - Verwende die `@keyframes`-Regel, um die Animation mit gewünschten Effekten bei verschiedenen Keyframe-Prozentwerten zu definieren. 
   - Wende die Animation auf ein Element mit der `animation`-Eigenschaft an. 
4. Verwendung von Google Icons: 
    Besuche die Google Icon Library ( https://fonts.google.com/icons). 
    Wähle geeignete Google Icons aus, die zu den Reisethemen auf deiner Website passen. 
    Verwende die ::before und ::after Pseudoelemente in CSS, um die ausgewählten Icons in bestimmte Bereiche deiner Website einzufügen. 
    Passe die Größe und Farbe der Icons an, um sie gut in das Gesamtdesign der Website einzufügen. 

    Code-Snippet: 
   ```css
   .element::before{ 
   content: '\{Icon-Name}'; 
   font-family: 'Material Icons'; 
   font-size: 24px; 
   color: #000000; 
   } 
   ```
   Anmerkung: Ersetze `{Icon-Name}` mit dem Namen deines gewünschten Icons.
---
**EN:**
Expand your website from the last competence check (Travel, etc.) with the following features:

1. Image Filter Effect: 
   - Experiment with adding a simple image filter effect using CSS. 
   - Use the `filter` property to apply effects like blur, grayscale, or brightness to the images in the grid. 
   - Test different filter values to create visually appealing effects. 
2. Mobile Navigation: 
   - Implement a mobile navigation menu, also known as a burger menu. 
   - You can use the provided example of a vertical navigation bar from W3Schools (Source: https://www.w3schools.com/howto/howto_js_mobile_navbar.asp). 
   - Copy and paste the CSS and HTML code from the source. 
   - Customize the navigation points and links to fit your travel destinations. 
3. Keyframe Animation: 
   - Add a simple keyframe animation to an element on your website. 
   - Use the `@keyframes` rule to define the animation with desired effects at different keyframe percentages. 
   - Apply the animation to an element using the `animation` property. 
4. Using Google Icons: 
   - Visit the Google Icon Library (https://fonts.google.com/icons). 
   - Select suitable Google Icons that align with the travel themes on your website. 
   - Use the `::before` and `::after` pseudo-elements in CSS to insert the chosen icons into specific areas of your website. 
   - Adjust the size and color of the icons to integrate them nicely into the overall design of the website. 

Code snippet: 
```css 
.element::before { 
   content: '{Icon-Name}'; 
   font-family: 'Material Icons'; 
   font-size: 24px; 
   color: #000000; 
} 
``` 
Note: Replace `{Icon-Name}` with the name of the chosen icon and adjust the font size and color as needed 
