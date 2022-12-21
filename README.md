# network-data_chord-diagram_api
## Using web services to a remote API construct a chord diagram with network data structures of protein relationships.


In **Anaconda**, you don't have to execute all the python, in this case, code in the file—you can pick-and-choose which lines in the code file to execute.  In this code, there are various **"protein_list" python lists** composed of different human proteins.   Actually, I wrote this code a while back and maybe some of the lists have non-human proteins.  Most should be human.   

The list is sent to an **API** at the **Protein-Protein Interaction Networks** Database "String"; and, relationships between proteins are returned as a **networked data structure**.

<img width="176" alt="string" src="https://user-images.githubusercontent.com/12736699/208809089-8648affc-a610-4c61-81b2-88b80de76f32.png">

<img width="465" alt="string_stats" src="https://user-images.githubusercontent.com/12736699/208809109-4f966ca6-7fd5-4cfb-9997-b33ddd999485.png">


This networked data structure is then graphed as a chord diagram using the networkx library:

<img width="943" alt="simple_chord" src="https://user-images.githubusercontent.com/12736699/208809144-f61ba308-38ba-437e-abb8-65bc2878cb73.png">

It is also demonstrated making a more complex chord diagram with the same network data structure:

<img width="948" alt="complex_chord" src="https://user-images.githubusercontent.com/12736699/208809176-fe806485-dc8c-437e-a13c-de9a3b90784b.png">
