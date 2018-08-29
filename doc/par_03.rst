Identificazione dei nuovi standard
==================================

Al fine di raggiungere gli scopi di cui al paragrafo precedente l’Agenzia per l’Italia Digitale ha tenuto presente che:

-	il Consiglio europeo nella `Conclusione 2012/C 325/02 <http://eur-lex.europa.eu/legal-content/IT/TXT/HTML/?uri=OJ:C:2012:325:FULL&from=IT>`__ [1]_ raccomanda l'applicazione di `ELI (European Legislation Identifier) <https://eur-lex.europa.eu/eli-register/about.html>`__ [2]_ ai testi legislativi europei e nazionali riportati nelle gazzette ufficiali o nelle banche dati e nei sistemi informatici giuridici da essi gestiti al fine di consentire un accesso semplice alle informazioni sulla legislazione dell’Unione europea (UE) e degli Stati membri;
-	il Consiglio europeo nella `Conclusione 2011/C 127/01 <https://eur-lex.europa.eu/legal-content/IT/TXT/HTML/?uri=OJ:C:2011:127:FULL&from=IT>`__ [3]_ raccomanda l’applicazione di `ECLI (European Case Law Identifier) <https://e-justice.europa.eu/content_european_case_law_identifier_ecli-175-en.do>`__ [4]_ allo scopo di facilitare il riferimento corretto ed inequivocabile a sentenze in materia di diritto dell'Unione emesse da organi giurisdizionali europei e nazionali unitamente;
-	il `Senato della Repubblica Italiana ha scelto lo standard Akoma Ntoso <https://www.senato.it/japp/bgt/showdoc/17/DOSSIER/0/920095/index.html?part=dossier_dossier1-sezione_sezione2-h3_h39>`__ [5]_ per la rappresentazione degli atti parlamentari e dei loro iter; 
- 	nell’ambito programma `ISA2 (Interoperability solutions for public administrations, businesses and citizens) è suggerito il riuso dello standard Akoma Ntoso <https://ec.europa.eu/isa2/sites/isa/files/actions/2016.38_en.pdf>`__ [6]_;
-	nell’ambito del High Level Committee on Management delle Nazioni Unite nel marzo del 2017 si è deciso di adottare formalmente Akoma Ntoso e l’ontologia UNDO come pilastri del `UN Semantic Interoperability Framework for normative and parliamentary documents (UNSIF) <https://www.unsceb.org/content/akn4un>`__ [7]_;
-	nelle `Linee guida nazionali per la valorizzazione del patrimonio informativo pubblico <http://lg-patrimonio-pubblico.readthedocs.io/it/latest/arch.html#formati-aperti-per-i-documenti>`__ [8]_ l’Agenzia per l’Italia Digitale ha individuato tra i formati aperti per i documenti anche lo standard *Akoma Ntoso*;
-	nell’ambito del progetto LexDatafication [9]_, e nello specifico nel documento *“Standard digitali internazionali per modellare la conoscenza giuridica in Italia. Uno sguardo globale per le esigenze locali”*, è costato analizzato lo stato dell’arte degli standard internazionali in materia di modellizzazione dei documenti giuridici .

La seguente tabella sintetizza gli standard utili alla modellazione di tutta la catena informativa dei documenti giuridici, riconosciuti a livello nazionale, europeo ed internazionale.

+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Livello                                   | Standard proposto                                                    | Vantaggi                                                                                                                           |
+===========================================+======================================================================+====================================================================================================================================+
| IRI persistenti per le risorse giuridiche | ELI e ECLI 2.0 (per le sentenze emesse da organi giurisdizionali)    | Interoperabilità con le istituzioni europee                                                                                        | 
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | Akoma Ntoso naming convention per l’Italia                           | Sintassi http e FRBR model                                                                                                         |
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | URN\:LEX                                                             | Compatibilità con URN\:NIR                                                                                                         |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Struttura documentale                     | Akoma Ntoso 3.0                                                      | Allineamento con gli standard internazionali                                                                                       |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Metadati                                  | ECLI 2.0 metadati (per le sentenze emesse da organi giurisdizionali) | Interoperabilità con le istituzioni europee                                                                                        |
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | LKIF RDF trasformazione dei metadati di AKN                          | Compatibilità con Linked Open Data                                                                                                 |
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | METS PREMIS                                                          | Metadati di conservazione archivistica                                                                                             |
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | ELI                                                                  | Interoperabilità con le istituzioni europee, ontologia attualmente adottata per il portale Gazzetta Ufficiale e Normattiva         |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Ontologie                                 | UNDO                                                                 | Ontologia sincronizzata con Akoma Ntoso                                                                                            |
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | OSR e OCD                                                            | Ontologia del Parlamento italiano                                                                                                  |
|                                           +----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
|                                           | LKIF                                                                 | Ontologia giuridica internazionale                                                                                                 |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Tesauri                                   | Tesauri attualmente adottati sui vari sistemi: EuroVoc, WordNet      | Riuso di quanto attualmente in esercizio, in prima istanza Tesauro giuridico multilingua Europeo e Risorsa linguistica multilingua |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Regole giuridiche                         | LegalRuleML                                                          | Linguaggio per la formalizzazione di regole giuridiche                                                                             |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+
| Trust                                     | PROV-O                                                               | Ontologia per modellare i metadati relativi alla provenienza                                                                       |
+-------------------------------------------+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------+



.. discourse::
   :topic_identifier: 4366
   
   
.. [1] http://eur-lex.europa.eu/legal-content/IT/TXT/HTML/?uri=OJ:C:2012:325:FULL&from=IT

.. [2] https://eur-lex.europa.eu/eli-register/about.html

.. [3] https://eur-lex.europa.eu/legal-content/IT/TXT/HTML/?uri=OJ:C:2011:127:FULL&from=IT

.. [4] https://e-justice.europa.eu/content_european_case_law_identifier_ecli-175-en.do

.. [5] https://www.senato.it/japp/bgt/showdoc/17/DOSSIER/0/920095/index.html?part=dossier_dossier1-sezione_sezione2-h3_h39

.. [6] https://ec.europa.eu/isa2/sites/isa/files/actions/2016.38_en.pdf 

.. [7] https://www.unsceb.org/content/akn4un

.. [8] http://lg-patrimonio-pubblico.readthedocs.io/it/latest/arch.html#formati-aperti-per-i-documenti

.. [9] Il progetto LexDatafication è coordinato dal Team per la trasformazione digitale della Presidenza del Consiglio dei ministri, dal Centro Interdipartimentale di Ricerca in Storia del Diritto, Filosofia e Sociologia del Diritto e Informatica Giuridica (CIRSFID) e dal Dipartimento di Informatica dell'Università di Bologna.
