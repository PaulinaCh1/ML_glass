# ML_glass

## 1. Context of the project

Glass is used in a wide variety of consumer and commercial applications. Its function is defined by its composition and in forensic sciences, the material composition of glass as well as its refractive index can be used to identify the type of glass and where it came from.

You are a material science expert that has been brought into a criminal investigation involving a high profile robbery of a prominent political figure. The gang have a set of old vehicles whose windows are made using classical float-driven techniques, and claim that these rare vehicles were not at the scene of the crime...but are they lieing?

There are 8 samples extracted from the scene of the crime, all of which are from different sources. Your task is to identify if any of the samples are from vehicle windows that are float processed, since if any are found, then the criminals can be convicted.

The US, UK and EU each have a glass database that you can use for fitting your model. Unfortunately, they all use different data standards. The UK use CSV files, the EU JSON files where samples are not grouped, and the US JSON files where samples are grouped by governmental department. To make things additionally awkward, each country uses a different set of standards when measuring glass properties. 

The classifications are:

| Type | Class |
| :-: | :-: |
| 1 | Building windows that are float processed |
| 2 | Building windows that are not float processed |
| 3 | Vehicle windows that are float processed |
| 4 | Vehicle windows that are not float processed |
| 5 | Containers |
| 6 | Tableware |
| 7 | Headlamps |
