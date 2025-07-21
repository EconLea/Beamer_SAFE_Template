# SAFE Themed Templates 

## Beamer Template
The folder "Beamer Template" provides a few variants of a Latex Beamer presentation in "SAFE-style". 

All of theses versions

1) allow you to easily use SAFE's colors, and
2) add SAFE's (and optionally Goethe's) logo to the title slide. 

**Please note:** The logos might not be position correctly after the initial "pdflatex" command. This apparent issue should resolve itself after running "pdflatex", "biber" and "pdflatex" again. 

Feel free to create an issue in case something isn't working properly or to suggest improvements. 

---

<details>
  <summary> I would like to adapt my own template. :sparkles: </summary>
  <br>

<details>
<summary>My template has a sty file/I want to use a sty file.</summary>
<br>
Take a look at the folder "Addon_YourTemplate". 


The folder "styles" contains a simple sty file, which you can either use directly or add the respective lines of code to your current sty file. :smirk:

In addition, be sure to copy the code in "0_Main_with_sty" to your preamble. 

</details>

<details>
<summary>I want the simplest possible code without sty files. </summary>
<br> 
The folder "MinimumExample" is for you! :innocent:
</details>
</details>

----

<details>
<summary>Give me a ready-to-use template. :no_mouth: </summary>
<br>
Check out "MyTemplate". As the name indicates, this is a (streamlined) version of the template I like to use - I hope you will, too! :heart_eyes:


**Folder structure**:
```
├── 0_Loadslides.tex         # Contains all packages and personalizable design options
├── 1_Core.tex               # Home to the content of your slides
├── 2_PresentationOnly.tex   # Imports packages/design options from  0_Loadslides.tex and
                             # contents from 1_Core.tex and wraps them in a beamer presentation
├── styles                   # sty files
├── figures                  # stores logos 

```
Alternatively, you can copy this [overleaf-template](https://www.overleaf.com/read/jfjntqbmgsnr#44c21c).
</details>

## Poster Template
The poster template has two main options: 
1) A poster with logos on a white background with blue font, or
2) A poster without logos, a blue header and footer with white font.
An example of both styles is provided in pdf form.

**Please note: This template heavily builds on [Gemini](https://github.com/anishathalye/gemini), Copyright (c) Anish Athalye (me@anishathalye.com), as reflected in the licence. 
