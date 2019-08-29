<div class="container-fluid monarch-view monarch-curation-guidelines-view">
    <h2 class="page-title">Phenotype Curation Guidelines</h2>
    <p>
    We have observed that performance of computational search algorithms within and across species improves if a 
    comprehensive list of phenotypic features is recorded. It is helpful if the person annotating thinks of the set of 
    annotations as a query against all known phenotype profiles. Therefore, the set of phenotypes chosen for the annotation 
    must be as specific as possible, and represent the most salient and important observable phenotypes. Towards this end, 
    Monarch has been asked to provide guidance on how to create a quality patient profile using the 
    Human Phenotype Ontology (HPO). Below we detail our annotation guidelines for use in the PhenoTips application, 
    our partner organization.</p>
    <p>
    The guidelines can also be considered more generically so as to be applicable to any annotation effort using HPO or 
    even using other phenotype ontologies. The annotations should be limited to those features that are abnormal or 
    considered potentially abnormal. Also note that not all facets of a patient phenotype can be annotated using 
    structured vocabularies. The goal is not to represent everything possible, but rather to represent that 
    which most aids query functions. The vocabularies are a work in progress and your feedback is very valuable. 
    Each of the following sections in the PhenoTips annotation tool may be edited by clicking on the pencil icon to 
    the right of the section header, visible when hovering over the title. The form autosaves, and there is also a 
    save button on the bottom of the form.
    </p>
    <h4>Patient Information</h4>
    <p>* IMPORTANT….Can one enter protected health information (PHI) in PhenoTips? Some instances of PhenoTips are behind 
    firewalls and PHI is expected. In other cases, this may not be the case. It is important to check with your administrator.
    Patient Identifier, Exam date, Attending Clinician, and Date of Birth. Sex should be recorded as biological 
    sex rather than gender. To create links to other patients or family members in the system, click the black 
    “new entry button” once for each desired relationship. For each relationship, choose the type of relationship in 
    the first box (for example, “Sibling” and then choose the patient ID for the second person in the second box. 
    Indicate the onset of the disease using the radio buttons. Note that the choice of a given onset designates that 
    this is the onset for the majority of the symptoms. Individual phenotypes may be designated with different onset than 
    recorded here in the Clinical Symptoms section (see below). Record the “Indication for Referral”. This content can be 
    a short summary or include content from the patient record.</p>
    <h4>Prenatal and Perinatal History</h4>
    <p>Gestation at delivery: Please record a numeric value in weeks, such as “38” or leave blank if unknown.</p>
    <p>AGPAR score at 1 and 5 mins: Please choose from the pulldowns the appropriate value if known.</p> 
    <p>Prenatal Growth Parameters: Indicate the birth measurements for Weight, Height, and Head Circumference as 97th 
    percentile for age by clicking the “Y” or “N” for yes or no, respectively. If not known, leave as the default “N/A”. 
    Note that values here will pre-populate the Clinical Symptoms and Physical Findings report (see below). For example, 
    >97th percentile for head circumference will autopopulate the HPO term “Macrocephaly”.</p>
    <p>Prenatal Development or Birth: Indicate “Oligohydramnios,” “Polyhydramnios”, or “Premature Birth”, or the latter’s 
    subtype “Premature delivery because of cervical insufficiency or membrane fragility” using the “Y” or “N” for yes or 
    no as per above.</p>
    <p>A field for additional pre- and perinatal notes: This content can be a short summary or include content from the patient record.</p>
    <h4>Medical and Developmental History</h4>
    <p>A “Medical and developmental history” notes field is provided to record notable issues in the medical history not 
    already recorded above. This content can be a short summary or include content from the patient record.</p>  
    <h4>Family History</h4>
    <p>Record Maternal and Paternal Ethnicity, such as “White” or “Hispanic.” These will autocomplete or specified by 
    the user. You may enter more than one ethnicity for each parent. </p>
    <p>Check the box if the patient was conceived using in vitro fertilization.</p>
    <p>Indicate Consanguinity using the “Y” or “N”. The default value is N/A if not relevant or unknown.</p>
    <p>List Health Conditions Found in Family (describe the relationship with proband) in the notes field.</p>
    <p>Pedigree drawing software is available within PhenoTips to support linking of patients and comparison of their phenotype data.</p>
    <h4>Measurements</h4>
    <p>Click the black “New entry” button to create a list of patient measurements. These are dated, and a new set of 
    measurements from a different date may be recorded by clicking the “new entry” button again. The age of the patient 
    at each measurement date will be displayed.</p>
    <p>Enter values for Weight (kg), and in cm: Height, Arm Span, Sitting Height, Head Circumference, Philtrum Length, 
    Left Ear Length, Right Ear Length, Outer Canthal Distance, Inner Canthal Distance, Palpebral Fissure Length, 
    Interpupilary Distance, Left Hand Length, Left Palm Length, Left Foot Length, Right Hand Length, Right Palm Length, 
    and Right Foot Length. The growth charts are displayed based on prior entries.</p>
    <h4>Genotype Information</h4>
    <p>Add “candidate genes” by clicking on the blue “Add new entry” and autocompleting on the gene symbol. 
    The “i” button next to the suggestions will provide additional information about the gene, to ensure you are 
    choosing the correct one. Add “Previously tested genes, unlikely causative” similarly. Upload a VCF file using the 
    blue “upload and manage” button, and choose which reference genome was utilized using the pulldown menu.</p>
    <h4>Clinical symptoms and physical findings</h4>
    <p>This is the main phenotyping section of PhenoTips. Click “This patient is clinically normal” for those 
    patients/family members that have no known abnormal phenotypes.</p>
    <p>Searching for Phenotypes. There are three methods to search for phenotypes. In all methods, PhenoTips allows 
    autocomplete on any HPO term and will add it directly to the record.</p>
    <ol>
    <li>You can use the “Quick Phenotype Search” in the black box at the top of the Clinical Symptoms section. 
    “Quick Phenotype Search” searches the whole HPO ontology</li>
    <li>
    You can “Browse Categories”, where you can click the “jump to” link to choose a specific category or “expand all” 
    to show all categories. The “collapse all” button reverts to closing all the categories, and the “hide” button hides 
    all of the categories, which are restored by clicking the “Browse Categories” button again. The categories are as 
    follows: 
    <ul>
    <li>Growth parameters</li>
    <li>Craniofacial</li>
    <li>Eye defects</li>
    <li>Cutaneous</li>
    <li>Ear defects</li> 
    <li>Cardiac</li> 
    <li>Respiratory </li> 
    <li>Musculoskeletal</li> 
    <li>Gastrointestinal</li> 
    <li>Genitourinary</li>
    <li>Behavior, Cognition and Development</li>
    <li>Neurological</li>
    <li>Other. See term requests below.</li>  
    </ul>
    </li>
    <li>
    You can use the “Other” search box within each diagnostic category. This searches only the relevant portion of the HPO 
    within each category, including synonyms and alternate spellings.
    </li>
    </ol>
    <p><strong>* We recommend method #1, which searches all of HPO, as phenotypes may overlap with multiple sections 
    and/or a phenotype may be found in a different section than expected.</strong></p>
    <p>Choosing Phenotype terms. Your phenotype selections will show up under the “Current Selection” section over on 
    the right panel of the Clinical symptoms section, where all of the selections from the different categories will 
    be shown. This is where you will visualize the whole phenotype profile for the given patient.</p>
    <p>For each phenotype, choose the most specific term possible, based on the definition (available by clicking 
    the “i”) and not necessarily simply based on the term label. Before selecting a term, examine any of the more 
    specific terms contained underneath it by opening the arrow. If any of those are appropriate, select the more 
    specific term. In particular, if you are using the “Quick Search” box, you should always browse related terms to 
    ensure that you have selected the most specific term. Record “Y” for Yes, to indicate a phenotype being present 
    in the patient. You may provide annotations for things that were investigated and specifically not observed by 
    clicking on the “N” for “No”. These will turn red in the interface. These “No” annotations are especially useful 
    to include in cases where there are only a few observable phenotypes. The default is a grey “N/A”, which means not 
    noted to be specifically present or absent.</p>
    <h3>IMAGE MISSING HERE, still needed?</h3>
    <p>The more specific the item chosen, the better the specificity of the whole phenotypic profile. If there are no 
    phenotypes in a given category, consider making a high level “N” (No) annotation. For example, if a full visual 
    exam finds no visual impairment, then you could choose N-”Visual impairment”. Choose terms that are thought to be 
    pathological or unusual, even if they are not so in the greater populace. For example, ‘blue irides’ is a common 
    phenotype in the population, but as a phenotype annotation, it is a subtype of ‘abnormal iris pigmentation’ and 
    should only be chosen in cases where abnormal pigmentation is suspected, such as Heterochromia. We will work to 
    support common traits in later enhancements of the HPO.</p>
    <p>Phenotype Annotation Sufficiency Meter. The sufficiency meter appears at the top of the “Current Selection” 
    section. This meter assesses the breadth and depth of your phenotype annotation profile using a five-star rating 
    system for a given patient in the context of all curated human and model organism phenotypes. The goal is to make 
    your annotation profile specific enough to exclude similar diseases and to identify model organisms with similar 
    phenotypes that may have mutations in relevant genes or pathways. The patient annotation profile is also used to 
    aid exome prioritization using the same technology. The function is available via Monarch services</p>
    <p>Annotate the patient record using the star rating to guide you in determining the sufficiency of your annotation 
    profile.</p>
    <p>Inclusion of “No” annotations in different categories can aid in obtaining a good rating, especially where there 
    are few specific observable phenotypes.</p>
    <p>Additional Phenotype Information. Each phenotype may be associated with an ‘age of onset’ term, such as congenital 
    onset, by clicking the “add details” button over in the Current Selection box on the right side of the interface. 
    If a later onset period is indicated for any given phenotype than for the disease onset recorded in the Patient 
    Information section, it is assumed that that phenotype was NOT present initially and was noted at the later time. 
    If an earlier onset is indicated for any given phenotype, then it is assumed that this indicates that the other 
    phenotypes were not present at the earlier time EXCEPT the one indicated by the earlier onset period.</p>
    <p>Each phenotype may also be associated with a “pace of progression” term, such as “slow progression”, “severity”, 
    “temporal pattern”, “spatial pattern”, “laterality”, and notes for any given phenotype.</p>
    <p>Comments, Images, and Medical reports may also be included in the “Add details” section for each phenotype.</p>
    <h3>IMAGE MISSING HERE,still needed?</h3>
    <p><strong>The ‘Add details’ button expands each phenotype in the Current Selection panel to allow annotation of 
    progression, severity, temporal pattern, as well as comments.</strong> Term requests. In some cases, you may not be 
    able to find the term you are looking for. The “Other” white box at the bottom of each category besides being 
    used to search that category is also used to record user requests. This allows a free-text request, which will be 
    reviewed by the curation staff. Please make sure to include only one term per request and make it as descriptive as 
    possible. A request may also be a refinement of existing terms, please feel free to reference these in the request. 
    Please do not request:
    <ul>
        <li>Acronyms</li>
        <li>Measurement values</li>
        <li>Collections of phenotypes, such as diseases or syndromes</li>
        <li>Genotype or chromosomal abnormalities (for example, Microarray Xp22.31 dup, maternally derived; ETFDH carrier)</li>
        <li>Identifiers — a human readable label is required</li>
        <li>Patient history (use the section above).</li>
        <li>Assays — however, observable phenotypes derived from a specific assay are fine. For example, “abnormal MRI” 
        does not describe a phenotype, rather what made that MRI abnormal is the observed phenotype (instead, request 
        “cerebral volume loss indicated by abnormal MRI”).</li>
        <li>Devices — similarly, do not request devices but rather the phenotypes that are addressed by their use. 
        For example, “mitral valve prolapse via echocardiogram.” If you have questions about whether a term is 
        applicable, please contact the Phenotype Team by emailing obo-human-phenotype@lists.sourceforge.net.</li>
    </ul>
    </p>
    <h4>You Might Want to Investigate</h4>
    <p>In the yellow box underneath the “Current Selection” one has the ability to indicate specific phenotypes that 
    are known to improve differential diagnosis. Clicking on this header opens up a direct selection of these phenotype 
    terms. Choice of these populates the Current Selection.</p>
    <h4>Diagnosis</h4>
    <p>Note that generally, a disorder is used to annotate the patient profile because it was either: tested and 
    confirmed to be either present or absent OR suspected based on the manifestations (phenotypes), but not yet tested.</p>
    <p>Choose an OMIM disease/disorder using the autocomplete based on the disease name in the box on the right.</p>
    <p>You may also use the “Instant OMIM Search” function at the bottom to identify the OMIM diseases based on the 
    matching of the phenotype profile. You can update the list of potential OMIM candidates by clicking on/off each of 
    the phenotypes listed at the top of the “Instant OMIM Search”. Note that a disorder is marked as confirmed_present, 
    confirmed_absent, or suspected in the toggle when you choose an OMIM disorder. Note also that not all the symptoms 
    present in an OMIM record for a given disease need to be present in the annotated patient Categories section.</p>
    </p>
</div>
