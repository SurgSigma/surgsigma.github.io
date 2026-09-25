# SurgΣ project website

This repository hosts the [SurgΣ project page](https://surgsigma.github.io/) and public annotation guidelines for SurgΣ-DB. The [dataset release](https://huggingface.co/datasets/SurgSigma/SurgSigma-DB) is hosted separately on Hugging Face.

## Annotation guidelines

The [guidelines section on the website](https://surgsigma.github.io/#annotation-guidelines) links to all three current documents:

1. **GraSP RARP instrument–action–target triplets:** [read the accessible web guide](https://surgsigma.github.io/static/guidelines/grasp-rarp-triplet.html) or [download the current Word guideline](https://github.com/SurgSigma/surgsigma.github.io/blob/master/static/guidelines/RARP_guideline_triplet.docx).
2. **Basic Surgical Actions 10:** [open the PDF guideline](https://github.com/SurgSigma/surgsigma.github.io/blob/master/static/guidelines/Basic%20Surgical%20Actions-10.pdf).
3. **Safe window for seminal vesicle dissection in RARP:** [open the Word guideline](https://github.com/SurgSigma/surgsigma.github.io/blob/master/static/guidelines/Safe%20window%20for%20seminal%20vesicle%20dissection%20in%20RARP.docx).

The RARP web guide presents the label space, 12 action labels, 156 valid triplets, and visual references. The Word file is the current source document for that guide.

---

# Academic Project Page Template

> **Update (September 2025)**: This template has been modernized with better design, SEO, and mobile support. For the original version, see the [original-version branch](https://github.com/eliahuhorwitz/Academic-project-page-template/tree/original-version).

A clean, responsive template for academic project pages.


Example project pages built using this template are:
- https://horwitz.ai/probex
- https://vision.huji.ac.il/probegen
- https://horwitz.ai/mother
- https://horwitz.ai/spectral_detuning
- https://vision.huji.ac.il/ladeda
- https://vision.huji.ac.il/dsire
- https://horwitz.ai/podd
- https://dreamix-video-editing.github.io
- https://horwitz.ai/conffusion
- https://horwitz.ai/3d_ads/
- https://vision.huji.ac.il/ssrl_ad
- https://vision.huji.ac.il/deepsim



## Start using the template
To start using the template click on `Use this Template`.

The template uses html for controlling the content and css for controlling the style. 
To edit the websites contents edit the `index.html` file. It contains different HTML "building blocks", use whichever ones you need and comment out the rest.  

**IMPORTANT!** Make sure to replace the `favicon.ico` under `static/images/` with one of your own, otherwise your favicon is going to be a dreambooth image of me.

## What's New

- Modern, clean design with better mobile support
- Improved SEO with proper meta tags and structured data
- Performance improvements (lazy loading, optimized assets)
- More Works dropdown
- Copy button for BibTeX citations
- Better accessibility

## Components

- Teaser video
- Image carousel
- YouTube video embedding
- Video carousel
- PDF poster viewer
- BibTeX citation

## Customization

The HTML file has TODO comments showing what to replace:

- Paper title, authors, institution, conference
- Links (arXiv, GitHub, etc.)
- Abstract and descriptions  
- Videos, images, and PDFs
- Related works in the dropdown
- Meta tags for SEO and social sharing

### Meta Tags
The template includes meta tags for better search engine visibility and social media sharing. These appear in the `<head>` section and help with:
- Google Scholar indexing
- Social media previews (Twitter, Facebook, LinkedIn)
- Search engine optimization

Create a 1200x630px social preview image at `static/images/social_preview.png`.

## Tips

- Compress images with [TinyPNG](https://tinypng.com)
- Use YouTube for large videos (>10MB)  
- Replace the favicon in `static/images/`
- Works with GitHub Pages

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
