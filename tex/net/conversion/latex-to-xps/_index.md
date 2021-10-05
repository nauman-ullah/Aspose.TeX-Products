---
title: Convert LATEX to XPS with .NET 
description: Convert TeX files using .NET API on Windows, macOS & Linux
url: /net/conversion/latex-to-xps/
family: tex
platformtag: net
feature: conversion
informat: LATEX
outformat: XPS
otherformats: PNG JPEG TIFF BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert LATEX to XPS via C#" h2="Convert TeX files to XPS, PDF & Image formats like XPS on Windows, macOS & Linux">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="LATEX to XPS Conversion on .NET" %}}
1. Initialize [TeXOptions](https://apireference.aspose.com/tex/net/aspose.tex/texoptions)
2. Specify the file system working directory for the output using [OutputWorkingDirectory](https://apireference.aspose.com/tex/net/aspose.tex/texoptions/properties/outputworkingdirectory)
3. Initialize the options for saving in XPS format using [XpsSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.xps/xpssaveoptions)
4. Run LaTeX to XPS conversion using [TeXJob](https://apireference.aspose.com/tex/net/aspose.tex/texjob) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET TeX API" %}}
Install from command line as ```nuget install Aspose.TeX``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.TeX```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://products.aspose.com/tex/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code for LATEX to XPS Conversion" gistPath="" %}}
```cs
TeXOptions options = TeXOptions.ConsoleAppOptions(TeXConfig.ObjectLaTeX);
options.OutputWorkingDirectory = new OutputFileSystemDirectory("/output");
options.SaveOptions = new XpsSaveOptions();
new TeXJob("sample.tex", new ImageDevice(), options).Run();
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}