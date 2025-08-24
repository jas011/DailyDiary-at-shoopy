# Shoopy Internship – Daily Diary  
**Duration:** 21 June 2025 – 17 July 2025  
**Excluding Saturdays & Sundays**  
**Project:** Converting Catalogue (HBS → PDF) + Template Selection Modal  

---

## Week 1

### 23 June (Monday)  
First day of real work! I got introduced to the catalogue-to-PDF project. The task was to convert **HBS (Handlebars templates)** into **PDFs**. I spent most of today setting up the dev environment and going through how catalogues were structured.  

### 24 June (Tuesday)  
Explored HBS templates in detail. Understood how product data is injected into them and how I could render them into HTML. Installed supporting libraries for the conversion pipeline.  

### 25 June (Wednesday)  
Started experimenting with rendering HBS into HTML. Managed to get some raw HTML output. From there, I tried generating PDFs. The layout was messy, but it felt like a small milestone.  

### 26 June (Thursday)  
Made good progress — set up the first working **HBS → HTML → PDF pipeline**. CSS wasn’t rendering properly yet, so most of the day went into debugging fonts and layouts.  

### 27 June (Friday)  
Focused on design cleanup. Worked on making the generated PDF look closer to a real product catalogue. Fixed fonts, spacing, and images. By evening, the PDF was starting to look like something real.  

---

## Week 2

### 30 June (Monday)  
Started adding **dynamic product data** into the templates. Got a few test catalogues generated successfully. This was the first time I saw real product data come through in the PDFs.  

### 1 July (Tuesday)  
Tackled the issue of **multi-page PDFs**. Previously, content would just cut off after one page. Implemented pagination and tested with bigger data — worked after a lot of trial and error.  

### 2 July (Wednesday)  
Added **headers and footers** with branding elements like logos and page numbers. Alignment was tricky at first, but I figured it out.  

### 3 July (Thursday)  
Polished layouts. Fixed issues like content breaking across pages. Learned how to manage page-break CSS effectively.  

### 4 July (Friday)  
Documented the work so far. Pipeline was now stable enough for regular usage. Ended the week with a cleaner, more reliable PDF generation system.  

---

## Week 3

### 7 July (Monday)  
Worked on **performance optimization**. Large catalogues were slow, so I cut down on extra assets and improved load speed.  

### 8 July (Tuesday)  
Added **error handling**. If product data was missing or invalid, the system now showed fallbacks instead of crashing.  

### 9 July (Wednesday)  
Enabled **direct download of generated PDFs** in the browser. Tested across multiple browsers.  

### 10 July (Thursday)  
Refined styling once again — margins, fonts, and spacing for a more professional look.  

### 11 July (Friday)  
Tested with **real Shoopy catalogue data**. Fixed issues with long product descriptions overflowing. By the end, the catalogue PDFs looked production-ready.  

---

## Week 4

### 14 July (Monday)  
Started working on **multiple catalogue layouts**. Some catalogues needed different formats, so I made the system more flexible.  

### 15 July (Tuesday)  
Built a **React modal** where users can select a template (Crisp, Sleek, Lumen) before exporting the PDF. This made the system more interactive.  

### 16 July (Wednesday)  
Collaborated with the **design team**. They shared Figma designs for catalogue templates, and I integrated them into the export workflow. Tested the modal with different layouts.  

### 17 July (Thursday)  
Final day! Completed documentation for the whole **HBS → PDF system** and the new **template selection modal**. Shared the final deliverables with the team. Felt proud seeing the system come together from scratch.  

---

## Final Reflection
This internship gave me real-world experience in **web-to-PDF rendering, UI development in React, and collaboration with a design team**.  

Key achievements:  
- Built an **HBS → HTML → PDF pipeline** with styling, pagination, and error handling.  
- Developed a **React modal** for template selection (Crisp, Sleek, Lumen).  
- Integrated **Figma designs from the design team** into the final output.  
- Optimized performance and tested with real catalogue data.  
- Documented everything for future use by the Shoopy team.  
