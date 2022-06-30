First PYE's signature homework, using Python I explore a dataset and analize it. In this notebook develop some useful functions to calculate central tendency's measures and scattering measures.

## Functions explained:
Functions development on the notebook were to get central tendency values and also get a dataframe with frequencies. These actions can be performed with `pandas` library but I decide to make it by myself.

### Get central measures
Function that returns a dataframe with these measures based on a qualitative variable.



### Get frequency table
Modify a dataframe to get absolute and relative frequencies and also accumulated values.

```mermaid
flowchart LR
S[Start]
A[Absolute frequency]
R[Relative frequency]
AD{Accumulated frequency}
S1[Sum each value to get Accum-absolute]
S2[Sum each value to get Accum-relative]
NR[Create a new column with accumulated absolute frequency]
NA[Create a new column with accumulated relative frequency]

%% Colores %%
	classDef blue  fill:#2374f7, stroke:#000, stroke-width:2px, color:#fff
	classDef pink  fill:#eb3dd6,stroke:#000, stroke-width:2px, color:#fff
	classDef orange  fill:#fc822b,stroke:#000,stroke-width:2px,color:#fff
	classDef red  fill:#ed2633,stroke:#000,stroke-width:2px,color:#fff
	classDef green  fill:#16b522,stroke:#000,stroke-width:2px,color:#fff

S ---> A ---> R ---> AD
AD --->|one| S1
AD --->|second| S2
S1 ---> NR
S2 ---> NA
```

---

Enjoy ~🎍
