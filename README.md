# Packaging-Workshop

VSD - Packaging Workshop


## Packaging Evolution: From Basics to 3D Integration

### Introduction To Semiconductor Packaging And Industry Overview

**Semiconductor Packaging: Purpose and Importance**

Semiconductor packaging plays a pivotal role in transitioning fragile silicon dies—fresh out of controlled foundries like TSMC or Intel—into robust components capable of surviving real-world environments.


**Packaging ensures:**

•	**Environmental Protection:** Shields dies from corrosion, moisture, and mechanical damage.

•	**Electrical Connectivity:** Enables integration into electronic systems via structures like Ball Grid Arrays (BGA). For instance, the iPhone 15’s logic board houses chips from Broadcom, SK Hynix, and Texas Instruments—all packaged for durability and compatibility.


**Core Components of a Semiconductor Package**

•	Molding Compound:

Encapsulates the die and wire bonds in epoxy resin, offering structural protection and resistance to moisture and contaminants.

•	Substrate:

Acts as an intermediary between the die and PCB, housing metal traces and vias for signal routing and mechanical support.

•	Die Attach:

A thermally conductive adhesive or solder that anchors the die to the substrate while enabling heat dissipation.


•	Wire Bonds:

Fine wires (gold, copper, or aluminum) that form electrical paths from the die’s bond pads to the substrate.

•	Traces:

Embedded metal lines within the substrate that transmit signals to the package’s external interfaces.


 
![image](https://github.com/user-attachments/assets/a3d82832-a7a5-4319-a958-650f33491a5e)


Once dies are separated from wafers, packaging and rigorous testing ensure their readiness for integration, thermal control, and reliable electrical connection.

 
![image](https://github.com/user-attachments/assets/c769a439-0241-450e-8ec1-d8447dfc6ef2)




### Understanding Package Requirements And Foundational Package Types




![image](https://github.com/user-attachments/assets/b1984a5f-5c44-41ae-93cd-44ed0759203a)
 

 **The Hierarchy of Electronic Integration**

From chip to package to board, packaging bridges functional silicon with practical systems. Choosing the right package depends on:

-	Application type (e.g., logic, memory, power)

-	Size constraints and form factor

-	Reliability and longevity

-	Cost-efficiency

-	Thermal performance

-	Number of I/O pins (pin count)

These factors ensure seamless integration and peak system efficiency.




![image](https://github.com/user-attachments/assets/54a52b2f-0ef9-4792-b777-a0e6b295fb2b)

 



![image](https://github.com/user-attachments/assets/16d4d7e5-1d0b-437a-9661-ea94b2e51bb1)






### Evolving Package Architectures - From Single Chip To Multi-Chip Modules


**1. Through-Hole Mounting (THM):**

Utilizes leads inserted through PCB holes. Offers sturdy mechanical anchoring—ideal for prototyping.

-	**DIP (Dual In-line Package):** Classic dual-row format.

-	**SIP (Single In-line Package):** One row of pins, often used for resistor arrays.
-	**TO (Transistor Outline):** Metal-can design for thermal efficiency.

 -**PGA (Pin Grid Array):** Dense grid of pins for high I/O, often seen in CPUs.


**2. Surface Mount Technology (SMT):**

Packages mounted directly onto PCB surfaces, allowing compact designs and automated manufacturing.

-	**QFN / QFP:** Flat packages with side or bottom leads.

-	**PBGA / LGA:** Grid-based or flat contacts for higher pin counts.

-	**CSP:** Ultra-miniature packages nearly die-sized.

- **PoP / MCM / CoWoS:** Multi-layer and 2.5D stack options enabling complex system integration.



 ![image](https://github.com/user-attachments/assets/9e6d916c-ffc9-4a6d-bf0c-2f0a7249d987)




**Anatomy of Packages:**

**Advance Package Substrate**

To integrate multiple dies, packaging may include intermediary layers:

-	2D: Two dies mounted on the substrate with ball-grid connections.

-	2.1D: Adds a Redistribution Layer (RDL) to improve routing speed.

-	2.3D: Introduces an organic interposer with multiple layers to support dense I/O.

-	2.5D: Employs a silicon interposer for higher speed and bandwidth.

-	3D: One chip stacked atop another for extreme integration.

Carrier Substrate Options:

-	Leadframe (DIP, QFN)

-	Laminate (multi-layer PCBs)

-	Ceramic, Plastic, Organic RDL, Silicon, or Glass


**Interconnection Technologies:**

-	**Wire bonding:** Loop stitching wires to connect die to substrate.

-	**Bump/Solder:** Direct die-to-substrate connection using solder bumps.

 


![image](https://github.com/user-attachments/assets/15170cab-05db-440f-a9c8-74cd2c8d77a8)






###   Interposers Re-distribution Layers And 2.5D/3D Packaging Approaches



![image](https://github.com/user-attachments/assets/4ad7e0a9-d899-4cc9-9206-edbf83edc722)




### Comparative Analysis And Selecting The Right Packaging Solution


**Comparative Packaging Evaluation**

-	On the lower end of the complexity/cost spectrum: DIP and QFN—cost-effective and easy to assemble but larger in size.

-	Toward the higher end: CSP, PoP, CoWoS—compact, higher I/O density, better performance, and more expensive.


![image](https://github.com/user-attachments/assets/c6d1c7f0-7958-4b33-8562-ea09321e048b)

 

Next steps are to know how to choose the correct package as per the requrements


![image](https://github.com/user-attachments/assets/622ebc2b-490b-4bfb-a05a-9902d068c717)





## From Wafer to Package: Assembly and Manufacturing 

### Setting The Stage - Supply Chain And Facilities


**ATMP: Assembly, Testing, Marking, and Packaging**


This post-manufacturing phase includes:

-	Die assembly into protective packages

-	Functional testing to screen out defects

-	Marking for product traceability (e.g., part numbers, batch IDs)

-	Packaging to shield the die and form external electrical interfaces


![image](https://github.com/user-attachments/assets/45d96502-692f-45a1-aa49-652ff73c73f5)

 
**Types of Manufacturing Facilities**

- Integrated Operations: Some companies handle packaging and testing within their own facilities, enabling tight quality control, intellectual property protection, and streamlined logistics.


-	Outsourced Providers: Specialized third-party manufacturers support both design-centric and vertically integrated companies by offering scalable services for assembly and testing.


**Cleanroom Environments**

 
- Operations are conducted in cleanrooms to minimize particle contamination and maintain precision.


-	Cleanroom classes (e.g., Class 1000) and ISO standards (e.g., ISO 6) define maximum particle thresholds and air cleanliness requirements.


-	These environments are especially important during processes like bonding, molding, and optical inspections.


![image](https://github.com/user-attachments/assets/af739f9b-0b88-4d11-ae43-7e10c87c2239)








### Wafer Pre-Preparation - Grinding And Dicing


Wafer Preparation Process (Cleanroom-based)

•	Receiving

•	Inspection

•	Front-Side Lamination

•	Back Grinding

•	Tape Frame Mounting

•	Dicing

•	Laser grooving 

•	Blade dicing 


 
![image](https://github.com/user-attachments/assets/3168fc94-0029-4e49-8a0b-79af3e91fbae)





### Wire Bond Packaging - Die Attach To Molding


1.	Die Attach: Die is fixed onto a carrier using conductive adhesives or solder materials for heat transfer and mechanical stability.

2.	Curing: Adhesive is hardened via heat or UV to solidify the attachment.

3.	Wire Bonding: Fine metal wires link die pads to package terminals using heat and ultrasonic bonding.

4.	Molding: A protective resin encapsulates the die and wires.

5.	Marking: Identification is added using laser or ink printing.

6.	Singulation: The molded panel is sliced into individual units for final test and distribution.


 
![image](https://github.com/user-attachments/assets/8773fd79-273b-471c-a60b-a63a707844b7)






### Flip Chip Assembly - Bump Formation And Underfill


1.	Bump Formation: Solder bumps are added to the die through dielectric patterning and metal deposition, followed by reflow.

2.	Flux Application: Flux is dispensed to ensure clean contacts between the die and substrate.

3.	Die Placement: The die is flipped and aligned with the substrate. Thermal compression bonds the bumps.

4.	Underfill Dispensing: Fills the gap between die and substrate to minimize mechanical stress.

5.	Curing: The underfill is hardened to strengthen the package.

6.	Final Steps: Molding, marking, and ball-grid connections follow as with wire bond packages.


![image](https://github.com/user-attachments/assets/29e60eea-4416-4b8f-a17c-ae432aef3089)

 


### Wafer Level Packaging And Conclusion

 
1.	Reconstitution:

   -	Known-good dies are placed on a temporary carrier.
   
   -	A mold compound encapsulates them to form a reconstituted wafer.
   
   -	The carrier is removed, revealing a planar structure for processing.


2.	Redistribution Layer (RDL) Formation:

   -	Multiple layers of dielectric and metal are added for signal routing.
   
   -	Vias and interconnects are patterned to redirect the die’s input/output terminals.
   
   -	Solder balls are added atop the RDL.

3.	Singulation: The wafer is cut into individual packages, each combining die, routing layers, and external connections.





![image](https://github.com/user-attachments/assets/f80b3b2f-9d62-41a6-8150-804f3153cfd0)

 

![image](https://github.com/user-attachments/assets/89ead636-4e17-473e-961d-ee1249eb07d5)




## LAB1: Thermal Simulation of Semiconductor Packages with ANSYS 

### Introduction And Getting Started With ANSYS Electronics Desktop

Instal ANSYS Electronics Desktop software. Then open Ansys EDT tool. 
If you cannot see all design file types. Go to tools -> Options -> General Options -> Desktop Configuration ->  ‘Set target configuration’ as ALL 


 ![image](https://github.com/user-attachments/assets/2c9f89e1-2a7c-4efc-8f31-12e046e01fd9)



Open / click on Icepak tool

 
![image](https://github.com/user-attachments/assets/ceabd390-2170-4dc1-8d40-d12cd022e69f)


Here, a Finite analysis is performed. So, a 3D model is made for thermal analysis where thermal flow is monitored using FlipChip BGA Package.

To import a Icepak FlipChip BGA Package, go to tool kit and packages as shown below

 
![image](https://github.com/user-attachments/assets/6687c2a5-c4a2-4a27-9f65-a62188b9ce58)



### Setting Up A Flip-Chip BGA Package

The FlipChip BGA Package details are as below 

![image](https://github.com/user-attachments/assets/ec6fe130-a1e8-41af-928e-d25fc81dd92f)

![image](https://github.com/user-attachments/assets/e59259c0-88ab-480f-a487-430c7c95b672)

![image](https://github.com/user-attachments/assets/1d6f8972-2c9c-41ee-b031-056aea4bfdae)

![image](https://github.com/user-attachments/assets/5f3345a2-bb8f-484d-b2bf-51270a8baac9)


As the thermal analysis is done trough Icepak, a power source is given to the chip, which helps in observing the power distribution. Here, a silicon type material is used with Bump size 0.01mm 

![image](https://github.com/user-attachments/assets/9896de7c-b056-4ffd-9e6e-c37757ffb8be)


![image](https://github.com/user-attachments/assets/1e31990f-cc7c-4501-8f2e-4b19df39678e)



### Material Definitions And Thermal Power Sources

The Icepak model using here: 

FlipChip BGA Ball group

 ![image](https://github.com/user-attachments/assets/2a9a9905-278f-4b47-9cb8-726d8f8241bc)

FlipChip BGA Substrate

![image](https://github.com/user-attachments/assets/7b49d9d2-5970-4cee-8743-1ba76655f4ee)

 

FlipChip BGA Die Underfill 

 ![image](https://github.com/user-attachments/assets/52727e9b-850f-4221-9dbd-74569f31b8c1)


FlipChip BGA VIA

![image](https://github.com/user-attachments/assets/d1beb50f-901c-40a2-b965-282c88174ad5)
 

FlipChip BGA Die
 
![image](https://github.com/user-attachments/assets/4636e5fc-54d9-456f-a49c-6fd4fe6b8fcf)


Now, Thermal conditions are given to the chip. To add thermal conditions go to Icepak -> Thermal -> FlipChip BGA1_Die_source and add thermal condition as shown.
 
![image](https://github.com/user-attachments/assets/5924c09b-024b-4dd3-b5c8-bf4a695a715e)


Die source on the chip

![image](https://github.com/user-attachments/assets/16296252-5091-4f50-b3f0-0a1bfc3c7c0c)
 


For boundary conditions, a source is added to the package, the process to add thermal condition and the values are added as shown
  

![image](https://github.com/user-attachments/assets/d8670b1f-6445-487d-a8cb-dfcbc80b87dc)

![image](https://github.com/user-attachments/assets/777d65c5-02f0-49b8-bcfb-e6b158c0232c)


As there is a warning of source and boundary source overlap, boundary source is deleted.

![image](https://github.com/user-attachments/assets/f84f5a3d-420a-40b1-a542-5f0f542161a6)
 

The next step is to add monitors to Substrate, Die and Underfill. 
 

 ![image](https://github.com/user-attachments/assets/7b865ad1-f16f-43e4-82f5-1afe5a6432ea)


 ![image](https://github.com/user-attachments/assets/7499890c-6651-4b9f-8cc4-04bd1e56096a)


![image](https://github.com/user-attachments/assets/d3309acb-7723-4369-9fce-c8d67c28cbad)




### Meshing And Running The Thermal Analysis

Now, Mesh is added to the packaging. 
 
![image](https://github.com/user-attachments/assets/b7fc9038-656b-4cc1-a52c-7b7ef62274da)


Now when mesh is generated, there is a ‘Mesh Visualization’ tab pops up, here in quality tab parameters like Face alignment, Skewness and Volume can be observed. 

![10d- maesh Volume](https://github.com/user-attachments/assets/9c354959-e62d-4353-9499-d26a29abc05e)
![10c- maesh skewness](https://github.com/user-attachments/assets/2e381035-172d-452e-becf-04fe2308c887)
![10b- maesh face alignment](https://github.com/user-attachments/assets/964bbeaa-caaf-4e3c-aebd-26b820f9ca43)



For doing Analysis, a solution step is added with default settings
 
![image](https://github.com/user-attachments/assets/a8714544-e04d-48ab-8722-77ff5e6cc7e8)


At the top in simulations, click the ‘Validation’

![image](https://github.com/user-attachments/assets/d9c563e9-d105-4311-a8af-2cba3d444a76)

 
Validation only verifies that all checks are there in the design, it will not analyse the design. 

As, there is a warning for Underfill have no mesh region, it is added manually. When a mesh added manually, there are errors seen 

Mesh region adding manually process and its setting are as below:
  
 ![image](https://github.com/user-attachments/assets/8570a50d-41f5-48d2-9382-3e0f40402d78)

![image](https://github.com/user-attachments/assets/f059afea-513d-4a4c-a76a-5da5a43c18a1)


The ‘Validation’ is re-run
 
![image](https://github.com/user-attachments/assets/9734ad3d-f34d-4d42-b0f4-fe6babb5b02a)


### Viewing Results And Exploring Other Package Types

Now, when ‘Analyze All’ is performed, now errors are seen due to manually added mesh region for Underfill region. 

![image](https://github.com/user-attachments/assets/5913b394-6d9d-44db-b715-929c4cc26703)


So, to resolve the errors seen, the newly added mesh region is deleted. Then, Mesh generation process is re-performed to make sure there are no errors with it.

![image](https://github.com/user-attachments/assets/f888be95-e830-4515-a438-ed713c35327c)
 


Now, ‘Validation’ and ‘Analyze all’ are performed and observed that errors are resolved.

 ![image](https://github.com/user-attachments/assets/bb7cd5ad-1091-4d84-8e42-2db9485b24a0)


Now, that Analysis is done. Next step is to plot the thermal plots. For that select the whole package, then right click -> Plot fields -> Temperature -> Temperature 

It opens a ‘Field plot’ tab

![image](https://github.com/user-attachments/assets/701a40b8-c439-48e0-9617-b29ff3effd3b)

 
In ‘Surface smoothing’ tab enable the Gaussian.

Now, Thermal plots are generated on the FlicpChip BGA Package
 
 ![image](https://github.com/user-attachments/assets/8d23848f-bbbb-4be7-8ff1-5d3308b7555f)


Here, the transition of thermal flow on the package from Substrate to Die and pins is analyzed.  

![image](https://github.com/user-attachments/assets/d49906e1-0309-4359-86fd-129ba34db0cd)


## Ensuring Package Reliability: Testing and Performance Validation



### Introduction to Package Testing and Electrical Functionality Checks


 
![image](https://github.com/user-attachments/assets/ad645a17-5e8f-4691-b561-ca8b835f964c)



 ![image](https://github.com/user-attachments/assets/18a4e93d-da7c-4a87-81b9-9631c8dd970a)


![image](https://github.com/user-attachments/assets/c97bf4a4-c40e-47d1-ba22-944f17979438)



 



### Reliability and Performance Testing of Semiconductor Packages
 

![image](https://github.com/user-attachments/assets/725734df-4507-40bd-b63d-274f4eb8c7d8)


 
![image](https://github.com/user-attachments/assets/fa7abbf8-520e-4cad-8a67-5156d5341944)




![image](https://github.com/user-attachments/assets/08a45c0c-b631-43c6-a112-bdf6420ace86)


 






## LAB2: Package Design and Modeling: Building a Semiconductor Package from Scratch 


### Introduction to Package Cross-Section Modeling in ANSYS Electronics Desktop (AEDT)


The process to make a Package Design:
 
![image](https://github.com/user-attachments/assets/c1111e5b-cee6-439c-b402-71dcb83c4d56)


In previous lab, a Thermal performance and electrical analysis is seen. Here in this lab, a Package cross- section is performed.


### Creating the Die and Substrate in AEDT


Open Ansys EDT tool and Insert an Q3D Extractor Design from the tools.

![image](https://github.com/user-attachments/assets/576cb400-a7e5-46c3-892b-d1a20a3f5f5d)

 

The first step is to create a *Die*
To create a Die, go to draw and select ‘Rectangle’. Make a rectangle / square shape from the origin. Here, a *3mm x 3mm* Die is being created.


 ![image](https://github.com/user-attachments/assets/9a31c418-6a0f-4d3f-8672-fbdab65c659f)


To verify the Die is on 3mm x3mm, click on ‘create rectangle’ -> right click on Properties.


 ![image](https://github.com/user-attachments/assets/f8a8340b-ce8c-415e-94b3-ffd2d4a51a16)



In properties, Origin, X-Size, y-Size can be edited according to the preferences. 

As of now, the Die is on 2D design and to have a 3D design, Thickness needs to be added.


![image](https://github.com/user-attachments/assets/10319b32-7957-4d2e-87e9-7e64d52576a6)


 

Select the rectangle, then go to Modeler -> Surface -> Thicken Sheet select. 
Here a thickness of 0.2mm was given to the Die.


 ![image](https://github.com/user-attachments/assets/f0f6ee5c-6d67-4722-a070-d16f02e52a17)



Now, the Rectangle is re-named as Die for easy understanding. Also, the *Die* material is selected as *Silicon*
 

![image](https://github.com/user-attachments/assets/bba56131-0118-4910-a565-6fbf1f23a048)



By following the same steps, a *Substrate* of *5mmx5mm*is created  with origin (-1,-1,0)


 ![image](https://github.com/user-attachments/assets/7cb9b4ff-dce4-4464-b360-a8d77dda03f2)



Material of Substrate used here is *FR4_epoxy*


![image](https://github.com/user-attachments/assets/18ea2dfb-3e27-4629-b409-e6fad1e362d4)

 

Now, Thickness is added to the substrate (0.5mm)
 

![image](https://github.com/user-attachments/assets/2417aab9-0a3d-44cb-957b-da1392445ec6)



As, it can be seen that Die gets hidden inside the substrate, the thickness of Substrate is changes to negative axis
 

![image](https://github.com/user-attachments/assets/4f04e6d5-9e68-40c8-88b5-23895526df86)



Now, both Substrate and Die can be seen in 3D.
 

![image](https://github.com/user-attachments/assets/533f1cc5-9ec7-439e-9d85-4d61b7dddbf8)



As Die is not going to sit directly on the substrate, an epoxy is added between a Die and a Substrate. This was Die and Substrate are attached trough the *Die Attach* film / material added.  


### Adding Die Attach Material and Bond Pads

As *Die Attach* is to be added between *Substrate* and *Die*, *Substrate* origin is moved to (-1, -1, -0.1) from (-1, -1, 0)

Now, there is space created between *Substrate* and *Die*


![image](https://github.com/user-attachments/assets/3013ae54-19b3-4a77-8647-559e5b4fa6b0)

 

Another rectangle is created from the origin (0,0,0) for *Die Attach* with the size same as die *3mmx3mm*


![image](https://github.com/user-attachments/assets/e356141b-f6bf-4279-83c9-0fc21e8042ff)

 

Placing it at the Origin (0,0,0)


 ![image](https://github.com/user-attachments/assets/307111a7-77b9-4f67-988c-30135cc49875)



The *Die Attach* thickness is added as *0.1mm* but in negative axis to fit it between Die and Substrate.


![image](https://github.com/user-attachments/assets/4de968f8-d781-4db5-b574-d4d1774d2106)

 

The Die Attach material is selected as *modified_epoxy*
 

![image](https://github.com/user-attachments/assets/6e4b080a-8377-4b44-a3cd-561a4068a26b)



Optional: Just to understand or to see the 3 Solids – Die, Die Attach, Substrate – Changing the colors of them. 


![image](https://github.com/user-attachments/assets/ab97c8fd-aa10-482f-b6b3-6aa3994918c0)

 

The next step here is to add Bond pads on Substrate and Die then attach those bond pads with a wire bond. 

To create a BondPad on Die, select a rectangle and draw a small rectangle on corner of the die.  Edit the Position of the *DieBondPad* as Origin (0.2, 0.2, 0.2) to keep the BondPad on top of the Die, with X-Size 0.2mm and Y-Size 0.2mm. 

The Bond Pad on the Die is a 2D material, a *0.005mm* of Thickness is added to it.


![image](https://github.com/user-attachments/assets/fa045f9b-e8da-4310-8b33-700f1e7699c6)

 

Same process is followed to create a *SubstrateBondPad* with the properties of X-Size 0.2mm and Y-Size 0.2mm. Origin on the SubstrateBondPad is (0.2, -0.8, -0.1)

Thickness of it is made as 0.010 mm

 
![image](https://github.com/user-attachments/assets/7cd7c99c-f8e1-450c-ace3-888beaa9bf9f)



### Wire Bond Creation and Material Assignment

To create a Wire Bond between *DieBondPad* and *SubstrateBondPad*, Select a wire bond option, Place it at the center of DieBondPad and then at the center of SubstrateBondPad. 

A BondWire properties tab opens up, there are different types to connect both bond pads, also the height can be edited as per the requirements. 
Here, the default measurements are taken with *JEDEC 4-Point* wire bond type, when clicked on OK, a wire bond is created. 


![image](https://github.com/user-attachments/assets/6fb8999b-0d7c-415d-9ae5-bb877cfa09aa)

 

The Wire should be able to bend, so we make the bond wire material as *Gold*

Same steps are followed to create a bond pads on over all Die and Substrate

 
![image](https://github.com/user-attachments/assets/1c6cdf1d-41b3-4c86-9020-b82bdb268961)



### Applying Mold Compound and Finalizing the Package Mode
Mold compound is going to be placed on the substrate covering the whole design. 

To understand the amount of thickness needed for the mold compound, Packaging thickness is calculated, here Substrate is 0.5mm, Die Attache is 0.1mm and Die is 0.2mm which comes to 0.8mm thickness, but here when observed the wire bonds in 3D, it can be seen that they are going above the Die so from H1 H2 values, approx. of  0.4mm of wire bond height is taken. 
The total Thickness comes to 1.2mm and the thickness about the substrate is 0.7mm. 

To create a mold compound, create a rectangle and place on the substrate to cover the whole substrate, which will be 5mm x 5mm. 

Properties of the mold will be Origin (-1, -1, -0.1) with X-Size 5mm and Y-Size 5mm. 
 


![image](https://github.com/user-attachments/assets/53136644-fa2f-4be4-8ca7-fbe6e39bc897)

 

![image](https://github.com/user-attachments/assets/61656d7c-0e7d-4fdf-8e83-63676615d0a9)



Thickness of *1.2mm* is added to the mold compound and material of it is assigned as epoxy_kevlar_xy 

Here the thickness is added to the mold compound is more the thickness calculated because at the end of packaging a laser etching will be performed which will etch some part of the mold compounds, so to make sure the wire bonds are not effected due to that, more thickness is added.
 

 ![image](https://github.com/user-attachments/assets/6b3887e8-064e-4fc6-8f52-1a0ae324a004)



FINAL Design 

 

![image](https://github.com/user-attachments/assets/191228b2-a32d-4731-a500-f934886e63d7)

 
![image](https://github.com/user-attachments/assets/f99e29f0-7e7a-4d1d-8172-f8acaec3750f)


 

![image](https://github.com/user-attachments/assets/39eb16cd-8130-479f-917c-4cd1df74f319)

 

 ![image](https://github.com/user-attachments/assets/261eb5c0-ddf9-4738-8861-bd463351ff2e)



![image](https://github.com/user-attachments/assets/ad04042e-e957-4722-b93d-9f59a38da92a)



### Conclusion
 - From this workshop, I have learn about the process to perform thermal analysis on a package.
 - Also, had an experience to do a cross-section packaging process from the scratch.

   
## 6. Acknowledgements
 - Tarun Kumar Agarwal, Faculty in Dept. Electrical Engineering, IIT Gandhinagar.
 - Kunal Ghosh, Co-founder (VSD Corp. Pvt. Ltd)



