# RAG-custom-medical
custom-made health &amp; medical RAG

via "Llama-3.3-70B-Instruct-Q8_0-00001-of-00002.gguf", Lucene, MySQL

The following is a snippet of the jupyer code file.

The question contains an extended medical case:
```
Is pituitary apoplexy a likely diagnoses for the following medical case?
Please reason step by step.

A 55-year-old woman presented to the emergency department (ED) with the chief complaint of headache for three days, associated with nausea, vomiting, and visual changes. The headache was described as being sudden in onset, constant, bilateral, retro-orbital, and throbbing. The pain was a six out of ten in intensity. The pain was not alleviated with over the counter acetaminophen use. She was not able to describe any alleviating or exacerbating factors. The visual changes were described by the patient as “blurry vision” and “double vision” affecting her left eye greater than her right. She reported photophobia and difficulty keeping the left eye open. The patient described this difficulty of keeping the eye open as a weakness and not secondary to pain. She had approximately five episodes of non-bloody and non-bilious vomiting over the past three days and reported inability to tolerate her home medications. She also reported a sore throat and cough productive of yellow sputum for the previous two to three days, but denied fever, chills, chest pain, hemoptysis, or dyspnea.

Her past medical history included essential hypertension, hyperlipidemia, and a remote history of uterine fibroids associated with iron deficiency anemia. Prescribed medications included losartan 25 milligrams (mg) and hydrochlorothiazide 12.5 mg. She had no known drug allergies, did not smoke, drink alcohol, or use illicit drugs. She was unemployed and lived alone. The patient was post-menopausal and was pregnant three times-two of which were normal spontaneous deliveries with two living children and one prior abortion.

Vital signs were: temperature 98.8° Fahrenheit, heart rate 84 beats per minute, blood pressure 135/74 millimeters of mercury, respiratory rate of 18 breaths per minute and room air oxygen saturation 97%. Her body mass index was 42 (normal 18.5–24.9). Complete physical examination was unremarkable except her left eye’s lateral gaze was restricted by approximately 25%. Her visual acuity was 20/25 and 20/30, right and left eyes, respectively. Initial laboratory testing were resulted (Tables 1 and 2). An electrocardiogram was performed (Image 1).

Table 1Complete blood cell count.
Serum hematology test	Value (reference range)
Complete blood cell count
 White blood cells	14.9 × 103/uL (4.0–11.0)
 Hemoglobin	14 g/dL (12.0–16.0)
 Hematocrit	43% (36.0–48.0)
 Platelets	225 × 103/uL (150–450)
Differential
 Neutrophils	78% (35.0–80.0)
 Lymphocytes	13% (20.0–50.0)
 Monocytes	7% (2.0–12.0)
 Eosinophils	0.6% (0.0–7.0)
 Basophils	0.8% (0.0–2.0)
uL, microliters; g, grams; dL, deciliter.

Table 2Chemistry results.
Serum chemistry test	Value (reference range)
Complete metabolic panel
 Sodium	128 mmol/L (133–145)
 Potassium	3.4 mmol/L (3.5–4.8)
 Chloride	88 mmol/L (97–110)
 Bicarbonate	27 mmol/L (23–30)
 Blood urea nitrogen	7 mg/dL (6–20)
 Creatinine	0.7 mg/dL (0.5–1.0)
 Glucose	81 mg/dL (70–109)
 Albumin	4.0 g/dL (3.5–5.2)
 Bilirubin	1.0 mg/dL (<= 1.0)
 Alkaline phosphatase	87 U/L (35–105)
 Total protein	8.5 g/dL(6.0–8.3)
 Aspartate transaminase	18 U/L (0–40)
 Alanine aminotransferase	11 U/L (0–33)
Additional chemistries
 Troponin	<0.01 ng/mL (0.00–0.30)
mmol, millimoles; L, liter; mg, milligram; dL, deciliter; U, units; ng, nanogram; mL, milliliter.

 

Image 1
Normal sinus rhythm at 64 beats per minute with sinus arrhythmia.
```

Here is the simplified-English answer from the system:
```
The patient's symptoms, such as a sudden and severe headache, feeling sick, vomiting, and vision problems, are similar to those of pituitary apoplexy.
The headache was severe and constant, and the vision problems included blurry vision, double vision, and sensitivity to light.
The patient also had trouble keeping one eye open, which could be related to nerve damage, a common symptom of pituitary apoplexy.
The lab results showed low levels of sodium and potassium in the blood, which could mean that the adrenal glands are not working properly, a common complication of pituitary apoplexy.
Although the patient's medical history and medications do not seem directly related, pituitary apoplexy should still be considered as a possible diagnosis because of the range of symptoms.
More tests, such as imaging studies, are needed to confirm the diagnosis.
Pituitary apoplexy is a serious medical condition that requires immediate attention and treatment.
Based on the information provided, pituitary apoplexy is a possible diagnosis, but more tests, such as an MRI and hormone studies, are necessary to confirm.
```




