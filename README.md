# Simple PDB Downloader and Organizer

The Simple PDB Downloader is a tool designed to enhance your protein structure research by simplifying the process of downloading PDB (Protein Data Bank) files. This tool allows you to effortlessly retrieve PDB files using a list of protein names while also assisting in the management and organization of your files for a more efficient workflow.
Features

    Easy Protein Name List: Simply provide a list of protein names, and the downloader will fetch the corresponding PDB files for you.

    File Management: The tool intelligently organizes downloaded PDB files and removes any unnecessary files that might not be relevant to your specific research.

# PDB Downloader Stages:

We aim to preserve essential data while enhancing our dataset creation process. Here are the steps:

1. **Initial Dataset Creation**: Our primary objective is to construct a comprehensive ultimatum dataset that is user-friendly. We intend to provide a readily accessible CSV dataset that anyone can download and utilize. Given its CSV format, Users can modify the data as needed.

2. **Advanced Dataset Customization**: For users with a more in-depth understanding of the PDB structure, they have the option to select and incorporate specific elements into their dataset right from the beginning. Moreover, they can modify the source from which files are fetched to tailor the dataset to their preferences.

3. **Expert-Level Data Control**: At the highest level of expertise, users can leverage our package to override specific code segments, making precise adjustments without the burden of developing an entirely new downloader from scratch each time they wish to manipulate the data. This empowers advanced users to fine-tune their datasets effortlessly.

# Dataset columns:

1. **Atomic Coordinates**:
   - Information: 3D coordinates (x, y, z) of atoms.
   - Data Type: Floating-point numbers (usually in angstroms).

2. **Secondary Structure**:
   - Information: Annotations indicating secondary structure elements (e.g., helix, sheet).
   - Data Type: Typically represented as strings (e.g., 'H' for helix, 'E' for sheet).

3. **Tertiary Structure**:
   - Information: 3D spatial arrangement of atoms in the molecule.
   - Data Type: Floating-point numbers (atomic coordinates).

4. **B-factor and Occupancy**:
   - Information: B-factor values (thermal vibrations) and occupancy values.
   - Data Type: Floating-point numbers.

5. **Residue Information**:
   - Information: Details about individual amino acid residues or nucleotide bases (e.g., residue type, modifications).
   - Data Type: Typically represented as strings (e.g., amino acid codes).

6. **Ligand Binding Sites**:
   - Information: Locations of ligands, binding affinities, and interactions.
   - Data Type: Depends on the specific information, but can include floating-point numbers and strings.

7. **Sequence Information**:
   - Information: Sequences of biological molecules (proteins or nucleic acids).
   - Data Type: Strings of characters (amino acid or nucleotide codes).

8. **Resolution and Experimental Method**:
   - Information: Experimental metadata, including resolution and method.
   - Data Type: Usually strings (e.g., 'X-ray', 'NMR'), sometimes floating-point numbers (resolution).

9. **Metadata**:
   - Information: Experiment-related metadata, author names, citations, and references.
   - Data Type: Strings, and may include identifiers (e.g., DOI).

10. **Geometric and Chemical Features**:
    - Information: Derived features such as distances, angles, and physicochemical properties.
    - Data Type: Typically floating-point numbers, but can include integers or other numerical representations.

# Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on this repository. Your contributions are greatly appreciated!
License

This project is licensed under the MIT License - see the LICENSE file for details.
