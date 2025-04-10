# EXPANSION MICROSCOPY

## INTRODUCTION

Sample preparation for expansion microscopy measurements. Expansion method optimized by Matt Lycas, documentation by Benedetta Noferi.
This procedure can all be performed in a week.

## MATERIALS AND EQUIPMENT

### Reagents

**Cell Culture Materials**
- 24-well plate for cell culture
- Glass slides (1.5, 12 mm)
- Cell line: U20S - NUP96 - GFP (or other cell line of interest)
- PBS (Phosphate Buffered Saline)

**Cryo-fixation Materials**
- Liquid nitrogen
- Dry ice
- Acetone (high purity)
- Ethanol (100%, 95%, 75%, 50%, 25%)

**Anchoring Reagents**
- Sodium bicarbonate (NaHCO₃, 1M solution)
- Glycidyl methacrylate (GMA)
- Sodium azide (0.01% for storage)

**Gelation Materials**
- Sodium acrylate (46% solution)
- Acrylamide (40% solution)
- Bis-acrylamide (2% solution)
- 10x PBS
- TEMED (N,N,N',N'-tetramethylethylenediamine, 10% solution)
- APS (Ammonium persulfate, 10% solution)
- Parafilm

**Denaturation Reagents**
- Sodium dodecyl sulfate (SDS)
- Sodium chloride (NaCl)
- Tris base
- Water (deionized)

**Staining Materials**
- Bovine serum albumin (BSA)
- Primary antibodies (e.g., GFP, α-Tubulin, mitochondrial protein)
- Secondary antibodies with fluorophores
- Paraformaldehyde (PFA, 32% solution)

**Imaging Materials**
- Glass coverslips (25 mm)
- Poly-D-Lysine (PDL)
- Methanol
- APTES (3-Aminopropyltriethoxysilane)

### Equipment

**Cryo-fixation Equipment**
- Plunging arm apparatus
- Thermos container for liquid nitrogen
- Dewar flask
- Cryo-gloves
- Safety glasses
- Rocking shaker
- Syringe
- Eppendorf tubes (5ml)
- Tweezers
- Filter paper/Kimwipes
- Hammer (for pulverizing dry ice)
- Polystyrene cooler

**General Equipment**
- Fume hood
- Sonicator
- Humidified chamber
- Heating block (for 95°C)
- Metal holder for glass coverslips (for imaging)
- Scalpel
- Microscope for cell checking and imaging
- 12-well and 6-well plates
- 50 mL tubes

## PROCEDURE

### **Cell preparation**

1. Cell culture preparation on glass slides (number 1.5, 12 mm) in a 24-well plate, 50000 cells per well

   In our case, we use the tumoral cell line U20S - NUP96 - GFP (the nuclear pores, more specifically the NUP96 protein is already genetically modified so that it intrinsically contains the GFP fluorescent protein already for IF imaging).

2. Wait for 24 hours for cells to grow enough.

3. **Pause point** Check at the microscope the number of cells and if they are still alive before continuing with the procedure.

### **Cryo-fixation**

This part of the protocol takes inspiration from cryo-electron microscopy protocols, in particular from the article of [Laporte et al., *Nat Methods* 19, 216–222 (2022)](https://doi.org/10.1038/s41592-021-01356-4). In the conventional fixing procedure we would usually just put for 15 minutes a fixing solution, i.e. 3% PFA, 0.1% Glutaraldehyde in PBS, and then wash at least 3 times with PBS, and follow up with a 5 minute incubation in PBS with 0.1% Triton for permeabilization.

4. **Materials preparation**

   Take the dry ice and pulverize with a hammer and place in a polystyrene cooler. One could use a cardboard box in order to have the right amount of space but maintain the necessary safety measurements, and then put it all back into the polystyrene box. Take a dewar for the liquid nitrogen as to pour it when needed.

   **!!** Remember to always use blue cryo gloves when handling dry ice and the nitrogen container, since it is very easy to get burnt. While smashing the ice use safety glasses as well.

5. Take as many 5ml Eppendorf tubes as the number of glass slides you have and put 3ml of acetone in each one[^1]

6. Use another container and fill it with liquid nitrogen as well to freeze the acetone tubes at an angle (always use tweezers)[^2]

   Then leave them inside the liquid nitrogen until you need them.

7. Pour liquid nitrogen into the metal chamber of the plunge freezer brass cup as well as in the dewar of the plunge freezer, so that all of the materials reach the desired temperature of -180° (technically, a dewar is a vacuum-insulated container used to maintain internal temperature for extended periods, but since it has the same function we are going to call it this way). Once you reach the right temperature, pour in the inner chamber the ethane gas, that will condense.[^3]

8. Before using the plunging arm, it is advisable to check that it will drop to the right depth, using a test glass slide.

   *Pro tip*: cover the tweezer with wax; this way you avoid any residual liquid to stay on them.

9. **Plunge freezing:** → take the glass slides out of the well plate and position it between the tweezers.[^4]

   Wipe what you can with a kimwipe or even better use filter paper, but be careful in scratching the cell surface.
   **!!** For the plunging always use glasses.

10. Activate the plunging arm

11. Slowly remove the tweezer from the plunging arm and take one Eppendorf out of the liquid nitrogen container and open the lid. Once everything is ready, transfer the glass slide into the Eppendorf tube as quickly as you can.

    *Note*: Not so quickly! We should still keep a slight pause with the open lid of the Eppendorf in order to let the Ethane evaporate well (at least that is our most realistic explanation), otherwise it can happen that the tube will explode after a while in the dry ice.

12. Close the lid and put the Eppendorf into the dry ice box.

    Use a hammer to help you put it inside.

13. Place the cooler filled with dry ice on a rocking shaker until the next day.

### **Washing**

14. Take the Eppendorf tubes out of the dry ice and leave them heat up to RT for at least one hour and a half[^5].

15. Washing procedure → take the glass slides out of the Eppendorf tubes and place them in a 12-well plate (with the cell surface facing up) and wash them with:

    - 2x Ethanol solution 100%, 2x Ethanol solution 95%, 1x Ethanol solution 75%, 1x Ethanol solution 50%, 1x Ethanol solution 25%, 5 minutes each
    - 3x PBS, without an incubation time.

    **Pause point** Once in this condition, you can leave them as much as you want (i.e. overnight for the following steps the next day).

### **Anchoring**

In a standard ExM experiment, target biomolecules (e.g., proteins and nucleic acids, or labels attached to them) in a biological specimen are covalently bound to anchoring molecules bearing vinyl groups (here, an epoxide such as glycidyl methacrylate, turning biomolecules to methacrylate (MA) forms) that can be crosslinked to a swellable polyacrylate hydrogel synthesized throughout the specimen (*Gelation*). This protocol has been taken and adapted from [Cui et al. *PLOS ONE* 18(9), (2023)](https://doi.org/10.1371/journal.pone.0291506).[^6]

16. Preparation of the **anchoring media**, i.e. 0.04% of glycidyl methacrylate (GMA) in a 100 mM sodium bicarbonate (NaHCO₃) solution - to have a fixed pH of 8.5
    The solubility of GMA is about 3% in most aqueous solutions and so the anchoring buffer has to be vigorously vortexed after addition of GMA. According to the safety data sheet of GMA, handling of undiluted GMA needs to be done in a fume hood with sufficient ventilation.

17. Transfer the glass slides to a new 12-wellplate. To ensure the removal of all the PBS solution, wash it at least three times with the anchoring solution, and let incubate after the third time.[^7]

18. Leave it at RT to be shaken for (at least) 4h - in the article supplementary information, where they vary temperature and incubation time, they show that this is a way to optimize the procedure.

19. **Pause point** One can pause by leaving the sample at RT until the next day as the reaction saturates at the written incubation time. Alternatively, the sample can be washed 3x to remove excess GMA and stored in PBS with 0.01% sodium azide at 4 °C.

### **Gelation**

20. Prepare the **monomer solution**:
    - 23% (weight by volume) Sodium Acrylate
    - 10% Acrylamide
    - 0.1% Bisacrylamide in PBS solution
    
    This can be made with:
    - 500 µl of 46% Sodium Acrylate
    - 250 µl of 40% Acrylamide
    - 50 µl of 2% Bisacrylamide
    - 100 µl of 10x PBS

<iframe width="560" height="315" src="https://youtu.be/3YyEKSIz6eA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

21. Put the microscope glass slide in a petri dish with the surface bottom covered by parafilm and put them at -80°C to cool down.

    **!!** Prepare an ice bucket as well on which to put the petri after 5/10 minutes of cooling down.

22. Aspirate the PBS from the well and put 1 ml of monomer solution to incubate over the sample

    **Critical Point** - *Pro tip*: This step allows us for the monomer solution to start diffusing onto the whole cell surface of the coverslip before the gel polymerization.

23. For two drops of 35 μl on the glass slides, consider these quantities:
    - 90 μl of monomer solution (Sodium acrylate, Acrylamide and Bisacrylamide)
    - 5 μl of 10% TEMED, for a final concentration of 0.5%, to be then vortexed
    - 5 μl of 10% APS, for a final concentration of 0.5%, to be then vortexed

24. Put the drops on the the glass slides. Trying to be as fast as possible, since the polymerization process starts as soon as you put the the TEMED, take the cell slides (with the cell side facing the gel) and put them on top of the gel.

25. **Pause Point** Leave them to incubate in a humidified chamber at 37°C for 1 h. The gels can be left overnight at fridge in the humidified chamber.

### **Denaturation**

26. Prepare the denaturation buffer recipe for stock solution: 200 mM SDS (Sodium dodecyl sulfate), 200 mM NaCl (Sodium chloride), 50 mM Tris. Adjust pH to 9. Taken from [Ku et al., *Nat Biotechnol* 34 (2016)](https://www.nature.com/articles/nbt.3641#citeas).

27. **Detachment** - detach the gels from the glass slide by placing them in hot denaturation solution in a 12 well plate. Transfer the gel to an eppendorf tube filled with denaturation solution (pre-heated at 95°C) for 1h and a half.

    To remove the gel and coverslip from the slide, use a scalpel and place the tip between the gel and the slide. Twist the scalpel to pop off the gel and coverslip and transfer these into the well of the 12 well plate.

28. Take the gel out of the Eppendorf of denaturation media and put them in bigger 50mL tubes with water.

    In order to wash them thoroughly of the denaturation media, wash them at least twice for 20 minutes.

29. After they expand, take them out of the water tubes and gently slide them on to a glass surface to cut them[^8].

    After a good enough number of cuts, we place all the little circles we made in a bigger well (6-well plate).

    We can even measure the diameter of the full expanded gel circle to confirm the 4x expansion (i.e. if the initial diameter was 12 mm, now it should be around 48 mm).

30. **Pause point** Cover the cut gel pieces with PBS (3mL for each well). Add also sodium azide for a total concentration of 0.1%.

    Since this process will take a while for all the samples, we won't have to wait further, since by the time we are finished the gel pieces will have shrunk again.

## **IF STAINING**

Whenever we want we can prepare the gel for imaging with immunofluorescence. We will apply the following protocol:

- Both primary and secondary antibodies are put in the same **blocking solution**, i.e. 3% BSA in PBS (for example. 300mg in 10mL of PBS, to be well centrifuged for good mixing).

- For the primary antibodies that we used, i.e. GFP (Rabbit), α-Tubulin (Chicken) and an intermembrane mitochondrial protein (Mouse), we put always a 1/100 dilution (10 μl for 1mL).

Then we follow this protocol:

1. **Primary antibodies staining** → Put 250 μl of blocking solution + primary antibody in each 2mL Eppendorf tube and put the gel inside[^9].

2. **Pause Point** Leave overnight at RT to be shaken.

3. **Secondary antibodies staining** → We can follow the product protocol for the secondary antibodies staining at the desired wavelength.

   In our case, Matt conjugates fluorophore to his secondary antibodies, and used them at a final concentration of 5 μg/ml for the following wavelengths:
   - Anti-Goat for the GFP - Star635p
   - Anti-Mouse for the MTCO1 - CF568
   - Anti-Rabbit for the αTUB - AlexaFluor488

## SAMPLE MOUNTING FOR IMAGING

### **Sticky coverslip preparation**

To avoid possible drift of the gel slides or any possible deformation caused by the shrinking of the gels, we would put our samples on sticky coverslips (this protocol has been adopted by tissue preparation and imaging protocols).

- Take a sufficient amount of glass 25 mm slides and place it in a coverslip container.

- Three washes for up to 4/5 minutes each: first water, then ethanol (to be shaken in the sonicator) and then methanol with 1:40 dilution of APTES (to be shaken in the sonicator, but not more than a minute).

- Dump it one last time in the water to remove all the residues and then dry them on a tissue inside a cover.

### **Post fixation**

After the staining, we can put the samples in 50ml tubes filled with water as the final wash for half an hour. We can then post-fix the samples by putting them in a 6% PFA water solution for ∼ 30 min. The post-fixation improves antibody retention, allowing us for a better imaging over the next days.  
Since we use a 6-well plate, we will put 2 ml of solution for each well. Moreover, be careful to prepare the appropriate amount starting from the product concentration. For example in our case, since we had to prepare 8 ml of solution with a 32% PFA solution, we put 1.5 of the latter and 6.5 ml of water.

**!!** All the steps involving PFA are to be made with gloves under the fume hood, as always.

After this, we can put the samples back into 50 ml water tubes.

### **Pre-check at the microscope**

The last important step of our protocol consists in identifying the gel surface with the cells - since the gel thickness is too much to still be able to image if it doesn't touch the coverslip.  
In order to do that we use a uncoated glass 25 mm coverslip in which we put our sample. For imaging, we use a metal holder that keeps us the coverslip in place. If you don't manage to see the cells, then flip the gel with a brush and you should be able to see them.

After knowing the right side, you can place the gel onto the sticky coverslips and place them in the 6-well plate with 2 ml of water.

### **Imaging**

For the imaging part, take the coverslips with the gel on top from its well and place it into the metal holder. Use the same water for the well to completely submerge the gel in the holder as well to minimize further changes in the gel size. At this point, everything is ready for imaging.

**!!** Once done with the imaging, pay attention to cleaning the bottom of the coverslip from any oil residue before putting it again into the water well. Since they are not in PBS, the samples degrade pretty fast, so you have to image them in the immediately following days after staining, without waiting for more than necessary.

---

[^1]: In order to keep the acetone dry, we collect the desired quantity with a syringe - remember always to inject the same amount of air first, in order not to create a vacuum in the liquid container. **!!** Freezing temperature of acetone is -90°, so right now it is in a liquid state.

[^2]: Do this with a slightly inclined angle to maximise the contact surface the glass slide will encounter afterwards.

[^3]: To reach the desired temperature fill up the inner cup with liquid nitrogen, then wait for it to evaporate, then fill it another time, and wait again. In the outside cup instead, always maintain the same level of liquid nitrogen. For the ethane gas pouring, be careful to put the tip closest to the metal surface (which is the coldest) and move it uniformly on the surface, as to spread homogenously the gas condensate.

[^4]: In our case, put a tape at the attachment of the tweezer for further stabilization.

[^5]: Pay attention to the lid. Since it could explode during the changing temperature, the advice is to open the lid and close it just enough to cover the contents.

[^6]: **Traditional protocol**, from [Gambarotto et al., *Methods in Cell Biology*, 161 (2021)](https://doi.org/10.1016/bs.mcb.2020.05.006) → The traditional protocol uses another anchoring solution made up of 0.7% Formaldehyde (FA) and 1% Acrylamide (AA) in PBS (so no washing is needed) to be left at 37°C for 5 hours. Since the products usually have a ∼37% concentration for FA and 40% for AA, it is advised to pay attention to the right quantities. In particular the used products are:
    - Formaldehyde (FA, 36.5–38%, F8775, SIGMA)—Ready to use—Store at RT
    - Acrylamide (AA, 40%, A4058, SIGMA)—Ready to use—Store at 4 °C.

    Moreover, when using FA, always work under the fume hood, and dispose of the solution accordingly. Since both the FA and the AA are quite viscous, pay attention to pipette slowly as well. Centrifuge afterwards for good mixing.

[^7]: We start from a bicarbonate solution of 1 M so we need to dilute 1:10. Calculate the final amount based on the number of glass slides (consider at least 1 ml to cover each well).

[^8]: Everyone has their own method for cutting them. For example, we use the top of a 5mL Eppendorf as a cutter, placing it on the wanted position with the help of tweezers.

[^9]: Do this step as delicately as possible, helping yourself with a thinner brush, in order to be sure that the gel is completely submerged in the antibody solution.
