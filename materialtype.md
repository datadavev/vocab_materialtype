---
comment: | 
  WARNING: This file is generated. Any edits will be lost!
title: "iSamples Materials Vocabulary"
date: "2023-07-14T15:53:15.091500+00:00"
subtitle: |
  High level vocabulary to specify the kind of material that constitutes a physical sample
execute:
  echo: false
---

Namespace: 
[`https://w3id.org/isample/vocabulary/material/0.9/materialsvocabulary`](https://w3id.org/isample/vocabulary/material/0.9/materialsvocabulary)

**History**


**Concepts**

  - [Material](#material)
    - [Any anthropogenic material](#any-anthropogenic-material)
      - [Anthropogenic metal material](#anthropogenic-metal-material)
      - [Anthropogenic material](#anthropogenic-material)
    - [Any ice](#any-ice)
      - [Frozen water](#frozen-water)
    - [Biogenic non-organic material](#biogenic-non-organic-material)
    - [Dispersed media](#dispersed-media)
    - [Natural Solid Material](#natural-solid-material)
      - [Mineral](#mineral)
      - [Mixed soil sediment or rock](#mixed-soil-sediment-or-rock)
      - [Particulate](#particulate)
      - [Rock or sediment](#rock-or-sediment)
        - [Rock](#rock)
        - [Sediment](#sediment)
      - [Soil](#soil)
    - [Fluid material](#fluid-material)
      - [Gaseous material](#gaseous-material)
      - [Liquid water](#liquid-water)
      - [Non-aqueous liquid material](#non-aqueous-liquid-material)
    - [Organic material](#organic-material)


## Material
[]{#material}

Concept: [Material](#material)

Narrower Concepts:

- [Any anthropogenic material](#any-anthropogenic-material)
- [Any ice](#any-ice)
- [Biogenic non-organic material](#biogenic-non-organic-material)
- [Dispersed media](#dispersed-media)
- [Natural Solid Material](#natural-solid-material)
- [Fluid material](#fluid-material)
- [Organic material](#organic-material)

Top Concept in iSamples Material Category scheme


### Any anthropogenic material
[]{#any-anthropogenic-material}

Concept: [Any anthropogenic material](#any-anthropogenic-material)

Broader Concepts:

- [Material](#material)

Narrower Concepts:

- [Anthropogenic metal material](#anthropogenic-metal-material)
- [Anthropogenic material](#anthropogenic-material)

Material produced by human activity.


#### Anthropogenic metal material
[]{#anthropogenic-metal-material}

Concept: [Anthropogenic metal material](#anthropogenic-metal-material)

Broader Concepts:

- [Any anthropogenic material](#any-anthropogenic-material)

Specimen is dominantly composed of metal that has been produced or used by humans; subclass of anthropogenic material. Samples of naturally occuring metallic material (e.g. native copper, gold nuggets) should be considered mineral material. Metallic material is material that when polished or fractured, shows a lustrous appearance, and conducts electricity and heat relatively well. Metals are typically malleable (they can be hammered into thin sheets) or ductile (can be drawn into wires). The boundaries between metals, nonmetals, and metalloids fluctuate slightly due to a lack of universally accepted definitions of the categories involved. (https://en.wikipedia.org/wiki/Metal). c.f. http://purl.obolibrary.org/obo/ENVO_01001069


#### Anthropogenic material
[]{#anthropogenic-material}

Concept: [Anthropogenic material](#anthropogenic-material)

Broader Concepts:

- [Any anthropogenic material](#any-anthropogenic-material)

Non-metallic material produced by human activity. Organic products of agricultural activity are both anthropogenic and organic. Include lab preparations like XRF pellet and rock powders. Examples: ceramics, concrete, slag, (anthropogenic) glass, mine tailing, plaster, waste.


### Any ice
[]{#any-ice}

Concept: [Any ice](#any-ice)

Broader Concepts:

- [Material](#material)

Narrower Concepts:

- [Frozen water](#frozen-water)

a solid material that is normally a liquid or gas at Standard Temperature and Pressre (STP)  that is in a solid state under the observed temperature and pressure conditions.


#### Frozen water
[]{#frozen-water}

Concept: [Frozen water](#frozen-water)

Broader Concepts:

- [Any ice](#any-ice)

Water that is in a solid state.


### Biogenic non-organic material
[]{#biogenic-non-organic-material}

Concept: [Biogenic non-organic material](#biogenic-non-organic-material)

Broader Concepts:

- [Material](#material)

Material produced by an organism but not composed of 'very large molecules of biological origin.' E.g. bone, tooth, shell, coral skeleton,


### Dispersed media
[]{#dispersed-media}

Concept: [Dispersed media](#dispersed-media)

Broader Concepts:

- [Material](#material)

A material contains discrete elements of one medium that are dispersed in a continuous fluid medium.  The dispersed component can be a gas, a liquid or a solid (based on https://en.wikipedia.org/wiki/Dispersed_media). Does not include mixtures of granular material like soil, sediment, particulate, or solids that would be considered a rock. E.g. aerosol ENVO_00010505, foam ENVO_00005738, emulsion ENVO_00010506, colloidal suspension ENVO_01001560, scum(?)ENVO:00003930, clathrate?


### Natural Solid Material
[]{#natural-solid-material}

Concept: [Natural Solid Material](#natural-solid-material)

Broader Concepts:

- [Material](#material)

Narrower Concepts:

- [Mineral](#mineral)
- [Mixed soil sediment or rock](#mixed-soil-sediment-or-rock)
- [Particulate](#particulate)
- [Rock or sediment](#rock-or-sediment)
- [Soil](#soil)

Undifferentiated soil, sediment, rock, or natural particulates. Typically (nessarily?) a granular aggregate that might include any of the previous constiturents. Use for Earth Material aggregates of uncertain origin


#### Mineral
[]{#mineral}

Concept: [Mineral](#mineral)

Broader Concepts:

- [Natural Solid Material](#natural-solid-material)

Material consists of a single mineral or mineraloid phase. .  'A mineral is an element or chemical compound that is normally crystalline and that has been formed as a result of geological processes.' (Nickel, Ernest H. (1995), The definition of a mineral, The Canadian Mineralogist. 33 (3): 689–90). Include mineraloids. ... A material primarily composed of some substance that is naturally occurring, solid and stable at room temperature, representable by a chemical formula, usually abiogenic, and that has an ordered atomic structure. (http://purl.obolibrary.org/obo/ENVO_01000256). Comment: the identity of a mineral species is defined by a crystal structure and a chemical composition that might include various specific elemental substitutions in that structure. Mineraloid: A naturally occurring mineral-like substance that does not demonstrate crystallinity. Mineraloids possess chemical compositions that vary beyond the generally accepted ranges for specific minerals. Examples: obsidian, Opal. (https://en.wikipedia.org/wiki/Mineraloid)


#### Mixed soil sediment or rock
[]{#mixed-soil-sediment-or-rock}

Concept: [Mixed soil sediment or rock](#mixed-soil-sediment-or-rock)

Broader Concepts:

- [Natural Solid Material](#natural-solid-material)

Material is mixed aggregation of fragments of undifferentiated soil, sediment or  rock origin. e.g. cuttings from some boreholes (rock fragments and caved soil or sediment), sea floor dredge haul (mixed sediment and rock)


#### Particulate
[]{#particulate}

Concept: [Particulate](#particulate)

Broader Concepts:

- [Natural Solid Material](#natural-solid-material)

Material consists of microscopic particulate material derived by precipitation, filtering, or settling from suspension in a fluid, e.g. filtrate from water, deposition from atmosphere, astro material particles. Might include mineral, organic, or biological material. ENVO definition (ENVO_01000060) has "composed of microscopic portions of solid or liquid material suspended in another environmental material.", refine here to define as the solid particles, distinct from a material in which they are suspended. A material that includes solid or liquid particles suspended in another material would be a dispersed_media in this scheme, not defined in ENVO. Human manufactured particulates (e.g. rock powder) should be categorized as 'anthropogenic material' as well as 'Particulate'


#### Rock or sediment
[]{#rock-or-sediment}

Concept: [Rock or sediment](#rock-or-sediment)

Broader Concepts:

- [Natural Solid Material](#natural-solid-material)

Narrower Concepts:

- [Rock](#rock)
- [Sediment](#sediment)

Material is rock or sediment.  E.g. for samples from subsurface cores that are not well described, from drill holes that likely penetrate sediment near the surface an might be sampling rock at greater depth.


##### Rock
[]{#rock}

Concept: [Rock](#rock)

Broader Concepts:

- [Rock or sediment](#rock-or-sediment)

Consolidated aggregate of particles (grains) of rock, mineral (including native elements), mineraloid, or solid organic material. Includes mineral aggregates such as granite, shale, marble; natural glass such as obsidian; organic material formed by geologic processes such a coal;  extraterrestrial material in meteorites; and  crushed rock fragments like drill cuttings from rock.  (based on http://resource.geosciml.org/classifier/cgi/lithology/rock, same as http://purl.obolibrary.org/obo/ENVO_00001995)


##### Sediment
[]{#sediment}

Concept: [Sediment](#sediment)

Broader Concepts:

- [Rock or sediment](#rock-or-sediment)

Solid granular material transported by wind, water, or gravity, not modified by interaction with biosphere or atmosphere (to differentiate from soil). Particles derived by erosion of pre-existing rock, from shell or other body parts from organisms, precipitated chemically in the surficial environment, or generated by explosive volcanic activity. (http://resource.geosciml.org/classifier/cgi/lithology/sediment). Sediment is not consolidated, i.e. Particulate constituents of a compound material do not adhere to each other strongly enough that the aggregate can be considered a solid material in its own right. Similar to http://purl.obolibrary.org/obo/ENVO_00002007


#### Soil
[]{#soil}

Concept: [Soil](#soil)

Broader Concepts:

- [Natural Solid Material](#natural-solid-material)

Mixed granular mineral and organic matter modified by interaction between earth material, biosphere, and atmosphere, consisting mostly of varying proportions of sand, silt, and clay, organic material such as humus, gases, liquids, and a broad range of resident micro- and macroorganisms. (https://en.wikipedia.org/wiki/Soil) Soil consists of horizons near the Earth's surface that, in contrast to the underlying parent material, have been altered by the interactions of climate, relief, and living organisms over time. (http://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/edu/?cid=nrcs142p2_054280) (http://purl.obolibrary.org/obo/ENVO_00001998)


### Fluid material
[]{#fluid-material}

Concept: [Fluid material](#fluid-material)

Broader Concepts:

- [Material](#material)

Narrower Concepts:

- [Gaseous material](#gaseous-material)
- [Liquid water](#liquid-water)
- [Non-aqueous liquid material](#non-aqueous-liquid-material)

a substance that continually deforms (flows) under an applied shear stress, or external force. Fluids are a phase of matter and include liquids, gases and plasmas. They are substances with zero shear modulus, or, in simpler terms, substances that cannot resist any shear force applied to them. (https://en.wikipedia.org/wiki/Fluid)


#### Gaseous material
[]{#gaseous-material}

Concept: [Gaseous material](#gaseous-material)

Broader Concepts:

- [Fluid material](#fluid-material)

Material composed of one or more chemical entities that has neither independent shape nor volume but tends to expand indefinitely (http://purl.obolibrary.org/obo/ENVO_01000797). Infer that the sample is curated in some kind of container.


#### Liquid water
[]{#liquid-water}

Concept: [Liquid water](#liquid-water)

Broader Concepts:

- [Fluid material](#fluid-material)

A material primarily composed of dihydrogen oxide in its liquid form; infer that the sample is curated in some kind of container.


#### Non-aqueous liquid material
[]{#non-aqueous-liquid-material}

Concept: [Non-aqueous liquid material](#non-aqueous-liquid-material)

Broader Concepts:

- [Fluid material](#fluid-material)

Liquid composed dominantly of material other than water. Includes liquids that do not fit in any other category. E.g. alcohol, petroleum.


### Organic material
[]{#organic-material}

Concept: [Organic material](#organic-material)

Broader Concepts:

- [Material](#material)

Environmental material derived from living organisms and composed primarily of one or more very large molecules of biological origin. Examples: body (animal or plant), body part, fecal matter, seeds, wood, tissue, biological fluids, biological waste, algal material, biofilm, necromass, plankton. source: http://purl.obolibrary.org/obo/ENVO_01000155


