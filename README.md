# Epidemiology and Risk Characterisation of Vitiligo using a Large UK Population-Based Dataset
Codelists, exposure/outcome definitions and algorithms for "Epidemiology and Risk Characterisation of Vitiligo using a Large UK Population-Based Dataset" study by Momentum Data.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification
For the purposes of codelist identification, primary care codes

### Vitiligo
1. People identified with a diagnosis code for [vitiligo](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Vitiligo) in primary care.
2. And people with no diagnosis codes for the alternative depigmentation conditions listed below.
   - [Congenital and genetic hypomelanoses](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c2b95a798ef69efc22afa6b75a70a4866b5f8524/Conditions/Congenital%20and%20Genetic%20Hypomelanoses%20v2):
     - Piebaldism
     - Tuberous sclerosis
     - Hypomelanosis of Ito
     - Waardenburg syndrome
     - Hermanski-Pudlak syndrome
     - Griscelli syndrome
     - Menkes syndrome
     - Genetic hypopigmenting conditions (excluding vitiligo)
    
   - Post-inflammatory hypomelanoses:
     - [Post-inflammatory leukoderma including after atopic eczema or psoriasis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Post-inflammatory%20Hypopigmentation)
     - [Lichen planus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Lichen%20Planus)
     - [Pityriasis alba](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Pityriasis%20Alba)
     - [Lichen sclerosus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Lichen%20Sclerosis)
       
   - [Post traumatic leukoderma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Post-traumatic%20Leucoderma)
     
   - [Para-malignant hypomelanoses](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Para-malignant%20Hypomelanoses):
     - Cutaneous T-cell lymphoma (mycosis fungoides)
     - Melanoma associated depigmentation

   - [Occupational vitiligo](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Occupational%20Vitiligo)
     
   - [Induced hypomelanoses (excluding vitiligo)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Other%20Induced%20Hypomelanoses%20v1)
     
   - [Pityriasis versicolor (or Tinea versicolor)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Pityriasis%20Versicolor)
  
   - Others:
     - [Melasma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Melasma)
     - [Morphoea](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Morphoea)
     - [Idiopathic guttate hypomelanosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Idiopathic%20Guttate%20Hypomelanoses)
     - [Xeroderma pigmentosum](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Xeroderma%20Pigmentosum)
     - [Progressive macular hypomelanosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Progressive%20Macular%20Hypomelanosis)
     - [Nevus depigmentosus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Nevus%20Depigmentosus)
     - [Cutaneous sarcoidosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Cutaneous%20Sarcoidosis)
    
### Trial-similar vitiligo
In addition to the criteria listed above for vitiligo, patients with any of the following diagnosis/medication/procedure codes (made in primary care) will be excluded from the trial similar cohort:
 - Vogt-Koyanagi-Harada disease (included in [Congenital and genetic hypomelanoses](https://github.com/MomentumData/Momentum-Data-Codelists/tree/933109f7d1f8ff28e32fe88ccc4417018c8af3c2/Conditions/Congenital%20and%20Genetic%20Hypomelanoses%20v2))
 - [Ataxia telangiectasia](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Ataxia%20Telangiectasia)
 - [Albinism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Albinism)
 - [Incontinentia pigmenti](https://github.com/MomentumData/Momentum-Data-Codelists/tree/5b78b7a5c15d07a55823ce6963d0a43a5a82a51f/Conditions/Incontinentia%20Pigmenti)
 - [Dyschromatosis symmetrica hereditarian](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e34f29b7f74498877cb3ca60db0b4d9a1c64a745/Conditions/Dyschromatosis%20Symmetrica%20Hereditarian)
 - [Leukoderma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e34f29b7f74498877cb3ca60db0b4d9a1c64a745/Conditions/Leukoderma)
 - [Discoid lupus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e34f29b7f74498877cb3ca60db0b4d9a1c64a745/Conditions/Discoid%20Lupus)
 - [Syphilis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0fc8ae9e13f9827d7a07bdf9e0c7ceab9aaca0e/Conditions/Secondary%20Syphilis%20of%20the%20Skin)
 - [Seborrheic dermatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0fc8ae9e13f9827d7a07bdf9e0c7ceab9aaca0e/Conditions/Seborrheic%20Dermatitis)
 - [Antibiotics](https://github.com/MomentumData/Momentum-Data-Codelists/tree/49b067d04d7c252eb8ef5e0b6a582656c1212ac4/Treatments/Antibiotics)
 - [Antivirals](https://github.com/MomentumData/Momentum-Data-Codelists/tree/f92782ba5eac8ae5beea728a2fed9d428ac997e2/Treatments/Antivirals)
 - [Antiparasitics](https://github.com/MomentumData/Momentum-Data-Codelists/tree/f92782ba5eac8ae5beea728a2fed9d428ac997e2/Treatments/Antiparasitics)
 - [Antiprotozoals](https://github.com/MomentumData/Momentum-Data-Codelists/tree/0c0974904cfe8ce4407b45239fc1f972523c8164/Treatments/Antiprotozoals)
 - [Antifungals](https://github.com/MomentumData/Momentum-Data-Codelists/tree/baf2d67d77864d4746842ba871333252d5f09c5a/Treatments/Antifungals)
 - Serious infections
   - [Encephalitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Encephalitis)
   - [Endocarditis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Endocarditis)
   - [Gastrointestinal infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Gastrointestinal%20Infections)
   - [Infectious hepatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Infectious%20Hepatitis)
   - [Joint infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Joint%20Infection)
   - [Mentingitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Meningitis)
   - [Bone infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Osteomyelitis%20(Bone%20Infections))
   - [Respiratory infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Respiratory%20Infections)
   - [Sepsis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Sepsis)
   - [Skin infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Skin%20Infections)
 - [Active tuberculosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d375622de34a9ad1cf6aed30e1a88bfb3814fd24/Conditions/Tuberculosis)
 - [Disseminated herpes simplex or zoster:](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Disseminated%20Herpes%20Simplex%20or%20Zoster)
   - Herpetic septicemia
   - Visceral herpes simplex
   - Herpes viral hepatitis
   - Herpesvirus encephalitis
   - Disseminated herpes viral disease
 - [Hepatitis B](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Hepatitis%20B)
 - [Hepatitis C](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Hepatitis%20C)
 - [Humman Immunodeficiency Virus (HIV)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/HIV%20(Humman%20Immunodeficiency%20Virus))
 - Clinically significant, severe, progressive or uncontrolled diseases:
   - [Renal](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/CKD%20(Chronic%20Kidney%20Disease)%20Any%20Stage)
   - [Hepatic](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/Chronic%20Liver%20Disease)
   - Haematological (Anemia dervied from algorithm)
   - Gastrointestinal
     - [Gastro-Oesophageal Reflux Disease (GORD)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/19cc71927af35556e3f7112295e7686b72931806/Conditions/GORD%20(Gastro-Oesophageal%20Reflux%20Disease))
     - [Peptic Ulcer Disease](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c8da54d43f52d3997d3779749731b7eee8160140/Conditions/Peptic%20Ulcer)
     - [Other Inflammatory Bowel Disease](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c8da54d43f52d3997d3779749731b7eee8160140/Conditions/Other%20IBD%20(Inflammatory%20Bowel%20Disease))
     - [Diverticular Disease and Diverticulitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/6e746643efe79163d3bff125de856d8e7afc148e/Conditions/Diverticular%20Disease%20and%20divertuculitis)
     - [Irritable Bowel Syndrome (IBS)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/6e746643efe79163d3bff125de856d8e7afc148e/Conditions/Irritable%20Bowel%20Syndrome%20(IBS))
     - [Acute/Chronic Pancreatitis(Sourced from Exeter Diabetes GitHub)](https://github.com/Exeter-Diabetes/CPRD-Codelists)
     - [Gall stone disease](https://github.com/MomentumData/Momentum-Data-Codelists/tree/b50c05e044f358fd27af97a02c0ed589d5912f50/Conditions/Gall%20Stone%20Disease)
   - Metabolic
   - [Endocrine (Hyperthyroidism excluding Graves Disease + Hyperparathyroidism + Hypopituitarism + Addison's Disease)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/779eef57c6491a4d242ee821c94d24185cf76cd2/Conditions/Hyperthyroidism)
   - Pulmonary
      - [Interstitial Lung Disease (ILD)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/779eef57c6491a4d242ee821c94d24185cf76cd2/Conditions/ILD%20(Interstitial%20Lung%20Disease))
      - [Bronchiectasis(Sourced from Exeter Diabetes GitHub)](https://github.com/Exeter-Diabetes/CPRD-Codelists)
   - Cardiovascular
    - [Myocardial Infarction](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/MI%20(Myocardial%20Infarction))
   - Psychiatric
      - Alcohol Abuse
      - [Schizophrenia](https://github.com/MomentumData/Momentum-Data-Codelists/tree/779eef57c6491a4d242ee821c94d24185cf76cd2/Conditions/Schizophrenia)
   - Immunologic/Rheumatologic
      - [Osteoarthritis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/34d46beface4bdc44f7dc03c9095dc1463c10706/Conditions/Osteoarthritis)
      - [Osteoporosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/779eef57c6491a4d242ee821c94d24185cf76cd2/Conditions/Osteoporosis)
   - Neurologic
      - [Dementia](https://github.com/MomentumData/Momentum-Data-Codelists/tree/34d46beface4bdc44f7dc03c9095dc1463c10706/Conditions/Dementia)
      - [Epilepsy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/34d46beface4bdc44f7dc03c9095dc1463c10706/Conditions/Epilepsy)
 - Hearing loss, middle or inner ear disease:
   - [Otis media](https://github.com/MomentumData/Momentum-Data-Codelists/tree/923d229b6b32090156693bc20692d83af34b5bbd/Conditions/Otitis%20Media)
   - [Cholesteatoma](https://github.com/MomentumData/Momentum-Data-Codelists/tree/fe7ab259a4335ca8e96c874677cb04660792ce83/Conditions/Cholesteatoma)
   - [Meniere's Disease](https://github.com/MomentumData/Momentum-Data-Codelists/tree/93d9a1a8c27ba064a57ed3aadff7df0f640d6163/Conditions/Meniere's%20Disease)
   - [Labyrinthitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/d10dd7bbf69f497d2cd9b76007c2bc6bd1d6310e/Conditions/Labyrinthitis)
 - [Lymphoproliferative disorders:](https://github.com/MomentumData/Momentum-Data-Codelists/tree/748d5244bd3f95c2f0fe62b68b33487df4130c5e/Conditions/Lymphoproliferative%20Disorders)
   - Waldenstorm's Macroglobulinemia
   - Wiskott-Aldrich syndrome
   - Pityriasis llichenoides
   - Parapsoriasis post-transplant lymphoproliferative disorder
   - Autoimmune lymphoproliferative syndrome
 - [Cardiompyopathy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/748d5244bd3f95c2f0fe62b68b33487df4130c5e/Conditions/Cardiomyopathy)
 - [Long QT syndrome]
 - [Torsade de pointe]
 - Malignancy (excluding non-melanoma skin cancer (NMSC))
    -[Solid cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Solid%20Cancer)
    - [Haematological cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Haematological%20Cancer)
 - Depigmentation treatment for pigmentation disorders
 - [Systemic JAK inhibitor](https://github.com/MomentumData/Momentum-Data-Codelists/tree/63b7a8c005c19d2fd174ac3be07b0de275b78187/Treatments/JAK-Inhibitors)
 - [Non-B cell selective lymphocyte depleting agent](https://github.com/MomentumData/Momentum-Data-Codelists/tree/bcd9f1286e273b7086a8d7f03ace1a32cd8fa4ad/Treatments/Non%20B%20cell%20selective%20lymphocyte%20depleting%20agents)
 - Melanocyte-keratinocyte transplantation
 - Surgical treatment for vitiligo
 - [B-cell-depleting agents](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/B-Cell%20Depleting%20Agents)
 - Immunomodulatory biologic agents:
     - [Bimekizumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Bimekizumab)
     - [Brodalumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Brodalumab)
     - [Certolizumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Certolizumab)
     - [Etanercept](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Etanercept)
     - [Golimumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Golimumab)
     - [Guselkumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Guselkumab)
     - [Infliximab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/2a8565f32e9e65f2201b90fabe74ec98c5bb6f41/Treatments/Infliximab)
     - [Ixekizumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Ixekizumab)
     - [Risankizumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Risankizumab)
     - [Secukinumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Secukinumab)
     - [Tildrakizumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Tildrakizumab)
     - [Ustekinumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Ustekinumab)
     - [Abatacept](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Abatacept)
     - [Adalimumab](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Adalimumab)
     - [Anakinra](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Anakinra)
     - [Apremilast](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Apremilast)
 - [Phototherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Conditions/Phototherapy)
 - Laser therapy
 - Oral immune suppressants:
     - [Azathioprine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Azathioprine)
     - [Ciclosporin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Ciclosporin)
     - [Methotrexate](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Methotrexate)
     - [Mycophenolate-mofetil](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Mycophenolate%20Mofetil)
 - [Intralesional steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/4cfe5d53a399523b7fbde5a7a073fb8b8adbbfc3/Treatments/Intralesional%20Steroids)
 - [Oral steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ec0326257badeb897c281d7dfcd80f2fdfa77f95/Treatments/Oral%20Steroids)
 - [Injectable steroids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ec0326257badeb897c281d7dfcd80f2fdfa77f95/Treatments/Injectable%20Steroids)
 - [Exposure to investigational drugs](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ec0326257badeb897c281d7dfcd80f2fdfa77f95/Conditions/Drug%20Trial%20Participant)

### Outcomes
People identified with the respective diagnosis codes recorded in primary or secondary care as for each of the outcomes below:
 - [Opportunistic infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Opportunistic%20Infections)
 - [Herpes zoster](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Herpes%20Zoster)
 - [Herpes simplex](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Herpes%20Simplex)
 - Psychiatric conditions:
   - [Anxiety disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Anxiety%20Episode)
   - [Bipolar disorders](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Bipolar%20Disorder)
   - [Personality disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Personality%20Disorders)
   - [Suicidal ideation or behaviour](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Suicidal%20Ideation)
   - [Depression](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Depressive%20Episodes)
 - [Type 1 Diabetes](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Type%201%20Diabetes)
 - [Type 2 Diabetes](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Type%202%20Diabetes)
 - Autoimmune thyroditis:
       - Defined by algorithm: A code for [Hashimoto's](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Hashimoto's%20Thyroditis) OR a code for [non-specific hypothyroidism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Non-Specific%20Hypothyroidism) AND no code for [non-autoimmune hypothyroidism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Non-Autoimmune%20Hypothyroidism)
 - [Rheumatoid arthritis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/RA%20(Rheumatoid%20Arthritis))
 - [Systemic lupus erythematosus](https://github.com/MomentumData/Momentum-Data-Codelists/tree/3b3ca570d00ca028fa8b5d320213b34f07c9b4cc/Conditions/Systemic%20lupus%20erythematosus)
 - [Sjorgen's Syndrome](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Sjorgen's%20Syndrome)
 - [Mysathenia Gravis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Myasthenia%20Gravis)
 - [Systemic sclerosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Systemic%20Sclerosis)
 - Autoimmune blistering diseases:
   - [Epidermolysis bullosa](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Epidermolysis%20Bullosa)
   - [Pemphigus vulgaris](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Pemphigus%20Vulgaris)
   - [Bullous pemphigoid](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Bullous%20Pemphigoid)
 - [Psoriasis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Psoriasis)
 - [Pernicious anemia](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Pernicious%20Anaemia)
 - [Hearing loss](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Hearing%20Loss)
 - [Alopecia areata](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Alopecia%20Areata)
 - Serious infections
   - [Encephalitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Encephalitis)
   - [Endocarditis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Endocarditis)
   - [Gastrointestinal infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Gastrointestinal%20Infections)
   - [Infectious hepatitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Infectious%20Hepatitis)
   - [Joint infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Joint%20Infection)
   - [Mentingitis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Meningitis)
   - [Bone infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Osteomyelitis%20(Bone%20Infections))
   - [Respiratory infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Respiratory%20Infections)
   - [Sepsis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Sepsis)
   - [Skin infections](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Skin%20Infections)
 - Malignancy (excluding non-melanoma skin cancer (NMSC))
    - [Solid cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Solid%20Cancer)
    - [Haematological cancer](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Haematological%20Cancer)
 - NMSC:
   - [Basal Cell Carcinoma (BCC)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/BCC%20(Basal%20Cell%20Carcinoma))
   - [Squamous Cell Carcinoma (SCC)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Squamous%20Cell%20Carcinoma)
 - Venous thromboembolism:
   - [Deep vein thrombosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/DVT%20(Deep%20Vein%20Thrombosis))
   - [Pulmonary embolism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/PE%20(Pulmonary%20Embolism))
 - [Arterial thromboembolism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Arterial%20Thrombosis)
 - Major Adverse Cardiovascular Event (MACE):
   - [Acute myocardial infarction](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/MI%20(Myocardial%20Infarction))
   - [Unstable angina](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Unstable%20Angina)
   - [Coronary vrevascularisation by PCI or CABG](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Revascularisation%20Procedures)
   - [Ischaemic stroke](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Ischaemic%20Stroke)
   - [Haemorrhagic stroke](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Hemorrahagic%20Stroke)
- [Peripheral neuropathy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Peripheral%20Neuropathy)
- [Sensorineural hearing loss](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Sensorineural%20Hearing%20Loss)
- [Parasthesia and dysesthesia](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c05db2366ed8eadebd798be25c33491863879644/Conditions/Paraesthesia%20and%20Dysesthesia)




