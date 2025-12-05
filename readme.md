# Person Marking in South-Central Trans-Himalayan: Monsang

This PARALEX set contains person markers in Monsang, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in "Paper in JOHD". Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ
 as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source_form column in the forms file contains the data exactly as it appears with in the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purporses.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in. 
* The docs folder contains the data sheet with more extensive description of how the data was gathered. It also contains csv tables with matrix layouts of the paradigms (similar to what we usually find in published sources) and a plot showing the distribution of each morph across most relevant grammatical categories.

## Additional information specific to Monsang
* Tone: Monsang has contrastive tone. Low tone is marked with a grave accent and high tone with an acute accent, or tones are marked with numbers (1 = low, 5 = high). Occasionally, due to fusion, a rising tone occurs over a lenghtened rhyme, indicated as 15 = rising). Tonal analysis is still ongoing.

* Descriptive statement on Monsang transitive indexation: The person indexation system of transitive verbs in Monsang makes use of inverse marking in 2->1 and 3->SAP scenarios, and 2->1 additionally indexes the A argument. There is one realis inverse marker and one irrealis inverse marker (the latter of which is found in future and negative contexts). The 1->2 scenario indexes both A and O arguments. In 3rd person O scenarios, only the A argument is indexed - depending on the paradigm, these forms may or may not be identical for intransitive and transitive verbs. 

* Mapping between database paradigm labels and Monsang descriptive labels:
  
   | **database label** | **language-specific descriptive label** |
   |--------------------|-----------------------------------------|
   | fut.aff            | future affirmative                      |
   | fut.neg            | future negative                         |
   | nfut.aff           | imperfective (affirmative)              |
   | nfut.neg           | non-future negative                     |

* Differences with published analyses: In contrast to Konnerth & Wanglar (2019), the form /-tʃʷú/ is not analyzed as a 2PL marker but as a sequence of a second person marker and an SAP plural marker: /-tʃ-ʷú/. The same holds for the 1pl exclusive suffix /-úŋ/, which is analyzed here as a sequence of the same SAP plural marker and a first person suffix /-ú-ŋ/. As a result, the form /m̥ú-váŋ-kín-tʃ-ʷù/ for 1PLE-2SG.FA is considered the default, while /m̥ú-váŋ-kín-tʃɘ̀/ receives the tag for optional plural marking. 

* Variation in this dataset: There is 
    * a) morphophonological variation involving homorganic nasals in person markers and voicing assimilation in specific local morpheme boundaries; 
    * b) optional plural marking in SAP and 3rd person contexts; 
    * c) optional future marking associated with 3rd person A arguments in future affirmative forms;
    * d) variable ordering of morphemes; 
    * e) variants that represent a phonological fusion of morphemes; 
    * f) tone alternation in person markers based on the tone of the stem (here, low tone stems are randomly selected as the default); 
    * g) variants that native speaker consultants deem pragmatically marked. 
  Note that for variation due to b), c), d), and e), we have no information about which form is pragmatically marked (from a native speaker consultant perspective) or which form is more frequent in the corpus. 

* Tagging notes: For decisions 1)-3) below, 'default' does not imply pragmatically unmarked (to native speakers) or more frequent (in the corpus) -- such information is not available.

  1. In the future affirmative paradigm, with a 3pl A argument (or in 3sg→3pl), two variants are attested. Since the future marker va~vaŋ occurs in the other forms of this paradigm, the variant with this future marker is considered the default.

     3.pl.1.pl.incl.fut.aff:
  
     ì Σ he tè (optional_future, variable_order)
  
     ì Σ vá tè he (default)


  2. The ʷu~u is considered an optional SAP plural marker (unlike in Konnerth & Wanglar 2019). As such, in 2sg->1pl.excl forms, the variant without it receives the optional_plural tag.

     2.sg.1.pl.excl.nfut.aff:
     
     ŋ̩̀ Σ náá tʃɘ̀  (optional_plural)
     
     ŋ̩̀ Σ náá tʃ ʷù (default)


  3. Transitive imperfective affirmative scenarios with a 3pl A argument and a 3sg or 3pl O argument can either take the 3pl velar nasal prefix or the combination of the 3(sg) a- prefix and the third person plural marker -he. The variant with the 3pl velar nasal prefix is considered the default. 

     3.pl.3sg.nfut.aff:
  
     ḿ̩ Σ náʔ (default)
  
     á Σ náá hè (pragm_marked)
