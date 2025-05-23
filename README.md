# 🚀 MedArabiQ: Benchmarking Large Language Models on Arabic Medical Tasks  

## Paper Link
- Preprint: https://www.arxiv.org/abs/2505.03427


## 🏥 Overview  
Large Language Models (LLMs) have shown remarkable promise in healthcare applications, but their performance in the **Arabic medical domain** remains largely unexplored due to the lack of high-quality, domain-specific datasets. **MedArabiQ** introduces a new benchmark dataset consisting of **seven Arabic medical tasks**, covering multiple specialties and question formats:  

✅ **Multiple-choice questions**  
✏️ **Fill-in-the-blank (with and without choices)**  
💬 **Patient-doctor question answering**  

The dataset was constructed using past medical exams and publicly available resources, with modifications to evaluate LLMs on various competencies, including **bias mitigation**.  

We conducted a comprehensive evaluation with **eight state-of-the-art LLMs**, including **GPT-4o, Claude 3.5-Sonnet, and Gemini 1.5**. Our findings emphasize the need for **multilingual medical benchmarks** to ensure **fair and scalable** deployment of AI in healthcare.  

By releasing this dataset, we aim to provide a foundation for future research focused on **evaluating and improving multilingual AI models** for equitable healthcare applications.  

---

## 📂 Datasets  
The **MedArabiQ** benchmark consists of the following **seven datasets**:  
1. 🏥 **Multiple Choice – Medical Knowledge Assessment**  
2. 🧠 **Multiple Choice – Bias Evaluation in Medical Contexts**  
3. ✏️ **Fill-in-the-Blank (With Choices)**  
4. 🔍 **Fill-in-the-Blank (Without Choices)**  
5. 🗣️ **Patient-Doctor Question Answering (QA)**  
6. ⚖️ **QA with GEC**  
7. 🚨 **QA with LLM modifications**  

Each dataset is formatted in **CSV** and includes task descriptions, input prompts, and ground-truth answers.  

If you use this dataset, please cite our work and give our repo a ⭐:


@article{daoud2025medarabiq,
  title={MedArabiQ: Benchmarking Large Language Models on Arabic Medical Tasks},
  author={Daoud, Mouath Abu and Abouzahir, Chaimae and Kharouf, Leen and Al-Eisawi, Walid and Habash, Nizar and Shamout, Farah E},
  journal={arXiv preprint arXiv:2505.03427},
  year={2025}
}
