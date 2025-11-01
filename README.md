# RPH-Trode: A Rapid Prototyping Approach to Patient Friendly Hybrid EEG Electrodes

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Authors

**Marius Gerdes¹**, **Simon Stock²**, **Heiko Maier³**, **Lukas Feckl¹**, **Florian Mazura¹**, **Wilhelm Stork¹**

¹ ITIV, Karlsruhe Institute of Technology, Karlsruhe, Germany  
² Faculty of Engineering, TH Rosenheim, Rosenheim, Germany  
³ Computer Aided Medical Procedures, Technical University of Munich, Munich, Germany

## Abstract

The demand for high-quality electroencephalography (EEG) is growing, yet conventional electrodes present a significant bottleneck. Wet electrodes offer excellent signal quality but are hindered by long setup times, gel residue, and signal degradation from drying, making them unsuitable for long-term or mobile use. Conversely, dry electrodes are convenient but often fail to provide the requisite signal-to-noise levels, especially during subject motion. 

This paper introduces a novel hybrid EEG electrode designed to bridge this gap. By employing a closed-loop channel system for precise electrolyte delivery, the electrode combines the signal quality of wet electrodes with the convenience of dry electrodes. We utilized stereolithography (SLA) 3D-printing for easy rapid prototyping of the electrode geometry. 

Experimental validation demonstrates that the hybrid electrode achieves performance comparable to the wet electrode gold standard, maintains stable contact impedance over extended periods, and provides robust signal acquisition during subject motion, including walking. This approach enables high-quality, long-term, and truly mobile EEG recordings, opening new possibilities for both clinical and consumer neurotechnology.

## Keywords

EEG, hybrid electrode, rapid prototyping, SLA, mobile EEG, BCI, SSVEP

## Repository Contents

###  Data & Results
Summary tables of experimental results including:
- Impedance measurements over one-hour recording sessions
- CCA (Canonical Correlation Analysis) performance metrics for SSVEP detection
- Motion artifact analysis across different activity levels (standing, walking 2 mph, walking 4 mph)

See [`data/RESULTS.md`](data/RESULTS.md) for detailed tables.

### 📈 Plots
High-resolution figures from the paper in multiple formats (PDF, PNG):
- Electrode design schematics and comparisons
- Impedance performance over time
- Power spectral density (PSD) analysis
- CCA correlation analysis for SSVEP detection
- Individual channel impedance tracking

See [`plots/README.md`](plots/README.md) for figure descriptions.

### 🎥 Video & Photos
Demonstration materials including:
- **Filling procedure**: Step-by-step video showing gel injection technique
- **Cleaning procedure**: Electrode maintenance and cleaning protocol
- **Photos**: Assembly views, filled electrodes, and preparation tools

See [`video_and_photo/README.md`](video_and_photo/README.md) for details.

### 🖨️ 3D Models
CAD files for reproducing the RPH-Trode electrode:
- STL files ready for 3D printing (resin or FDM)
- STEP files for CAD modification
- Printing instructions and post-processing guidelines

**Original print settings**: Prusa resin printer, high detail preset

See [`3d-models/README.md`](3d-models/README.md) for printing instructions.

## Key Findings

### Impedance Performance
Our one-hour recording sessions revealed:
- **RPH-Trode**: Mean impedance of 85.88 ± 17.33 kΩ with stable performance
- **Dry Electrodes**: Mean impedance of 188.39 ± 14.76 kΩ with gradual increase
- **Wet Electrodes**: Mean impedance of 25.96 ± 2.27 kΩ (lowest) but subject to drying effects

### SSVEP Detection Quality
All electrode types successfully detected SSVEP signals at 7.5 Hz:
- RPH-Trode showed robust performance across all motion conditions
- Clear signal differentiation with CCA ratios > 1.5 for target frequencies
- Maintained performance during walking tasks (2 and 4 mph)

### Signal Quality (PSD Analysis)
Power spectral density analysis demonstrated:
- Comparable alpha band (8-12 Hz) signal quality across electrode types
- Lower noise floor for RPH-Trode compared to dry electrodes
- Consistent performance across multiple recording channels

### Motion Artifacts
Performance across three experimental conditions:
- **Standing** (baseline): All electrodes performed well
- **Walking (2 mph)**: RPH-Trode maintained stable signals
- **Walking (4 mph)**: RPH-Trode showed best motion artifact resistance

## Advantages of RPH-Trode

✅ **High Signal Quality**: Comparable to wet electrode gold standard  
✅ **Long-Term Stable**: Maintains impedance over extended recordings  
✅ **Motion Robust**: Performs well during subject movement  
✅ **User Friendly**: Minimal gel application, easy cleanup  
✅ **Fast Setup**: Quick preparation compared to traditional wet electrodes  
✅ **Rapid Prototyping**: SLA 3D printing enables design iteration  
✅ **Reusable**: Designed for multiple uses with proper cleaning

## Usage

### Viewing the Data
All data tables are provided in markdown format in the [`data/`](data/) directory for easy viewing on GitHub.

### Viewing Figures
High-resolution plots are available in the [`plots/`](plots/) directory in PDF and PNG formats. PDFs provide the best quality for presentations and publications.

### 3D Printing the Electrode
STL files in the [`3d-models/`](3d-models/) directory can be directly used with resin or FDM 3D printers:

- Resin printer (e.g., Prusa SL1)
- High detail preset
- Post-process: IPA wash + UV cure

See the [3D models README](3d-models/README.md) for detailed instructions.

### Electrode Preparation
Watch the demonstration videos in [`video_and_photo/`](video_and_photo/) for:
1. Proper gel filling technique
2. Cleaning and maintenance procedures
3. Assembly verification

## Citation

If you use this work in your research, please cite our paper:

```bibtex
@inproceedings{Gerdes2025_RPHTrode,
  author    = {Gerdes, Marius and Stock, Simon and Maier, Heiko and 
               Feckl, Lukas and Mazura, Florian and Stork, Wilhelm},
  title     = {RPH-Trode: A Rapid Prototyping Approach to Patient Friendly 
               Hybrid EEG Electrodes},
  booktitle = {[Conference/Journal Name - To Be Published]},
  year      = {2025},
  note      = {Submitted for publication}
}
```

**Note**: Full publication details will be updated once the paper is accepted and published.

## Publication Status

This work has been submitted for publication. The preprint/final version will be linked here once available.

## Contact

For questions, additional data, or collaboration inquiries:

- marius.gerdes@kit.edu

## Related Links

- **KIT ITIV Research Group**: [https://www.itiv.kit.edu/](https://www.itiv.kit.edu/)
- **3D Models and Videos**: Available in this repository

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

The 3D models are released under the same license and can be freely modified and distributed with attribution.

## Acknowledgments

We thank all participants who volunteered for the experimental validation studies. This research was conducted in compliance with institutional ethics guidelines.

## Additional Resources

For raw data, detailed analysis scripts, or other materials not included in this repository, please contact the authors directly.

### Requesting Additional Materials

If you need:
- **Raw EEG data files**: Contact the corresponding author
- **Analysis code**: Python scripts available upon reasonable request
- **Custom electrode designs**: We can provide design consultation
- **Collaboration opportunities**: Open to academic and industrial partnerships
