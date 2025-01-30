<!--
author:   KRE-DSS

email:    

version:  0.1

language: de

narrator: Deutsch Female

classroom: disable

mode: Presentation

@Kekule.load: @Kekule.load_(@uid,@0)

@Kekule.load_
<div id="structureContainer_@0"></div>

<script>
// Load the XYZ file from a URL
Kekule.IO.loadUrlData('@1', (mol, success) => {
if (!success) {
  document.getElementById("structureContainer_@0").innerHTML = 'Failed to load @1';
  return;
}

var viewer = new Kekule.ChemWidget.Viewer(document);
viewer.setDimension('100%', '60vh');
viewer.appendToElem(document.getElementById('structureContainer_@0')).setChemObj(mol);  
viewer.setAutofit(true);
viewer.setEnableToolbar(true);
viewer.setRenderType(Kekule.Render.RendererType.R3D);
});

console.log("loading file", Kekule)

</script>

@end

-->

# Vom Alkohol zum Aromastoff

[![Shield](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

## Woher kommt der Kater?

@Kekule.load

@[Kekule.load](media/Ethanol.mol)


