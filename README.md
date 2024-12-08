# citation-network-analysis
### Analysis of Citation Network Among US Patents

**Tech Stack:** **Python**, **NetworkX**, **Louvain Algorithm**, **PageRank Algorithm**

In this project, I analyzed the **citation network of US patents** from 1975 to 1999, using a dataset of 3,774,768 patent nodes and 16,518,948 directed citation edges. Through data preprocessing, exploratory data analysis, strategic sampling, and network analysis techniques, I extracted meaningful insights from the complex network structure. 

The project involved:
- **Data sampling** to manage computational complexity while preserving key structural characteristics of the network
- Community detection and influence analysis using the **Louvain and PageRank algorithms**

**Limitations & Potential:**  
While the analysis utilizes simple models/algorithms and limited data (comprising only of information on directed edges between nodes/patents), there is potential for deeper analyses if detailed nodes/patent information becomes available, such as:
- Temporal patent/innovation network evolution
- Cross-domain innovation tracking

The methodology can also be extended beyond patent networks to other domain applications, such as:
- Analyzing co-purchase networks to identify complementary or substitutive products
- Exploring social network interactions
- Investigating research collaboration networks

**Lessons Learned:**
- Optimizing computational efficiency with large datasets through sampling methods
- Data processing techniques
- Applying the Louvain and PageRank algorithms
- Analyzing network structures