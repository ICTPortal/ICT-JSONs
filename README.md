# Sri Lankan ICT Textbooks in JSON (Grade 10/11)

This repository contains **Sri Lankan Grade 10 and 11 ICT textbooks in JSON format**. Each chapter, section, and lesson is structured so developers, web/app creators, or AI projects can **use it directly**.

The JSON files include:

- Chapters, sections, and subsections  
- Definitions, concepts, examples, activities  
- Lists, paragraphs, history, and computer generations  
- Learning objectives and summaries  

Basically, it’s the **textbook content converted into structured JSON**, ready to use in apps, websites, or AI models.

---

## Resources

The textbook content is based on official **Sri Lankan ICT textbooks** and online resources:  

- [e-thaksalawa ICT Textbooks](https://e-thaksalawa.moe.gov.lk)  
- Other publicly available ICT resources and PDFs  

You can download the PDFs and use them for reference or cross-checking content. A `resources` folder in this repo contains the PDF copies for your convenience.

---

## JSON Structure

Each chapter has its **own JSON file**, structured like this:

- `document_info`: Title, language  
- `chapter_content`: chapter number, learning objectives, sections  
- `sections`: each section or subsection with content  
- `content` inside sections: definitions, concepts, examples, activities, lists, paragraphs, history, generations  

**Simplified structure example:**

```text
Chapter JSON
├── document_info
├── chapter_content
│    ├── chapter_number
│    ├── learning_objectives
│    └── sections
│         ├── id
│         ├── title
│         └── content
│              ├── definition / concept / paragraph
│              ├── example
│              ├── list
│              └── activity
```
