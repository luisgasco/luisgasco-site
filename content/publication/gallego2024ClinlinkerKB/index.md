---
title: "Clinlinker-Kb: Clinical Entity Linking in Spanish with Knowledge-Graph Enhanced Biencoders"
authors:
- Fernando Gallego
- Guillermo Lopez-García
- Admin
- Martin Krallinguer
- Francisco J. Veredas

date: "2024"
doi: "https://dx.doi.org/10.2139/ssrn.4939986"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]


abstract: "Background and objectives: The transition to the digital era has driven significant advancements across various sectors, including healthcare, through the implementation of electronic health records. These records contain valuable information, necessitating the development of techniques to extract and utilize these data. Natural language processing (NLP) has made considerable progress in this area, particularly in named entity recognition and medical entity linking (MEL). MEL techniques facilitate the linking or harmonization of identified entities to standardized vocabularies and knowledge bases like the Unified Medical Language System (UMLS) or SNOMED-CT. Previous studies proposed the ClinLinker tool for effective MEL in Spanish using in-domain adapted language models trained with a contrastive-learning strategy. This study aims to analyze the impact of different strategies to enhance ClinLinker’s candidate generation stage by leveraging UMLS’s graph structure, resulting in an enriched model named ClinLinker-KB.Methods: The ClinLinker pipeline initially involved a candidate-retrieval bi-encoder for concept candidate generation, followed by a candidate-reranking cross-encoder. In this study, various strategies to enrich the candidate generation stage of ClinLinker were explored by utilizing the graph structure of UMLS. The enriched model, ClinLinker-KB, was evaluated on three MEL tasks with medical corpora in Spanish: DisTEMIST, MedProcNER, and SympTEMIST. The performance was measured using top-200-accuracy values. In addition, the use of cross-encoders based on the ClinLinker-KB output was analyzed for efficient reordering of the obtained candidate concepts.Results: ClinLinker-KB demonstrated promising results, surpassing the state-of-the-art in the three analyzed MEL tasks. The model achieved the highest top-200-accuracy values of 0.912 for DisTEMIST, 0.943 for MedProcNER, and 0.969 for SympTEMIST. These results indicate that ClinLinker-KB effectively optimizes the candidate-retrieval phase for MEL, transforming the entity normalization challenge into a simpler candidate-reranking task with a reduced number of candidates.Conclusion: The enriched ClinLinker-KB model shows significant improvements in MEL performance over previous methods, achieving state-of-the-art results in Spanish medical corpora tasks. The approach of leveraging the UMLS graph structure for candidate generation proves to be effective. Additionally, the proposed methodology can be easily transferred to other languages supported by UMLS ontology, highlighting its potential for broader applicability in multilingual contexts."

# Summary. An optional shortened abstract.

tags:
- Information Retrieval
- EL 
- NER
- Health
- Medical Entity Linking
- Knowledge-graph enrichment

featured: false

url_pdf: 'https://papers.ssrn.com/sol3/Delivery.cfm/58e07141-76e2-49a4-b483-61d0270de393-MECA.pdf?abstractid=4939986&mirid=1'
url_code: 'https://github.com/ICB-UMA/ClinLinker-KB'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}                        