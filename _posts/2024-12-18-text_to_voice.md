---
layout: post
title:  "Text-to-Voice: Making Product Labels Accessible"
categories: ["Python", "API Development", "Computer Vision", "Accessibility", "NLP"] 
---

Born from a simple observation: product labels contain critical information, but they're not accessible to everyone. Small print, complex medical terminology, or even language barriers can make labels a challenge for many people.

<img src="/assets/images/email.png" />
    
`_The problem`: 
So many times I have struggled to read ingredients on a food package? Now imagine facing this challenge daily due to visual impairment, language barriers, or other limitations. Critical information like dosage instructions, allergen warnings, and consumption guidelines becomes dangerously inaccessible.

`_The wake-up call`:
One too many close calls heard of on social media or family stories on struggles to read medication instructions, I realized I probably take text accessibility for granted. Sure, manual assistance works, but what about independence and privacy? I think everyone deserves access to product information without depending on others.

`_The solution`:
This Text-to-Voice project was built to bridge this accessibility gap. It's not just a simple OCR tool, it was built to understand the structure of product labels, extracts key information like product names, ingredients, and usage instructions, and converts them to natural-sounding speech. The real thing? - probably recognizing and prioritizing the most critical information, like consumption instructions, even when the image quality is poor.

`_Key features`:
- Text extraction from images using both traditional OCR and AI vision models
- Parsing for product label structures
- English and German languages support
- 'Natural-sounding' text-to-speech conversion

`_Technical highlights`:
The project gave me hands-on experience with:
- Building RESTful APIs with FastAPI
- Computer vision techniques for image preprocessing
- Hybrid OCR approaches combining traditional and AI-based methods
- Natural language processing for extracting structured information
- Regular expressions for pattern matching
- Text-to-speech integration


`_Learning outcomes`:
This project taught me the challenging aspects of dealing with the variability in real-world images—different lighting conditions, angles, and label formats. I discovered the limitations of traditinal opencv (could not identify German letters correctly) - which messed up the voice output/ user interpretation. Combining traditional OCR with AI-powered vision models created a more reliable solution (in this project image editing was done with opencv and the default text extraction was with AI, with a cv2 fallback).
What's most satisfying? Knowing this tool could help people access critical information independently, whether they're dealing with visual impairments, language barriers, or simply aging eyes.

Check out the [code][github].

[github]: https://github.com/belladoeswork/text_to_voice.git

`_Future plans`:
I'm working on expanding language support, adding other file format(e.g pdf), adding a mobile app interface, and implementing better handling of specialized label formats like prescription medications. 


Remember: Technology is most meaningful when it makes `everyday information accessible to everyone`.
