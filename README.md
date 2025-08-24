# Shoopy Internship – Daily Diary  
**Duration:** 21 June 2025 – 17 July 2025  
**Excluding Saturdays & Sundays**  
**Project:** Converting Catalogue (HBS → PDF)  

---

## Week 1

### 23 June (Monday)  
Today was my first proper working day at Shoopy. I got introduced to the project and the task assigned to me – converting product catalogues written in **HBS (Handlebars templates)** into **PDFs**. I spent most of the day setting up my development environment and going through the existing catalogue structure to understand how everything is linked together.  

### 24 June (Tuesday)  
I explored HBS templates in more detail today. I went through how they are structured and how data is injected into them. I also installed the necessary tools and libraries that could help me convert HBS into HTML, which I would later transform into PDF.  

### 25 June (Wednesday)  
I experimented with some sample templates and tried converting them into HTML. Once I had some basic output, I moved forward to generating PDFs from that HTML. The first few tries were rough – styling was all over the place – but it was a good start.  

### 26 June (Thursday)  
Big breakthrough today! I managed to set up a working prototype for HBS → HTML → PDF conversion. However, there were still many formatting issues, especially with CSS not rendering correctly in PDFs. Spent quite a bit of time debugging fonts and layouts.  

### 27 June (Friday)  
I focused on improving the design of the generated PDFs. Fixed issues with fonts, spacing, and images. By the end of the day, I had a cleaner-looking PDF that was much closer to what a real catalogue should look like. Felt good seeing proper output for the first time!  

---

## Week 2

### 30 June (Monday)  
Started working on adding **dynamic data** into the templates instead of just static content. The goal was to generate catalogues that adapt to product data. Successfully pulled some test data and confirmed it rendered correctly in the final PDF.  

### 1 July (Tuesday)  
Learned how to handle **multi-page PDFs**. Up until now, catalogues would break after one page, but today I managed to get proper pagination working. Tested with larger product data – lots of debugging but it worked.  

### 2 July (Wednesday)  
Worked on adding headers and footers into the PDF for branding. Experimented with company logo placement, page numbers, and contact details. The first versions didn’t align properly, but later in the day, I got a neat header-footer working.  

### 3 July (Thursday)  
Most of today went into cleaning up the design – fixing alignment issues, spacing, and making sure the content didn’t break between pages. I also learned a few tricks to control page breaks in HTML before conversion.  

### 4 July (Friday)  
Wrapped up the week by finalizing a more polished version of the pipeline. I documented what was done so far – how HBS is rendered, how CSS is applied, and how the final PDF is generated. The progress feels solid now.  

---

## Week 3

### 7 July (Monday)  
I noticed that generating PDFs for larger catalogues was a bit slow. Today I worked on **optimizing performance**, trimming down unnecessary assets and reducing the load time. The PDFs were noticeably faster to generate by the end of the day.  

### 8 July (Tuesday)  
I added **error handling** for cases where product data might be missing or corrupted. Instead of the pipeline breaking, the system now shows a fallback message or skips problematic entries. This made the process much more stable.  

### 9 July (Wednesday)  
Today’s focus was on enabling an easy way for users to **download the generated PDFs directly**. I tested the download functionality across different browsers to make sure it worked consistently.  

### 10 July (Thursday)  
I spent time on styling again – making sure the PDF output looked consistent with the original catalogue design. This included fixing small CSS bugs like margins, fonts, and table borders.  

### 11 July (Friday)  
I tested the system with **real Shoopy catalogue data** today. Found a few bugs with long product descriptions spilling over, but fixed them quickly. The output now looked like an actual ready-to-share product catalogue.  

---

## Week 4

### 14 July (Monday)  
I started working on supporting **multiple catalogue formats**. Some catalogues had different layouts, so I had to make sure the pipeline could handle variations. It was tricky but interesting.  

### 15 July (Tuesday)  
Improved the CSS once again, this time focusing on making the layout lighter and more optimized for PDF rendering. Also fixed a few alignment problems reported by the team.  

### 16 July (Wednesday)  
Today was mainly about **testing and validation**. I tested the pipeline with several sample catalogues and shared the PDFs with the team for review. Minor feedback was noted, which I’ll finalize tomorrow.  

### 17 July (Thursday)  
My last day on this task! I completed all documentation for the **HBS → PDF workflow**, including setup steps, troubleshooting, and usage notes. Shared the final deliverables with the team. Felt good to see the whole process working end to end.  

---

## Final Reflection
Working on this project taught me a lot about **templating, HTML-to-PDF rendering, CSS debugging, and performance optimization**. It was challenging at times, but also very rewarding. By the end, I was able to create a reliable system that can generate well-formatted, dynamic PDF catalogues from HBS templates – something I’m proud of contributing during my time at Shoopy.
