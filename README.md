``Magnetization, Permeability, and
 Susceptibility in Medical Imaging
 1. Introduction
 Magnetic Resonance Imaging (MRI) is a key medical technology that produces high
resolution internal images without using radiation. Its operation depends on how matter
 interacts with magnetic fields—specifically through magnetization (M), magnetic
 permeability (μ), and magnetic susceptibility (χ).
 These properties determine image clarity, safety, and the ability to distinguish tissues.
 Engineers and clinicians use them to design precise scanners and interpret images
 accurately.
 2. Background
 MRI employs a strong static magnetic field, typically 1.5 – 3 T, to align hydrogen nuclei in
 the body. A radio-frequency (RF) pulse disturbs this alignment, and as the nuclei relax,
 they emit measurable signals.
 Differences in magnetic behavior among tissues create image contrast. Field stability and
 material choice in MRI systems depend on the magnetic parameters explained below.
 3. Magnetization (M)
 M=χH
 Magnetization is the net magnetic moment per unit volume caused by an external
 magnetic field. In MRI, it represents the alignment of nuclear spins that generate the
 detectable signal.
 Application: Stable, uniform magnetization maintained by superconducting magnets
 ensures clear images. For example, in brain scans, consistent M prevents signal loss and
 distortion.
4. Magnetic Permeability (μ)
 B=μH,μ=μ0 (1+χ)
 Permeability shows how easily magnetic lines of force pass through a material. Biological
 tissues have permeability close to free space, but MRI hardware uses materials with
 specific μ values.
 Application: Scanner rooms use mu-metal shielding to block outside magnetic noise.
 Gradient coils are built from low-loss materials with stable μ to maintain field linearity.
 5. Magnetic Susceptibility (χ)
 χ=H/M 
Susceptibility measures how strongly a material becomes magnetized.
 Diamagnetic (χ < 0): Water, fat—weakly repelled.
 Paramagnetic (χ > 0): Blood with deoxyhemoglobin, contrast agents—weakly attracted.
 Ferromagnetic (χ ≫
 1): Iron, steel—unsafe in MRI.
 Application: MRI contrast depends on χ variations. Functional MRI (fMRI) tracks small
 susceptibility changes linked to blood oxygen levels. Gadolinium agents locally alter χ to highlight
 tumors.
6. Relation Between M, μ, and χ
 B=μ0 (H+M)=μ0 (1+χ)H=μH
 These parameters are interdependent. Accurate modeling of their relationship helps
 maintain field uniformity and image accuracy. Engineers use them when designing coils,
 magnets, and shielding.
 7. Real-Time Example
 Modern MRI scanners apply AI-based correction to counter field distortion caused by
 susceptibility differences near air cavities or metallic implants. Adjusting gradient fields
 in real time improves anatomical precision in cardiac and brain imaging.
 Dynamic Field Mapping: AI algorithms continuously monitor magnetic field uniformity
 and automatically re-calibrate gradient coils to maintain homogeneity across the
 imaging region.
 Distortion Compensation: In areas like the sinuses, ears, or post-surgical regions
 containing metal clips, real-time correction minimizes geometric distortion and signal
 loss.
 Noise Reduction: Machine learning models separate true tissue signals from artifacts
 caused by local magnetic field variations, improving overall image clarity.
 Adaptive Scanning: AI adjusts pulse sequences and acquisition parameters during
 scanning based on tissue magnetic response, optimizing scan time and image quality.
 Enhanced fMRI Accuracy: In functional MRI, susceptibility correction reduces false
 activations and enhances the accuracy of blood oxygen level–dependent (BOLD)
 contrast.
Solved Problem 1: Magnetization of a Tissue Sample
 Problem:
 A biological tissue is placed in a magnetic field of strength .
 The tissue has a magnetic susceptibility  (diamagnetic).
 Find the magnetization (M) of the tissue and the magnetic flux density (B) inside it.
 Take .
 Solution:
 Given:
 Step 1: Magnetization
 Step 2: Magnetic flux density
 Since  is very small compared to ,
 Answer:
 Interpretation:
 The negative magnetization shows the tissue is diamagnetic, slightly opposing the applied field —
 typical for biological materials like water and fat in MRI.
 Solved Problem 2: Magnetic Susceptibility and Permeability
 Problem:
 A paramagnetic contrast agent used in MRI has a magnetic susceptibility .
 Calculate its relative permeability (μᵣ) and the magnetic flux density (B) when the applied field is 
.
 Take .
 Solution:
 Step 1: Relative permeability
 H=2.0×10A/m 5
 χ=−9.0×10−6
 μ 
=0 4π×10 H/m −7
 H=2.0×10A/m, χ= 5 −9.0×10 , μ 
= −6 0 4π×10−7
 M=χH=(−9.0×10 )(2.0× −6 10)= 5 −1.8A/m
 B=μ 
(H+ 0 M)
 M H
 B≈μ 
H= 0 (4π×10 )(2.0× −7 10)= 5 0.251T
 
, 
M=−1.8A/m B=0.251T
 χ=2.5×10−4
 H=1.0×10A/m 5
 μ 
=0 4π×10 H/m −7
−4
 μ =
 r
 Step 2: Magnetic flux density
 1 +χ =1+2.5×10 =
 B =μμH =
 0 r
 −7
 1.00025
 (4π × 10 )(1.00025)(1.0 ×
 B =0.1257T
 Answer:
 Interpretation:
 χ
 r
 μ =1.00025
 ,
 B =0.1257T
 10 )5
 Because  is positive and small, the material slightly enhances the magnetic field inside it.
 Such agents improve MRI signal strength by altering local field uniformity — making tissues appear
 brighter in contrast-enhanced scans.
Patient-Specific Calibration: Systems learn from previous scans to predict and
 correct field errors specific to each patient’s anatomy or implanted device.
 Reduced Need for Manual Shimming: Traditional shimming (manual adjustment of
 field uniformity) is replaced by automated, real-time magnetic optimization.
 Improved Diagnostic Confidence: These AI-driven corrections allow radiologists to
 visualize fine details in challenging regions — such as the heart, brainstem, or near
 metal implants — with higher spatial accuracy.
 8. Conclusion
 Magnetization, permeability, and susceptibility form the physical basis of MRI. Their
 combined influence governs how magnetic fields interact with tissues, how signals
 are formed, and how clear an image becomes. From shielding design to contrast
 enhancement, these principles transform invisible magnetic behavior into visible
 medical insight.
 References
 Haacke E. M. et al., Magnetic Resonance Imaging: Physical Principles
 and Sequence Design, Wiley, 2014.
 AIIMS Radiology Technical Overview, 2023.
 Siemens Healthineers, MRI Field Design Notes, 2022.
 NIST, Magnetic Properties of Biological Materials, 2023
