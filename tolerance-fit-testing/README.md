# SolidWorks to 3D Print — Tolerance & Fit Testing

## Project Overview

I created this project to see how the tolerances and clearances I designed in SolidWorks would translate to actual 3D-printed parts.

The main goal was not to create a complicated part. I wanted a simple physical test that would let me compare the dimensions I modeled in CAD with how the parts actually fit after printing. This gave me a better understanding of how small dimensional changes can make the difference between a fit that is too tight and one that can move as intended.

🎥 **[Watch the Tolerance & Fit Test on YouTube](https://www.youtube.com/shorts/eJ8chKEDIlw)**

## Test Process

I modeled test geometry in SolidWorks using different clearances between the mating features. I then 3D printed the parts and physically tested how each clearance affected the fit.

My process was:

1. Model the test parts in SolidWorks.
2. Test different clearances between the mating features.
3. Export and 3D print the test pieces.
4. Physically test how the parts fit together.
5. Compare the results and adjust the clearance based on what I observed.
6. Print and test the revised design again.

## Results & Iteration

I first tested **0.05 mm and 0.10 mm clearances** to see how the difference translated from SolidWorks to the physical 3D-printed parts.

- **0.05 mm clearance:** very tight fit
- **0.10 mm clearance:** more movement than I wanted

Instead of stopping with those two results, I tested intermediate clearances to narrow down the fit. I found that a **0.07 mm clearance produced the fit I was looking for — snug, but still able to move without being excessively tight.**

This was useful because it showed me how even a few hundredths of a millimeter in the CAD model could noticeably change the fit of the printed parts. The testing process gave me experience using physical results to refine a CAD design instead of assuming the first dimensions would work.

These results are specific to the parts, printer, material, and print settings I used for this test, but the process gave me a practical reference for similar parts printed under the same conditions.

## What I Learned

This project helped me understand that the exact dimensions in a CAD model do not automatically produce the same type of fit in a physical 3D-printed part. Printer accuracy, material behavior, layer deposition, and other manufacturing variables can affect the final dimensions.

More importantly, I learned to use an iterative approach. I compared multiple clearance values, used the physical results to narrow the range, and tested again. The **0.07 mm** result gave me the snug movable fit I was trying to achieve.

Instead of assuming a clearance would work, I was able to **design → print → test → adjust → reprint** and use the result to guide future SolidWorks designs.

## Skills Demonstrated

- SolidWorks part modeling
- Dimensioning and clearances
- 3D printing
- Tolerance and fit testing
- Physical prototyping
- Iterative design and testing
- Design for additive manufacturing
- Comparing CAD intent with manufactured results
- Using physical test results to refine a design

## Project Takeaway

This was a small project, but it was useful because it connected CAD design directly to manufacturing. Finding the final **0.07 mm clearance** required me to compare multiple printed fits and refine the design based on the physical results. It showed me how small dimensional changes in SolidWorks can affect real 3D-printed components and why testing and iteration are important when designing parts that need to fit together.

## SolidWorks CAD Files

The original SolidWorks part files from the tolerance testing are included so the different modeled clearances can be reviewed directly.

- **[0.05 mm Clearance Test](coupler%20to%20base%20test%20with%20.05%20tolerance.SLDPRT)**
- **[0.07 mm Clearance Test — Selected Snug Fit](coupler%20to%20base%20test%20with%20.07%20tolerance.SLDPRT)**
- **[0.09 mm Clearance Test](coupler%20to%20base%20test%20with%20.09%20tolerance.SLDPRT)**
- **[0.10 mm Clearance Test](coupler%20to%20base%20test%20with%20.1%20tolerance.SLDPRT)**

These files show the CAD variations used during the physical fit-testing process.