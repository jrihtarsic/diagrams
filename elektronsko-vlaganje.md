Urejanje diagramov
Navodila: https://mermaid-js.github.io/mermaid/#/flowchart
Editor: https://mermaid.live/

Elektronsko vlaganje

```mermaid
flowchart LR
    A[Elektronska\nvloga] --> B{Ima\nelektronski\nžig}
    B -->|Ne| D[Izdelaj elektronski žig]
    D --> B
    B -->|Da| E{Ali je\nelektronski žig\nveljaven}
    E -->|Da| F{Ali je\nvloga tehnicno\nustrezna?}    
    E -->|Ne| G[Napaka pri\nsprejemu!]
    F -->|Ne| G[Napaka pri\nsprejemu!]
    F -->|Da| H[Sprejmi vlogo!]
```

</details>
<!-- generated by mermaid compile action - END -->

</details>
<!-- generated by mermaid compile action - END -->

Goal: comment out the above, insert image ref

<!-- generated by mermaid compile action - START -->
![~mermaid diagram 2~](/.resources/readme-md-2.svg)
<details>
  <summary>Mermaid markup</summary>

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    W-->D;
    E-->Z;