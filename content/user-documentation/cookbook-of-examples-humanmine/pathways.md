# Pathways

### Where does the pathway data come from?

In HumanMine, we load pathway data from both [Reactome](http://www.reactome.org/) and [KEGG](http://www.genome.jp/kegg/). 

### How do I find which pathways my gene or list of genes are involved in?

Use the following template search:

[Gene → Pathway](http://bluegenes-alpha.apps.intermine.org/humanmine/templates/Gene_Pathway)

### My gene is in pathway X; how I can find other genes involved in this pathway?

Use the following template search:

[Pathway → Genes](http://bluegenes-alpha.apps.intermine.org/humanmine/templates/PathwayGenes)

### I am not sure of the exact name of the pathway that I am interested in; how I can find this?

Just start typing in the pathway name box - the type-ahead function will automatically show you matching pathways.

### Can I visualize this pathway data in InterMine?

We do not currently have any pathway visualization within FlyMine. However, linkouts enable you to view the pathways in either Reactome or Kegg.

### How do I find out if my genes or lists of genes have any pathways in common?

The underlying data model makes it possible to construct queries which effectively compare two lists for a specified attribute. Such a query is available as a template for comparing the pathways for two genes or two sets of genes. For two genes, the query will return any pathways that are shared by the two genes. Similarly, if two lists are provided, any pathways shared between any two genes in the lists are returned. The template is:

[Gene A → Pathways ← Gene B](http://www.flymine.org/query/template.do?name=ListPathway&scope=all)

### How do I find whether orthologues of my gene\(s\) share similar or have additional pathways?

For a single gene, use the report page pathways viewer:

Each gene report page in FlyMine \(and in other MOD-InterMines\) includes a table displaying pathways for the orthologues of the gene you are viewing. The table is created by searching the other InterMine databases for orthologous genes and the pathways they are involved in:

For a list of genes:

1. Send your list of genes to the relevant organisms Mine:

see [Open another organisms MOD-intermine via the orthologues of your list](https://flymine.readthedocs.io/en/latest/lists/analysis/Documentationlistanalysispages.html#listanalysisjumptomine)

1. Once in the other Mine, search the templates for a search that will provide you with the pathway data for your genes.
2. At present we do not have a tool that will directly compare the pathways for your list of genes. However, if you download your pathway list \(see [Download a set of results](https://flymine.readthedocs.io/en/latest/results-tables/Documentationresultstables.html#resultsdownload)\) and upload it back into your original mine \(see [Upload a list](https://flymine.readthedocs.io/en/latest/lists/upload/Documentationlistupload.html#listupload)\), you can use the [List Set operations:](https://flymine.readthedocs.io/en/latest/lists/overview/Documentationlists.html#listsetoperations) to carry out an intersection on the two pathway lists. 
