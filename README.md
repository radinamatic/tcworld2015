# A11y Testing Workshop at tcworld 2015

#### These resources are Work in Progress - check back on Friday November 6 for the final version that will help you prepare for the workshop. 

### Full list of A11y Testing tools 

## Color Contrast tools
### Accessibility Color Wheel  
**[http://gmazzocato.altervista.org/colorwheel/wheel.php](http://gmazzocato.altervista.org/colorwheel/wheel.php)**  
Find an accessible color pair and compare contrast with simulation of three types of color deficiency: deuteranopia, protanopia and tritanopia.  
### CONTRAST-A-WEB
**[http://dasplankton.de/ContrastA/](http://dasplankton.de/ContrastA/)**  
Web application that allows users to experiment with color combinations, examine them under the aspect of accessibility guidelines and to create custom color palettes.
### Color Safe
**[http://colorsafe.co/](http://colorsafe.co/)**  
Accessible color palettes based on WCAG Guidelines of text and background contrast ratios.
### WCAG Contrast checker
**[ https://addons.mozilla.org/ca/firefox/addon/wcag-contrast-checker/](https://addons.mozilla.org/ca/firefox/addon/wcag-contrast-checker/)**  
Firefox addon; very complete sidebar contrast checker, on top of which is provided a filter to simulate 4 types of colorblindness.
### Color Palette Accessibility Evaluator
**[http://accessibility.oit.ncsu.edu/tools/color-contrast/](http://accessibility.oit.ncsu.edu/tools/color-contrast/)**  
Online tool for analyzing color combinations that meet WCAG 2 a11y specifications.
### Color Extractor Bookmarklet
**[http://accessibility.oit.ncsu.edu/tools/color-extractor/](http://accessibility.oit.ncsu.edu/tools/color-extractor/)**  
Extracts colors from the page CSS files and feeds them to Color Palette Accessibility Evaluator (see above).
### Contrast Analyzer
**[http://www.paciellogroup.com/resources/contrastanalyser/](http://www.paciellogroup.com/resources/contrastanalyser/)**  
Standalone tool; provides a pass/fail check for WCAG 2.0 contrast criteria; simulates certain visual conditions. 
### Color Contrast Visualizer
**[http://www.stainlessvision.com/blog/projects/colour-contrast-visualiser](http://www.stainlessvision.com/blog/projects/colour-contrast-visualiser)**  
[SWF tool](http://www.stainlessvision.com/blog/files/ColourContrastVisualiser.swf) with Photoshop style color picker.

## Firefox Add-ons

### OpenAjax Alliance (OAA) Accessibility Extension
**[https://addons.mozilla.org/EN-US/firefox/addon/openajax-accessibility-exte/](https://addons.mozilla.org/EN-US/firefox/addon/openajax-accessibility-exte/)**  
My favourite sidebar (full WCAG support with the possibility to generate and export reports).
### Juicy Studio Accessibility Toolbar
**[https://addons.mozilla.org/en-uS/firefox/addon/juicy-studio-accessibility-too/](https://addons.mozilla.org/en-uS/firefox/addon/juicy-studio-accessibility-too/)**  
Good for checking ARIA features, tables and color contrast.
### AInspector Sidebar
**[https://addons.mozilla.org/en-US/firefox/addon/ainspector-sidebar/](https://addons.mozilla.org/en-US/firefox/addon/ainspector-sidebar/)**  
Very similar to OAA extension, no reports, **[docs and latest release on GitHub](http://ainspector.github.io/)**.
### WAVE Web Accessibility Evaluation Toolbar
**[https://addons.mozilla.org/en-US/firefox/addon/wave-toolbar/](https://addons.mozilla.org/en-US/firefox/addon/wave-toolbar/)**  
Nice visual tool, **[Chrome](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)** version is more recent.
### Accessibility Evaluation Toolbar
**[https://addons.mozilla.org/en-US/firefox/addon/accessibility-evaluation-toolb/](https://addons.mozilla.org/en-US/firefox/addon/accessibility-evaluation-toolb/)**  
Good set of checkers, no updates for a while.
### Jim Thatcher’s Favelets
**[http://jimthatcher.com/favelets/](http://jimthatcher.com/favelets/)**  
Several handy a11y assessment favelets/bookmarklets.
### Opquast Desktop
**[https://addons.mozilla.org/ca/firefox/addon/opquast-desktop/](https://addons.mozilla.org/ca/firefox/addon/opquast-desktop/)**  
Originally in French; A11y, SEO and more.
### NCAM Accessibility QA Favelet
**[http://ncam.wgbh.org/invent_build/web_multimedia/tools-guidelines/favelet](http://ncam.wgbh.org/invent_build/web_multimedia/tools-guidelines/favelet)**  
Not updated for a while, but still works well.

## Online A11y validation tools
### AChecker
**[http://achecker.ca/checker/index.php](http://achecker.ca/checker/index.php)**  
Full HTML, CSS, WCAG & Section 508 online assessment tool.
### Functional Accessibility Evaluator 2.0
**[http://fae20.cita.illinois.edu/](http://fae20.cita.illinois.edu/)**  
Sitewide evaluation and reports (requires registration).
### Cynthia Says
**[http://www.cynthiasays.com/](http://www.cynthiasays.com/)**
### TENON
**[http://tenon.io](http://tenon.io)**	


## _**(TODO)**_ Options for automated A11y testing  
**[Choosing an Automated Accessibility Testing Tool: 13 Questions you should ask](http://www.karlgroves.com/2013/06/28/choosing-an-automated-accessibility-testing-tool-13-questions-you-should-ask/)**  

### [pa11ly](https://github.com/nature/pa11y)
Requires Node.js and PhantomJS; **[Custom Reporters option](https://github.com/nature/pa11y#custom-reporters)**.  
### quails
**<http://quailjs.org/>**  
jQuery plugin; comes with a collection of **[250 tests from which to pick and choose or write our own in YAML/JSON](http://quail.readthedocs.org/en/latest/)**.
### Tanaguru
**<https://github.com/Tanaguru/Tanaguru>**  
Very complete website a11y assessment tool; **[basic](http://tanaguru.readthedocs.org/en/develop/userdoc-scenario-audit/)** and **[advanced](http://tanaguru.readthedocs.org/en/develop/userdoc-scenario-audit-advanced/)** Scenario audits based on Selenium).
