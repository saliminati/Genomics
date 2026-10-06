# Virtual NGS Lab — Product & Curriculum Specification

## Audience
Undergraduate student with basic biology knowledge.

## Platform
Illumina iSeq 100 sequencing workflow.

## Overall learning objective
By the end of the lab, the student should understand what happens to DNA at each stage and why each step is needed, rather than simply memorizing a protocol.

## Full planned workflow
1. Bacterial colony selection/resuspension
2. DNA extraction
3. Qubit QC
4. Fragmentation
5. Adapter/index addition
6. Library QC
7. iSeq 100 sequencing
8. FASTQ generation
9. Basic bioinformatics/analysis

## Module 1 sequence

### Screen 1 — Welcome
Learning goals, sample ID E_COLI_001, workflow explanation, educational-simulation disclaimer.

### Screen 2 — Prepare for colony selection
Bench selection interaction. Required: agar plate, sterile loop, culture tube, nutrient broth, appropriate liquid handling, rack, label, waste. Distractors include Zymo reagents and Qubit materials.

### Screen 3 — Select a colony
Four colony choices. Correct choice is a well-isolated colony. Teach that transferred material is bacterial cells, not DNA.

### Screen 4 — Prepare culture
Label tube. Add 2 mL nutrient broth. Transfer colony. No volume calculation. Teach use of an appropriate 2 mL-capable device.

### Screen 5 — Incubate
37°C for 24 hours. Simulation clock can compress time. Teach biomass generation.

### Screen 6 — Harvest cells
Teach pellet vs supernatant and centrifuge balance. Retain pellet. Exact upstream centrifuge speed/time must come from an approved SOP rather than being invented.

### Screen 7 — Prepare extraction
Quick-DNA Miniprep Plus equipment/reagents. For this E. coli scenario use BioFluid & Cell Buffer (Red), not Solid Tissue Buffer (Blue).

### Screen 8 — Resuspend
Simulation assumption: 1–5×10^6 cells. Use 200 µL DNA Elution Buffer or isotonic buffer such as PBS.

### Screen 9 — Proteinase K
Add 200 µL BioFluid & Cell Buffer and 20 µL Proteinase K to the 200 µL sample. Mix. 55°C for 10 minutes.

### Screen 10 — Binding preparation
420 µL digested sample. Add one volume = 420 µL Genomic Binding Buffer. Use this as the main calculation checkpoint.

### Screen 11 — Binding
Transfer to Zymo-Spin IIC-XLR column. Centrifuge ≥12,000×g for 1 min. Discard collection tube/flow-through. DNA is retained on silica membrane.

### Screen 12 — DNA Pre-Wash
400 µL, centrifuge 1 min, empty collection tube.

### Screen 13 — g-DNA Wash
700 µL, centrifuge 1 min, empty collection tube.

### Screen 14 — Final g-DNA Wash
200 µL, centrifuge 1 min, discard collection tube/flow-through.

### Screen 15 — Elution
Transfer column to clean tube. Add ≥50 µL DNA Elution Buffer. Incubate 5 min. Centrifuge 1 min.

### Screen 16 — QC
Simulated Qubit concentration 18.4 ng/µL. With 50 µL elution, total DNA = 920 ng. Separate simulated purity metric A260/A230 = 2.1. Explain concentration versus purity.

### Screen 17 — Complete
Show sample journey, final QC, notebook summary, and transition to Nextera library preparation.

## Future enhancements
- Real product photographs beside virtual reagents/equipment.
- More realistic pipette interaction.
- Drag-and-drop bench preparation.
- Error simulation library.
- Expanded troubleshooting.
- Small FASTQ analysis module.
- Module 2 Nextera library preparation.
- Persistent student progress.

## Recorded Actions Export
The lab includes **Save Recorded Actions**, which downloads the current electronic lab notebook/progress as a JSON file. **Reset Recorded Actions** clears the saved browser state and recorded actions after confirmation.
