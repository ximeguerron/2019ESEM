# Welcome 
Here you can find relevant information attach to the article the **_Quality of experience metrics for cloud services: A systematic mapping_**. The research methodology and results are detailed in the next sections.

## Index

1. [Search Protocol](#Protocolo)
2. [Search Strings](#busqueda)
3. [Primary Studies](#estudios)
4. [Data Extraction Strategy](#criterios)
5. [Clasification of QoE metrics](#clasificacion)

# Planning 
## 1. Search Protocol {#Protocolo}

The purpose aim of this research is:
```markdown
To obtain, classify, analyze and synthetize the existing metrics 
about QoE for cloud services. 
```

The research question is: 
```markdown
Which metrics are proposed to evaluate the QoE in cloud services and 
how have them being used?
```

The study of the population and the intervention is as follows:

- **Population**: Research articles that present metrics for the evaluation of the quality in use of cloud services.
- **Intervention**: Quality metrics used to evaluate the quality characteristics of cloud services.
- **Results**: Analysis of a set of metrics that serve as the basis for the development of a cloud services quality model aligned with the ISO / IEC 25010 and based on the literature.
- **Context**: Quality assessment of cloud services that propose metrics to measure quality in use (QoE - Quality of Experience).

Finally, the search string selected is shown below:

Concept	| Alternative Terms or Synonyms
------------ | -------------
Measure	| ((metric* OR measur*) AND
Quality 	| (QoE OR "quality of experience" OR "quality model" OR "evaluation model" OR "assessment model" OR "quality in cloud" OR "quality of cloud") AND
Cloud	| (cloud*))

The search used _title, abstract and keyword_ of the articles. 
The period or search dated from _2006_ to _November 2018_. 

## 2. Search Strings {#busqueda}
The source was the digital libraries listed below: IEEE Xplore, ACM Digital Library, ScienceDirect y Springer Link. 

Digital Libray| Search String | Search Metadata |Constraints
------------ | ------------- |------------ | ------------- 
IEEE Xplore |(( "Document Title":metric* OR  "Document Title":measur*) AND ( "Document Title":QoE OR  "Document Title":"quality of experience" OR "Document Title":"quality model" OR  "Document Title":"evaluation model" OR  "Document Title":"assessment model" OR  "Document Title":"quality in cloud" OR  "Document Title":"quality of cloud") AND ( "Document Title":cloud*)) OR (("Publication Title":metric* OR  "Publication Title":measur*) AND ("Publication Title":QoE OR  "Publication Title":"quality of experience" OR "Publication Title":"quality model" OR  "Publication Title":"evaluation model" OR  "Publication Title":"assessment model" OR  "Publication Title":"quality in cloud" OR  "Publication Title":"quality of cloud") AND ( "Publication Title":cloud*)) AND (("Abstract":metric* OR  "Abstract":measur*) AND ( "Abstract":QoE OR  "Abstract":"quality of experience" OR  "Abstract":"quality model" OR  "Abstract":"evaluation model" OR  "Abstract":"assessment model" OR  "Abstract":"quality in cloud" OR  "Abstract":"quality of cloud") AND ( "Abstract":cloud*)) AND (( "Author Keywords":metric* OR  "Author Keywords":measur*) AND ( "Author Keywords":QoE OR  "Author Keywords":"quality of experience" OR  "Author Keywords":"quality model" OR  "Author Keywords":"evaluation model" OR  "Author Keywords":"assessment model" OR  "Author Keywords":"quality in cloud" OR  "Author Keywords":"quality of cloud") AND ( "Author Keywords":cloud*)) |Title, abstract and keywords|Content Type: Conference Publications and Journals & Magazines. Year: 2006-2018
ACM Digital Library|((acmdlTitle:metric* OR acmdlTitle:measur*) AND (acmdlTitle:QoE OR acmdlTitle:"quality of experience" OR  acmdlTitle:"quality model" OR acmdlTitle:"evaluation model" OR acmdlTitle:"assessment model" OR acmdlTitle:"quality in cloud" OR acmdlTitle:"quality of cloud") AND (acmdlTitle:cloud*)) OR ((recordAbstract:metric* OR recordAbstract:measur*) AND (recordAbstract:QoE OR recordAbstract:"quality of experience" OR recordAbstract:"quality model" OR recordAbstract:"evaluation model" OR recordAbstract:"assessment model" OR recordAbstract:"quality in cloud" OR recordAbstract:"quality of cloud") AND (recordAbstract:cloud*)) OR ((keywords.author.keyword:metric* OR keywords.author.keyword:measur*) AND (keywords.author.keyword:QoE OR keywords.author.keyword:"quality of experience" OR keywords.author.keyword:"quality model" OR keywords.author.keyword:"evaluation model" OR keywords.author.keyword:"assessment model" OR keywords.author.keyword:"quality in cloud" OR keywords.author.keyword:"quality of cloud") AND (keywords.author.keyword:cloud*)) |Title, abstract and keywords |Published since: 2006
ScienceDirect|TITLE-ABSTR-KEY((((metric* OR measur*)) AND (QoE OR {quality of experience} OR {quality model} OR {evaluation model} OR {quality in cloud} OR {quality of cloud}) AND (cloud*))) |Title, abstract and keywords|Pub-date > 2005. Content type: Journal.
SpringerLink| ((metric* OR measur*) AND (QoE OR "quality of experience"  OR "quality model" OR "evaluation model" OR "quality in cloud" OR "quality of cloud") AND (cloud*))|Full text 	|Content Type: Article. Discipline: Computer Science Language: English.

# Conducting
## 3. Primary Studies {#estudios}
Here we list the papers selected in the systematic mapping.

Num. | Primary Studies
------------ | -------------
S01	| Afify, Y. M., Moawad, I. F., Badr, N. L., & Tolba, M. F. (2013). A semantic-based Software-as-a-Service (SaaS) discovery and selection system. In Computer Engineering Systems (ICCES), 2013 8th International Conference on (pp. 57–63). http://doi.org/10.1109/ICCES.2013.6707171
S02	| Baranwal, G., & Vidyarthi, D. P. (2014). A framework for selection of best cloud service provider using ranked voting method. In Advance Computing Conference (IACC), 2014 IEEE International (pp. 831–837). http://doi.org/10.1109/IAdCC.2014.6779430
S03	| Baranwal, G., & Vidyarthi, D. P. (2016). A cloud service selection model using improved ranked voting method. Concurrency and Computation: Practice and Experience, 28(13), 3540–3567. https://doi.org/10.1002/cpe.3740
S04	| Bilal, K., Erbad, A., & Hefeeda, M. (2018). QoE-aware distributed cloud-based live streaming of multisourced multiview videos. Journal of Network and Computer Applications, 120(July), 130–144. https://doi.org/10.1016/j.jnca.2018.07.012
S05	| Bruneo, D. (2014). A Stochastic Model to Investigate Data Center Performance and QoS in IaaS Cloud Computing Systems. IEEE Transactions on Parallel and Distributed Systems, 25(3), 560–569. http://doi.org/10.1109/TPDS.2013.67
S06	| Chen, K. T., Chang, Y. C., Hsu, H. J., Chen, D. Y., Huang, C. Y., & Hsu, C. H. (2014). On the Quality of Service of Cloud Gaming Systems. IEEE Transactions on Multimedia, 16(2), 480–495. http://doi.org/10.1109/TMM.2013.2291532
S07	| de Assunção, M. D., Cardonha, C. H., Netto, M. A. S., & Cunha, R. L. F. (2016). Impact of user patience on auto-scaling resource capacity for cloud services. Future Generation Computer Systems, 55, 41–50. http://doi.org/http://dx.doi.org/10.1016/j.future.2015.09.001
S08	| Ezenwoke, A., Daramola, O., & Adigun, M. (2018). QoS-based ranking and selection of SaaS applications using heterogeneous similarity metrics. Journal of Cloud Computing, 7(1), 15. https://doi.org/10.1186/s13677-018-0117-4
S09	| Feng, J., & Kong, L. (2015). A Fuzzy Multi-objective Genetic Algorithm for QoS-based Cloud Service Composition. In 2015 11th International Conference on Semantics, Knowledge and Grids (SKG) (pp. 202–206). http://doi.org/10.1109/SKG.2015.23
S10	| Garcia-Pineda, M., Segura-Garcia, J., & Felici-Castell, S. (2018). Estimation techniques to measure subjective quality on live video streaming in Cloud Mobile Media services. Computer Communications, 118, 27–39. https://doi.org/10.1016/j.comcom.2017.08.009
S11	| Garg, S. K., Versteeg, S., & Buyya, R. (2013). A framework for ranking of cloud computing services. Future Generation Computer Systems, 29(4), 1012–1023. http://doi.org/http://dx.doi.org/10.1016/j.future.2012.06.006
S12	| Guérout, T., Medjiah, S., Costa, G. Da, & Monteil, T. (2014). Quality of service modeling for green scheduling in Clouds. Sustainable Computing: Informatics and Systems, 4(4), 225–240. http://doi.org/http://dx.doi.org/10.1016/j.suscom.2014.08.006
S13	| Hasan, M. S., Alvares, F., Ledoux, T., & Pazat, J. (2017). Investigating Energy Consumption and Performance Trade-Off for Interactive Cloud Application. IEEE Transactions on Sustainable Computing, 2(2), 113–126. https://doi.org/10.1109/TSUSC.2017.2714959
S14	| Hwang, K., Bai, X., Shi, Y., Li, M., Chen, W.-G., & Wu, Y. (2016). Cloud Performance Modeling with Benchmark Evaluation of Elastic Scaling Strategies. IEEE Transactions on Parallel and Distributed Systems, 27(1), 130–143. https://doi.org/10.1109/TPDS.2015.2398438
S15	| Liu, X., Xia, C., Wang, T., & Zhong, L. (2017). CloudSec: A Novel Approach to Verifying Security Conformance at the Bottom of the Cloud. In 2017 IEEE International Congress on Big Data (BigData Congress) (pp. 569–576). https://doi.org/10.1109/BigDataCongress.2017.87
S16	| Lu, L., & Yuan, Y. (2018). A novel TOPSIS evaluation scheme for cloud service trustworthiness combining objective and subjective aspects. Journal of Systems and Software, 143, 71–86. https://doi.org/10.1016/j.jss.2018.05.004
S17	| Ma, H., Hu, Z., Yang, L., & Song, T. (2014). User feature-aware trustworthiness measurement of cloud services via evidence synthesis for potential users. Journal of Visual Languages & Computing, 25(6), 791–799. http://doi.org/http://dx.doi.org/10.1016/j.jvlc.2014.10.006
S18	| Moller, S., Schmidt, S., & Zadtootaghaj, S. (2018). New ITU-T Standards for Gaming QoE Evaluation and Management. 2018 10th International Conference on Quality of Multimedia Experience, QoMEX 2018. https://doi.org/10.1109/QoMEX.2018.8463404
S19	| Rizvi, S., Roddy, H., Gualdoni, J., & Myzyri, I. (2017). Three-Step Approach to QoS Maintenance in Cloud Computing Using a Third-Party Auditor. Procedia Computer Science, 114, 83–92. https://doi.org/10.1016/j.procs.2017.09.014
S20	| Samet, N., Letaïfa, A. Ben, Hamdi, M., & Tabbane, S. (2016). Real-Time User Experience Evaluation for Cloud-Based Mobile Video. In 2016 30th International Conference on Advanced Information Networking and Applications Workshops (WAINA) (pp. 204–208). http://doi.org/10.1109/WAINA.2016.120
S21	| Singh, S., & Chana, I. (2015). Q-aware: Quality of service based cloud resource provisioning. Computers & Electrical Engineering, 47, 138–160. http://doi.org/http://dx.doi.org/10.1016/j.compeleceng.2015.02.003
S22	| Slivar, I., Skorin-Kapov, L., & Suznjevic, M. (2016). Cloud Gaming QoE Models for Deriving Video Encoding Adaptation Strategies. In Proceedings of the 7th International Conference on Multimedia Systems (pp. 18:1–18:12). New York, NY, USA: ACM. doi:10.1145/2910017.2910602
S23	| Souza, R. H. de, Flores, P. A., Dantas, M. A. R., & Siqueira, F. (2016). Architectural recovering model for Distributed Databases: A reliability, availability and serviceability approach. In 2016 IEEE Symposium on Computers and Communication (ISCC) (pp. 575–580). https://doi.org/10.1109/ISCC.2016.7543799
S24	| Tasoulas, E., Hammer, H. L., Haugerud, H., Yazidi, A., Bratterud, A., & Feng, B. (2017). The concept of workload delay as a quality-of-service metric for consolidated cloud environments with deadline requirements. In 2017 IEEE 16th International Symposium on Network Computing and Applications (NCA) (pp. 1–5). https://doi.org/10.1109/NCA.2017.8171342
S25	| Viji Rajendran, V., & Swamynathan, S. (2015). Hybrid model for dynamic evaluation of trust in cloud services. Wireless Networks, 1–12. http://doi.org/10.1007/s11276-015-1069-y
S26	| Wang, S., & Dey, S. (2012). Cloud Mobile Gaming: Modeling and Measuring User Experience in Mobile Wireless Networks. SIGMOBILE Mob. Comput. Commun. Rev., 16(1), 10–21. doi:10.1145/2331675.2331679
S27	| Wen, Z. Y., & Hsiao, H. F. (2014). QoE-driven performance analysis of cloud gaming services. In Multimedia Signal Processing (MMSP), 2014 IEEE 16th International Workshop on (pp. 1–6). http://doi.org/10.1109/MMSP.2014.6958835
S28	| Wu, X., Liu, G., & Xu, J. (2015). A QoS-constrained scheduling for access requests in cloud storage. In Industrial Electronics and Applications (ICIEA), 2015 IEEE 10th Conference on (pp. 155–160). http://doi.org/10.1109/ICIEA.2015.7334102
S29	| Xiao, Y., Lin, C., Jiang, Y., Chu, X., & Shen, X. (2010). Reputation-Based QoS Provisioning in Cloud Computing via Dirichlet Multinomial Model. In Communications (ICC), 2010 IEEE International Conference on (pp. 1–5). http://doi.org/10.1109/ICC.2010.5502407
S30	| Xiong, K., & Chen, X. (2015). Ensuring Cloud Service Guarantees via Service Level Agreement (SLA)-Based Resource Allocation. In 2015 IEEE 35th International Conference on Distributed Computing Systems Workshops (pp. 35–41). http://doi.org/10.1109/ICDCSW.2015.18
S31	| Zheng, X., Martin, P., & Brohman, K. (2013). Cloud Service Negotiation: A Research Roadmap. In Services Computing (SCC), 2013 IEEE International Conference on (pp. 627–634). http://doi.org/10.1109/SCC.2013.93
S32	| Zheng, X., Martin, P., Brohman, K., & Xu, L. D. (2014). CLOUDQUAL: A Quality Model for Cloud Services. IEEE Transactions on Industrial Informatics, 10(2), 1527–1536. http://doi.org/10.1109/TII.2014.2306329
S33	| Zhou, P., Wang, Z., Li, W., & Jiang, N. (2015). Quality Model of Cloud Service. In High Performance Computing and Communications (HPCC), 2015 IEEE 7th International Symposium on Cyberspace Safety and Security (CSS), 2015 IEEE 12th International Conferen on Embedded Software and Systems (ICESS), 2015 IEEE 17th International Conference on (pp. 1418–1423). http://doi.org/10.1109/HPCC-CSS-ICESS.2015.134

## 4. Data Extraction Strategy {#criterios}
In this subsection, we present the data extraction criteria for classifying the collected metrics of quality of experience at cloud services. Each criterion has its possible options detailed.

Criteria | Possible Options 
------------ | -------------
Quality Characteristic	|Effectiveness, Efficiency, Satisfaction, Freedom from risk, Context coverage. [5]
Lifecycle Phase |	Requirements, Acquisition, Development, Integration, Operation, Retirement [6]
Artifact	|Cloud service Specification, cloud service Architecture, cloud Service.
Type of Service	|Software as a Service (SaaS), Platform as a Service (PaaS), Infraestructure as a Service (IaaS).
Stakeholder viewpoint	|Cloud Service Consumer (CSC), Cloud Service Provider (CSP), Cloud Service Broker (CSB), Cloud Service Developer (CSD), Final Client .
Validation	|Theory validation, Empiric validation, No validation.

# Reporting
## 5. Clasification of QoE metrics {#clasificacion}
In this subsection, is shown the results' metrics obtained from primary studies. Their classification was done using the data extraction criteria. 

<a href ="./Files/Appendix1.ClassificationMetrics.pdf">  Apéndice 1 </a>

**Acknowledgments**

The work of X. Guerrón is partially supported by Universidad Central del Ecuador.

## Support or Contact 

Information to contact the authors 
- Ximena Guerrón, xguerron@uce.edu.ec,xiguesan@doctor.upv.es
- Silvia Abrahão, sabrahao@dsic.upv.es
- Emilio Insfran, einsfran@dsic.upv.es,
- Marta Fernández-Diego, marferdi@omp.upv.es
- Fernando González-Ladrón-de-Guevara, fgonzal@omp.upv.es

Having trouble with Pages or any questions or suggestions ? Please, contact us by email xiguesan@doctor.upv.es 



