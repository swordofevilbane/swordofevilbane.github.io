---
layout: post
title:  "Synthesis of a Pillar[5]arene Derivative to Create a Chemical Sensor"
type: article
date:   2017-03-01
tags: ["Pillar[5]arene", "Synthesis"]
journal: Integrated Science III, Independent Project
author:
  - name: Cassandra Masschelein
    affiliation:
      - Integrated Science, McMaster University
  - name: Dr. Alex Adronov
    affiliation:
      - Supervisor, Department of Chemistry, McMaster University
  - name: Vladimir Kardelis
    affiliation:
      - Supervisor, Department of Chemistry, McMaster University
  - name: Christina Shamshoom
    affiliation:
      - Supervisor, Department of Chemistry, McMaster University
abstract: |- # COMMENT: make sure to retain proper tabbing
  From disease diagnostics to roadside measurement of impairment, there is a need for portable, affordable, and robust chemical sensors. The conducting nature of single-walled carbon nanotubes (SWNTs) has recently gained much attention for applications in sensors. Any signal generated from the chemical sensor can be recorded between two gold electrodes. The use of “click chemistry” allows us to produce receptor-functionalized SWNTs that can be made selective. This is achieved through strain-promoted alkyne-azide cycloaddition (SPAAC) of a pillar[5]arene derivative. Conjugated polymers interact strongly with SWNTs, allowing us to readily install chemiresistive sensors that respond to binding events with electron deficient guest molecules such as 1,6-dicyanohexane via host-guest chemistry with the pillar[5]arene. The pillar[5]arene is synthesized through a condensation reaction of 1,4-diethoxybenzene with paraformaldehyde, catalyzed by the Lewis acid boron trifluoride diethyl etherate. This is followed by removal of a single ethyl group using boron tribromide, liberating a hydroxyl-functionalized pillar[5]arene. This structure is then alkylated with 1,6-dibromohexane, and the remaining terminal bromide is substituted with sodium azide. This azide containing pillararene derivative will then be introduced to a dibenzocyclooctyne (DIBO)-containing polyinime to click together via SPAAC. This polyimine undergoes efficient assembly onto the surface of SWNTs through supramolecular interactions, creating a connection between the pillararene derivative and the carbon nanotubes. If the binding affinity of the host-guest chemistry is not degraded by structural modifications to the pillar[5]arene, proof-of-concept studies will be undertaken to show that interactions of SWNT-bound pillar[5]arenes with 1,6-dicyanohexane will lead to changes in thin-film conductivity of this material.
---

## Introduction

Carbon nanotubes are allotropes of carbon, just like fullerenes and graphene. Since their discovery it has been determined that they have a number of possible applications due to their high tensile strength and electronic properties (Ajayan and Zhou, 2001). These applications so far include incorporation into field-effect transistors, photovoltaics, flexible electronics, sensors, touch screens, high-strength fibres, and biotechnological constructs (Fong et al., 2016). For the purpose of this study, we will be focusing on their ability to be incorporated into sensors. There are two general types of carbon nanotubes; Multi-Walled Nanotubes (MWNTs) consisting of several graphene cylinders nested together concentrically like the rings of a tree, and Single-Walled Nanotubes (SWNTs) consisting of the individual cylinders 1-2nm in diameter, as seen in Figure 1 (Ajayan and Zhou, 2001; Endo, Strano, and Ajayan, 2007). The SWNTs can be either metallic or semiconducting depending on whether the carbon bonds about the nanotube diameter are armchair, zigzag, or chiral. The properties are the same for MWNTs because the coupling between the cylinders is fairly weak (Endo, Strano, and Ajayan, 2007). It is this conducting nature of the SWNTs that we will be utilizing when incorporating the structures into chemical sensors. Any signal generated from the chemical sensor can be recorded between two gold electrodes, creating a transistor-type device that senses changes in the resistivity of the SWNTs.

{% include figure.html
            fig="image1.png"
            title="Figure 1"
            caption="The basic structures of a) single-walled, b) double-walled, and c) multi-walled carbon nanotubes are shown. You can conceptualize this by imagining wrapping a one-atom thick layer of graphene (hexagonal carbon rings packed in an atomic-scale chicken wire pattern) into a seamless cylinder, and if you wrap up two or more concentric layers, you get MWNTs. These lattice structures consist of carbon atoms arranged in hexagons (Kaushik and Majumder, 2015)." %}

In order to utilize this conducting property for detection, we will be using a pillararene derivative as the receptor. Pillararenes arose from the need to improve the structure of calixarenes so as to allow them to form stable inclusion complexes with guest molecules (Ogoshi et al., 2008). The typical “basket” shape of the meta-bridged phenolic macrocycle makes the molecule an inefficient receptor, and so a para-bridged host—pillararene—was developed as the solution to this inefficiency of structure (Ogoshi et al., 2008). In addition, pillararenes are more rigid than calixarenes, allowing more effective binding of guests (Li et al., 2011).

For this study, 1,4-diethoxybenzene units are connected to methylene bridges at the 2- and 5- positions rather than at the 2- and 6- positions (Ogoshi et al., 2008; Ogoshi and Yamagishi, 2013). These structures are highly symmetrical, allowing them to stably capture guests without a need for modification. When the structure is viewed from above, it appears to be arranged in a pentagon shape, while from the side it takes on the appearance of a “pillar”, as seen in Figure 2 (Ogoshi and Yamagishi, 2013).

{% include figure.html
            fig="image2.png"
            title="Figure 2"
            width="40%"
            caption="The “pillar-like” symmetry of dimethoxypillar[5]arene as viewed from a side-on view, as well as the cyclic pentagonal structure as viewed from a top-down view (Ogoshi and Yamagishi, 2013)." %}

Pillararenes are very similar in structure and function to cucurbiturils with a cavity size of approximately 5.5 Å, allowing the macrocycles to form inclusion complexes with viologens and pyridinium derivatives. The average angle of the carbon-carbon methylene bridges across units is about 110°, thus making the structures extremely stable (Ogoshi and Yamagishi, 2013). They are similar to α-cyclodextrins in that they are easily functionalized via monodeprotection, yielding very reactive hydroxyl groups (Ogoshi and Yamagishi, 2013). The presence of this monohydroxy group offers us the potential to introduce any monofunctionalized group to our pillar[5]arene (Ogoshi et al., 2011b). Pillar[5]arenes can also form complexes with linear alkanes containing electron-poor systems such as amines, ammonium, cyano, and halogen groups (Ogoshi and Yamagishi, 2013). Thus, pillararenes offer a new platform for host-guest and supramolecular chemistry as a novel host because they are highly symmetrical macrocycles with high yields and relatively simple synthetic pathways (Ogoshi et al., 2011a).

For the purpose of this study, 1,4-diethoxybenzene will be used in place of 1,4-dimethoxybenzene, and thus the initial synthetic pathway will result in diethoxypillar[5]arene. In order to allow derivatization of this molecule, a monodeprotection reaction is necessary so that a hydroxyl group can be substituted for one of the ten possible ethoxy groups (Ogoshi and Yamagishi, 2013). This functionalization is necessary so that we can attach the pillararene receptor to the SWNT signal generator. This can be achieved via a monodeprotection approach where the de-O-ethylation is controlled, resulting in mono-O-de-ethylated pillar[5]arene. In the literature, this reaction is performed with 0.9 equivalents of boron tribromide, and the reaction run-time is said to be about 45 minutes (Ogoshi et al., 2011a; Ogoshi, Demachi, Kitajima and Yamagishi, 2011b). We will be investigating the optimization of this reaction in order to make it more efficient and hopefully bring yields above 50%.

The third step of the synthesis is the Williamson ether reaction between monodeprotected pillararene and 1,6-dibromohexane to create an alkyl chain extending from our pillararene. The end of this chain is where we will be able to attach a “clickable” moiety (Strutt et al., 2011).

This can be achieved by substituting the terminal bromide using sodium azide. This azide terminated pillar[5]arene derivative can undergo strain-promoted alkyne-azide cycloaddition (SPAAC) with a dibenzocyclooctyne (DIBO)-containing polyimine. This is because DIBO contributes the necessary reactive cyclooctyne functionality. This strained cyclooctyne can be used in place of a catalyst to “click” the pillararene to a conjugated polymer. Many classes of conjugated polymers are known to exhibit strong supramolecular interactions with carbon nanotubes, one of which includes polyimines (Chadwick et al., 2013; Kardelis et al., 2016). The utilization of polyimine backbones will permit a selective dispersion of SWNTs, allowing us to harness their conductive properties for our sensor.

As mentioned, we will be using a polyimine derivative with DIBO units integrated within each monomer. These DIBO units contain very high strain and a decrease in distortion energies. In addition, the biaryl substitution increases the ring strain and conjugates the alkynes thus improving the reactivity further. The azides terminating the pillar[5]arene derivatives will undergo SPAAC with the reactive cyclooctyne moieties on DIBO. This Huisgen cycloaddition between an azide and alkyne is efficient, selective, and very useful in the synthesis of functional architectures (Chadwick et al., 2013). This specific Huisgen cycloaddition is not copper catalyzed, but rather the strain-promotion of the cycloalkyne is what drives it forward. This strain also permits the reaction to occur rapidly at room temperature with high yields (Chadwick et al., 2013; Gobbo et al., 2013). The absence of the copper catalyst allows this reaction to be biocompatible, and thus it is a copper-free [3+2] Huisgen cycloaddition, also known as a bioorthogonal reaction (Gobbo et al., 2013).

As mentioned, this DIBO-containing polyimine will form a supramolecular structure with carbon nanotubes throughπ-stacking, thus completing the connection between the receptor (pillararene) and the signal output material (SWNT) in our sensor. Host-guest systems that respond to binding events provide readable signals as molecular changes occur (Clavier and Audebert, 2010). When an electron deficient guest molecule enters an electron rich pillararene, it is hypothesized that the resistivity changes of the carbon nanotubes will allow us to detect the electrochemical interaction (Clavier and Audebert, 2010). This is because the electrical properties of the carbon nanotubes will change quickly and with a high degree of sensitivity in response to this event. Measurements of these changes can be recorded and used in our sensing device (Kong et al., 2000).

For the purpose of this experiment, the guest molecule to be introduced is 1,6-dicyanohexane, and we are curious to see if the alkylation and the addition of the clickable group will change the strength of the host-guest binding constant. If the binding constant remains strong, and the DIBO-containing polyimine is found to suspend on the SWNTs, proof-of-concept studies will move on to designing sensors with similar architectures that are selective for specific analytes.

## Results and Discussion

The condensation reaction resulted in a solution that was decorated with a black tarry substance. This flexible material is the polymer that forms with the pillar[5]arene, and it needs to be filtered out using a silica plug so that the pure pillar can be collected. The later fractions collected of the pillararene contained a fluorescence spot under long wave ultraviolet (UV) irradiation, as seen in Figure 3. This was considered an impurity, and so fractions containing fluorescence under long wave UV irradiation were collected separately. Fortunately, the proton nuclear magnetic resonance imaging (<sup>1</sup>H NMR) and mass spectrometry data came back clean for all fractions containing pillar. The pure pillar[5]arene was a white crystalline solid, and the yield of this reaction was 40%, resulting in a combined 3.41g of synthesized product. The <sup>1</sup>H NMR of this product is shown below in Figure 4, and the mass spectrum is shown in Figure 5:

{% include figure.html
            fig="image3.png"
            title="Figure 3"
            caption="Image showing the fluorescence spots observed under long wave UV irradiation for the later pillar containing fractions. These fluorescent spots showed up on the thin-layer chromatography plates for all of the condensation reactions." %}

{% include figure.html
            fig="image4.png"
            title="Figure 4"
            caption="<sup>1</sup>H NMR (600 MHz, CDCl3) of the condensation reaction product, 1,4-bis(ethoxy)pillar[5]arene. The singlet at δ6.785 corresponds to the protons in the aromatic ring (Hc), the quartet around δ3.85 corresponds to the protons on the 2° carbons of the ethoxy groups (Hb), the singlet at δ3.765 corresponds to the protons on the methyl groups that attach the benzenes together (Hd), the triplet around δ1.327 corresponds to the protons on the 1° carbons of the ethoxy groups (Ha). The peak at δ7.26 corresponds to deuterated chloroform, and the peak at δ1.52 corresponds to water." %}

{% include figure.html
            fig="image5.png"
            title="Figure 5"
            caption="The mass spectrum (run with ammonium acetate as the adduct) from the condensation reaction product, 1,4-bis(ethoxy)pillar[5]arene. The peak at m/z 891.3 corresponds to the M+1 peak for the pillar[5]arene, while the peak at m/z 908.3 corresponds to the M+NH4+ peak for the pillar[5]arene." %}

A recrystallization of the pillar[5]arene can be done in acetone, in order to purify the product. The crystals can be grown by slow evaporation of the solution in acetone using a heat gun. Just enough acetone needs to be added so that the pillar is in solution, and once this is achieved, the solution can be cooled to room temperature and then put into the freezer to wait for crystal growth.

The first time the synthesis of the mono-O-de-ethylated pillar[5]arene was performed, white flakes appeared in the solution that did not dissolve, but this did not affect the final product. The third time that this reaction was performed, an additional 0.2 equivalents of the Lewis acid boron tribromide was added 60 minutes into the reaction. This was done in order to optimize the reaction and increase the yield. Unfortunately, this addition was found to significantly decrease the yield of the reaction. The product of this synthesis was purified via a gradient elution silica column (5-10% ethyl acetate in hexanes) on a flash system. The purified product for this synthesis was a white solid (0.11g), with an overall yield of 17%. The <sup>1</sup>H NMR of this product is shown below, in Figure 6:

{% include figure.html
            fig="image6.png"
            title="Figure 6"
            caption="<sup>1</sup>H NMR (600MHz, CDCL3) of the monodeprotection reaction product, mono-O-de-ethylated pillar[5]arene. The signals in the aromatic region correspond to the protons in the aromatic ring (Hc) and the additional integration arises from the presence of the hydroxyl on the one benzene, the quartets around δ4.0-3.6 correspond to the protons on the 2° carbons of the ethoxy groups (Hb), the multiplet around δ3.8-3.7 corresponds to the protons on the methyl groups that attach the benzenes together (Hd), the triplets and multiplets around δ1.4-1.0 correspond to the protons on the 1° carbons of the ethoxy groups (Ha). The signal around δ1.52 corresponds to water." %}

The synthesis of mono-O-alkylated pillar[5]arene bromide was done only once and the product was a white solid. This solid product had to be purified via a gradient elution silica column (5-10% ethyl acetate in hexanes) on a flash system in order to isolate the pillar bromide from the starting material as well as other potential impurities. The overall yield of this reaction was 40%, and thus we synthesized 40mg of the desired mono-O-alkylated pillar[5]arene bromide. The <sup>1</sup>H NMR of this product is shown below, in Figure 7:

{% include figure.html
            fig="image7.png"
            title="Figure 7"
            caption="<sup>1</sup>H NMR (600MHz, CD2CL2) of the pillar bromide reaction product, mono-O-alkylated pillar[5]arene bromide. The signals around δ6.9-6.8 correspond to the protons in the aromatic ring (Hc), the triplet around δ3.9 correspond to the protons on the alpha carbon to the oxygen on the alkyl chain (He), the multiplet around δ3.9 corresponds to the protons on the alpha carbons to the ethers (Hb), the singlet at δ3.75 corresponds to the protons on the methyl groups that attach the benzenes together (Hd), the triplet around δ3.4 corresponds to the protons on the alpha carbon to the bromide (Hf), the quintets between δ1.9-1.6 correspond to the protons on the carbons of the alkyl chain (Hg), and the multiplet around δ1.4 corresponds to the 1° carbons of the ethoxy groups (Ha). The signal around δ5.32 corresponds to deuterated dichloromethane, and the signal at δ1.52 corresponds to water." %}

The synthesis of mono-O-alkylated pillar[5]arene azide was only done once and the product was an off-white solid. This solid product had to be purified via a gradient elution silica column (5-10% ethyl acetate in hexanes) on a flash system in order to isolate the pillar azide from the starting material as well as other potential impurities. The overall yield of this reaction was 80%, and thus we synthesized 24mg of pillar azide. The <sup>1</sup>H NMR of this product is shown below, in Figure 8:

{% include figure.html
            fig="image8.png"
            title="Figure 8"
            caption="<sup>1</sup>H NMR (600MHz, CD2CL2) of the pillar bromide reaction product, mono-O-alkylated pillar[5]arene bromide. The signals around δ6.9-6.8 correspond to the protons in the aromatic ring (Hc), the triplet around δ3.9 correspond to the protons on the alpha carbon to the oxygen on the alkyl chain (He), the multiplet around δ3.9 corresponds to the protons on the alpha carbons to the ethers (Hb), the singlet at δ3.75 corresponds to the protons on the methyl groups that attach the benzenes together (Hd), the triplet around δ3.4 corresponds to the protons on the alpha carbon to the bromide (Hf), the quintets between δ1.9-1.6 correspond to the protons on the carbons of the alkyl chain (Hg), and the multiplet around δ1.4 corresponds to the 1° carbons of the ethoxy groups (Ha). The signal around δ5.32 corresponds to deuterated dichloromethane, and the signal at δ1.52 corresponds to water." %}

High performance liquid chromatography (HPLC) was run for all four of the synthesized products in order to determine that the product consisted of a pure compound that was different in retention time than the starting material. The HPLC was set using a phenyl-hexyl column with 95% deionized water, and 5% acetonitrile as the eluent. Figure 9 shows the different HPLC traces of the pillar synthesis reactions, and as you can see, all of the retention times are different and there only exists single peaks:

{% include figure.html
            fig="image9.png"
            title="Figure 9"
            caption="The chromatogram from the HPLC (run with a phenyl-hexyl column and monitored at 296nm) from each of the four steps of the pillar[5]arene derivative synthesis. The pink trace corresponds to 1,4-bis(ethoxy)pillar[5]arene with a retention time around 11.70 minutes, the orange trace corresponds to mono-O-de-ethylated pillar[5]arene with a retention time around 11.19 minutes, the blue trace corresponds to mono-O-alkylated pillar[5]arene bromide with a retention time around 12.00 minutes, and the black trace corresponds to mono-O-alkylated pillar[5]arene azide with a retention time around 11.85 minutes." %}

It should be noted that pillar[5]arene and all of its derivatives are susceptible to oxidation, and this can be prevented by storing the solid products under argon gas.

## Conclusions

Thus far in this proof-of-concept study we have shown the facile, rapid, and efficient synthesis of a monofunctionalized pillar[5]arene derivative that can be easily clicked onto a DIBO-containing polyimine through SPAAC. The next steps in the synthesis of this chemiresistive sensor are being worked on, including clicking the pillar azide onto the DIBO-containing polyimine. This has been done on a small scale, and the pillar-clicked polymers have been suspended onto SWNTs. The suspension was very successful and currently we are conducting resistivity measurements with these pillar-clicked suspensions between two gold electrodes. We expect that when we introduce the guest molecule (1,6-dicyanohexane) into the system, the host-guest interactions with the pillar[5]arene derivatives will result in a change in the resistivity measurements of the carbon nanotubes between the two gold electrodes. If this is found to be a sensitive system that can detect the presence of selected analytes, we will have successfully synthesized a portable, affordable, and robust chemical sensor.

This host-guest chemistry with the pillar[5]arene derivative can then be switched out for more selective interactions, such as those between aptamers and specific chemical compounds. Thus, this sensor composed of a receptor molecule (pillar[5]arene derivative) attached a conjugated polymer that π-stacks onto the signal generating molecule (SWNTs) has the potential to enable the introduction of a broad array of sensory elements onto the surface of the polymer-SWNT complex.

## Experimental Methods

### Step 1: Condensation reaction to synthesize 1,4-bis(ethoxy)pillar[5]arene

{% include figure.html
            fig="image10.png"
            title=""
            caption="(Ogoshi et al., 2011b; ChemDraw Prime 16.0)" %}

For the condensation reaction at the 1g scale to synthesize the 1,4-bis(ethoxy)pillar[5]arene, a stir bar was placed into a 100mL round bottom flask (RBF), and the flask was clamped to a hot plate. The RBF was charged with 1,4-diethoxybenzene (1g, 6.02mmol), paraformaldehyde (0.54g, 18.06mmol), and 1,2-dichloroethane (13mL). The reaction was stirred under an argon environment for 30 minutes. Next, boron trifluoride diethyl etherate (0.743mL, 6.02mmol) was added dropwise, and the reaction was left to stir vigorously for 1 hour at room temperature. Then the reaction was quenched with 20mL of hexanes. The mixture was filtered through a silica plug under vacuum by washing with 1:1 of dichloromethane:hexane (DCM:Hex) and collecting 50-100mL fractions. Fractions were monitored via thin-layer chromatography (TLC) in 7:3 DCM:Hex. Fractions containing pillar[5]arene were evaporated in two sections because fractions 2-5 looked pure while fraction 6-14 had unknown fluorescence under long wave UV irradiation. The condensation reaction yielded a white solid (0.415g, 39 %). M.W.: 890.50 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.76 (s, 10H), 3.84 (q, 20H), 3.77 (s, 10H), 1.30 (t, 30H).

This reaction was repeated again on the 1g scale, and fractions containing pillar[5]arene were again evaporated in two sections because fractions 2-3 looked pure while fraction 4-12 had unknown fluorescence under long wave UV irradiation. The condensation reaction yielded a white solid (0.381g, 36%). M.W.: 890.5 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.79 (s, 10H), 3.85 (q, 20H), 3.77 (s, 10H), 1.33 (t, 30H).

For the condensation reaction at the 2g scale to synthesize the 1,4-bis(ethoxy)pillar[5]arene, a stir bar was placed into a 100mL RBF, and the flask was clamped to a hot  plate. The RBF was charged with 1,4-diethoxybenzene (2g, 12.04mmol), paraformaldehyde (1.09g, 36.12mmol), and 1,2-dichloroethane (26mL). The reaction was stirred under an argon environment for 30 minutes. Next, boron trifluoride diethyl etherate (1.486mL, 12.04mmol) was added dropwise, and the reaction was left to stir vigorously for 30 minutes at room temperature. The reaction was quenched with 40mL of hexanes. The mixture was then filtered through a silica plug under vacuum by washing with 1:1 DCM:Hex and collecting 50-100mL fractions. This time the collected fractions were placed directly under nitrogen after collection in order to help evaporate off some of the DCM so that the TLC spots were more concentrated. Starting at fraction 17 and onward the polarity of the eluent was increased to 6:4 DCM:Hex. Fractions were monitored via TLC (in 7:3 DCM:Hex). Fractions containing pillar[5]arene were evaporated together because they all appeared to have the unknown fluorescence under long wave UV irradiation. The reaction yielded a white solid (0.793g, 37%). M.W.: 890.5 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.76 (s, 10H), 3.85 (q, 20H), 3.78 (s, 10H), 1.30 (t, 30H).

For the condensation reaction at the 5g scale to synthesize the 1,4-bis(ethoxy)pillar[5]arene, a stir bar was placed into a 500mL RBF, and the flask was clamped to a hot plate. The RBF was charged with 1,4-diethoxybenzene (5g, 30.10mmol), paraformaldehyde (2.71g, 90.31mmol), and 1,2-dichloroethane (65mL). The reaction was stirred under an argon environment for 30 minutes. Next, boron trifluoride diethyl etherate (3.72mL, 30.10mmol) was added dropwise, and the reaction was left to stir vigorously for 1 hour at room temperature. The reaction was quenched with 100mL of hexanes. The mixture was then filtered through a silica plug under vacuum by washing with 1:1 DCM:Hex and collecting 200-250mL fractions. Fractions were run via TLC (in 7:3 DCM:Hex). Fractions containing pillar[5]arene were evaporated in three sections because fractions 2-3 looked the sharpest for absorbance, fraction 1 looked like it might not have as much pillar, and fractions 4-14 did not appear as concentrated with pillar[5]arene. The reaction yielded a white solid (1.823g, 34%). M.W.: 890.5 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.82 (s, 10H), 3.88 (q, 20H), 3.77 (s, 10H), 1.35 (t, 30H).

#### Recrystallization of 1,4-bis(ethoxy)pillar[5]arene

We recrystallized 1.0g of the 1,4-bis(ethoxy)pillar[5]arene from the condensation reactions by acetone. The pillar[5]arene crystals were transferred into a 250mL Erlenmeyer flask and 25mL fractions of acetone were added periodically. The solution was stirred vigorously and heated at 80°C. The solution was still cloudy after adding 300mL of acetone so a hot filtration was performed and then the solution was heated and stirred with a heat gun until enough acetone had evaporated off and the pillar began crashing out. Once there was enough acetone for the pillar[5]arene to stay in solution, the mixture was brought to room temperature and stirring was terminated. At room temperature, the mixture was put into the freezer to allow crystal formation for two days.

The crystalized pillar was vacuum filtered and the crystals were collected from the filter paper (recrystallized). The mother liquor (ML) was then evaporated, and those crystals were collected. <sup>1</sup>H NMR and mass spectrometry was ran for both the recrystalized and ML products. The yield from recrystalization was found to be (0.1g, 10%), and the yield from the ML was found to be (0.812g, 81.2%). M.W.: 890.5 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.72 (s, 10H), 3.82 (q, 20H), 3.77 (s, 10H), 1.26 (t, 30H).

### Step 2: Monodeprotection of pillar[5]arene to form Mono-O-de-ethylated pillar[5]arene

{% include figure.html
            fig="image11.png"
            title=""
            caption="(Ogoshi et al., 2011a; ChemDraw Prime 16.0)" %}

1,4-bis(ethoxy)pillar[5]arene (200mg, 224µmol) was dissolved in dichloromethane (24mL) in a 100mL flame-dried round bottom flask. 1 M solution of boron tribromide (202 µL, 202mmol) was added dropwise to the stirring solution at room temperature via syringe while under an argon environment. The reaction was left to stir vigorously for 60 minutes and then TLC (1:9 Ethyl acetate (EtOAc):Hex) was performed to check that the desired product was being formed before quenching the reaction with distilled water. The organic phase was extracted (x3) with distilled water, and then it was dried with magnesium sulfate (MgSO4). The compound was purified via silica gel column chromatography using a 5-10% gradient of ethyl acetate in hexanes. The monodeprotection yielded a white solid (0.046g, 24%). M.W.: 863.10 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.89 (s, 1H), 6.76 (s, 1H), 6.69 (s, 1H), 6.67 (s, 1H) 6.63 (s, 1H), 6.62 (s, 1H), 6.54 (s, 1H), 6.54 (s, 1H), 6.53 (s, 1H), 6.47 (s, 1H), 4.02 (q, 2H), 3.89 (q, 2H), 3.83 (q, 2H), 3.80-3.70 (m, 22H), 3.63 (q, 2H), 1.41-1.34 (m, 12H), 1.21 (t, 3H), 1.17-1.13 (m, 6H), 1.11 (t, 3H), 1.07 (t, 3H), 1.02 (t, 3H).

This reaction was repeated again on the 200mg scale, however, this time the reaction was left to stir vigorously for 40 minutes before high performance liquid chromatography (HPLC) analysis using a phenyl-hexyl column and 95% deionized water, 5% acetonitrile as the eluent was used to monitor the progress of the reaction. Once the HPLC showed a sufficient peak for the monodeprotected pillararene, the reaction was quenched with deionized water and then transferred into separatory funnel. Brine was added to wash the organic phase, and then the organic layer (approximately 50mL) was collected in an Erlenmeyer flask. Magnesium sulfate was added to the Erlenmeyer flask to dry it. The magnesium sulfate was filtered out and the solution was rotovapped to dryness, and then placed under high vacuum over-night. At the same time a 250mL flame-dried round bottom flask was charged with 1,4-bis(ethoxy)pillar[5]arene (500mg, 560µmol) and dissolved in dichloromethane (60mL). 1 M solution of boron tribromide (504µL, 504mmol) was added dropwise to the vigorously stirring solution at room temperature via syringe while under an argon environment. The reaction was left to stir for 40 minutes, and then monitored by HPLC using a phenyl-hexyl column with 95% deionized water, and 5% acetonitrile as the eluent. After checking the HPLC, another 0.2 equivalents of boron tribromide (0.112mL) was added to the reaction in order to convert more of the 1,4-bis(ethoxy)pillar[5]arene into the mono-O-de-ethylated pillar[5]arene. After 5 minutes, the reaction was again monitored by HPLC, and it was found that the additional boron tribromide did not result in the desired conversion and so the reaction was quenched with deionized water after a total of 2 hours run time. The reaction was transferred into a separatory funnel, and then brine was added to wash the organic phase. The organic layer (approximately 100mL) was collected in an Erlenmeyer flask, and then magnesium sulfate was added to dry it. The magnesium sulphate was filtered out and the solution was rotovapped to dryness, and then placed under high vacuum over-night. The combined product of these two reactions was purified via gradient elution silica column (5-10% ethyl acetate in hexanes) on a flash system, monitored at 296nm. The monodeprotection yielded a white solid (0.064g, 9.5%). M.W.: 863.10 g/mol. 1H-NMR (600 MHz; CDCl3): δ 6.89 (s, 1H), 6.77 (s, 1H), 6.69 (s, 1H), 6.67 (s, 1H) 6.63 (s, 1H), 6.63 (s, 1H), 6.54 (s, 1H), 6.54 (s, 1H), 6.53 (s, 1H), 6.47 (s, 1H), 4.02 (q, 2H) 3.90 (q, 2H), 3.84 (q, 2H), 3.80-3.70 (m, 22H), 3.62 (q, 2H), 1.41-1.34 (m, 12H), 1.21 (t, 3H), 1.17-1.13 (m, 6H), 1.11 (t, 3H), 1.07 (t, 3H), 1.02 (t, 3H).

### Step 3: Williamson ether reaction to synthesize Mono-O-alkylated pillar[5]arene bromide

{% include figure.html
            fig="image12.png"
            title=""
            caption="(Strutt et al., 2011; ChemDraw 16.0)" %}

Mono-O-de-ethylated pillar[5]arene (100mg, 0.116mmol) and 1,6-dibromohexane (283mg, 1.16mmol) were dissolved in acetone (1mL) in a 5 mL conical flask. Potassium carbonate (160mg, 1.16.mmol) and 18-crown-6 (3mg, 0.012mmol) were added to the solution, which was then stirred for 24 hours at 50 °C. The reaction was monitored by TLC (1:9 EtOAc:Hex) to see when the reaction had formed the desired product. Upon completion, the reaction was filtered to remove the remaining potassium carbonate, and then it was concentrated under vacuum. The solution was purified via gradient elution silica column (5-10% ethyl acetate in hexanes) on a flash system, monitored at 296nm. The pure product was an off-white solid (40mg, 40%). M.W.: 1026.14 g/mol. 1H-NMR (600 MHz; CD2Cl2): δ 6.89-6.86 (broad, 10H), 3.99-3.91 (m, 18H), 3.91-3.90 (t, 2H) 3.76 (s, 10H), 3.45 (t, 2H), 1.95-1.90 (q, 2H), 1.90-1.85 (q, 2H), 1.63-1.53 (m, 4H), 1.48-1.44 (m, 27H).

###  Step 4: Nucleophilic substitution reaction to synthesize Mono-O-alkylated pillar[5]arene azide

{% include figure.html
            fig="image13.png"
            title=""
            caption="(Strutt et al., 2011; ChemDraw 16.0)" %}

Mono-O-alkylated pillar[5]arene bromide (30mg, 0.03mmol) and sodium azide (10mg, 0.150mmol) were dissolved in 1:1 dimethylformamide:tetrahydrofuran (DMF:THF) (0.5mL) in a 5mL RBF. The solution was then stirred for 24 hours at 50 °C. The reaction was monitored by TLC (1:9 EtOAc:Hex) and upon completion, an extraction was performed. For the extraction, 10-20mL of ether was added to wash the organic phase, and then 15mL of 0.5 M lithium chloride solution was added three separate times. The organic layer was then washed with brine and dried over magnesium sulfate. The magnesium sulphate was filtered out and then the crude product was run through a silica plug with 1:9 EtOAc:Hex, collecting 100mL fractions. These fractions were then run on a TLC plate (1:9 EtOAc:Hex) in order to determine which fractions contained the product. Only fraction 1 contained the pillar azide, and so this fraction was concentrated on a rotary evaporator yielding an off white solid (24mg, 80%). M.W.: 988.28 g/mol. 1H-NMR (600 MHz; CD2Cl2): δ 6.89-6.85 (broad, 10H), 3.98-3.91 (m, 18H), 3.89 (t, 2H), 3.73 (s, 10H) 3.30 (t, 2H), 1.86 (q, 2H), 1.66 (q, 2H), 1.59 (q, 2H), 1.49 (q, 2H), 1.48-1.42 (m, 27H).

{% include references.md
            reference="
Ajayan, P.M. and Zhou, O.Z., 2001. Applications of carbon nanotubes. In Carbon nanotubes (pp. 391-425). Springer Berlin Heidelberg.

Chadwick, R., Kardelis, V., Liogier, S., and Adronov, A., 2013. Synthesis of Conjugated Polymers Containing DIBAC-Derived Triazole Monomers. Macromolecules, 46, pp.9593-9598.

Clavier, G., and Audebert, P., 2010. s-Tetrazines as Building Blocks for New Functional Molecules and Molecular Materials. Chemical Reviews, 110(6), pp.3299–3314.

Endo, M., Strano, M.S., and Ajayan, P.M., 2007. Potential applications of carbon nanotubes. In Carbon nanotubes (pp. 13-62). Springer Berlin Heidelberg.

Fong, D., Bodnaryk, W.J., Rice, N.A., Saem, S., Moran-Mirabal, J.M., and Adronov, A., 2016. Influence of Polymer Electronics on Selective Dispersion of Single-Walled Carbon Nanotubes. Chemistry (Weinheim an der Bergstrasse, Germany), 22(41), pp.14560–6.

Gobbo, P., Novoa, S., Biesinger, M., and Workentin, M., 2013. Interfacial strain-promoted alkyne-azide cycloaddition (I-SPAAC) for the synthesis of nanomaterial hybrids. Royal Society of Chemistry: Chem. Commun., 49, pp.3982-3984.

Kardelis, V., Chadwick, R.C., and Adronov, A., 2016. Click Functionalization of a Dibenzocyclooctyne-Containing Conjugated Polymine. Angewandte Chemie: International Edition, 55, pp.945-949.

Kaushik, B.K., Majumder, M.K., 2015. Carbon Nanotube Based VLSI Interconnects. Analysis and Design., 11(86), pp.17-37.

Kong, J., Franklin, N., Zhou, C., Chapline, M., Peng, S., and Cho, K., 2000. Nanotube Molecular Wires as Chemical Sensors. Science, 287(5453), pp. 622.

Li, C., Chen, S., Li, J., Han, K., Xu, M., Hu, B., Yu, Y., and Jia, X., 2011. Novel neutral guest recognition and interpenetrated complex formation from pillar[5]arenes. Chemical Communications, 47(40), pp.11294.

Ogoshi, T., Kani, S., Fujinami, S., Yamagishi, T., and Nakamoto, Y., 2008. Para-Bridged Symmetrical Pillar[5]arenes: Their Lewis Acid Catalyzed Synthesis and Host-Guest Property. Journal of the American Chemical Society, 130, pp.5022-5023.

Ogoshi, T., Demachi, K., Kitajima, K., and Yamagishi, T., 2011a. Monofunctionalized pillar[5]arenes: synthesis and supramolecular structure. The Royal Society of Chemistry: ChemComm.

Ogoshi, T., Aoki, T., Kitajima, K., Fujinami, S., Yamagishi, T., and Nakamoto, Y., 2011b. Facile, Rapid, and High-Yield Synthesis of Pillar[5]arene from Commercially Available Reagents and Its X-ray Crystal Structure. American Chemical Society: JOC Note.

Ogoshi, T., Yamagishi, T., 2013. Pillararenes: Versatile Synthetic Receptors for Supramolecular Chemistry. European Journal of Organic Chemistry: Microreview, pp.2961-2975.

PerkinElmer Incorporated, 2016. ChemDraw Prime (16.0). [computer program].

Strutt, N.L., Forgan, R.S., Spruell, J.M., Botros, Y.Y., and Stoddart, J.F., 2011. Monofunctionalized Pillar[5]arene as a Host for Alkanediamines. Journal of the American Chemical Society, 133, pp.5668-5671.
"
%}
