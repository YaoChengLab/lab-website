---
title: pxGPT
permalink: /resources/tools-data/pxGPT/
---

# pxGPT turns plant photos into clear records with AI

{% include figure.html image="images/projects/pxgpt.jpg" %}

{% include button.html type="github" text="pxGPT on GitHub" link="YaoChengLab/pxgpt" %}
{% include button.html type="paper" text="Bioinformatics (2026)" link="https://doi.org/10.1093/bioinformatics/btag781" %}
{% include button.html type="link" text="中文版" link="resources/tools-data/pxgpt-tw" %}

A plant breeder might describe a plant like this: "The leaves are round, slightly wrinkled, and bright green."
These notes are useful.
But looking at many plants and writing each record takes time.
Different words for the same feature also make the notes hard to compare.

A research team led by Associate Research Fellow Yao-Cheng Lin at the Agricultural Biotechnology Research Center (ABRC), Academia Sinica, has developed pxGPT, an open-source software tool, to help with this task.
The study appears in *Bioinformatics*.
pxGPT uses AI that can read both images and text.
It turns photos taken from different angles into plant records with fixed fields.

Think of it as three steps: write a description, build a form, then fill it in.

1. **Look and describe.** The AI views photos of the same sample from several angles. It writes a description of the plant features it can see.
2. **Build and review the form.** The AI uses descriptions from the image collection to propose features and answer choices. Researchers check and edit the form. Which leaf shapes should it include? What does each choice mean? Once the form is ready, its rules stay fixed.
3. **Look again and fill it in.** The AI checks the photos again and records each feature using those rules. The result is a table that researchers can compare and count. The form also separates "this structure is absent" from "the photos do not show enough detail to decide."

The team tested pxGPT with photos of *Brassica* plants, a group that includes cabbage and oilseed rape.
Several people also assessed the images independently.
The tests showed that pxGPT could produce records in the required format.
However, it still made mistakes.
Agreement between AI and people remained below agreement among people.
Different AI models could use the same form, although their results differed.

pxGPT offers a way to organize visible plant features: AI helps examine photos and fill in records, while researchers check the results.
Its accuracy must be tested again for other crops or different photo conditions.

The study was supervised by Associate Research Fellow Yao-Cheng Lin.
The first author is Po-Xing Zheng, a manager of the "AI for AgroTech" core facility at the ABRC.
Other contributors are Jheng-Yan Ou, Yu-Lin Wu, Ruei-Shiuan Wang, Ting-Li Wu, and Te-Chang Hsu, research assistants at the ABRC.
The research was supported by Academia Sinica through its Sustainable Agricultural Grant.

**Paper:** Zheng et al. (2026). pxGPT: a schema-constrained multimodal large language model framework for plant phenotyping. *Bioinformatics*. DOI: [10.1093/bioinformatics/btag781](https://doi.org/10.1093/bioinformatics/btag781)  
**Software:** [pxGPT](https://github.com/YaoChengLab/pxgpt)
