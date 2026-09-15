# college-of-computing-ontology
A Knowledge Representation &amp; Semantic Web ontology modeling an academic computing college using Protégé, OWL 2 DL, HermiT reasoner, and SPARQL.
# College of Computing Ontology (Knowledge Representation & Semantic Web)

## 📌 Overview
An academic domain ontology modeling the organizational, academic, and community structure of the College of Computing at Umm Al-Qura University. Built in compliance with **OWL 2 DL** standards to support automated logical deduction and semantic data querying.

## 🛠 Tech Stack & Tools
- **Ontology Editor:** Protégé 5.x
- **Knowledge Representation Language:** OWL 2 DL / RDF-XML
- **Automated Reasoner:** HermiT Reasoner (v1.4.3)
- **Query Language:** SPARQL 1.1

## 🏛 Ontology Architecture
- **TBox (Terminology):** 25 classes organized hierarchically (Academic Programs, Roles, Departments, Facilities, Events).
- **Properties:** 20 Object Properties (with inverse and functional characteristics) and 9 Data Properties.
- **Logical Constraints:** Cardinality restrictions (`headedBy exactly 1 DepartmentHead`), disjointness axioms, and equivalence classes (`SeniorFaculty`, `ActiveStudent`, `ResearchDepartment`).
- **ABox (Assertions):** 28 real-world asserted individuals.

## 🔍 Reasoning & Validation
- **Consistency Verification:** Successfully validated satisfiability across all classes using HermiT Reasoner with 0 contradictions.
- **Inferred Knowledge:** Reasoner automatically classified individuals into equivalent classes (e.g., inferring `SeniorFaculty` based on teaching and research participation).

## 📊 Semantic Queries (SPARQL)
Demonstrated advanced querying capabilities using:
- Aggregate functions (`COUNT`, `GROUP BY`)
- Boolean verification (`ASK`)
- Pattern matching (`FILTER`, `REGEX`)
- Disjunctive logic (`UNION`)

## 📂 Repository Contents
- `college_ontology.owl`: Full OWL 2 DL ontology file.
- `FinalReport_2.pdf`: Detailed documentation report covering design methodology, reasoning results, and query execution screenshots.
