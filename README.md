# network-data_chord-diagram_api
## Using web services to a remote API construct a chord diagram with network data structures of protein relationships.


In **Anaconda**, you don't have to execute all the code in the file—you can pick-and-choose.  In this code, there are various **"protein_list" python lists** composed of different human proteins.   Actually, I wrote this code a while back and maybe some of the lists have non-human proteins.  Most should be human.   

The list is sent to an **API** at the **Protein-Protein Interaction Networks** Database "String"; and, relationships between proteins are returned as a **networked data structure**.

This networked data structure is then graphed as a chord diagram using the networkx library.
