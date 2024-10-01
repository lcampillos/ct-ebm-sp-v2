# CT-EBM-SP corpus version 2
Corpus of clinical trials for evidence-based medicine in Spanish (version 2)

A collection of __1200 texts about clinical trials__:
- __500 abstracts__ published in medical journals available from [SciELO](https://scielo.org/es/)
- __700 clinical trials announcements__ from the [Spanish Clinical Trials Register](https://reec.aemps.es) and the [European Register of Clinical Trials (EudraCT)]([https://scielo.org/es/](https://www.clinicaltrialsregister.eu)) 

Texts were annotated with the following entity types:
- Medical entities from the [__Unified Medical Language System__](https://www.nlm.nih.gov/research/umls/index.html) (Bodenreider, 2004):
  - ANAT: Anatomic entities: e.g. _brazo_ (‘arm’)  
  - CHEM: Biochemical or pharmacological substances: e.g. _aspirina_ (‘aspirin’)   
  - DEVI: Medical devices: e.g. _sonda_ (‘probe’) 
  - DISO: Pathologic conditions: e.g. _diabetes_ 
  - LIVB: Living beings and virus: e.g. _paciente_ (‘patient’) 
  - PHYS: Physiological processes: e.g. _digestion_  
  - PROC: Lab tests, diagnostic or therapeutic procedures: e.g. _endoscopia_ (‘endoscopy’) 
- Temporal entities:
  - Age: e.g. _18 años_ (‘18 years old’) 
  - Date: e.g. _2022_
  - Duration: e.g. _2 horas_ (‘2 hours’) 
  - Frequency: e.g. _mensualmente_ (‘monthly’)
  - Time or part of the day: e.g. _por la noche_ (‘at night’)
- Medication information entities:
  - Contraindicated: e.g. _contraindicación a aspirina_ (‘contraindication to aspirin’) 
  - Dose or strength: e.g. _150 mg_
  - Form: e.g. _pastillas_ (‘pills’) 
  - Route or administration mode: e.g. _oral_
- Miscellaneous medical entities:
  - Concept: e.g. _inicio del ensayo_ (‘at study start’)
  - Food or Dring: e.g. _alcohol_ 
  - Observation or Finding: e.g. _normotenso_ (‘normal blood pressure’)
  - Quantifier or Qualifier: e.g. _grave_ (‘severe’)
  - Result or Value: e.g. _> 90 mmHg_
- Assertion and uncertainty information:
  - Negation cue (```Neg_cue```) and Negated events: e.g. _sin fiebre_ (‘no fever’)
  - Speculation cue (```Spec_cue```) and Speculated events: e.g. _sospecha de carcinoma_ (‘carcinoma suspected’)
- Experiencer and event temporality attributes:
  - Experiencer attributes:
    - Patient: e.g. _mujer embarazada_ (‘pregnant woman’)
    - Family\_member: e.g. _padres_ (‘parents’)
    - Other: e.g. _cirujano_ (‘surgeon’)
  - Event temporality attributes:    
    - Family_history\_of: e.g. _antecedentes familiares de diabetes_ (‘family history of diabetes’)
    - Future: e.g. _cirugía pendiente_ (‘pending surgery’)
    - History\_of: e.g. _antecedentes de migraña_ (‘history of migraine’)
    - Hypothetical: e.g. _si el paciente tuviera fiebre_ (‘if the patient had a fever’)
    

A companion annotated guideline is available in this repository.

[//]: <> (### Contact)

[//]: <> ()

# Data for human evaluation of the medical entity recognizer (MedSpaNER)
This repository includes the data used for the human evaluation:

- 100 clinical trial announcements from [EudraCT](https://www.clinicaltrialsregister.eu/) not used for system development: we provide files of the version revised by medical professionals (```Reference``` folder)
- 100 clinical cases with Creative Commons license: we provide files with the files revised by medical professionals (```Reference``` folder). 

The data come from:
  - [Urgencias Bidasoa](https://urgenciasbidasoa.wordpress.com/casos-clinicos-3/)
  - [Hipocampo.org](https://www.hipocampo.org/)
  - Cases published by [Sociedad Andaluza de Medicina Familiar y Comunitaria (SAMFyC)](https://www.samfyc.es/): we are greatly thankful for giving us permission to use these cases and we acknowledge that the copyright belongs to the authors' contents. Clinical cases were extracted from [books published from 2016 to 2022](https://www.samfyc.es/tipos-publicacion/publicaciones/).


## How to cite
The article describing the first version of the corpus is [available here](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-021-01395-z).

If you use this second version of the corpus, please cite the reference as follows:

```
@article{campillosetal2024,
  title={{Hybrid natural language processing tool for semantic annotation of medical texts in Spanish}},
  author={Campillos-Llanos, Leonardo and Valverde-Mateos, Ana and Capllonch-Carri{\'o}n, Adri{\'a}n},
  journal={BMC Bioinformatics},
  publisher={BioMed Central}
}
```

## Contact

Leonardo Campillos-Llanos, CSIC (Spanish National Research Council)

```leonardo.campillos AT csic.es```


CLARA-MeD Project (PID2020-116001RA-C33), 2021-24

Funded by MCIN/AEI/10.13039/501100011033/, in project call: "Proyectos I+D+i Retos Investigación"



